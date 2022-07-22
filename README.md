# Estudos-JavaScript

ESTUDOS DE JAVASCRIPT  

 

Pode alterar o conteúdo do HTML com JS 

EX:  

<!DOCTYPE html> 

<html> 

<body> 

<h2>Meu primeiro documento JS</h2> 

<p id="teste">Mudar o HTLM</p> 

<button type="button" onclick='document.getElementById("teste").innerHTML = "Hello JavaScript!"'>Clique Aqui!</button> 

</body> 

</html> 

 

Pode alterar o elemento CSS com JS 

<!DOCTYPE html> 

<html> 

<body> 

<h2> Meu primeiro documento JS</h2> 

<p id="teste">Mudar elemento css</p> 

<button type="button" onclick="document.getElementById('teste').style.fontSize='35px'">Clique Aqui!</button> 

</body> 

</html> 

Pode ocultar elementos com JS 

<!DOCTYPE html> 

<html> 

<body>  

<h2>Meu primeiro JS</h2> 

<p id="teste">Ocultar Elementos</p> 

<button type="button" onclick="document.getElementById('teste').style.display='none'">Clique Aqui!</button> 

</body> 

</html> 

 

Function é colocado na <head> seção de uma página HTML. 

A função é invocada (chamada) quando um botão é clicado: 

 

<!DOCTYPE html> 
<html> 
<head> 
<script> 
function myFunction() { 
  document.getElementById("teste").innerHTML = "Mudar paragráfo.";} 
</script> 
</head> 
<body> 

<h2>Teste JavaScript no HEAD </h2> 
 
<p id="teste">Paragráfo</p> 
<button type="button" onclick="myFunction()">Tente Aqui</button> 

</body> 
</html> 

Function é colocado na <body> seção de uma página HTML. 

A função é invocada (chamada) quando um botão é clicado: 

 

<!DOCTYPE html> 
<html> 
<head> 
</head> 
<body> 

<script> 
function myFunction() { 
  document.getElementById("teste").innerHTML = "Mudar paragráfo.";} 
</script> 

<h2>Teste JavaScript no BODY </h2> 
<p id="teste">Paragráfo</p> 
<button type="button" onclick="myFunction()">Tente Aqui</button> 

</body> 
</html> 

 

Possibilidades de exibição de JavaScript 

 

JavaScript pode "exibir" dados de diferentes maneiras: 

Escrevendo em um elemento HTML, usando innerHTML. 

Escrevendo na saída HTML usando document.write(). 

Escrevendo em uma caixa de alerta, usando window.alert(). 

Escrevendo no console do navegador, usando console.log(). 

 

Usando innerHTML 

Para acessar um elemento HTML, JavaScript pode usar   o document.getElementById(id)método.     

O id atributo define o elemento HTML. A innerHTML propriedade define o conteúdo HTML: 

 

<!DOCTYPE html> 
<html> 
<body> 
<h1>My First Web Page</h1> 
<p>My First Paragraph</p> 
<p id="demo"></p> 
<script> 
document.getElementById("demo").innerHTML = 5 + 6; 
</script> 
</body> 
</html> 

Usando document.write() 

Para fins de teste, é conveniente usar document.write(): 

<!DOCTYPE html> 
<html> 
<body> 
 
<h1>My First Web Page</h1> 
<p>My first paragraph.</p> 
 
<script> 
document.write(5 + 6); 
</script> 
 
</body> 
</html> 

O uso de document.write() após o carregamento de um documento HTML excluirá todo o HTML existente : 

<!DOCTYPE html> 
<html> 
<body> 
 
<h1>My First Web Page</h1> 
<p>My first paragraph.</p> 
 
<button type="button" onclick="document.write(5 + 6)">Try it</button> 
 
</body> 
</html> 

O método document.write() deve ser usado apenas para teste. 

 
