<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Quiz com Pontuação</title>
</head>
<body>

<h2>Quiz com Pontuação</h2>

<form id="quizForm">
  <label for="q1">Questão 1: Qual é a capital do Brasil?</label><br>
  <select id="q1" name="q1">
    <option value="0">Selecione uma opção</option>
    <option value="0">Rio de Janeiro</option>
    <option value="1">Brasília</option>
    <option value="0">São Paulo</option>
  </select><br>

  <label for="q2">Questão 2: Quanto é 2 + 2?</label><br>
  <select id="q2" name="q2">
    <option value="0">Selecione uma opção</option>
    <option value="0">3</option>
    <option value="1">4</option>
    <option value="0">5</option>
  </select><br>

  <button type="button" onclick="calculateScore()">Calcular Pontuação</button>
</form>

<p>Pontuação: <span id="score">-</span></p>

<script>
function calculateScore() {
  var q1 = parseInt(document.getElementById("q1").value);
  var q2 = parseInt(document.getElementById("q2").value);
  
  var score = q1 + q2;
  
  document.getElementById("score").textContent = score;
}
</script>

</body>
</html>
