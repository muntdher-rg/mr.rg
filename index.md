<!DOCTYPE html>
<html>
    <head>
        <title>muntadher</title>
        <meta charset="utf-8">
        <style>
           
@import url('https://fonts.googleapis.com/css?family=Poppins&display=swap');

* {
	box-sizing: border-box;
}

body {
	background-color:black
	color: black
	font-family: 'Poppins', sans-serif;
	margin: 0;
}

header {
	background-image: url('https://www.google.com/imgres?imgurl=https%3A%2F%2Fe-cdns-images.dzcdn.net%2Fimages%2Fartist%2F0df7c9931cdb8de51bb5de1db35116b8%2F500x500.jpg&imgrefurl=http%3A%2F%2Fwww.deezer.com%2Fnl%2Fartist%2F167095%3Fapp_id%3D100023&tbnid=VUgd8dmaLyS_BM&vet=12ahUKEwib36vEzKDpAhUat6QKHasTDyMQMygKegUIARCHAg..i&docid=2LVXJrhVbvBYNM&w=500&h=500&q=2pac&ved=2ahUKEwib36vEzKDpAhUat6QKHasTDyMQMygKegUIARCHAg');
	background-size: cover;
	background-position: center center;
	display: flex;
	align-items: center;
	justify-content: center;
	min-height: calc(100vh - 64px);	
	position: relative;
}

header * {
	z-index: 1;
}

header::after {
	content: '';
	background-color: #000;
	opacity: 0.4;
	position: absolute;
	top: 0;
	left: 0;
	height: 100%;
	width: 100%;
}

header h1 {
	color: rgb(14, 12, 12);
	font-size: 4em;
	text-align: center;
	width: 60%;
}

nav {
	background-color: #fff;
	box-shadow: 0 3px 5px rgba(0, 0, 0, 0.1);
	display: flex;
	align-items: center;
	justify-content: space-between;
	flex-wrap: wrap;
	padding: 15px;
}

nav p {
	color: rgb(19, 20, 20);
	font-weight: bold;
	margin: 5px;
	letter-spacing: 1px;
	text-transform: uppercase;
}

.burger {
	border: 0;
	cursor: pointer;
	display: none;
	font-size: 22px;
	position: relative;
	padding: 0;
	outline: none;
	height: 30px;
	width: 30px;
}

.burger:active {
	color: #0594EC;
	outline: none;
}

.burger .bar {
	background-color: #0594EC;
	position: absolute;
	left: 50%;
	transform: translate(-50%, -50%) rotate(0deg);
	height: 3px;
	width: 20px;
	transition: transform 0.2s ease;
}

.burger .bar:first-of-type {
	top: 40%;
}

.burger .bar:last-of-type {
	top: 60%;
}

ul {
	display: flex;
	margin: 0;
	padding: 0;
	list-style-type: none;
}

ul li {
	margin: 0 10px;
}

ul li a {
	color: #2C405E;
	position: relative;
	text-decoration: none;
}

ul li a::after {
	content: '';
	background-color: #2C405E;
	position: absolute;
	bottom: -18px;
	left: 0;
	opacity: 0;
	height: 2px;
	width: 100%;
	transition: transform 0.2s ease;
}

ul li a:hover::after {
	opacity: 1;
	transform: translateY(-15px);
}

@media screen and (max-width: 480px) {
	header h1 {
		font-size: 2em;
	}
	
	.burger {
		display: block;
	}
	
	.burger.show-x .bar:first-of-type {
		transform: translate(-50%, 50%) rotate(225deg);
	}
	
	.burger.show-x .bar:last-of-type {
		transform: translate(-50%, -150%) rotate(-225deg);
	}
	
	ul {
		background-color: #fff;
		box-shadow: 0 3px 5px rgba(0, 0, 0, 0.1);
		flex-direction: column;
		text-align: center;
		position: fixed;
		top: 80px;
		left: 10%;
		transform: translateX(120%);
		width: 80%;
		transition: transform 0.3s ease-in;
		z-index: 100;
	}
	
	ul.show {
		transform: translateX(0);
	}
	
	ul li {
		margin: 15px;
	}
}

.a {
  background-image: url(2pac.jpg);
}

.b {
  background-image: url();
}
    

/*
* The function calc is working wrong in case calculations in the Firefox
*/

.photobox{
  display: inline-block;
}

.photobox__previewbox{
  position: relative;
  overflow: hidden;
}

.photobox__preview{
  display: block;
  max-width: 100%;
}

.photobox__previewbox:before{
  content: "";
}

