<html lang="en">
<head>
  <!-- ALlerlei links die in het theme al stonden, om Bootstrap en fonts te kunnen gebruiken. -->
  <title>Het Parijsakkoord</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">
  <link href="https://fonts.googleapis.com/css?family=Montserrat" rel="stylesheet" type="text/css">
  <link href="https://fonts.googleapis.com/css?family=Lato" rel="stylesheet" type="text/css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>
  <!-- De styling zat ook al in het theme, wel kleuren aangepast, dingen verwijdert die niet meer nodig waren, zoals de styling van een boostrap carousel. -->
  <style>
  body {
    font: 400 15px Lato, sans-serif;
    line-height: 1.8;
    color: #818181;
  }
  h2 {
    font-size: 24px;
    text-transform: uppercase;
    color: #303030;
    font-weight: 600;
    margin-bottom: 30px;
  }
  h4 {
    font-size: 19px;
    line-height: 1.375em;
    color: #303030;
    font-weight: 400;
    margin-bottom: 30px;
  }  
  .jumbotron {
    background-color: #006666;
    color: #fff;
    padding: 100px 25px;
    font-family: Montserrat, sans-serif;
  }
  .container-fluid {
    padding: 60px 50px;
  }
  .bg-grey {
    background-color: #f6f6f6;
  }
  .logo-small {
    color: #006666;
    font-size: 50px;
  }
  .logo {
    color: #006666;
    font-size: 200px;
  }
  .thumbnail {
    padding: 0 0 15px 0;
    border: none;
    border-radius: 0;
  }
  .thumbnail img {
    width: 100%;
    height: 100%;
    margin-bottom: 10px;
  }

  .item h4 {
    font-size: 19px;
    line-height: 1.375em;
    font-weight: 400;
    font-style: italic;
    margin: 70px 0;
  }
  .item span {
    font-style: normal;
  }
  .panel {
    border: 1px solid #006666; 
    border-radius:0 !important;
    transition: box-shadow 0.5s;
  }
  .panel:hover {
    box-shadow: 5px 0px 40px rgba(0,0,0, .2);
  }
  .panel-footer .btn:hover {
    border: 1px solid ##006666;
    background-color: #fff !important;
    color: #006666;
  }
  .panel-heading {
    color: #fff !important;
    background-color: #006666 !important;
    padding: 25px;
    border-bottom: 1px solid transparent;
    border-top-left-radius: 0px;
    border-top-right-radius: 0px;
    border-bottom-left-radius: 0px;
    border-bottom-right-radius: 0px;
  }
  .panel-footer {
    background-color: white !important;
  }
  .panel-footer h3 {
    font-size: 32px;
  }
  .panel-footer h4 {
    color: #aaa;
    font-size: 14px;
  }
  .panel-footer .btn {
    margin: 15px 0;
    background-color: #006666;
    color: #fff;
  }
  .navbar {
    margin-bottom: 0;
    background-color: #006666;
    z-index: 9999;
    border: 0;
    font-size: 14px !important;
    line-height: 1.42857143 !important;
    letter-spacing: 4px;
    border-radius: 0;
    font-family: Montserrat, sans-serif;
  }
  .navbar li a, .navbar .navbar-brand {
    color: #fff !important;
  }
  .navbar-nav li a:hover, .navbar-nav li.active a {
    color: #006666 !important;
    background-color: #fff !important;
  }
  .navbar-default .navbar-toggle {
    border-color: transparent;
    color: #fff !important;
  }
  
  footer .glyphicon {
    font-size: 20px;
    margin-bottom: 20px;
    color: #006666;
  }
  
  @media screen and (max-width: 768px) {
    .col-sm-4 {
      text-align: center;
      margin: 25px 0;
    }
    .btn-lg {
      width: 100%;
      margin-bottom: 35px;
    }
  }
  @media screen and (max-width: 480px) {
    .logo {
      font-size: 150px;
    }
  }
  </style>
</head>
 
 <!-- Home Page -->
<body id="myPage" data-spy="scroll" data-target=".navbar" data-offset="60">

