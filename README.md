<!DOCTYPE html>
<html lang="es">

<!--
web o pagina:
alumno:
fecha:
-->

<head>
  <title>ejercicio</title>
  <meta charset="UTF-8">
  <meta name="description" content="Fotografía,dibujos,consejos y mucho arte es lo que podrás encontrar en este espacio dedicado a lo artístico"/>
  <meta name="keywords" content="fotografía, dibujos, poesía,arte"/>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"// seccion de codigo javascript ></script>
</head>


<body>
<details>
	<summary>Ejercicios:</summary>
	<ul>
	<li><a href="https://francosejas.github.io/proy/ejer/plantilla.html" target="blank">plantilla</a></li>
	<li><a href="https://francosejas.github.io/proy/ejer/uso de type of javascript.html" target="blank">javascript</a></li>
	<li><a href="https://francosejas.github.io/proy/ejer/1deFebreroLM-divs.html" target="blank">divs</a></li>
	<li><a href="https://francosejas.github.io/proy/ejer/La ciudad de Málaga.html" target="blank">Málaga</a></li>
	<li><a href="https://francosejas.github.io/proy/ejer/La Mafia en el cine.html" target="blank">mafia en el cine</a></li>
	</ul>
</details>
<input type="text" name"campo1"/>
<input type="text" name"campo2"/>
  //seccion de codigo javascript 
<script>
$(document).ready(function(){
 $("input").focus(function(){
 $(this).css("background-color", "yellow");
 });
 $("input").blur(function(){
 $(this).css("background-color", "white");
 }); 
});

</script>
</body>
<footer>
	
</footer>
</html>
