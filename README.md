@import url('https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,200;0,300;0,400;0,700;1,400&display=swap');

* {
	margin: 0;
	padding: 0;
	box-sizing: border-box;
	text-decoration: none;
}
.max-width{
	max-width: 1300px;
	padding: 0 80px;
	margin: auto;
}

/* Style for Navigation Section */

.navbar{
	position: fixed;
	width: 100%;
	padding: 15px 0;
	font-family: 'Montserrat', sans-serif;
	background: black;
	z-index: 1;
}
.navbar.sticky{
	padding: 15px;
	background: gray;
}
.navbar .max-width{
	display: flex;
	align-items: center;
	justify-content: space-between;
}
.navbar .logo a{
	color: white;
	font-size: 35px;
	font-weight: 600;
}
.navbar .logo a:hover{
	color: red;
}
.navbar .logo a span{
	color: red;
}
.navbar .menu li{
	list-style: none;
	display: inline-block;

}
.navbar .menu li a{
	display: block;
	color: white;
	font-size: 20px;
	font-weight: 600;
	margin-left: 30px;
	transition: all 0.3s linear;
}
.navbar .menu li a:hover{
	color: red;
}
/* Menu Button */
.menu-btn{
	cursor: pointer;
}

/* Style for Home Section */

.home{
	display: flex;
	background: url("images/banner-1.jpg") repeat center;
	height: 100vh;
	color: white;
	min-height: 500px;
	max-height: 720px;
	background-size: cover;
	background-attachment: fixed;
	font-family: 'Montserrat', sans-serif
}
.home .max-width{
	margin: auto 0 auto 30px;
}
.home .home-content .text-1{
	font-size: 25px;
}
.home .home-content .text-2{
	font-size: 50px;
	font-weight: 700;
	margin-left: -3px;
}
.home .home-content .text-3{
	font-size: 25px;
}
.home .home-content a{
	display: inline-block;
	background: black;
	color: white;
	font-size: 20px;
	padding: 12px 36px;
	margin-top: 30px;
	border-radius: 20px;
	transition: all 0.5s linear;
}
.home .home-content a:hover{
	color: white;
	background: gray;
}

/* Style for About Section */

section {
	padding: 100px 0;
}
.about {
	display: flex;
	background: rgb(3,3,3);
	background: linear-gradient(rgba(3,3,3,1) 25%, rgba(84,50,50,1) 100%, rgba(0,0,0,1) 100%);
	font-family: 'Montserrat', sans-serif;
}
.about .title{
	text-align: center;
	font-size: 30px;
	padding-bottom: 50px;
	color: white;
}
.about .about-content{
	display: flex;
	flex-wrap: wrap;
	align-items: center;
	justify-content: space-between;
}
.about .about-content .left{
	width: 45%;
}
.about .about-content .left img{
	height: 300px;
	width: 300px;
	object-fit: cover;
	border-radius: 18px;
}
.about .about-content .right{
	width: 55%;
}
.about .about-content .right .text{
	margin-bottom: 20px;
	color: white;
}
.about .about-content .right p{
	font-size: 20px;
	text-align: justify;
	color: #bdbdbd;
}

/* Style for Services Section */
.services{
	color: black;
	background: rgb(3,3,3);
	background: linear-gradient(rgba(3,3,3,1) 25%, rgba(84,50,50,1) 100%, rgba(0,0,0,1) 100%);
}
.services .title{
	font-family: 'Montserrat', sans-serif;
	color: white;
	text-align: center;
	font-size: 30px;
	padding-bottom: 50px;
}
.services .services-content{
	display: flex;
	flex-wrap: wrap;
	align-items: center;
	justify-content: space-between;
}
.services .services-content .card{
	width: calc(33% - 20px);
	background: white;
	text-align: center;
	border-radius: 6px;
	padding: 20px 25px;
}
.services .services-content .card:hover{
	background: gray;
	color: white;
}
.services .services-content .card .box{
	transition: all 0.3s ease;
}
.services .services-content .card .box:hover{
	transform: scale(1.05);
}
.services .services-content .card img{
	height: 60px;
	width: 60px;
}
.services .services-content .text{
	font-family: 'Montserrat', sans-serif;
	font-size: 25px;
	font-weight: 600;
	margin: 10px 0;
}
.services .services-content p{
	font-family: 'Montserrat', sans-serif;
	font-size: 18px;
}

/* Style for Skills Section */

.skills{
	display: flex;
	background: rgb(5,5,5);
	background: linear-gradient(rgba(3,3,3,1) 25%, rgba(84,50,50,1) 100%, rgba(0,0,0,1) 100%);
	font-family: 'Montserrat', sans-serif;
	font-size: 18px;
}
.skills .title{
	text-align: center;
	font-size: 30px;
	padding-bottom: 50px;
	color: white;
}
.skills .skills-content{
	display: flex;
	flex-wrap: wrap;
	align-items: center;
	justify-content: space-between;
}
.skills .skills-content .column{
	width: calc(50% - 30px)
}
.skills .skills-content .left .text{
	font-size: 20px;
	font-weight: 600;
	margin-bottom: 20px;
	color: white;
}
.skills .skills-content .left p{
	text-align: justify;
	font-size: 18px;
	color: #bdbdbd;
}
.skills .skills-content .left a{
	display: inline-block;
	background: black;
	color: white;
	font-size: 20px;
	padding: 12px 36px;
	margin-top: 30px;
	border-radius: 20px;
}
.skills .skills-content .left a:hover{
	color: white;
	background: #bdbdbd;
}
.skills .skills-content .right .bar{
	margin-bottom: 15px;
}
.skills .skills-content .right .info{
	display: flex;
	margin-bottom: 5px;
	align-items: center;
	justify-content: space-between;
	color: #bdbdbd;
}
.skills .skills-content .right .info:hover{
	color: red;
}
.skills .skills-content .right span{
	font-weight: 600;
	font-size: 18px;
	padding: 5px;
}
.skills .skills-content .right .line{
	height: 10px;
	width: 100%;
	background: lightgray;
	position: relative;
}
.skills .skills-content .right .line::before{
	content: "";
	position: absolute;
	height: 100%;
	left: 0;
	right: 0;
	background: white;

}
.skills .skills-content .right .html::before{
	width: 95%;

}
.skills .skills-content .right .css::before{
	width: 85%;

}
.skills .skills-content .right .js::before{
	width: 82%;

}
.skills .skills-content .right .php::before{
	width: 80%;

}
.skills .skills-content .right .mysql::before{
	width: 80%;

}