<!--Navbar, titels aangepast, nieuwe buttons erbij en glyphicon toegevoegd aan de navbar brand  -->
<nav class="navbar navbar-inverse navbar-fixed-top">
  <div class="container-fluid">
    <div class="navbar-header">
      <button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#myNavbar">
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>
        <span class="icon-bar"></span>                        
      </button>
      <a class="navbar-brand" href="#myPage">PWS</a>
    </div>
    <div class="collapse navbar-collapse" id="myNavbar">
      <ul class="nav navbar-nav">
        <li class="active"><a href="#myPage">HOME</a></li>
        <li><a href="#hoofdstuk1">INHOUD AKKOORD</a></li>
        <li><a href="#hoofdstuk2">REDENEN</a></li>
        <li><a href="#hoofdstuk3">UITTREDING</a></li>
        <li><a href="#hoofdstuk4">RELATIES</a></li>
        <li><a href="#hoofdstuk5">TOEKOMST</a></li>
        <li><a href="#eigenvoorspelling">VOORSPELLING</a></li>
      </ul>
     </div>
  </div>
</nav>

<!-- Jumbotron zal er ook al in, kleuren en text verandert en deel van text italics gemaakt -->
<div class="jumbotron text-center">
  <h1>PWS - Het Parijsakkoord</h1> 
  <p>Door Julia Hoevenaar</p> 
  <p><i>Wat is het effect van het uitreden uit het Parijskoord door de VS op de toekomst van het akkoord en de internationale betrekkingen?</i></p>
</div>

<!-- Hoofdstuk 1, bij alle hoofdstukken colums aangepast en text en plaatjes toegevoegd-->
<div id="hoofdstuk1" class="container-fluid">
  <div class="row">
    <div class="col-sm-8">
      <h2>Inhoud van het Parijsakkoord</h2>
      <h4>Om te begrijpen wat het effect is van het verlaten van het Parijsakkoord door de VS is het belangrijk om te bekijken wat er in het akkoord zelf staat en hoe het in elkaar zit. In dit hoofdstuk behandel ik de totstandkoming van het akkoord, de algemene inhoud van het akkoord, de binding van de afspraken en kritiek die erop is gekomen.</h4>
    <p> In het Parijs-akkoord staat samengevat dat alle landen samen moeten werken om er zo voor te zorgen dat de gemiddelde temperatuur niet meer stijgt dan 2.0°C. Hiervoor moeten de landen hun uitstoot van broeikasgassen beperken. De doelen die landen hebben om minder broeikasgassen uit te stoten worden samengevat in NDCs, die landen zelf kunnen bepalen. Het niet nakomen van de beloftes heeft geen consequenties. Het idee is dat landen elkaar door groepsdruk motiveren om hard hun best te doen. Elke 5 jaar wordt gecontroleerd of landen hun NDCs hebben gehaald en moeten ze nieuwe doelen indienen. Ook wordt voor het akkoord een Climate Fund opgezet, waar rijkere landen aan kunnen doneren om zo armere landen te helpen met het behalen van hun doelen. Het Parijs-akkoord is er dus alleen om de doelen te inventariseren, te evalueren en het voor alle landen mogelijk te maken om maatregelen te treffen. De kritiek die op het akkoord is gekomen is onder andere dat het mechanisme zonder bindende consequenties niet werkt, het ontoereikend is om het uiteindelijke doel van maximaal 2.0°C opwarming te behalen, er te weinig richtlijnen zijn rond de NDCs en er niets wordt gezegd over de lucht- en scheepvaart.
</p>
    </div>
    <div class="col-sm-4">
      <br><img class="img-responsive" src="https://upload.wikimedia.org/wikipedia/en/thumb/a/ae/2015_Climate_Conference.svg/1200px-2015_Climate_Conference.svg.png" alt="Logo of COP21">
    </div>
  </div>
</div>

