<!DOCTYPE html>
<html>
<body style="background-color: lightblue;"></body>
<h2>Media de notas com JavaScript </h2>
Primeira nota <input id="nota1" type="number"> <br/>
Segunda nota <input id="nota2" type="number"> <br/>
<button onclick="media()">Calcular Média</button>
<script>
function media(){
var nota1 = parseFloat(document.getElementById("nota1").value);
var nota2 = parseFloat(document.getElementById("nota2").value);
var media = (nota1 + nota2)/2 ;
if(media >= 7) {
alert("Parabens, aprovado! Media "+media);
} else {
alert("Reprovado!");
}
}
</script>
</body>
</html>
