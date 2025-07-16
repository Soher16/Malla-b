# Malla-b
document.addEventListener("DOMContentLoaded", () => {
  const asigns = Array.from(document.querySelectorAll(".asignatura"));
  const state = {};

  asigns.forEach(div => {
    const id = div.dataset.id;
    const prerq = JSON.parse(div.dataset.prerq);
    state[id] = { element: div, prerq, completed: false };
  });

  function updateAll() {
    Object.values(state).forEach(item => {
      if (item.prerq.length === 0 || item.prerq.every(r => state[r]?.completed)) {
        item.element.classList.add("unlocked");
        item.element.classList.remove("completed");
      } else {
        item.element.classList.remove("unlocked");
        item.element.classList.remove("completed");
      }
    });
  }

  asigns.forEach(div => {
    div.addEventListener("click", () => {
      const id = div.dataset.id;
      const item = state[id];
      if (!item.element.classList.contains("unlocked")) return;
      item.completed = !item.completed;
      if (item.completed) {
        item.element.classList.add("completed");
      } else {
        item.element.classList.remove("completed");
      }
      updateAll();
    });
  });

  updateAll();
});