<!-- Hoofdstuk 2 -->
<div id="hoofdstuk2" class="container-fluid">
  <div class="row">
    <div class="col-sm-4">
       <br><img class="img-responsive" src="https://s.abcnews.com/images/Politics/paris-agreement-01-ap-jrl-180531_hpMain_4x5_992.jpg" alt="Trump speech over klimaatakkoord"><br><br><br>
      <img class="img-responsive" src="https://cloudinary.cagle.com/image/upload/w_600/cartoons/191175.png" alt="Trump cartoon klimaatakkoord">
    </div>
    <div class="col-sm-8">
      <h2>Waarom verlaat de VS het Parijsakkoord?</h2>
      <h4>Op 1 juni 2017 maakte Trump bekent dat de VS het klimaatakkoord van Parijs zou verlaten. Trump zei over deze beslissing dat hij het had besloten ‘om zijn plicht te vervullen de burgers van de Verenigde Staten te beschermen.’ Verder liet hij weten dat hij er open voor stond om over het akkoord te onderhandelen, maar de UNFCCC liet weten dat er geen onderhandeling gestart kunnen worden door een enkele deelnemer van het akkoord. Daarnaast bekritiseerde Trump het Green Climate Fund en noemde het een manier om rijkdom van de rijkere naar de armere landen te verplaatsen. In dit hoofdstuk ga ik op zoek naar de redenen van Trump’s beslissing. Er zijn namelijk 
meerdere redenen die hebben geleid tot zijn beslissing. </h4>
       <p>Ten eerste heeft Trump meerdere keren gezegd, in vooral tweets, dat hij niet gelooft in klimaatverandering. Daarom denkt hij dat de kosten van het Parijs-akkoord nutteloos zijn, aangezien de mens volgens hem helemaal niet zoveel impact heeft op het klimaat. Ondertussen lijkt het alsof Trump deze uitspraken over klimaatverandering doet om een excuus te hebben voor zijn beslissingen, zoals het ontmantelen van Obama’s Clean Power Plan en dus het verlaten van het Parijs-akkoord. Waarschijnlijk is er dus een diepere achterliggende rede voor zijn beslissing </p>
      <p>Een achterliggende rede voor Trump’s uitspraken over klimaatverandering is dat hij de beslissing eigenlijk alleen maar maakt om politieke redenen. Tot nu toe heeft Trump moeite met het nakomen van zijn belangrijkste beloftes. Veel van zijn beloftes zijn geëindigd in compromissen of nog totaal niet nagekomen. Om zijn kiezers toch tevreden te stellen, heeft Trump besloten het Parijs-akkoord te verlaten. Deze beslissing is ook in lijn met zijn campagneslogan ‘America First’, omdat hij door het akkoord te verlaten het welzijn van de VS verkiest boven dat van de wereld. Door uit te gaan van wat hij in zijn campagne beloofde, hoopt hij meer kiezers voor zich te winnen.</p>
      <p>Een andere rede die meespeelt is dat Trump vindt dat de maatregelen te veel geld kosten. Trump vindt dat de NDCs die door Obama zijn ingediend de VS te duur zijn en oneerlijk zijn tegenover de burgers van de VS. Als laatste heeft Trump ook gezegd dat hij niet gelooft dat het mechanisme van het Parijs-akkoord, wat uitgaat van vrijwillige bijdragen, niet in staat zal zijn het probleem van klimaatverandering op te lossen. Daarom is het geld dat er naartoe gaat nutteloos.</p>
      </div>
  </div>
</div>