/* type 1 */

.photobox_type1 .photobox__previewbox:before{
  width: 0;
  height: 0;
  padding: 25%;
  border-radius: 50%;
  
  position: absolute;
  top: 0;
  left: 0;

  background-color: var(--photoboxOverlay, rgba(0, 0, 0, .8));
  transition: transform calc(var(--photoboxAnimationDuration, .4s) / 2) ease calc(var(--photoboxAnimationDuration, .2s) / 2);
  will-change: transform;
  transform: scale(0);
}

.photobox_type1:hover .photobox__previewbox:before{
  transform: scale(2);
  transition-duration: var(--photoboxAnimationDuration, .4s);
  transition-delay: 0s;
}

.photobox_type1 .photobox__label{
  width: 50%;
  transform: translate(-200%, -50%);
  transition: transform var(--photoboxAnimationDuration, .4s) ease-out;
  will-change: transform;
  
  position: absolute;
  top: 50%;
  left: 15%;
}

.photobox_type1:hover .photobox__label{
  transition-duration: var(--photoboxAnimationDuration, .4s);
  transform: translate(0, -50%);
}

/* type 2*/

.photobox_type2 .photobox__previewbox:before{
  width: 0;
  height: 0;
  padding: 25%;
  
  border-radius: 50%;
  background-color: var(--photoboxOverlay, rgba(0, 0, 0, .8));
  
  position: absolute;
  top: 0;
  right: 0;

  transition: transform var(--photoboxAnimationDuration, .2s) ease calc(var(--photoboxAnimationDuration, .2s) / 2);
  will-change: transform;
  transform: scale(0);
}

.photobox_type2:hover .photobox__previewbox:before{
  transform: scale(2);
  transition-duration: var(--photoboxAnimationDuration, .4s);
  transition-delay: 0s;
}

.photobox_type2 .photobox__label{
  width: 50%;
  text-align: right;
  
  transform: translate(200%, -50%);
  transition: transform var(--photoboxAnimationDuration, .4s) ease-out;
  will-change: transform;
  
  position: absolute;
  top: 50%;
  right: 15%;
}

.photobox_type2:hover .photobox__label{
  transition-duration: var(--photoboxAnimationDuration, .4s);
  transform: translate(0, -50%);
}

/* type 3 */

.photobox_type3 .photobox__previewbox:before{
  width: 0;
  height: 0;
  padding: 25%;
  
  background-color: var(--photoboxOverlay, rgba(0, 0, 0, .8));
  border-radius: 50%;
  
  position: absolute;
  top: 50%;
  left: 50%;
  z-index: 2;

  transition: transform var(--photoboxAnimationDuration, .4s) ease;
  will-change: transform;
  transform: translate(-50%, -50%) scale(0);
}

.photobox_type3:hover .photobox__previewbox:before{
  transform: translate(-50%, -50%) scale(4);
  transition-duration: calc(var(--photoboxAnimationDuration, .4s) * 2);
}

.photobox_type3 .photobox__label{
  width: 95%;
  text-align: center;
  
  opacity: 0;
  transform: translate(-50%, -50%);
  transition: opacity var(--photoboxAnimationDuration, .4s) ease-out;
  will-change: opacity;
  
  position: absolute;
  top: 50%;
  left: 50%;
  z-index: 3;
}

.photobox_type3:hover .photobox__label{
  transition-duration: calc(var(--photoboxAnimationDuration, .4s) / 2);
  transition-delay: calc(var(--photoboxAnimationDuration, .4s) / 2);
  opacity: 1;
}

.photobox_type3 .photobox__preview{
    transition: transform var(--photoboxAnimationDuration, .4s) cubic-bezier(0.71, 0.05, 0.29, 0.9);
  will-change: transform;
    transform: scale(1);
}

.photobox_type3:hover .photobox__preview{
  transform: scale(1.2);
}

/* type 4 */

.photobox_type4 .photobox__previewbox:before{
  width: 0;
  height: 0;
  padding: 25%;
  
  background-color: var(--photoboxOverlay, rgba(0, 0, 0, .8));
  border-radius: 50%;
  
  position: absolute;
  top: 50%;
  left: 50%;
  z-index: 2;

  transition: transform var(--photoboxAnimationDuration, .4s) ease;
  will-change: transform;
  transform: translate(-50%, -50%) scale(0);
}

.photobox_type4:hover .photobox__previewbox:before{
  transform: translate(-50%, -50%) scale(4);
  transition-duration: calc(var(--photoboxAnimationDuration, .4s) * 2);
}

