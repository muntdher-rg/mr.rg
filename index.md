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

/*********** About Me Section Start ********/

#about {
    padding-top: 40px;
    padding-bottom: 40px;
    color: #5a5a5a;
    background-image: linear-gradient( to left top, rgba(109, 110, 110, 0.8), rgba(112, 112, 112, 0.8)), url(https://images.unsplash.com/photo-1467703834117-04386e3dadd8?ixlib=rb-0.3.5&ixid=eyJhcHBfaWQiOjEyMDd9&s=2de85761d45711c4109ba4f215b6e21e&auto=format&fit=crop&w=1350&q=80);
    background-size: cover;
    background-position: center;
    color: #fff;
}

.featurette-heading {
    font-weight: 300;
    line-height: 1;
    letter-spacing: -1px;
}

@media (min-width: 768px) {
    .featurette-heading {
        font-size: 30px;
    }
}

@media (min-width: 992px) {
    .featurette-heading {
        margin-top: 120px;
    }
}

.img-responsive {
    border-radius: 100px;
    max-width: 100%;
    height: auto;
    display: block;
}


/*********** About Me Section End **********/

/******** My blog Section Start *******/

#blog {
    background-image: linear-gradient( to left bottom, rgba(54, 10, 136, 0.8), rgba(139, 0, 0, 0.8)), url(https://images.unsplash.com/photo-1497892597262-2983614aa886?ixlib=rb-0.3.5&ixid=eyJhcHBfaWQiOjEyMDd9&s=2051e3b8338218a0f163b9a6ab48bb84&auto=format&fit=crop&w=1350&q=80);
    background-size: cover;
    background-position: top;
    color: #fff;
    padding-top: 150px;
    padding-bottom: 100px;
    position: relative;
}

.project {
    transition: transform .3s;
}

.project:hover {
    transform: scale(1.1);
}


/********* My blog Section End ********/

/********* Footer Section Start ************/

footer #footer-above {
    background-image: linear-gradient( to left top, rgba(63, 10, 161, 0.8), rgba(139, 0, 0, 0.8)), url(https://images.unsplash.com/photo-1495277493816-4c359911b7f1?ixlib=rb-0.3.5&ixid=eyJhcHBfaWQiOjEyMDd9&s=cea505d70dc1770c4dd470ff9715ac36&auto=format&fit=crop&w=1346&q=80);
    background-size: cover;
    background-position: center;
    color: #fff;
    position: relative;
    display: -webkit-box;
    display: -moz-flexbox;
    display: -ms-flexbox;
    display: flex;
    -ms-flex-flow: row wrap;
    -webkit-box-orient: horizontal;
    -webkit-box-direction: normal;
    flex-flow: row wrap;
    -ms-flex-pack: distribute;
    justify-content: space-around;
    -webkit-box-align: start;
    -ms-flex-align: start;
    align-items: flex-start;
    margin: 0 auto;
    width: 100%;
}

footer h3 {
    margin-bottom: 30px;
    color: #000;
    font-size: 2em;
}

#footer-above {
    padding-top: 50px;
    width: 80%;
}

#footer-above div {
    margin-bottom: 50px;
    width: 250px;
    text-align: center;
}

#footer-above ul {
    padding: 0;
}

#footer-above li {
    display: inline;
}

#footer-below {
    color: #fff;
    font-size: 1.0em;
    padding: 25px 0;
    background-color: #000;
    background-position: center;
    text-align: center;
}

.button {
    color: #fff;
    border: solid 2px #000;
    border-radius: 70%;
    display: inline-block;
    width: 50px;
    height: 50px;
    text-align: center;
    font-size: 20px;
    line-height: 48px;
    -webkit-transitional: all .3s ease-in-out;
    transition: all .3s ease-in-out;
}

.button:hover {
    border: solid 2px rgb(21, 102, 214);
    color: #2998E4;
}

.col-sm-6,
.col-xs-12 {
    position: relative;
    min-height: 1px;
    padding-right: 15px;
    padding-left: 15px;
}

.col-xs-12 {
    float: left;
    width: 100%;
}

@media (min-width: 768px) {
    .col-sm-6 {
        float: left;
    }
}


/********* Footer Section End **************/

/********* home sction home  ***************/