/* Contact Style */
.contact{
	display: flex;
	background: rgb(3,3,3);
	background: linear-gradient(rgba(3,3,3,1) 25%, rgba(84,50,50,1) 100%, rgba(0,0,0,1) 100%);
	font-family: 'Montserrat', sans-serif;
}
.contact .title{
	text-align: center;
	font-size: 30px;
	padding-bottom: 50px;
	color: white;
}
.contact .contact-content{
	display: flex;
	flex-wrap: wrap;
	align-items: center;
	justify-content: space-between;
}
.contact .contact-content .column{
	width: calc(50% - 30px)
}
.contact .contact-content .column .text{
	color: white;
	font-size: 25px;
	font-weight: 600;
	margin: 10px 0;
}
.contact .contact-content .left p{
	font-size: 18px;
	text-align: justify;
	color: #bdbdbd;
}
.contact .contact-content .row{
	display: flex;
	height: :65px;
	align-items: center;
}
.contact .contact-content .row .info{
	margin-left: 30px;
}
.contact .contact-content .left img{
	height: 20px;
	width: 20px;
}
.contact .contact-content .info .head{
	color: white;
	font-weight: 600;
	padding: 5px 0;
}
.contact .contact-content .info .sub-title{
	font-weight: 600;
	color: #bdbdbd;
}
.contact .right form .fields{
	display: flex;
}
.contact .right form .field,
.contact .right form .fileds .field{
	height: 45px;
	width: 100%;
	margin-bottom: 10px;
}
.contact .right form .textarea{
	height: 80px;
	width: 100%;
}
.contact .right form .name{
	margin-right: 10px;
}
.contact .right form .email{
	margin-left: 10px;
}
.contact .right form .field input,
.contact .right form .textarea textarea{
	height: 100%;
	width: 100%;
	border: 1px solid lightgray;
	border-radius: 6px;
	outline: none;
	padding: 0 15px;
}
.contact .right form .field input:focus,
.contact .right form .textarea textarea:focus{
	border-color: red;
}
.contact .right form .textarea textarea{
	padding-top: 10px;
	resize: none;
}
.contact .right form .button{
	height: 50px;
	width: 150px;
}
.contact .right form .button button{
	width: 100%;
	height: 100%;
	background: black;
	color: white;
	font-size: 18px;
	border-radius: 6px;
	cursor: pointer;
}
.contact .right form .button button:hover{
	color: white;
	background: #bdbdbd;
}

/* Footer Style */
footer{
	font-family: 'Montserrat', sans-serif;
	color: white;
	background: black;
	text-align: center;
	padding: 50px 25px;
}
footer span a{
	color: red;
}
footer span a:hover{
	text-decoration: underline;
	color: turquoise;
}

/*Responsive Media Query */
@media (max-width: 1920px){
	.home .max-width{
		margin-left: 0px;
	}
	.menu-btn{
		display: none;
		z-index: 999;
	}
}
@media (max-width: 1104px){
	.about .about-content .left img{
		height: 350px;
		width: 350px;
	}
}
@media (max-width: 991px){
	}
	.max-width{
		padding: 0 50px;
}
@media (max-width: 947px){
	.menu-btn{
		display: block;
		z-index: 999;
	}
	.navbar .menu{
		position: fixed;
		height: 80vh;
		width: 100%;
		left: -100%;
		top: 0;
		background: black;
		opacity: 90%;
		text-align: center;
		padding-top: 80px;
		transition: all 0.3s ease;
	}
	.navbar .menu.active{
		left: 0;
	}
	.navbar .menu li{
		display: block;
	}
	.navbar .menu li a{
		display: inline-block;
		margin: 20px;
		font-size: 25px;
	}
	.home .home-content .text-2{
		font-size: 35px;
	}
	.home .home-content a{
		font-size: 18px;
		padding: 10px 30px;
	}
	.max-width{
		max-width: 930px;
	}
	.about .about-content .column{
		width: 100%;
	}
	.about .about-content .left{
		display: flex;
		justify-content: center;
		margin: 0 auto 60px;
	}
	.about .about-content .right{
		flex: 100%;

	}
	.services .services-content .card{
		width: calc(50% - 10px);
		margin-bottom: 35px;
	}
	.skills .skills-content .column,
	.contact .contact-content .column{
		width: 100%;
		margin-bottom: 35px;
	}
}
@media (max-width: 690px){
	.max-width{
		padding: 0  23px;
	}
	.services .services-content .card{
		width: 100%;
	}
}
@media (max-width: 500px){
	.contact .right form .fields{
		flex-direction: column;
	}
	.contact .right form .name,
	.contact .right form .email{
		margin: 0;
	}
}
