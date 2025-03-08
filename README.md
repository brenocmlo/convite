# convite
<script>
var pulaLinha = function(){
	document.write("<br>");
};
var mostra = function(frase){
	document.write(frase);
	pulaLinha();
};
let nome = prompt("Qual é o seu nome?");
let restaurane = prompt( nome  + ", Qual é o nome do restaurante que você mais gosta?");
alert( nome + ", temos um encontro marcado no " + restaurane + ", dia 14 de março, às 20h. Não se atrase!");
mostra("Até lá!");
</script>
