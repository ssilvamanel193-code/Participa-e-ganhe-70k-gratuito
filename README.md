<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Continue</title>
</head>
<body style="display:flex;justify-content:center;align-items:center;height:100vh;flex-direction:column;">

<div id="tela">
<h2>Clique para continuar</h2>
<button onclick="abrir()">Entrar</button>
</div>

<img id="foto" src="https://i.postimg.cc/4xvw70ND/images-(1).jpg" style="display:none;max-width:95%;">

<script>
function abrir(){
document.getElementById("tela").style.display="none";
document.getElementById("foto").style.display="block";
}
</script>

</body>
</html>
