# Snapbackshops
HTML/CSS . FIRST CODE
html{
  scroll-behavior: smooth;
}
body {
	padding:0 ;
	margin: 0;
}

nav {
	position: fixed;
	z-index: 10;
	left: 0;
	right: 0;
	top: 0;
	font-family: 'Montserrat', sans-serif;
	padding: 0 5%;
	height: 50px;
	background-color: black;
}
nav .logo {
	float: left;
	width: 50%;
	height: 100%;
	display: flex;
	align-items: center;
	font-size: 14px;
  font-weight: bold;
	color: #fff;
}
.logo i {
  color: white;
}
.logo .t1{
  color: red;
}
.logo .t2{
  color:blue;
}
nav .links {
	float: right;
	padding: 0;
	margin: 0;
	width: 14%;
	height: 100%;
	display: flex;
	justify-content: space-around;
	align-items: center;
}
nav .links li {
	list-style: none;
	margin: 2px
}
nav .links a {
	display: block;
	padding: 1em;
	font-size: 12px;
	font-weight: bold;
	color: #fff;
	text-decoration: none;
}
#toggle {
	position: absolute;
	top: -100px;
}
nav .icon {
  display: none;
	position: absolute;
	right: 10%;
	top: 50%;
	transform: translateY(-50%);
}
nav .icon .line {
	width: 40px;
	height: 5px;
	background-color: #fff;
	margin: 5px;
	border-radius: 3px;
	transition: all .3s ease-in-out;
}
nav .links li a.active{
  background-color: gray;
  border-radius: 20px;
}
nav .links li:hover a{
  background-color: black;
  border-radius: 20px;
  transition: .5s;
}

@media screen and (max-width: 768px) {
	nav .logo {
		float: none;
		width: auto;
		justify-content: center;

	}
	
	nav .links a {
		font-size: 20px;
	}
	nav :checked ~ .links {
		bottom: 0;
	}
	nav .icon {
		display: block;
	}
	nav :checked ~ .icon .line:nth-child(1) {
		transform: translateY(10px) rotate(225deg);
	}
	nav :checked ~ .icon .line:nth-child(3) {
		transform: translateY(-10px) rotate(-225deg);
	}
	nav :checked ~ .icon .line:nth-child(2) {
		opacity: 0;
	}
}
.section1{

  height: 100vh;
    display: flex;
background: url(sirkol.png) no-repeat;
background-size: cover;
text-align: center;
justify-content: center;

}
.section1 .c1{
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  font-family: algerian;
  user-select: none;
  font-weight: ;
  color: white;
  font-size: 110px;

}
.section1 .c2{
  position: absolute;
  top: 60%;
  left: 50%;
  transform: translate(-50%, -50%);

  user-select: none;
  font-size: 24px;
  font-weight: lighter;
  color: white;

}
.section1 .c3{
  position: absolute;
  top: 90%;
  left: 51%;
  transform: translate(-50%, -50%);

  user-select: none;
  font-size: 20px;
  font-weight: bold;
  color: black;
  border: white;
  padding: 0 20px;
  background: gray;
  border-radius: 15px;
}
.section1 a{
  text-decoration: none;
}
.section1 .c3:hover{
  background: black;
  transition: .3s;
}
@media screen and (max-width: 768px){
  .section1 .c1{

      position: absolute;
      top: 50%
      left: 50 %;
      transform: translate(-50%, -50%);
      font-family: cursive;
      user-select: none;
      font-weight: bold;
      color: #2980b9;
      font-size: 60px;
  }
  .section1 .c2{
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    font-family: cursive;
    user-select: none;
    font-size: 9px;
    font-weight: lighter;
    color: white;
  }
}

.section2{
  height: 127vh;

  background: url(vintage.jpg) no-repeat;
  background-size: cover;
}
.section2 .c4{
  position: absolute;
  color: white;
  background:  rgba(0,0,0,0.9);
  border-radius: 25px;
  text-align: justify;
  padding: 10px;
  margin: 15px;
  font-size: 20px;
  height: auto;
  width:auto;
  top: 145%;
  left: 35%;
  transform: translate(-50%, -50%);
}
.ab{

text-transform: uppercase;
  font-family: arial;
font-weight: bold;
color: white;
font-size: 70px;
}
@media screen and (max-width: 700px){
  .section2 .c4{
    position: absolute;
    color: white;
    background:  rgba(0,0,0,0.9);
    border-radius: 25px;
    text-align:center;
    padding: 10px;
    font-size: 15px;
    height: auto;
    width:auto;
    top: 150%;
    left: 45%;

  }
}

.section3{
background:#313131;
height: 22vh;
}
.section3 table{
  position: absolute;
  top: 235%;
  left: 50%;
  transform: translate(-50%, -50%);
  text-align: center;
  justify-content: center;


}
.section3 table th{
  padding: 5px; 
font-size: 28px;
  color: white;
}
.section3 table td{
font-size: 20px;
  color: white;
    font-weight: bold;
}

footer {
  text-align: center;
  justify-content: center;
  font-color:black;
  background:#2a2a2b;
  font-weight:bold;
  
}
p{
color: white;
}

.slideshow-container {
        width: 100%;
        height: 400px;
        position: relative;
        margin: auto;
      }

     
      .slideshow-container img {
        display: none;
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
      }

     
      .slideshow-container img:first-child {
        display: block;
      }
	  
	 
