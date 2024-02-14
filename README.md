//code html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>

 
    <div id="Zone"style="height: 100px; width: 100px; border:solid;" onmouseover="into()" onmouseout="out()" onclick="bgColor()"></div>
    <script src="app.js"></script>
</body>
</html>
//code java
/*
function max2(a,b)
{
    if (a>b)
    return a
    else 
    return b
}
console.log(max2(5,8))
console.log(max2(15,8))
console.log(max2(18,18))
*/
//ex2
/*
function direbonjour(){
    console.log("bonjour")
}
direbonjour()
*/
//ex3
/*function calculerSomme(a, b) {
    return a + b;
}


var premierNombre = parseInt(prompt("Entrez le premier nombre :"));
var deuxiemeNombre = parseInt(prompt("Entrez le deuxième nombre :"));

var resultat = calculerSomme(premierNombre, deuxiemeNombre);
console.log("La somme est :", resultat);
*/
//ex4
const container = document.getElementById("Zone")

function into() {
    container.innerHTML="Enter"
    
}

function out() {
    container.innerHTML="Out"
    
}

function bgColor() {
    container.style.backgroundColor="red";
}