.photobox_type4 .photobox__label{
  width: 95%;
  text-align: center;
  
  opacity: 0;
  transform: translate(-50%, -50%);
  transition: opacity var(--photoboxAnimationDuration, .4s) ease-out;
  will-change: opacity;
  
  position: absolute;
  top: 50%;
  left: 50%;
  z-index: 3;
}

.photobox_type4:hover .photobox__label{
  transition-duration: calc(var(--photoboxAnimationDuration, .4s) / 2);
  transition-delay: calc(var(--photoboxAnimationDuration, .4s) / 2);
  opacity: 1;
}

.photobox_type4 .photobox__preview{
    transition: transform var(--photoboxAnimationDuration, .4s) cubic-bezier(0.71, 0.05, 0.29, 0.9);
  will-change: transform;
    transform: scale(1) translate(0, 0);
}

.photobox_type4:hover .photobox__preview{
  transform: scale(1.2) translate(4%, 4%);
}

/* type 5 */

.photobox_type5 .photobox__previewbox:before{
  width: 0;
  height: 0;
  padding: 25%;
  
  background-color: var(--photoboxOverlay, rgba(0, 0, 0, .8));
  border-radius: 50%;
  
  position: absolute;
  top: 50%;
  left: 50%;
  z-index: 2;

  transition: transform calc(var(--photoboxAnimationDuration, .8s) / 2) ease;
  transform: translate(-50%, -50%) scale(0);
  will-change: transform;
}

.photobox_type5:hover .photobox__previewbox:before{
  transform: translate(-50%, -50%) scale(4);
  transition-duration: var(--photoboxAnimationDuration, .8s);
}

.photobox_type5 .photobox__label{
  width: 95%;
  text-align: center;
  
  transform: translate(-200%, -50%);
  transition: transform calc(var(--photoboxAnimationDuration, .8s) / 2) ease-out;
  will-change: transform;
  
  position: absolute;
  top: 50%;
  left: 50%;
  z-index: 3;
}

.photobox_type5:hover .photobox__label{
  transition-duration: calc(var(--photoboxAnimationDuration, .8s) / 2);
  transform: translate(-50%, -50%);
}

.photobox_type5 .photobox__preview{
    transition: transform calc(var(--photoboxAnimationDuration, .8s) / 2) cubic-bezier(0.71, 0.05, 0.29, 0.9);
  will-change: transform;
    transform: scale(1);
}

.photobox_type5:hover .photobox__preview{
  transform: scale(1.2);
}

/* type 6 */

.photobox_type6 .photobox__previewbox:before{
  width: 0;
  height: 0;
  padding: 25%;
  
  background-color: var(--photoboxOverlay, rgba(0, 0, 0, .8));
  border-radius: 50%;
  
  position: absolute;
  top: 50%;
  left: 50%;

  transition: transform calc(var(--photoboxAnimationDuration, .8s) / 2) ease;
  will-change: transform;
  transform: translate(-50%, -50%) scale(0);
}

.photobox_type6:hover .photobox__previewbox:before{
  transform: translate(-50%, -50%) scale(4);
  transition-duration: var(--photoboxAnimationDuration, .8s);
}

.photobox_type6 .photobox__label{
  width: 95%;
  text-align: center;
  
  transform: translate(-200%, -50%);
  transition: transform calc(var(--photoboxAnimationDuration, .8s) / 2) ease-out;
  will-change: transform;
  
  position: absolute;
  top: 50%;
  left: 50%;
}

.photobox_type6:hover .photobox__label{
  transition-duration: calc(var(--photoboxAnimationDuration, .8s) / 2);
  transform: translate(-50%, -50%);
}

/* type 7 */

.photobox_type7 .photobox__previewbox:before{
  width: 0;
  height: 0;
  padding: 25%;
  
  background-color: var(--photoboxOverlay, rgba(0, 0, 0, .8));
  border-radius: 50%;
  
  position: absolute;
  top: 50%;
  left: 50%;
  z-index: 2;

  transition: transform calc(var(--photoboxAnimationDuration, .8s) / 2) ease;
  will-change: transform;
  transform: translate(-50%, -50%) scale(0);
}

.photobox_type7:hover .photobox__previewbox:before{
  transform: translate(-50%, -50%) scale(4);
  transition-duration: var(--photoboxAnimationDuration, .8s);
}

