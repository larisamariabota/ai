<!DOCTYPE html>
<html lang="en">
<head>
    <title>Inteligența Artificială</title>
    <meta charset="UTF-8">
   
</head>
<body>
<style>
/* Stiluri CSS */

html {
    background-color: #7bbfd6;
    color: purple;
    margin: 0;
    padding: 0;
}

body {
    display: flex;
    flex-direction: column;
    align-items: center;
    background-color: #7bbfd6;
}

header {
    width: 100%;
    background-color: #536895;
    color: white;
    text-align: center;
    padding: 9px;
}

.div img {
    filter: saturate(0%);
    width: 10%;
    border: 2px solid whitesmoke;
    height: 100%;
    object-fit: cover;
    border-radius: 10px;
    transition: all ease 0.4s;
    cursor: pointer;
}


.div img:hover {
    filter: saturate(100%);
    width: 50%;
}


.cadru-mic {
    border: 4px solid pink;
    padding: 50px;
    width: 350px;
    text-align: center;
    margin-bottom: 20px;
	font-family:  Lucida Handwriting,cursive;
	font-size:20;
}


ul {
    list-style-type: none;
    padding: 0;
    display: flex;
}

.meniu {
    list-style-type: none;
    padding: 0;
    display: flex;
    justify-content: center;
    margin-top: 25px;
    position: relative;
}

.meniu li {
    margin: 0 15px;
    position: relative;
}

.meniu a {
    text-decoration: none;
    color: gray;
    font-weight: bold;
    font-size: 22px;
    position: relative;
    transition: color 0.3s ease;
}

.meniu a:hover {
    color: #ff4400;
}

.meniu a::before {
    content: "";
    position: absolute;
    bottom: 0;
    left: 0;
    width: 100%;
    height: 2px;
    background-color: #0a7e8c;
    transform: scaleX(0);
    transform-origin: bottom right;
    transition: transform 0.3s ease;
}

.meniu a:hover::before {
    transform: scaleX(1);
    transform-origin: bottom left;
}

.submeniu {
    display: none;
    position: absolute;
    background-color: #f9f9f9;
    box-shadow: 0 6px 12px 0 rgba(0,0,0,0.2);
    z-index: 1;
    padding: 9px;
    top: 100%;
    left: 0;
    width: 140px;
}

.submeniu li {
    float: none;
    padding: 7px;
}

.meniu li:hover .submeniu {
    display: block;
}
h1{
text-align: center;

color: #ffb6c1;
 }
 .titlu {
        color: transparent;
        font-size: 74px; /* Mărește dimensiunea textului */
        background-image: url('fanda.jpg');
        -webkit-background-clip: text; /* Cliparea imaginii în text */
        background-clip: text; /* Pentru compatibilitate cu browserele care nu utilizează prefixul -webkit- */
        text-fill-color: transparent; /* Pentru a păstra culoarea textului transparentă */
    }
div.static {
position: fixed;
  bottom: 0;
  right: 0;

  width: 10px;
  height: 3px;
  
            
}

/* Adăugare stiluri pentru poziționarea imaginilor */
.imagine-sus-stanga {
    position: fixed;
    top: 0;
    left: 0;
}

.imagine-sus-dreapta {
    position: fixed;
    top: 0;
    right: 0;
}

.imagine-jos-stanga {
    position: fixed;
    bottom: 0;
    left: 0;
}

.imagine-jos-dreapta {
    position: fixed;
    bottom: 0;
    right: 0;
}
</style>

<header>
    <h1 class="titlu">Inteligența Artificială</h1>
    <nav>
        <ul class="meniu">
            <li>
                <a href="#evolutia-ai">Cum a apărut AI</a>
                <ul class="submeniu">
                    <li><a href="evolutia-ai.html">Cum s-a format AI</a></li>
               
                </ul>
            </li>
			
			<li>
                <a href="ai-azi">AI azi</a>
                <ul class="submeniu">
                    <li><a href="google.html">Asistențe personale</a></li>
                    <li><a href="chatbot.html">Chatbots</a></li>
					 <li><a href="chatgbt.html">Chatgpt</a></li>
                    <li><a href="boc.html">BOC</a></li>
                    <li><a href="arta.html">Arta în era digitală</a></li>
                    
                </ul>
			
            <li>
			
                <a href="#viitorul-ai">Viitorul AI</a>
                <ul class="submeniu">
                    <li><a href="meta.html">Metaverse</a></li>
                    <li><a href="nano.html">Nano-
					tehnologia</a></li>
					
               
                </ul>
            </li>
			
            <li>
                <a href="#concluzii">Amenințarea-ai</a>
                <ul class="submeniu">
                    <li><a href="amen.html">Sănătatea afectată</a></li>
                    
                </ul>
            </li>
			
			</ul>
    </nav>
</header>

<div class="div">
    <img class="imagine-sus-dreapta" src="desen2.jpg" alt="">
    <img src="p13.jpg" alt="">
    <img src="p12.jpg" alt="">
	<img src="anim.gif" alt="">
	<img src="concluzii.jpg" alt="">
	<img src="mm.jpg"alt="">
	<img src="of.jpg" alt="">
	<img class="imagine-jos-stanga" src="desen.jpg" alt="">
   
</div>

<div class="cadru-mic">
    <p>Inteligența artificială (IA) se referă la capacitatea calculatoarelor și a sistemelor informatice de a simula inteligența umană. Acest lucru implică învățarea din date, luarea deciziilor și rezolvarea problemelor în mod autonom.</p>
</div>

</body>
</html>
