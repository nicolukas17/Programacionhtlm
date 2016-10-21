# Programacionhtlm

<!DOCTYPE HTML>
<html>
<head>
  <title>Peso en otros planetas</title>
  <style type="text/css">

  </style>
</head>
<body>
  <h1>Tu peso en otros planetas</h1>
  <p>En la tierra pesas distinto a Marte o Jupiter</p>
<script type="text/javascript">
  var usuario = prompt("Cual es tu peso?");
   var planeta = prompt("En qué planeta deseas saber tu peso \n 1. marte \n 2. Jupiter \n 3. Venus\n 4. Mercurio ");

   //alert(usuario);
   //alert(planeta);

   var gravedad_tierra = 9.8;
   var gravedad_marte = 3.7;
   var gravedad_jupiter = 24.7;
   var gravedad_venus = 8.8;
   var gravedad_Mercurio = 3.7;

   if (planeta == 1) {
     var peso_et = (usuario * gravedad_marte) / gravedad_tierra;
     var nombrep = "Marte";
   }
   else if( planeta == 2){
     var peso_et = (usuario * gravedad_jupiter) / gravedad_tierra;
     var nombrep = "jupiter";
}
     else if(planeta == 3){
       var peso_et = (usuario * gravedad_venus) / gravedad_tierra;
        var nombrep = "Venus";
}
else if(planeta == 4){
  var peso_et = (usuario * gravedad_Mercurio) / gravedad_tierra
  var nombrep = "Mercurio";

}




peso_et = parseInt(peso_et);

//alert(peso_et);

document.write("tu peso en <strong>" + nombrep + "</strong> es igual a " + peso_et + "kg" );



</script>
</body>
</html>
