# Malla-b
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Malla Curricular Interactiva</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <h1>Malla Curricular</h1>
  <div id="malla">
    <h2>1° Semestre</h2>
    <div class="asignatura" data-id="bcm1" data-prerq="[]">Bases Científicas de la Medicina I</div>
    <div class="asignatura" data-id="morfologia1" data-prerq="[]">Integrado de Morfología I</div>
    <div class="asignatura" data-id="salud_com_fam1" data-prerq="[]">Salud Comunitaria y Familiar I</div>
    <div class="asignatura" data-id="metodologia" data-prerq="[]">Metodología</div>

    <h2>2° Semestre</h2>
    <div class="asignatura" data-id="bcm2" data-prerq='["bcm1"]'>Bases Científicas de la Medicina II</div>
    <div class="asignatura" data-id="integrado2" data-prerq='["morfologia1"]'>Integrado II</div>
    <div class="asignatura" data-id="salud_com_fam2" data-prerq='["salud_com_fam1"]'>Salud Comunitaria y Familiar II</div>

    <h2>3° Semestre</h2>
    <div class="asignatura" data-id="bcm3" data-prerq='["bcm2"]'>Bases Científicas de la Medicina III</div>
    <div class="asignatura" data-id="morfologia2" data-prerq='["morfologia1"]'>Integrado de Morfología II</div>
    <div class="asignatura" data-id="salud_com_fam3" data-prerq='["salud_com_fam2"]'>Salud Comunitaria y Familiar III</div>

    <h2>4° Semestre</h2>
    <div class="asignatura" data-id="bcm4" data-prerq='["bcm3"]'>Bases Científicas de la Medicina IV</div>
    <div class="asignatura" data-id="morfologia2b" data-prerq='["morfologia1"]'>Integrado de Morfología II</div>
    <div class="asignatura" data-id="microbiologia" data-prerq='["bcm3"]'>Microbiología</div>
    <div class="asignatura" data-id="medicina_evidencia" data-prerq='["metodologia"]'>Medicina Basada en la Evidencia</div>
    <div class="asignatura" data-id="salud_com_fam2b" data-prerq='["salud_com_fam1"]'>Salud Comunitaria y Familiar II</div>

    <h2>5° Semestre</h2>
    <div class="asignatura" data-id="bcm5" data-prerq='["bcm4"]'>Bases Científicas de la Medicina V</div>
    <div class="asignatura" data-id="integrado3" data-prerq='["integrado2"]'>Integrado III</div>
    <div class="asignatura" data-id="salud_com_fam3b" data-prerq='["salud_com_fam2"]'>Salud Comunitaria y Familiar III</div>

    <h2>6° Semestre</h2>
    <div class="asignatura" data-id="bcm6" data-prerq='["bcm5"]'>Bases Científicas de la Medicina VI</div>
    <div class="asignatura" data-id="integrado4" data-prerq='["integrado3"]'>Integrado IV</div>
    <div class="asignatura" data-id="salud_com_fam4" data-prerq='["salud_com_fam3"]'>Salud Comunitaria y Familiar IV</div>

    <h2>7° Semestre</h2>
    <div class="asignatura" data-id="bcm7" data-prerq='["bcm6"]'>Bases Científicas de la Medicina VII</div>
    <div class="asignatura" data-id="integrado5" data-prerq='["integrado4"]'>Integrado V</div>
    <div class="asignatura" data-id="salud_com_fam5" data-prerq='["salud_com_fam4"]'>Salud Comunitaria y Familiar V</div>

    <h2>8° Semestre</h2>
    <div class="asignatura" data-id="bcm8" data-prerq='["bcm7"]'>Bases Científicas de la Medicina VIII</div>
    <div class="asignatura" data-id="integrado6" data-prerq='["integrado5"]'>Integrado VI</div>
    <div class="asignatura" data-id="salud_com_fam6" data-prerq='["salud_com_fam5"]'>Salud Comunitaria y Familiar VI</div>

    <h2>9° Semestre</h2>
    <div class="asignatura" data-id="bcm9" data-prerq='["bcm8"]'>Bases Científicas de la Medicina IX</div>
    <div class="asignatura" data-id="integrado7" data-prerq='["integrado6"]'>Integrado VII</div>
    <div class="asignatura" data-id="salud_com_fam7" data-prerq='["salud_com_fam6"]'>Salud Comunitaria y Familiar VII</div>

    <h2>10° Semestre</h2>
    <div class="asignatura" data-id="bcm10" data-prerq='["bcm9"]'>Bases Científicas de la Medicina X</div>
    <div class="asignatura" data-id="integrado8" data-prerq='["integrado7"]'>Integrado VIII</div>
    <div class="asignatura" data-id="salud_com_fam8" data-prerq='["salud_com_fam7"]'>Salud Comunitaria y Familiar VIII</div>

    <h2>11° Semestre</h2>
    <div class="asignatura" data-id="bcm11" data-prerq='["bcm10"]'>Bases Científicas de la Medicina XI</div>
    <div class="asignatura" data-id="integrado9" data-prerq='["integrado8"]'>Integrado IX</div>

    <h2>12° Semestre</h2>
    <div class="asignatura" data-id="bcm12" data-prerq='["bcm11"]'>Bases Científicas de la Medicina XII</div>
    <div class="asignatura" data-id="integrado10" data-prerq='["integrado9"]'>Integrado X</div>

    <h2>13° Semestre</h2>
    <div class="asignatura" data-id="internado1" data-prerq='["bcm12","integrado10"]'>Internado Clínico I</div>

    <h2>14° Semestre</h2>
    <div class="asignatura" data-id="internado2" data-prerq='["internado1"]'>Internado Clínico II</div>
  </div>

  <script src="script.js"></script>
</body>
</html>
