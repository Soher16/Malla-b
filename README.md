# Malla-b
body {
  font-family: Arial, sans-serif;
  padding: 20px;
  background: #f7f9fc;
}
h1 {
  text-align: center;
}
#malla {
  display: grid;
  gap: 10px;
}
.asignatura {
  padding: 10px;
  border-radius: 5px;
  background: #ddd;
  color: #222;
  cursor: not-allowed;
  opacity: 0.5;
  transition: background 0.3s;
}
.asignatura.unlocked {
  background: #4caf50;
  color: white;
  cursor: pointer;
  opacity: 1;
}
.asignatura.completed {
  background: #2e7d32;
  text-decoration: line-through;
}
