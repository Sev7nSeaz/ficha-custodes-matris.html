<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Ficha - Custodes Matris</title>
  <style>
    body {
      font-family: 'Georgia', serif;
      background: #1b1b1b;
      color: #f0e6d2;
      margin: 0;
      padding: 20px;
    }
    h1, h2 {
      color: #e7c285;
      border-bottom: 1px solid #444;
    }
    label {
      display: block;
      margin-top: 10px;
      font-weight: bold;
    }
    input, textarea {
      width: 100%;
      background: #2e2e2e;
      border: 1px solid #555;
      color: #f0e6d2;
      padding: 5px;
      margin-top: 3px;
      font-family: inherit;
    }
    .section {
      background: #242424;
      padding: 15px;
      margin-bottom: 20px;
      border-radius: 6px;
      box-shadow: 0 0 8px #00000088;
    }
  </style>
</head>
<body>
  <h1>Ficha de Personagem – Custodes Matris</h1>

  <div class="section">
    <h2>Identidade</h2>
    <label>Nome</label><input type="text" />
    <label>Idade</label><input type="text" />
    <label>Profissão</label><input type="text" />
    <label>História / Motivação</label><textarea rows="3"></textarea>
  </div>

  <div class="section">
    <h2>Atributos</h2>
    <label>Força</label><input type="text" />
    <label>Agilidade</label><input type="text" />
    <label>Intelecto</label><input type="text" />
    <label>Presença</label><input type="text" />
    <label>Vontade</label><input type="text" />
  </div>

  <div class="section">
    <h2>Recursos</h2>
    <label>Vida (PV)</label><input type="text" />
    <label>Sanidade (SAN)</label><input type="text" />
    <label>Defesa</label><input type="text" />
    <label>Movimento</label><input type="text" />
  </div>

  <div class="section">
    <h2>Perícias Treinadas</h2>
    <textarea rows="5" placeholder="Liste até 6 perícias escolhidas..."></textarea>
  </div>

  <div class="section">
    <h2>Traços Únicos e Mentais</h2>
    <label>Vantagem Única</label><input type="text" />
    <label>Medo Profundo</label><input type="text" />
    <label>Segredo</label><input type="text" />
  </div>

  <div class="section">
    <h2>Equipamento Inicial</h2>
    <textarea rows="4"></textarea>
  </div>

</body>
</html>