<!-- Hoofdstuk 3 -->
<div id="hoofdstuk3" class="container-fluid">
  <div class="row">
    <div class="col-sm-8">
      <h2>Kans dat de VS het Parijsakkoord echt verlaat</h2>
      <h4>Hoewel Trump bekend heeft gemaakt dat hij het Parijs-akkoord wil verlaten, bestaat er nog veel onzekerheid over hoe groot de kans is dat dat echt gebeurt. De uitslag van de verkiezingen van 2020 in de VS kunnen alles nog veranderen. In dit hoofdstuk behandel ik de regels over het verlaten van het Parijs-akkoord, de gevolgen van de uitslag van de volgende verkiezingen en de grootte van de kans dat Trump wordt herkozen. </h4>
      <p>Het duurt veel langer om het Parijs-akkoord te verlaten dan om het toe te treden of weer te herintreden. Uitreden uit het akkoord kan pas 3 jaar nadat het akkoord in werking is getreden en dan is er ook nog een verwerkingstijd van 1 jaar. Toetreden of herintreden kan in slechts 30 dagen. Als Trump niet wordt herkozen bij de volgende verkiezingen, zal de VS herintreden tot het Parijs-akkoord. Alle tegenstanders van Trump hebben namelijk laten weten dat ze dat van plan zijn als ze de verkiezingen winnen. Over de kans dat Trump de verkiezingen wint is nog weinig te zeggen, omdat de polls dicht bij elkaar liggen. Daarnaast voorspelden de polls in 2016 ook dat Hillary Clinton zou winnen won Trump alsnog.</p>
    </div>
    <div class="col-sm-4">
      <br><img class="img-responsive" src="https://cdn.vox-cdn.com/thumbor/OdBTI43zJk_o0sI9nO39OEo1RSE=/0x0:1501x2790/1200x0/filters:focal(0x0:1501x2790):no_upscale()/cdn.vox-cdn.com/uploads/chorus_asset/file/12438451/180821_2020_matchup_sidebar.png" alt="Polls 2020 verkiezingen VS">
    </div>
  </div>
  </div>
  
<!-- Hoofdstuk 4 -->
<div id="hoofdstuk4" class="container-fluid">
    <div class="row">
       <div class="col-sm-4">
      <br><img class="img-responsive" src="https://media.newyorker.com/photos/5930923fd7cd35454b875d11/master/w_2560%2Cc_limit/Davidson-Merkel-Trump-Comments.jpg" alt="Merkel kijkt naar Trump"><br>
      <img class="img-responsive" src="https://s.abcnews.com/images/International/trump-bolsonaro-rt-ml-190319_hpMain_4x5_992.jpg" alt="Trump en Bolsonaro">
    </div>
      <div class="col-sm-8">
       <h2>Internationale Betrekkingen</h2>
        <h4>De relaties tussen de VS en andere landen in de wereld verandert doordat de het land uit het Parijs-akkoord stapt. In dit hoofdstuk behandel ik hoe de relatie tussen de VS en andere landen nu is, hoe die kan veranderen nadat de VS het akkoord verlaat en de positie als voorbeeld van de VS</h4>
        <p>Als Trump wel wordt herkozen en de VS uit het Klimaatakkoord van Parijs treedt, in ieder geval gedurende de komende termijn van 4 jaar, zijn er verschillende scenario’s mogelijk in de toekomst. De relaties tussen de VS en de andere landen verliepen al redelijk stroef sinds Trump president is en de beslissing om het Parijs-akkoord te verlaten helpt niet mee om die te verbeteren. Toch blijven de relaties waarschijnlijk redelijk stabiel, omdat de VS erg machtig en rijk is. Bijna alle landen zijn erg afhankelijk van de VS en zullen daarom niet snel ruzie zoeken met het land. <br><br> De beslissing van Trump die in lijn is met zijn America First beleid kan wel als
voorbeeld worden gezien door andere landen. In bijvoorbeeld Brazilië en Australië zijn recent rechtse leiders aan de macht gekomen die het voorbeeld van Trump volgen en vooral keuzes maken waar hun eigen land profijt van heeft, maar wat voor de rest van de wereld niet per se de beste keuze is. </p>
   </div>
  </div> 
  </div>

<!-- Hoofdstuk 5 -->
<div id="hoofdstuk5" class="container-fluid">
   <div class="row">
    <div class="col-sm-8">
      <h2>Toekomst van het akkoord</h2>
          <h4>De leider van het Parijs-akkoord wil het akkoord verlaten. Dit zal zeker een impact
