<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />
<title>六道轮回</title>
</head>
	<style>
		.navbar{
		width: 300px;
		height: 300px;
		line-height: 300px;
		border-radius: 50%;
		border:1px solid #ccc;
		background:url(img/bj.png) no-repeat;
		margin: 300px auto;
		position: relative;
		cursor: pointer;
		text-align: center;
		font-size:60px;
		color: #99b977;
		transition: 0.24s 0.2s;
		transition-property:all; transition-duration:1s;
		animation:gogo 5s infinite linear;
	}
	.navbar:hover{
		
	}
	.navbar .menu{
		list-style: none;
		padding: 0;
		margin: 0;
		position: absolute;
		top: -75px;
		left: -75px;
		border: 150px solid transparent;
		cursor: default;
		border-radius: 50%;
		transform: scale(0);
		transition: transform 1.4s 0.07s;
		z-index: -1;
	}
	.navbar:hover .menu{
		transition: transform 0.4s 0.08s, z-index   0s  0.5s;
		transform: scale(1);
		z-index: 1;
	}
	.navbar .menu li{
		position: absolute;
		top: -210px;
		left: -220px;
		transform-origin: 300px 300px;
		transition: all 0.5s 0.1s;
	}
	.navbar:hover .menu li{
		transition: all 0.6s;
	}
	.navbar .menu li a{
		width: 140px;
		height: 140px;
		line-height: 140px;
		border-radius:100%;
		background:url(img/bj1.png) no-repeat;
		position: absolute;
		font-size: 80%;
		color:purple;
		transition: 0.6s; 
		box-shadow:-10px 0px 20px red,
		10px 0px 20px red,
		0px -10px 20px red,
		0px 10px 20px red;		
		}
	
	@keyframes gogo{
		100%{
			transform:rotate(360deg);
		}	
	 }	

	.navbar:hover .menu li:nth-child(1){
		transition-delay: 0.02s;
		transform: rotate(85deg);
	}
	.navbar:hover .menu li:nth-child(1) a{
		transition-delay: 0.04s;
		transform: rotate(635deg);
	}
	.navbar:hover .menu li:nth-child(2){
		transition-delay: 0.04s;
		transform: rotate(125deg);
	}
	.navbar:hover .menu li:nth-child(2) a{
		transition-delay: 0.08s;
		transform: rotate(595deg);
	}
	.navbar:hover .menu li:nth-child(3){
		transition-delay: 0.06s;
		transform: rotate(165deg);
	}
	.navbar:hover .menu li:nth-child(3) a{
		transition-delay: 0.12s;
		transform: rotate(555deg);
	}
	.navbar:hover .menu li:nth-child(4){
		transition-delay: 0.08s;
		transform: rotate(205deg);
	}
	.navbar:hover .menu li:nth-child(4) a{
		transition-delay: 0.16s;
		transform: rotate(515deg);
	}
	.navbar:hover .menu li:nth-child(5){
		transition-delay: 0.1s;
		transform: rotate(245deg);
	}
	.navbar:hover .menu li:nth-child(5) a{
		transition-delay: 0.2s;
		transform: rotate(475deg);
	}
	.navbar:hover .menu li:nth-child(6){
		transition-delay: 0.12s;
		transform: rotate(285deg);
	}
	.navbar:hover .menu li:nth-child(6) a{
		transition-delay: 0.24s;
		transform: rotate(435deg);
	}
	.navbar:hover .menu li:nth-child(7){
		transition-delay: 0.14s;
		transform: rotate(325deg);
	}
	.navbar:hover .menu li:nth-child(7) a{
		transition-delay: 0.28s;
		transform: rotate(395deg);
	}
	.navbar:hover .menu li:nth-child(8){
		transition-delay: 0.16s;
		transform: rotate(365deg);
	}
	.navbar:hover .menu li:nth-child(8) a{
		transition-delay: 0.32s;
		transform: rotate(355deg);
	}
	.navbar:hover .menu li:nth-child(9){
		transition-delay: 0.18s;
		transform: rotate(405deg);
	}
	.navbar:hover .menu li:nth-child(9) a{
		transition-delay: 0.36s;
		transform: rotate(315deg);
	}
</style>
<body> 

		<div class="navbar">
					<ul class="menu">
						<li><a href="#" class="">一</a></li>
						<li><a href="#" class="">切</a></li>
						<li><a href="#" class="">有</a></li>
                        <li><a href="#" class="">情</a></li>
                        <li><a href="#" class="">皆</a></li>
                        <li><a href="#" class="">以</a></li>
                        <li><a href="#" class="">诸</a></li>
                        <li><a href="#" class="">欲</a></li>
                        <li><a href="#" class="">缘</a></li>
					</ul>
			</div>
 </body>
</html>
