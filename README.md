# trabalho-site--Surpresa-tropical-2C
//Site sobre a empresa "Surpresa Tropical" criada por alunos do 2C do colégio Mondrone, diretamente relacionado a feira do dia 9/10.  Integrantes: Ana //flávia,Sofia, Letícia Mariana, Lucas Gabriel, Maria Vitória

//Código do site
<!DOCTYPE html>
<html>
<head>
<title>W3.CSS Template</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/5/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Amatic+SC">
<style>
body, html {height: 100%}
body,h1,h2,h3,h4,h5,h6 {font-family: "Amatic SC", sans-serif}
.menu {display: none}
.bgimg {
 
  background-image: url("imagens/logo.jpeg");
  background-repeat: no-repeat;
  background-size: cover; /* ajusta a imagem inteira */
  background-position: center;
  background-color: #aef3b1; /* cor de fundo do header (opcional) */
  min-height: 90%;
}
.w3-black {
  background-color: #3b0a0a !important; /* usa !important para garantir que substitua */
}
.w3-white {
  background-color: #ede7c0 !important; /* usa !important para garantir que substitua */
}
.w3-red {
  background-color: #5d1d03 !important;
}
.w3-blue-grey{
    background-color: #fbd30c !important;

}

</style>
</head>
<body>

<!-- Navbar (sit on top) -->
<div class="w3-top w3-hide-small">
  <div class="w3-bar w3-xlarge w3-black w3-opacity w3-hover-opacity-off" id="myNavbar">
    <a href="#" class="w3-bar-item w3-button">HOME</a>
    <a href="#menu" class="w3-bar-item w3-button">MENU</a>
    <a href="#about" class="w3-bar-item w3-button">SOBRE</a>
    <a href="#myMap" class="w3-bar-item w3-button">CONTATO</a>
  </div>
</div>
  
<!-- Header with image -->
<header class="bgimg w3-display-container w3-grayscale-min" id="home">
  <div class="w3-display-bottomleft w3-padding">
    <span class="w3-tag w3-xlarge"> <p><strong>Hora de atendimento:</strong> apartir das 9:45 até 10:00.</p></span>
  </div>
  <div class="w3-display-middle w3-center">
    <span class="w3-text-white w3-hide-small" style="font-size:100px"><br></span>
    <span class="w3-text-white w3-hide-large w3-hide-medium" style="font-size:60px"><b><br></b></span>
    <p><a href="#menu" class="w3-button w3-xxlarge w3-black">Desejo ver o menu</a></p>
  </div>
</header>

<!-- Menu Container -->
<div class="w3-container w3-black w3-padding-64 w3-xxlarge" id="menu">
  <div class="w3-content">
  
    <h1 class="w3-center w3-jumbo" style="margin-bottom:64px">O menu</h1>
    <div class="w3-row w3-center w3-border w3-border-dark-grey">
      <a href="javascript:void(0)" onclick="openMenu(event, 'Pizza');" id="myLink">
        <div class="w3-col s4 tablink w3-padding-large w3-hover-gray">Nossos doces</div>
      </a>
      <a href="javascript:void(0)" onclick="openMenu(event, 'Starter');">
        <div class="w3-col s4 tablink w3-padding-large w3-hover-gray">Bebidas</div>
      </a>
    </div>

    <div id="Pizza" class="w3-container menu w3-padding-32 w3-white">
      <h1><b>Surpresa de morango</b> <span class="w3-right w3-tag w3-dark-grey w3-round">R$8,00</span></h1>
      <p class="w3-text-black">Um delicioso bombom no pote! - Morangos frescos, brigadeiro branco e ganache de chocolate </p>
      <hr>
   
      <h1><b>Surpresa de uva</b> <span class="w3-right w3-tag w3-dark-grey w3-round">R$8,00</span></h1>
      <p class="w3-text-black">Uvas graudas, brigadeiro branco e ganache de chocolate</p>
      <hr>
      
      <h1><b>Mousse de maracujá</b> <span class="w3-right w3-tag w3-dark-grey w3-round">R$6,00</span></h1>
      <p class="w3-text-black">Mousse de maracujá( feito com suco natural) e ganache de chocolate</p>
      <hr>
    </div>


    <div id="Starter" class="w3-container menu w3-padding-32 w3-white">
      <h1><b>Água do bebedouro</b> <span class="w3-tag w3-grey w3-round">Popular</span><span class="w3-right w3-tag w3-dark-grey w3-round">grátis</span></h1>
      <p class="w3-text-grey">Pode levar água da sua garrafinha também</p>
      <hr>
    </div><br>

  </div>
