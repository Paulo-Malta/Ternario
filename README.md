var nota = Number(window.prompt("Qual a sua nota :"))
var media = Number(window.prompt("Qual a media da sua escola :"))

document.write("<p> Você esta :" + (nota >=media ? "Aprovado" : "Reprovado"  ))
