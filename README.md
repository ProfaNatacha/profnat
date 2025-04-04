escolhajogador = prompt("1 PEDRA; 2 PAPEL ou 3 TESOURA");
  escolhacomputador = Math.floor(Math.random() * 3) + 1;
}
// empates
if (escolhajogador == escolhacomputador) {
  alert("Empate! O computador também escolheu" + escolhacomputador);
}
// Pedra
<button "Pedra">
if (escolhajogador == 1) {
  if (escolhacomputador == 2) {
    alert("Computador venceu!");
  }
  if (escolhacomputador == 3) {
    alert("Jogador venceu! A escolha do computador foi: " + escolhacomputador);
  }
}

// papel
if (escolhajogador == 2) {
  if (escolhacomputador == 1)
    alert("Você venceu! O computador escolheu" + escolhacomputador);
}
if (escolhacomputador == 3) {
  alert("Jogador venceu! A escolha do computador foi:" + escolhacomputador);
}
// tesoura
if (escolhajogador == 3) {
  if (escolhacomputador == 1) {
    alert("Computador venceu! Escolha do computador:" + escolhacomputador);
  }
  if (escolhacomputador == 2) {
    alert("Você venceu!!! A escolha do computador foi:" + escolhacomputador);
  }
}