.photobox_type7 .photobox__label{
  width: 95%;
  text-align: center;
  
  transform: translate(-200%, -50%);
  transition: transform calc(var(--photoboxAnimationDuration, .8s) / 2) ease-out;
  will-change: transform;
  
  position: absolute;
  top: 50%;
  left: 50%;
  z-index: 3;
}

.photobox_type7:hover .photobox__label{
  transition-duration: calc(var(--photoboxAnimationDuration, .8s) / 2);
  transform: translate(-50%, -50%);
}

.photobox_type7 .photobox__preview{
    transition: transform calc(var(--photoboxAnimationDuration, .8s) / 2) cubic-bezier(0.71, 0.05, 0.29, 0.9);
  will-change: transform;
    transform: scale(1) rotate(0);
}

.photobox_type7:hover .photobox__preview{
  transform: scale(1.2) rotate(5deg);
}

/* type 8 */

.photobox_type8 .photobox__previewbox:before{
  width: 0;
  height: 0;
  padding: 25%;
  
  background-color: var(--photoboxOverlay, rgba(0, 0, 0, .8));
  border-radius: 50%;
  
  position: absolute;
  top: 50%;
  left: 50%;
  z-index: 2;

  transition: transform calc(var(--photoboxAnimationDuration, .8s) / 2) ease;
  will-change: transform;
  transform: translate(-50%, -50%) scale(0);
}

.photobox_type8:hover .photobox__previewbox:before{
  transform: translate(-50%, -50%) scale(4);
  transition-duration: var(--photoboxAnimationDuration, .8s);
}

.photobox_type8 .photobox__label{
  width: 95%;
  text-align: center;
  
  opacity: 0;  
  transition: opacity calc(var(--photoboxAnimationDuration, .8s) / 4) cubic-bezier(0.71, 0.05, 0.29, 0.9), transform calc(var(--photoboxAnimationDuration, .8s) / 4) cubic-bezier(0.71, 0.05, 0.29, 0.9);
  will-change: opacity, transform;
  
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, 200%);
  z-index: 3;
}

.photobox_type8:hover .photobox__label{
  opacity: 1;
  transform: translate(-50%, -50%);
  transition-duration: calc(var(--photoboxAnimationDuration, .8s) / 2);
  transition-delay: calc(var(--photoboxAnimationDuration, .8s) / 4);
}

.photobox_type8 .photobox__preview{
    transition: transform calc(var(--photoboxAnimationDuration, .8s) / 2) cubic-bezier(0.71, 0.05, 0.29, 0.9);
  will-change: transform;
    transform: scale(1) rotate(0);
}

.photobox_type8:hover .photobox__preview{
  transform: scale(1.2) rotate(5deg);
}

/* type 9 */

.photobox_type9 .photobox__previewbox:before{
  width: 0;
  height: 0;
  padding: 25%;
  
  background-color: var(--photoboxOverlay, rgba(0, 0, 0, .8));
  border-radius: 50%;
  
  position: absolute;
  top: 50%;
  left: 50%;
  z-index: 2;

  transition: transform calc(var(--photoboxAnimationDuration, .8s) / 2) ease;
  will-change: transform;
  transform: translate(-50%, -50%) scale(0);
}

.photobox_type9:hover .photobox__previewbox:before{
  transform: translate(-50%, -50%) scale(4);
  transition-duration: var(--photoboxAnimationDuration, .8s);
}

.photobox_type9 .photobox__label{
  width: 95%;
  text-align: center;
  
  opacity: 0;  
  transition: opacity calc(var(--photoboxAnimationDuration, .8s) / 4) cubic-bezier(0.71, 0.05, 0.29, 0.9), transform calc(var(--photoboxAnimationDuration, .8s) / 4) cubic-bezier(0.71, 0.05, 0.29, 0.9);
  will-change: opacity, transform;
  
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, 200%);
  z-index: 3;
}

.photobox_type9:hover .photobox__label{
  opacity: 1;
  transform: translate(-50%, -50%);
  transition-duration: calc(var(--photoboxAnimationDuration, .8s) / 2);
  transition-delay: calc(var(--photoboxAnimationDuration, .8s) / 4);
}

.photobox_type9 .photobox__preview{
    transition: transform calc(var(--photoboxAnimationDuration, .8s) / 2) cubic-bezier(0.71, 0.05, 0.29, 0.9);
  will-change: transform;
    transform: scale(1);
}

.photobox_type9:hover .photobox__preview{
  transform: scale(1.2);
}

/*
* demo styles for photobox
*/

.photobox{
  color: #fff;
  font-size: 2.5rem;
  font-weight: 700;
  width: 33.33333%;
  --photoboxOverlay: rgba(72, 27, 174, .7);
  /*--photoboxAnimationDuration: .5s;*/
}