body {
  background: #2980b9;
}
.loading {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  width: 240px;
  animation-name: beesandbombs;
  animation-duration: 4s;
  animation-iteration-count: infinite;
  animation-timing-function: cubic-bezier(0.82, 0.01, 0.15, 1.01);
}
.loading .circle {
  position: relative;
  background: white;
  width: 100px;
  height: 100px;
  border-radius: 100%;
  margin: 10px;
  float: right;
  animation-name: beesandbombscircle;
  animation-duration: 4s;
  animation-iteration-count: infinite;
  animation-timing-function: cubic-bezier(0.82, 0.01, 0.15, 1.01);
}
.loading .circle:before {
  content: "";
  position: absolute;
  background: #2980b9;
  width: 50px;
  height: 50px;
  animation-name: beesandbombscirclebox;
  animation-duration: 4s;
  animation-iteration-count: infinite;
  animation-timing-function: cubic-bezier(0.82, 0.01, 0.15, 1.01);
}
.loading .circle:nth-child(1)::before {
  left: 0;
  bottom: 0;
  border-bottom-left-radius: 40px;
}
.loading .circle:nth-child(2)::before {
  right: 0;
  bottom: 0;
  border-bottom-right-radius: 40px;
}
.loading .circle:nth-child(3)::before {
  top: 0;
  left: 0;
  border-top-left-radius: 40px;
}
.loading .circle:nth-child(4)::before {
  top: 0;
  right: 0;
  border-top-right-radius: 40px;
}
.loading:before {
  content: "";
  position: absolute;
  width: 120px;
  height: 120px;
  background: #2980b9;
  top: 50%;
  left: 50%;
  z-index: 1;
  transform: translate(-50%, -50%);
  animation-name: beesandbombsrev;
  animation-duration: 4s;
  animation-iteration-count: infinite;
  animation-timing-function: cubic-bezier(0.82, 0.01, 0.15, 1.01);
}
@keyframes beesandbombs {
  0% {
    transform: translate(-50%, -50%) rotate(0deg);
  }
  50% {
    transform: translate(-50%, -50%) rotate(90deg);
  }
  100% {
    transform: translate(-50%, -50%) rotate(0deg);
  }
}
@keyframes beesandbombsrev {
  0% {
    transform: translate(-50%, -50%) rotate(0deg);
  }
  50% {
    transform: translate(-50%, -50%) rotate(90deg);
  }
  52% {
    visibility: hidden;
  }
  100% {
    transform: translate(-50%, -50%) rotate(0deg);
    visibility: hidden;
  }
}
@keyframes beesandbombscircle {
  0% {
    transform: rotate(0deg);
  }
  50% {
    transform: rotate(0deg);
  }
  100% {
    transform: rotate(-360deg);
  }
}
@keyframes beesandbombscirclebox {
  0% {
    visibility: hidden;
  }
  50% {
    visibility: hidden;
  }
  51% {
    visibility: visible;
  }
  100% {
    visibility: visible;
  }
}

/********* home section end *********/


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
      
        <!-- About Me Section Start -->
<div id="about">
  <div class="container">
      <div class="row featurette">
          <div class="col-md-7">
              <h2 class="featurette-heading">Hi, am MUNYADHER . <span class="text-muted">A Web Developer.</span></h2>
              <p class="lead">Through coding i've acquired problem-solving skills and a way to communicate with others on a technical level. I'd love to work in a tech company, with artists, athletes, photographers, non-profits, and small businesses to improve
                  their Web presence.
              </p>
              <blockquote>
                  <p>Content is like water. You put water into a cup it becomes <strong>the cup</strong>. <br>You put water into a bottle it becomes <strong>the bottle</strong>. <br>You put it in a teapot, it becomes <strong>the teapot</strong>.<br><em>~ Bruce Lee</em>
                  </p>
              </blockquote>

          </div>
          <div class="col-md-5">
              <img class="https://www.google.com/url?sa=i&rct=j&q=&esrc=s&source=images&cd=&cad=rja&uact=8&ved=2ahUKEwiij7ytwubaAhWBvBQKHXwxBtQQjRx6BAgBEAU&url=https%3A%2F%2Fgithub.com%2FChell0&psig=AOvVaw2GUUY9mxUw0YZqB52ike7W&ust=1525332959428917"
                  alt="machel's smiling photo">
          </div>
      </div>
  </div>
</div>
<!-- About Me Section End -->
            
       
<!-- My blog Section Start -->

<<div class="wrapper">
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
<!-- My blog  Section End -->
        
          
<!--my home section start--> 
<div class="loading">
  <div class="circle"></div>
  <div class="circle"></div>
  <div class="circle"></div>
  <div class="circle"></div>
</div>
<!--my home section end-->           
          مصادر
    </body>
</html>