hebben op de toekomst van het akkoord. In dit hoofdstuk behandel ik verschillende
perspectieven over hoe de toekomst van het akkoord eruit ziet en de mogelijkheid van
een nieuwe leider. </h4>
          <p>De toekomst van het akkoord is lastig te voorspellen. Ik heb in mijn profielwerkstuk 3 scenario’s onderscheiden. Het kan dat landen het voorbeeld van Trump volgen, voor zichzelf kiezen en daarom het akkoord verlaten of niet meer hun best gaan doen om hun doelen te bereiken. Dan zal het akkoord uit elkaar vallen. Een ander scenario is dat de landen niet het akkoord verlaten, wellicht omdat de druk van de burgers te groot is, maar ook niet meer hun best doen om de NDCs te halen. Dan zal het akkoord wel blijven bestaan, maar nauwelijks effect hebben. De laatste mogelijkheid is dat door meer druk van de straat en de media en bijvoorbeeld lagere prijzen van duurzame energie landen toch hun NDCs halen en meer gemotiveerd zijn en de akkoord in staat is om de opwarming van de aarde te beperken.
<br> <br> Ook over een nieuwe leider van het Parijs-akkoord is nog veel onzekerheid. Wellicht wordt het China, misschien de EU of een verzameling van landen die het eerst de gevolgen van klimaatverandering zullen ondervinden. Misschien komt er helemaal geen nieuwe leider. </p>
    </div> 
       <div class="col-sm-4">
      <br>
        <img class="img-responsive" src="https://www.rollingstone.com/wp-content/uploads/2019/03/GettyImages-1135966575.jpg?w=800" alt="Klimaatstaking"><br><br>
       <img class="img-responsive" src="https://image.cnbcfm.com/api/v1/image/106237415-1573481552152rtx78e3r.jpg?v=1573481622&w=678&h=381" alt="Xi Jinping">
    </div>
  </div> 
  </div>
  
<!-- Eigen voorspelling -->
<div id="eigenvoorspelling" class="container-fluid">
  <div class="row">
   <div class="col-sm-4"> 
     <br>
    <img class="img-responsive" src="https://img2.chinadaily.com.cn/images/201909/19/5d82da3ca310cf3e979cf08b.jpeg" alt="Caroon aarde"> 
      </div>
  <div class="col-sm-8">
    <h2>Eigen voorspelling</h2>
         <h4>Over hoe de toekomst van het Parijs-akkoord eruit ziet zijn vele verschillende meningen. Hier zal ik mijn inschatting doen van de toekomst gebaseerd op mijn bevindingen tijdens het schrijven van mijn profielwerkstuk.</h4>
           <p>Mijn eigen verwachting is dat China de leiderschapsrol zal invullen en de kans pakt om zijn imago op te poetsen. Daarnaast denk ik dat de toekomst van het akkoord er niet al te rooskleurig uit zal zien. Dat andere landen het akkoord ook gaan verlaten zie ik niet zo snel gebeuren, maar ik denk wel dat de landen te weinig zullen doen om de opwarming van de aarde te beperken tot 2.0°C. <br> <br> Het effect van Trump’s beslissing op met de VS uit het Parijs-akkoord te treden kan dus allerlei gevolgen hebben. Het valt eerst nog te bezien of de VS daadwerkelijk voor langere tijd uit het akkoord stapt. Als dat wel gebeurt kan het akkoord falen of een groot succes worden. De kans dat het gaat falen acht ik vrij groot. Ik hoop natuurlijk op een succes.</p>
    </div>
   </div> 
  </div>
     

<!-- Footer -->
<footer class="container-fluid text-center">
  <br><br>
  <a href="#myPage" title="To Top">
    <span class="glyphicon glyphicon-chevron-up"></span>
  </a>
  <p>Bootstrap Theme Made By <a href="https://www.w3schools.com">w3schools</a></p> 
</footer>

<!--Javascript, dit zat ook al in het theme. Volgens mij zorgt dit ervoor dat de site niet crashed en goed werkt.-->
<script>
$(document).ready(function(){
 $(".navbar a, footer a[href='#myPage']").on('click', function(event) {
   if (this.hash !== "") {
    event.preventDefault();
  var hash = this.hash;
 $('html, body').animate({
        scrollTop: $(hash).offset().top
      }, 900, function(){
   window.location.hash = hash;
      });
    } 
  });
  
  $(window).scroll(function() {
    $(".slideanim").each(function(){
      var pos = $(this).offset().top;
       var winTop = $(window).scrollTop();
        if (pos < winTop + 600) {
          $(this).addClass("slide");
        }
    });
  });
})
</script>