</div>

<!-- About Container -->
<div class="w3-container w3-padding-64 w3-red w3-grayscale w3-xlarge" id="about">
  <div class="w3-content">
    <h1 class="w3-center w3-jumbo" style="margin-bottom:64px">Sobre nós</h1>
    <img src="imagens/integrantes.jpeg" style="width:100%; border-radius:20px;" alt="integrantes">
    <p>Surpresa Tropical foi nosso ponto de partida para apresentarmos nossa "empresa" aos alunos do Colégio Estadual João Manuel Mondrone no dia 09/10. Com esse nome buscamos deixar visível os elementos e realces de nossos produtos.</p>
    <p>Nossa sobremesa principal é Surpresa de uva e morango, daí veio o incentivo do nosso forte nome, além do mousse de maracujá que trás o frescor em meio aos chocolates.</p>
    <p> As frutas são o toque e sutileza que falta em qualquer sobremesa, frutas tropicais que trazem o equilíbrio e novos aromas ao nosso paladar é coisa de outro mundo, não acha?</p></p>
    <p><strong>Cadê a chef?</strong> <p>Maria Vitória(Mavi)</p>
    <img src="imagens/mavi.jpeg" style="width:50%; border-radius:20px;" alt="chef mavi">
    <h1><b>Onde nos encontrar</b></h1>
    
    <div class="w3-row">
      <div class="w3-col s6">
        <p>R.Mato Grosso, 2233 - Cidade Alta - Medianeira-PR</p>
        <p>Colégio Mondrone</p>
        <p>Apenas no dia 9/10 (quinta-feira)</p>
        <p>das 9h45 até 10h</p>
      </div>
    
  </div>
</div>

<!-- Image of location/map -->
<img src="imagens/mondrone222.webp" style="width:100%; border-radius:20px;" alt="local de venda">
<!-- Contact -->
<div class="w3-container w3-padding-64 w3-blue-grey w3-grayscale-min w3-xlarge" id="myMap">
  <div class="w3-content">
    <h1 class="w3-center w3-black" style="margin-bottom:64px">Contato</h1>

    <p><span class="w3-tag">Reserve seu pedido!</span>     <p class="w3-text-black"><strong class="w3-text-black">Reserve o seu para garantir!</strong> se caso tiver interesse em pagar no pix ou retirar seu pedido mais rápido, peço que reserve seu pedido, colégios estaduais não aceitam celular!</p></p>
    <p class="w3-xxlarge"><strong class="w3-text-black">reserve seu pedido aqui:</strong></p>
    <form action="/action_page.php" target="_blank">
      <p><input class="w3-input w3-padding-16 w3-border" type="text" placeholder="Nome" required name="Nome"></p>
      <p><input class="w3-input w3-padding-16 w3-border" type="text" placeholder="Qual doce deseja pedir?" required name="doces"></p>
      <p><input class="w3-input w3-padding-16 w3-border" type="datetime-local" placeholder="Date and time" required name="date" value="2020-11-16T20:00"></p>
      <p><input class="w3-input w3-padding-16 w3-border" type="text" placeholder="Retirar ou trocar algum ingrediente" required name="Message"></p>
      <p><button class="w3-button w3-light-grey w3-block" type="submit">ENVIAR</button></p>
    </form>
  </div>
</div>

<!-- Footer -->
<footer class="w3-center w3-black w3-padding-48 w3-xxlarge">
  <p>Desenvolvido por <a href="https://www.w3schools.com/w3css/default.asp" title="W3.CSS" target="_blank" class="w3-hover-text-green">Surpresa Tropical</a></p>
</footer>

<script>
// Tabbed Menu
function openMenu(evt, menuName) {
  var i, x, tablinks;
  x = document.getElementsByClassName("menu");
  for (i = 0; i < x.length; i++) {
     x[i].style.display = "none";
  }
  tablinks = document.getElementsByClassName("tablink");
  for (i = 0; i < x.length; i++) {
     tablinks[i].className = tablinks[i].className.replace(" w3-red", "");
  }
  document.getElementById(menuName).style.display = "block";
  evt.currentTarget.firstElementChild.className += " w3-red";
}
document.getElementById("myLink").click();
</script>

</body>
</html>