@media screen and (max-width: 480px){
  .photobox{
    width: 100%;
  }
}

/*
=====
DEMO
=====
*/

@media (min-width: 768px){

  html{
    font-size: 62.5%;
  }
}

@media (max-width: 767px){

  html{
    font-size: 50%;
  }
}

body{
  font-family: -apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Open Sans, Ubuntu, Fira Sans, Helvetica Neue, sans-serif;
  font-size: 1.6rem;
  color: #fff;
  margin: 0;
  overflow-y: scroll;
  -webkit-overflow-scrolling: touch;   
  
  min-height: 100vh;
  display: flex;
  flex-direction: column;  
}

a{
  text-decoration: none;
  color: inherit;
}

a:hover, a:focus{
  text-decoration: underline;
}

.page{
  flex-grow: 1;
  order: 1;
}

.page__container{
  display: flex;
  flex-wrap: wrap;
  align-items: flex-start;
}



مصادر

        </style>
        <script>
const burger = document.getElementById('burger');
const ul = document.querySelector('nav ul');

burger.addEventListener('click', () => {
	burger.classList.toggle('show-x');
	ul.classList.toggle('show');
});
        </script>
    </head>
    <body>
        <nav>
            <p>mr.rg</p>
            
            <button id="burger" class="burger">
                <div class="bar"></div>
                <div class="bar"></div>
            </button>
            
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">Blog</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>
        <header>
            <h1>mumtadher-rg web site dv cco</h1>

           
        </header>
        <div class="wrapper">
            <div class="box a"></div>
            <div class="box b"></div>
          </div>
          <div class="page">
            <div class="page__demo">
              <div class="page__container">
                <div class="photobox photobox_type1">
                  <div class="photobox__previewbox">
                    <img src="https://stas-melnikov.ru/cliparts/man3_640x426.jpg" class="photobox__preview" alt="Preview">
                    <span class="photobox__label">Effect #1</span>
                  </div>
                </div>
                <div class="photobox photobox_type2">
                  <div class="photobox__previewbox">
                    <img src="https://stas-melnikov.ru/cliparts/girl3_640x426.jpg" class="photobox__preview" alt="Preview">
                    <span class="photobox__label">Effect #2</span>
                  </div>
                </div>
                <div class="photobox photobox_type3">
                  <div class="photobox__previewbox">
                    <img src="https://stas-melnikov.ru/cliparts/nature640x426.jpg" class="photobox__preview" alt="Preview">
                    <span class="photobox__label">Effect #3</span>
                  </div>
                </div>
                <div class="photobox photobox_type4">
                  <div class="photobox__previewbox">
                    <img src="https://stas-melnikov.ru/cliparts/girl3_640x426.jpg" class="photobox__preview" alt="Preview">
                    <span class="photobox__label">Effect #4</span>
                  </div>
                </div>            
                <div class="photobox photobox_type5">
                  <div class="photobox__previewbox">
                    <img src="https://stas-melnikov.ru/cliparts/man3_640x426.jpg" class="photobox__preview" alt="Preview">
                    <span class="photobox__label">Effect #5</span>
                  </div>
                </div>                        
                <div class="photobox photobox_type6">
                  <div class="photobox__previewbox">
                    <img src="https://stas-melnikov.ru/cliparts/girl3_640x426.jpg" class="photobox__preview" alt="Preview">
                    <span class="photobox__label">Effect #6</span>
                  </div>
                </div>
                <div class="photobox photobox_type7">
                  <div class="photobox__previewbox">
                    <img src="https://stas-melnikov.ru/cliparts/man3_640x426.jpg" class="photobox__preview" alt="Preview">
                    <span class="photobox__label">Effect #7</span>
                  </div>
                </div>
                <div class="photobox photobox_type8">
                  <div class="photobox__previewbox">
                    <img src="https://stas-melnikov.ru/cliparts/girl3_640x426.jpg" class="photobox__preview" alt="Preview">
                    <span class="photobox__label">Effect #8</span>
                  </div>
                </div>      
                <div class="photobox photobox_type9">
                  <div class="photobox__previewbox">
                    <img src="https://stas-melnikov.ru/cliparts/nature640x426.jpg" class="photobox__preview" alt="Preview">
                    <span class="photobox__label">Effect #9</span>
                  </div>
                </div>
              </div>  
            </div>
          </div>
          
          
          
          مصادر
    </body>
</html>
