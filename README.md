<!DOCTYPE html>
<html lang="ko">
  <head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="user-scalable=no, initial-scale=1.0,width=device-width">
    <title>NILTECH</title>
    <link rel="icon" type="ICON" sizes="192x192" href="imagefile1/favicon/android-icon-192x192.ico">
    <link rel="stylesheet" href="css/style.css">
    <script src="js/ie.js"></script>
    <script defer src="js/main.js"></script>
    <script src="main.js" defer></script>
<style>
    *      { margin: 0px;padding: 0px;box-sizing: border-box;}
	
    ul,ol  { list-style: none;margin:0 0 0 0;}
    a      { text-decoration: none;}

    /*---------------header------------------*/
    header { width: 100%;height: 13.5vmin;}
    header .navbar
           { width: 100%;height: 13.5vmin;
             display: flex;
             justify-content: space-between;
             align-items: center;
             position: absolute;padding: 3vmin 0;}
    header .util         /*--상단 네비게이션 위치---*/
           { width: 25%;height: 10vmin;
             display: block;position: absolute;
             margin: 0vmin 0 0 60%;}
    header .util li
           { display: block;float: left;}
    header .util li a    /*--상단 네비게이션 text---*/
           { font: 1.2vmin "arial";
             color: rgb(192, 193, 201);
             display: block;
             padding: 0 2vmin;margin: 0 0 0 0vmin;}             
    header .navbar__logo
           { width: 27vmin;height: 20vmin;background-color: #00378f;
             background: url(imagefile1/logo.png)no-repeat;
             background-size: 100%;
             position:absolute;margin: -3vmin 0 0 5.9vmin;}             
    header .navbar__menu 
           { width: 120vmin;height: 5vmin;
             list-style: none;
             display: flex;position: absolute;
             margin: 9vmin 0 0 45vmin;}
    header .navbar__menu li 
           { width: 41vmin;height: 5.1vmin;text-align: center;
             padding: 1vmin 0 0 1vmin;}
    header .navbar__menu li a
           { width: 10vmin;height: 5vmin;
             font: bold 1.7vmin/1 "arial";color: #0a0c0c;
             text-decoration: none;}
    header .navbar__menu li:hover 
           { z-index : 1;
             color: white;text-align: center;
             border-radius: 3px;border-bottom: 0.5vmin solid #143cfb;}                   
             
    header .navbar__icons 
           { color: white;list-style: none;align-items: center;
             display: flex;}
    header .navbar__icons li 
           { width: 35vmin;height: 5.1vmin;
             padding: 0;margin: 0;}
    header .menubar 
           { width: 9vmin;height: 7vmin;
             background-image: url(imagefile1/menuBar.png);
             background-size: 100%;
             position: absolute;
             margin: 1.9% 0 0 85%;display: none;} 
    /*-----------MOBILE----------*/                    
    @media screen and (min-width: 80px) and (max-width: 980px) 
           { header .navbar
           { width: 100%;height: 13.5vmin;
             flex-direction: column;align-items: flex-start;margin: 0;}  
             header .util         /*--상단 네비게이션 위치---*/
           { width: 50%;height: 10vmin;
             display: block;position: absolute;
             margin: -1.5vmin 0 0 40vmin;}
             header .util li
           { display: block;float: left;}
             header .util li a    /*--상단 네비게이션 text---*/
           { font: 2vmin "arial";
             color: rgb(192, 193, 201);
             display: block;
             padding: 0 2vmin;margin: 0 0 0 0vmin;} 
             header .navbar__logo
           { width: 43vmin;height: 20vmin;
             background: url(imagefile1/logo.png)no-repeat;
             background-size: 100%;
             position:absolute;margin: 1.5% 0 0 0vmin;}  
             header .navbar__menu 
           { width: 35vmin;height: 60vmin;background-color: #1b2f58; 
             z-index : 1;flex-direction: column;
             align-items: center;
             border-radius: 0 0 1.5vmin 1.5vmin;
             display: none;margin: 14.5vmin 0 0 60vmin;}
             header .navbar__menu li 
           { width: 100%;height: 60vmin;
             z-index : 1;text-align: center;
             padding: 2.7vmin 0 0 0;margin: 0;}
             header .navbar__menu li a
           { font: normal 3vmin/1 "arial";color: #fff;} 
             header .navbar__menu li:hover 
           { z-index : 1;
             background:radial-gradient(circle,#00378f,#071b74);/*-#162544-*/
             color: white;text-align: center;
             border-radius: 3px;border-bottom: none;}                                  
             header .navbar__icons 
           { width: 100%;
             justify-content: center;display: none;}
             header .menubar
           { width: 9vmin;height: 7vmin;
             background-image: url(imagefile1/menuBar.png);
             background-size: 100%;
             display: block;position: absolute;
             margin: 1.9% 0 0 85%;}
             header .navbar__menu.active,.navbar__icons.active 
           { display: flex;}} 
    /*-----------TABLET----------*/       
    @media screen and (min-width: 600px) and (max-width: 1280px) 
           { header .navbar
           { width: 100%;height: 13.5vmin;
             flex-direction: column;align-items: flex-start;margin: 0;}  
             header .util         /*--상단 네비게이션 위치---*/
           { width: 50%;height: 10vmin;
             display: block;position: absolute;
             margin: -1.5vmin 0 0 40vmin;}
             header .util li
           { display: block;float: left;}
             header .util li a    /*--상단 네비게이션 text---*/
           { font: 2vmin "arial";
             color: rgb(192, 193, 201);
             display: block;
             padding: 0 2vmin;margin: 0 0 0 0vmin;} 
             header .navbar__logo
           { width: 37vmin;height: 20vmin;
             background: url(imagefile1/logo.png)no-repeat;
             background-size: 100%;
             position:absolute;margin: 2vmin 0 0 1.5%;}  
             header .navbar__menu 
           { width: 32vmin;height: 55vmin;background-color: #1b2f58; 
             z-index : 1;flex-direction: column;
             align-items: center;
             border-radius: 0 0 1.5vmin 1.5vmin;
             display: none;margin: 14.5vmin 0 0 61.5vmin;}
             header .navbar__menu li 
           { width: 100%;height: 60vmin;
             z-index : 1;text-align: center;
             padding: 2.7vmin 0 0 0;margin: 0;}
             header .navbar__menu li a
           { font: normal 2.5vmin/1 "arial";color: #fff;} 
             header .navbar__menu li:hover 
           { z-index : 1;
             background:radial-gradient(circle,#00378f,#071b74);/*-#162544-*/
             color: white;text-align: center;
             border-radius: 3px;border-bottom: none;}                                  
             header .navbar__icons 
           { width: 100%;
             justify-content: center;display: none;}
             header .menubar
           { width: 8.7vmin;height: 6.7vmin;
             background-image: url(imagefile1/menuBar.png);
             background-size: 100%;
             display: block;
             margin: 1.5% 0 0 87%;}
             header .navbar__menu.active,.navbar__icons.active 
           { display: flex;}}
    @media screen and (min-height: 0px) and (max-height: 768px)
           { header .navbar
           { width: 100%;height: 13.5vmin;
             flex-direction: column;align-items: flex-start;margin: 0;}  
             header .util         /*--상단 네비게이션 위치---*/
           { width: 50%;height: 10vmin;
             display: block;position: absolute;
             margin: -1.5vmin 0 0 40vmin;}
             header .util li
           { display: block;float: left;}
             header .util li a    /*--상단 네비게이션 text---*/
           { font: 2vmin "arial";
             color: rgb(192, 193, 201);
             display: block;
             padding: 0 2vmin;margin: 0 0 0 0vmin;} 
             header .navbar__logo
           { width: 43vmin;height: 20vmin;
             background: url(imagefile1/logo.png)no-repeat;
             background-size: 100%;
             position:absolute;margin: -0.3% 0 0 -47%;}  
             header .navbar__menu 
           { width: 35vmin;height: 60vmin;background-color: #1b2f58; 
             z-index : 1;flex-direction: column;
             align-items: center;
             border-radius: 0 0 1.5vmin 1.5vmin;
             display: none;margin: 5.5% 0 0 70%;}
             header .navbar__menu li 
           { width: 100%;height: 60vmin;
             z-index : 1;text-align: center;
             padding: 2.7vmin 0 0 0;margin: 0;}
             header .navbar__menu li a
           { font: normal 3vmin/1 "arial";color: #fff;} 
             header .navbar__menu li:hover 
           { z-index : 1;
             background:radial-gradient(circle,#00378f,#071b74);/*-#162544-*/
             color: white;text-align: center;
             border-radius: 3px;border-bottom: none;}                                  
             header .navbar__icons 
           { width: 100%;
             justify-content: center;display: none;}
             header .menubar
           { width: 9vmin;height: 7vmin;
             background-image: url(imagefile1/menuBar.png);
             background-size: 100%;
             display: block;position: absolute;
             margin: -0.2% 0 0 85%;}
             header .navbar__menu.active,.navbar__icons.active 
           { display: flex;}}

           /*--------------------메인화면----------------------*/
    body   { width: 100%;height: 130vmin;}

    figure { width: 100%;height: 60%; /*전체 브라우저 높이에서 120px만큼 빼줌*/
             /*background: linear-gradient(-55deg,  #061c8a, #7df0a9e8);*/
             position: relative;
	           overflow: hidden;
	           padding-top: 0px;}    
    figure .background-color
           { width: 100%;height: 100%;
             background: linear-gradient(120deg, #1b2f58b6,#11b8a2bd,#1b2f58,rgb(16, 20, 34), rgb(16, 20, 34));
             background-size: 400% 400%;      
             object-fit: cover;
             opacity: 100%;
             position: absolute;margin: 0px 0 0 0px;
             animation: gradient 10s ease infinite;}
             @keyframes gradient {
	           0%   { background-position: 0% 50%;}
	           50%  { background-position: 100% 50%;}
	           100% { background-position: 0% 50%;}}
    figure .background-color .grid             
           { width: 130%;height: 130%;
             background: url(imagefile1/grid2.png);
             background-size: 100%;
             position: absolute;margin: -5vmin 0 0 -20vmin;
             transform: perspective(60vmin)rotateX(0deg);
             transform-origin: 50% 50%;
             animation: grid 40s linear infinite;}
             @keyframes grid 
           { 0%  { opacity: 5%;transform: perspective(60vmin)rotateX(70deg)rotate( 360deg);}
             5%  { opacity: 70%;}
             45% { opacity: 100%;}
             50% { opacity: 70%;}
             60% { opacity: 0%;}
	           100%{ opacity: 0%;transform: perspective(60vmin)rotateX(70deg)rotate( 0deg);}}

    /*------------------이미지회전 배경-----------------------------*/              
  figure .main  
           { width: 100%;height: 100%;
             overflow: hidden;
             position: absolute;}
  figure .rotate1 
           { width: 100%;             
             position: absolute;perspective: 105vmax;}
  figure .rotate1 #rotate2 
           { width: 70vmax;height: 77vmax;
             position: absolute; 
             top: -10vmin;left: 23vmin;
             transform-style: preserve-3d;
             animation: ani1 linear 30s infinite;}
             @keyframes ani1 
           { 0%  {transform: perspective(105vmax)rotateY(0deg);}
             100%{transform: perspective(105vmax)rotateY(360deg);}}
  figure .rotate1 #rotate2 article .inner1 
           { width: 100%;height: 100%;background: rgba(42, 33, 161, 0.527);
             opacity: 0.7;overflow: hidden;
             box-sizing: border-box; 
             border-radius: 9vmin 9vmin 0 0; 
             position: absolute;     
             padding: 0px;
             transition: all 0.5s;}
                    /* common ui */
  figure .rotate1 #rotate2 article 
           { width: 100%;height: 50%;
             position: absolute;top: 0px;left: 0px;
             backface-visibility: hidden;}

                      /* 3D 배치 */
  .image1  { transform: rotateY(0deg)   translateZ(-100vmax);}
  .image2  { transform: rotateY(45deg)  translateZ(-100vmax);}
  .image3  { transform: rotateY(90deg)  translateZ(-100vmax);}
  .image4  { transform: rotateY(135deg) translateZ(-100vmax);}
  .image5  { transform: rotateY(180deg) translateZ(-100vmax);}
  .image6  { transform: rotateY(225deg) translateZ(-100vmax);}
  .image7  { transform: rotateY(270deg) translateZ(-100vmax);}
  .image8  { transform: rotateY(315deg) translateZ(-100vmax);} 

           /*------------------DOT 장식-----------------------------*/  

    figure .dot-rotate1 
           { position: fixed;
             width: 150vmin;height: 50vmin; 
             perspective: 150vmin;}

    figure .dot-rotate1 #dot-rotate2 
           { width: 150vmin;height: 100vmin; 
             position: absolute;
             margin-top: 0vmin;margin-left: 25vmin; 
             transform-style: preserve-3d;
             animation: ani linear 10s infinite;}
             @keyframes ani {
             0% {transform: rotateY(360deg);}
             100% {transform: rotateY(0deg);}}
    
                             /* common ui */
    figure .dot-rotate1 #dot-rotate2 article 
           { position: absolute;top: 0px;left: 0px; 
             backface-visibility: hidden;}
                               /*face1*/
    figure .dot-rotate1 #dot-rotate2 .dot1 .inner2 .dot1-1 
           { opacity:50%;
             width: 5px;height: 5px;background-color: #fff;
             border-radius: 50px;box-shadow: #fff 0px 0px 30px 5px;
             float: left;margin: 450px 0 0 500px;}
    figure .dot-rotate1 #dot-rotate2 .dot1 .inner2 .dot1-2
           { width: 5px;height: 5px;background-color:#fff;
             border-radius: 50px;box-shadow: #fff 0px 0px 30px 5px;
             float: left;margin: 400px 0 0 -200px;}
    figure .dot-rotate1 #dot-rotate2 .dot1 .inner2 .dot1-3
           { width: 5px;height: 5px;background-color: #fff;
             border-radius: 50px;box-shadow: #fff 0px 0px 30px 5px;
             float: left;margin: 200px 0 0 -500px;}
    figure .dot-rotate1 #dot-rotate2 .dot1 .inner2 .dot1-4
           { opacity:50%;width: 10px;height: 10px;background-color: #fff;
             border-radius: 50px;box-shadow: #fff 0px 0px 30px 5px;
             float: left;margin: 500px 0 0 -400px;}
    figure .dot-rotate1 #dot-rotate2 .dot1 .inner2 .dot1-5
           { width: 10px;height: 10px;background-color: #fff;
             border-radius: 50px;box-shadow: #fff 0px 0px 30px 5px;
             float: left;margin: 550px 0 0 -700px;}
    figure .dot-rotate1 #dot-rotate2 .dot1 .inner2 .dot1-6
           { width: 5px;height: 5px;background-color: #fff;
             border-radius: 50px;box-shadow: #fff 0px 0px 30px 5px;
             float: left;margin: 250px 0 0 -300px;}
    figure .dot-rotate1 #dot-rotate2 .dot1 .inner2 .dot1-7
           { width: 10px;height: 10px;background-color: #fff;
             border-radius: 50px;box-shadow: #fff 0px 0px 30px 5px;
             float: left;margin: 300px 0 0 -480px;}
    figure .dot-rotate1 #dot-rotate2 .dot1 .inner2 .dot1-8
           { width: 10px;height: 10px;background-color: #fff;
             border-radius: 50px;box-shadow: #fff 0px 0px 30px 5px;
             float: left;margin: 450px 0 0 200px;}
    figure .dot-rotate1 #dot-rotate2 .dot1 .inner2 .dot1-9
           { opacity:50%;width: 5px;height: 5px;background-color: #fff;
             border-radius: 50px;box-shadow: #fff 0px 0px 30px 5px;
             float: left;margin: 300px 0 0 250px;}

                           /*face2*/
    figure .dot-rotate1 #dot-rotate2 .dot2 .inner2  
           { margin: 0 0 0 0;}
    figure .dot-rotate1 #dot-rotate2 .dot2 .inner2 .dot2-1 
           { opacity:50%;
             width: 5px;height: 5px;background-color: #fff;
             border-radius: 50px;box-shadow: #fff 0px 0px 30px 5px;
             float: left;margin: 150px 0 0 450px;}
    figure .dot-rotate1 #dot-rotate2 .dot2 .inner2 .dot2-2
           { opacity:50%;
             width: 3px;height: 3px;background-color: #fff;
             border-radius: 50px;box-shadow: #fff 0px 0px 30px 5px;
             float: left;margin: 100px 0 0 200px;}
    figure .dot-rotate1 #dot-rotate2 .dot2 .inner2 .dot2-3
           { width: 3px;height: 3px;background-color: #fff;
             border-radius: 50px;box-shadow: #fff 0px 0px 30px 5px;
             float: left;margin: 250px 0 0 150px;}
    figure .dot-rotate1 #dot-rotate2 .dot2 .inner2 .dot2-4
           { width: 10px;height: 10px;background-color: #fff;
             border-radius: 50px;box-shadow: #fff 0px 0px 30px 5px;
             float: left;margin: 350px 0 0 350px;}
    figure .dot-rotate1 #dot-rotate2 .dot2 .inner2 .dot2-5
           { opacity:50%;
             width: 10px;height: 10px;background-color: #fff;
             border-radius: 50px;box-shadow: #fff 0px 0px 30px 5px;
             float: left;margin: 180px 0 0 100px;}
    figure .dot-rotate1 #dot-rotate2 .dot2 .inner2 .dot2-6
           { width: 15px;height: 15px;background-color: #fff;
             border-radius: 50px;box-shadow: #fff 0px 0px 30px 5px;
             float: left;margin: 200px 0 0 -380px;}
    figure .dot-rotate1 #dot-rotate2 .dot2 .inner2 .dot2-7
           { opacity:80%;width: 15px;height: 15px;background-color: #fff;
             border-radius: 50px;box-shadow: #fff 0px 0px 30px 5px;
             float: left;margin: 300px 0 0 -580px;}
    figure .dot-rotate1 #dot-rotate2 .dot2 .inner2 .dot2-8
           { opacity:70%;width: 10px;height: 10px;background-color: #fff;
             border-radius: 50px;box-shadow: #fff 0px 0px 30px 5px;
             float: left;margin: 230px 0 0 200px;}
    figure .dot-rotate1 #dot-rotate2 .dot2 .inner2 .dot2-9
           { opacity:80%;width: 10px;height: 10px;background-color: #fff;
             border-radius: 50px;box-shadow: #fff 0px 0px 30px 5px;
             float: left;margin: 250px 0 0 200px;}
    figure .dot-rotate1 #dot-rotate2 .dot2 .inner2 .dot2-10
           { opacity:50%;width: 5px;height: 5px;background-color: #fff;
             border-radius: 50px;box-shadow: #fff 0px 0px 30px 5px;
             float: left;margin: 230px 0 0 300px;}
 
                                 /*face3*/
    figure .dot-rotate1 #dot-rotate2 .dot3 .inner2
           { margin: 0 0 0 0;}
    figure .dot-rotate1 #dot-rotate2 .dot3 .inner2 .dot3-1 
           { opacity:50%;
             width: 3px;height: 3px;background-color: #fff;
             border-radius: 50px;box-shadow: #fff 0px 0px 30px 5px;
             float: left;margin: 420px 0 0 -300px;}
    figure .dot-rotate1 #dot-rotate2 .dot3 .inner2 .dot3-2
           { opacity:50%;
             width: 3px;height: 3px;background-color: #fff;
             border-radius: 50px;box-shadow: #fff 0px 0px 30px 5px;
             float: left;margin: 300px 0 0 -100px;}
    figure .dot-rotate1 #dot-rotate2 .dot3 .inner2 .dot3-3
           { opacity:80%;
             width: 3px;height: 3px;background-color: #fff;
             border-radius: 50px;box-shadow: #fff 0px 0px 30px 5px;
             float: left;margin: 400px 0 0 -150px;}
    figure .dot-rotate1 #dot-rotate2 .dot3 .inner2 .dot3-4
           { opacity:50%;
             width: 10px;height: 10px;background-color: #fff;
             border-radius: 50px;box-shadow: #fff 0px 0px 30px 5px;
             float: left;margin: 500px 0 0 50px;}
    figure .dot-rotate1 #dot-rotate2 .dot3 .inner2 .dot3-5
           { opacity:50%;
             width: 10px;height: 10px;background-color: #fff;
             border-radius: 50px;box-shadow: #fff 0px 0px 30px 5px;
             float: left;margin: 300px 0 0 0;}
    figure .dot-rotate1 #dot-rotate2 .dot3 .inner2 .dot3-6
           { width: 10px;height: 10px;background-color: #fff;
             border-radius: 50px;box-shadow: #fff 0px 0px 30px 5px;
             float: left;margin: 400px 0 0 200px;}
    figure .dot-rotate1 #dot-rotate2 .dot3 .inner2 .dot3-7
           { opacity:70%;width: 15px;height: 15px;background-color: #fff;
             border-radius: 50px;box-shadow: #fff 0px 0px 30px 5px;
             float: left;margin: 200px 0 0 0;}
    figure .dot-rotate1 #dot-rotate2 .dot3 .inner2 .dot3-8
           { opacity:50%;width: 15px;height: 15px;background-color: #fff;
             border-radius: 50px;box-shadow: #fff 0px 0px 30px 5px;
             float: left;margin: 450px 0 0 100px;}

                          /* 3D 배치 */
    .dot1  { transform: rotateY(0deg) translateZ(-900px);}
    .dot2  { transform: rotateY(20deg) translateZ(-900px);}
    .dot3  { transform: rotateY(40deg) translateZ(-900px);}

           /*--------------- 메인화면 / 그림 ----------------------*/             
    figure .image
           { position: absolute;margin: 21vmin 0 0 -5vmin;}
           /*-------------톱니바퀴 그림---------------*/
    figure .img0
           { opacity: 100%;margin: 2vmin 0 0 107vmin;
             animation: opacity ease normal infinite;
             animation-delay: 9s;
             animation-duration: 45s;}
             @keyframes opacity 
           { 0%  { opacity: 100%;}
             2%  { opacity: 100%; }
             40% { opacity: 100%; }}                         
    figure .img0-1 /*-큰톱니바퀴-*/
           { width: 20vmin;height: 19vmin;
             background-image: url(imagefile1/톱니바퀴2.png);
             background-size: 100%;
             position:absolute;margin-top: 27vmin;margin-left: -8vmin;
             animation: rotate_img1 linear infinite;
             animation-duration: 20s;
             transform-origin: 50% 50%;}
             @keyframes rotate_img1
           { 0%  { transform: rotate(.001deg);}
             100%{ transform: rotate(360deg); }} 
    figure .img0-2 /*-작은톱니바퀴-*/
           { width: 23.5vmin;height: 23.5vmin;
             background-image: url(imagefile1/톱니바퀴2-1.png);
             background-size: 100%;
             position:absolute;margin-top: 10.5vmin;margin-left: -16.5vmin;
             opacity: 100%;
             animation: rotate_img1-1 linear infinite;
             animation-duration: 20s;
             transform-origin: 50% 50%;}
             @keyframes rotate_img1-1
           { 0%  { transform: rotate(-001deg);}
             100%{ transform: rotate(-360deg); }} 
    figure .img0:hover
           { opacity: 100%;
             transition: 0.5s;}     

    /*-------------------지구--------------------*/
    figure .img1
           { width: 67vmin;height: 67vmin;
             background-image: url(imagefile1/세계지도.png);
             background-size: 100%;
             opacity: 100%;position:absolute;margin: -3vmin 0 0 29vmin;}
    figure .img1-1
           { width: 67vmin;height: 67vmin;
             background-image: url(imagefile1/grid.png);
             background-size: 99%;
             opacity: 30%;position:absolute;margin: 0.2vmin 0 0 0.4vmin;
             animation: img1-1 ease infinite;
             animation-duration: 15s;}
             @keyframes img1-1 
           { 0%  { opacity: 0%; }
             50% { opacity: 30%;}
             60% { opacity: 0%;}             
             100%{ opacity: 0%; }}

    /*-------------공장,해,달 그림---------------*/
    figure .img2 /*-공장-*/
           { width: 33vmin;height: 21vmin;
             background-image: url(imagefile1/공장.png);
             background-size: 100%;
             opacity: 90%;
             position: absolute;
             margin-top: 27.5vmin;margin-left: 19vmin;}
    figure .img2-1 /*-해-*/
           { width: 6vmin;height: 6vmin;
             background-image: url(imagefile1/해.png);
             background-size: 100%;
             opacity: 100%;            
             position: absolute;
             margin-top: -4vmin;margin-left: 22vmin;
             animation: img0-1 ease infinite;
             animation-duration: 20s;}
             @keyframes img0-1 
           { 50% { opacity: 0%;animation: 5s}}
    figure .img2-2 /*-달-*/
           { width: 6vmin;height: 6vmin;
             background-image: url(imagefile1/달.png);
             background-size: 100%;
             opacity: 100%;animation: 20s ease infinite;
             position: absolute;
             margin-top: -4vmin;margin-left: 22vmin;}
    figure .img2:hover
           { opacity: 100%;
             transition: 0.5s linear;} 

    /*-------------노트북 그림---------------*/             
    figure .img3
           { width: 20vmin;height: 20vmin;
             background-image: url(imagefile1/노트북.png);
             background-size: 103%;
             opacity: 100%;
             position:absolute;margin-top: 0vmin;margin-left: 69vmin;}
    figure .img3:hover
           { opacity: 100%;
             transition: 0.5s;}
    figure .img3-1    /*--노트북 text-*/
           { width: 14vmin;height: 9vmin;
             background-image: url(imagefile1/노트북text.gif);
             background-size: 100%;
             opacity: 100%;
             position:absolute;margin-top: 2.3vmin;margin-left: 4.5vmin;}
    figure .img3-2     /*-- 아이콘 --*/
           { width: 9vmin;height: 9vmin;
             position: absolute;margin-top: -4vmin;margin-left: 19vmin;
             animation: img3-2 linear infinite;
             animation-delay: 2s;
             animation-duration: 10s;}
             @keyframes img3-2 
           { 0%   { opacity:0%  ;background:url(imagefile1/아이콘1-1.png)no-repeat;background-size: 95%;}
             1%   { opacity:100%;background:url(imagefile1/아이콘1-1.png)no-repeat;background-size: 95%;}  
             9%   { opacity:100%;background:url(imagefile1/아이콘1-1.png)no-repeat;background-size: 95%;}
             10%  { opacity:100%;background:url(imagefile1/아이콘2-1.png)no-repeat;background-size: 95%;}
             18%  { opacity:100%;background:url(imagefile1/아이콘2-1.png)no-repeat;background-size: 95%;}
             19%  { opacity:100%;background:url(imagefile1/아이콘3-1.png)no-repeat;background-size: 95%;}
             27%  { opacity:100%;background:url(imagefile1/아이콘3-1.png)no-repeat;background-size: 95%;}
             28%  { opacity:100%;background:url(imagefile1/아이콘4-1.png)no-repeat;background-size: 95%;}
             36%  { opacity:100%;background:url(imagefile1/아이콘4-1.png)no-repeat;background-size: 95%;}
             37%  { opacity:100%;background:url(imagefile1/아이콘5-1.png)no-repeat;background-size: 95%;}
             45%  { opacity:100%;background:url(imagefile1/아이콘5-1.png)no-repeat;background-size: 95%;}
             46%  { opacity:100%;background:url(imagefile1/아이콘6-1.png)no-repeat;background-size: 95%;}
             54%  { opacity:100%;background:url(imagefile1/아이콘6-1.png)no-repeat;background-size: 95%;}
             55%  { opacity:100%;background:url(imagefile1/아이콘7-1.png)no-repeat;background-size: 95%;}
             63%  { opacity:100%;background:url(imagefile1/아이콘7-1.png)no-repeat;background-size: 95%;}
             64%  { opacity:100%;background:url(imagefile1/아이콘8-1.png)no-repeat;background-size: 95%;}
             72%  { opacity:100%;background:url(imagefile1/아이콘8-1.png)no-repeat;background-size: 95%;}
             80%  { opacity:0%  ;background:url(imagefile1/아이콘8-1.png)no-repeat;background-size: 95%;}
             100% { opacity:0%  ;background:url(imagefile1/아이콘8-1.png)no-repeat;background-size: 95%;} }
    figure .img3-3       /*-- loading --*/
           { width: 37vmin;height: 37vmin;
             background-size: 100%;
             opacity: 100%;
             position: absolute;margin-top: -15vmin;margin-left: 2.2vmin;
             animation: loading linear infinite;
             animation-delay: 2s;animation-direction: normal;
             animation-duration: 10s;}
             @keyframes loading 
           { 1%   { opacity:100%;left:0px; top:0px;background-image: url(imagefile1/loading\(1\).png);} 
             9%   { opacity:100%;left:0px; top:0px;background-image: url(imagefile1/loading\(3\).png);} 
             17%  { opacity:100%;left:0px; top:0px;background-image: url(imagefile1/loading\(5\).png);}   
             25%  { opacity:100%;left:0px; top:0px;background-image: url(imagefile1/loading\(7\).png);}
             33%  { opacity:100%;left:0px; top:0px;background-image: url(imagefile1/loading\(9\).png);}
             37%  { opacity:100%;left:0px; top:0px;background-image: url(imagefile1/loading\(1\).png);} 
             45%  { opacity:100%;left:0px; top:0px;background-image: url(imagefile1/loading\(3\).png);} 
             53%  { opacity:100%;left:0px; top:0px;background-image: url(imagefile1/loading\(5\).png);}
             61%  { opacity:100%;left:0px; top:0px;background-image: url(imagefile1/loading\(7\).png);}
             69%  { opacity:100%;left:0px; top:0px;background-image: url(imagefile1/loading\(9\).png);}
             80%  { opacity:0%  ;left:0px; top:0px;background-image: url(imagefile1/loading\(9\).png);}
             100% { opacity:0%  ;left:0px; top:0px;background-image: url(imagefile1/loading\(9\).png);} }

    /*-------------카메라 그림---------------*/ 
    figure .img4
           { opacity: 100%;
             width: 35vmiin;height: 15vmin;object-fit: cover;
             position: absolute;margin-top: 1vmin;margin-left: 2.1vmin;}
    figure .img4-1 /*-작은상자-*/
           { width: 18vmin;height: 10vmin;
             background-image: url(imagefile1/작은상자2.gif);
             background-size: 100%;
             opacity: 100%;
             position: absolute;margin-top: 8vmin;margin-left: 38vmin;}
    figure .img4-2 /*-화면-*/
           { width: 18.3vmin;height: 10.6vmin;
             background-image: url(imagefile1/카메라1-1.png);
             background-size: 100%;
             opacity: 100%;
             position: absolute;margin-top: -0.2vmin;margin-left: -0.1vmin;}
    figure .img4-3 /*-카메라-*/
           { width: 8vmin;height: 7vmin;
             background-image: url(imagefile1/카메라1.png);
             background-size: 100%;
             opacity: 100%;
             position: absolute;margin-top: 14vmin;margin-left: 51.9vmin;}
    figure .img4:hover
           { opacity: 100%;transition: 0.5s;}

    /*-------------EES ICON---------------*/ 
    figure .img5   /*-EES ICON-*/
           { opacity: 100%;background-color: ;
             width: 30px;height: 200px;object-fit: cover;
             display: none;
             position: absolute;margin-top: -450px;margin-left: 1200px;
             animation: ;}
    figure .img5-1 
           { opacity: 100%;background-color: ;
             width: 30px;height: 200px;object-fit: cover;
             position: absolute;margin-top: -500px;margin-left: 1300px;}
    figure .img5:hover
           { opacity: 100%;transition: 0.5s;}

      /*-------------회사이름/text, 문의하기버튼---------------*/
    figure .inner 
           { width: 50vmin;height: 30vmin;
             position: absolute;margin: 8vmin 0 0 17vmin;}
    figure .inner .logo
           { width: 7vmin;height: 4.5vmin;
             background-image: url(imagefile1/logo-white\(GIF\).gif);
             background-size: 100%;margin: 5vmin 0 0 0vmin;}             
    figure .inner h1 
           { font: lighter 5.8vmin "HY견고딕";color: rgb(255, 255, 255);
             padding-left: 2.2vmin;margin: -5.3vmin 0 2.1vmin 7.7vmin;}          
    figure .inner p 
           { font: 3vmin/1.4 "franklin gothic book";
             letter-spacing: 1px;color: rgb(255, 255, 255);
             margin-bottom: 35px;}
    figure .inner a 
           { width: 280px;height: 65px;
	           border: 2px solid #ffffff;border-radius: 15px;
	           font: bold 20px/30px "HY헤드라인M";color: #ffffff;
	           text-align: center;letter-spacing: 1px;
	           transition: all 0.5s;display: block;padding-top:15px;}
    figure .inner a:hover 
           { opacity: 70%;
             font: bold 20px/30px "HY헤드라인M";color: #2e4ada;
             border: 2px solid #2e4ada;}

    /*-----------------------------NOTICE-----------------------------*/
    figure .NOTICE
           { width: 100%;height: 60vmin;
             position: relative;margin: 3.5vmin 0 0 115vmin;}
    figure .NOTICE-background
           { width: 100%;height: 60vmin;
             background-color: rgba(26, 63, 211, 0.589); /*rgba(255, 255, 255, 0.301)rgba(16, 27, 68, 0.733);;*/
             opacity: 0%;
             border-radius: 4.1vmin 0 0 4.1vmin;
            /*box-shadow: rgba(82, 159, 231, 0.733) 0px 0px 50px 15px;*/
             position: absolute;margin: 3.5vmin 0 0 105vmin;
             animation: slide ease normal infinite;
             animation-delay: 9s;
             animation-duration: 45s;}
             @keyframes slide
           { 0%  {opacity: 100%;margin-left: 200vmin;background-color: rgba(27, 48, 139, 0.911);}
             2%  {opacity: 100%;margin-left: 0vmin;background-color: rgba(21, 30, 70, 0.911);}             
             40% {opacity: 100%;margin-left: 0vmin;background-color: rgba(26, 41, 109, 0.911);}
             55% {opacity: 100%;margin-left: 0vmin;background-color: rgba(21, 30, 70, 0.911);}
             65% {opacity: 100%;margin-left: 0vmin;background-color: rgba(26, 41, 109, 0.911);}
             70% {opacity: 100%;margin-left: 200vmin;background-color: rgba(27, 48, 139, 0.911);}
             80% {opacity: 100%;margin-left: 200vmin;background-color: rgba(21, 30, 70, 0.911);}
             100%{opacity:   0%;margin-left: 200vmin;background-color: rgba(21, 30, 70, 0.911);}}/*rgba(26, 63, 211, 0.589)*/
    figure .NOTICE-title
           { width: 33vmin;height: 5vmin;
             position: absolute;margin: 3.9vmin 0 0 10.5%;
             animation: EESICON ease normal infinite;
             animation-delay: 9s;
             animation-duration: 45s;}
             @keyframes EESICON
           { 0%  { opacity: 100%;}
             80% { opacity: 100%;}
             100%{ opacity:   0%;}}
    figure .title-text
           { font: bolder 3.5vmin "franklin gothic book";letter-spacing: 1px;
             background: linear-gradient(180deg,#48defb 30%,#2132cc,#1f66ff 80%);
             text-align: center;color: transparent;
             background-clip: text;
             -webkit-background-clip: text;
             color: transparent;
             position: center;margin: -1vmin 0 0 7.5%;}
    figure .NOTICE .NOTICE-background .H1 /*----알림 text (1)----*/
           { width: 100%;height: 45vmin;background-color: rgb(34, 49, 116);/*rgb(35, 46, 94)*/
             font: lighter 2.5vmin "arial";color: #fff;
             text-align: left;float: left;
             border-radius: 2.9vmin;
             position: absolute;
             padding: 5vmin 5vmin;margin: 10.1vmin 0 0 5vmin;
             animation: H1 ease normal infinite;
             animation-delay: 9s;
             animation-duration: 45s;}
             @keyframes H1
           { 0%  { opacity: 0%;}
             3%  { opacity: 100%;}
             30% { opacity: 100%;}
             32% { opacity: 100%;}
             100%{ opacity: 100%;}}
    figure .EESSolution .background .H2   /*----알림 text (2)----*/
           { width: 100%;height: 45vmin;background-color: rgb(34, 49, 116);/*rgb(35, 46, 94)*/
             font: lighter 2.5vmin "arial";color: #fff;
             text-align: left;float: left;
             position: absolute;margin: 40px 0 0 0;}

    /*-----------------------INFOMATION--------------------------*/
    section 
           { width: 123vmin;height: 70vmin;
             position: center;padding: 19vmin 0vmin;margin: 0 auto 0;}
    section .inner 
           { width: 123vmin;height: 40vmin;
             position: center;padding: 0 0 0;margin: -150px auto 0;}
    section .inner h1   /*------제목------*/
           { font: bold 3.5vmin "franklin gothic book";color: rgb(46, 46, 46);
	           text-align: center;letter-spacing: 0.15vmin;
	           margin-bottom: 5vmin;}
    section .inner article 
           { width: 18.5vmin;height: 30vmin;
             float: left;
             padding: 4vmin auto 0;margin: 5vmin 0 0 10vmin;}
	           /*제일 오른쪽 마지막 요소만 여백제거*/   
    section .inner article img 
           { object-fit: cover; /*pic프레임안에 이미지 꽉 채움*/
	           width: 100%;height: 100%;padding-top:0px;}
    /*--------Email---------*/
    section .inner article .pic1 
           { width: 100%;height: 13vmin;background:rgb(255, 255, 255);
             object-fit: cover;position:relative;
	           overflow: hidden;animation: mogocen 1s steps(1) 4 forwards;
             margin-bottom: 15px;}
    section .inner article .pic1 .Emailicon2
           { opacity: 0;}
    section .inner article .pic1 .Emailicon2
           { width: 100%;height: 13vmin;background:rgb(255, 255, 255);
             object-fit: cover;display:block; position:absolute;
	           overflow: hidden;transition: opacity 1s; 
             margin-bottom: 15px;}
    section .inner article .pic1:hover .Emailicon2 
           { opacity: 100;}

    /*--------Fax---------*/
   section .inner article .pic2
           { width: 100%;height: 13vmin;background:rgb(255, 255, 255);
             object-fit: cover;position:relative;
	           overflow: hidden;animation: mogocen 1s steps(1) 4 forwards;
             margin-bottom: 15px;}
   section .inner article .pic2 .Faxicon2
           { opacity: 0;}             
   section .inner article .pic2 .Faxicon2
           { width: 100%;height: 13vmin;background:rgb(255, 255, 255);
             object-fit: cover;display:block; position:absolute;
	           overflow: hidden;transition: opacity 1s; 
             margin-bottom: 15px;}
   section .inner article .pic2:hover .Faxicon2 
           { opacity: 100;}
             
    /*--------Tell---------*/             
   section .inner article .pic3
           { width: 100%;height: 13vmin;background:rgb(255, 255, 255);
             object-fit: cover;position:relative;
	           overflow: hidden;animation: mogocen 1s steps(1) 4 forwards;
             margin-bottom: 15px;}
   section .inner article .pic3 .Tellicon2
           { opacity: 0;}             
   section .inner article .pic3 .Tellicon2
           { width: 100%;height: 13vmin;background:rgb(255, 255, 255);
             object-fit: cover;display:block; position:absolute;
	           overflow: hidden;transition: opacity 1s; 
             margin-bottom: 15px;}
   section .inner article .pic3:hover .Tellicon2 
           { opacity: 100;}
             
    /*--------Adress---------*/             
   section .inner article .pic4
           { width: 100%;height: 13vmin;background:rgb(255, 255, 255);
             object-fit: cover;position:relative;
	           overflow: hidden;animation: mogocen 1s steps(1) 4 forwards;
             margin-bottom: 15px;}
   section .inner article .pic4 .Adressicon2
           { opacity: 0;}             
   section .inner article .pic4 .Adressicon2
           { width: 100%;height: 13vmin;background:rgb(255, 255, 255);
             object-fit: cover;display:block; position:absolute;
	           overflow: hidden;transition: opacity 1s; 
             margin-bottom: 15px;}
   section .inner article .pic4:hover .Adressicon2 
           { opacity: 100;}

    /*--------Info---------*/             
   section .inner article .pic5 
           { width: 100%;height: 13vmin;background:rgb(255, 255, 255);
             object-fit: cover;position:relative;
	           overflow: hidden;
             margin-bottom: 15px;}
   section .inner article .pic5 img
           { width: 100%;height: 13vmin;background:rgb(255, 255, 255);
             object-fit: cover;display:block; position:absolute;
	           overflow: hidden;transition: opacity 1s; 
             margin-bottom: 15px;}
   section .inner article .pic5:hover img:last-child 
           { opacity: 0;} 

    /*--------Text---------*/
   section .inner article h2    /*------제목-----*/
           { font: bold 2.3vmin/1 "franklin gothic book";color: #1834a2;
             text-align: center;letter-spacing: 1px;margin-bottom: 10px;}
   section .inner article p     /*------영문-----*/
           { font: normal 2.2vmin/1.6 "arial";color: rgb(73, 73, 73);
             text-align: center;letter-spacing: 1px;}
   section .inner article .p1   /*------숫자-----*/
           { font: normal 2.1vmin/1.3 "arial";color: rgb(73, 73, 73);
             text-align: center;letter-spacing: 2px;padding-top: 4px;}
   section .inner article .p2   /*------한글-----*/
           { font: normal 1.8vmin/1.3 "arial";color: rgb(32, 32, 32);
             letter-spacing: 1px;padding-top: 5px;}

    /*-------------------------CLIENTS---------------------------------*/
    section .inner2 
           { width: 123vmin;height: 50vmin;
             position: relative;margin: 0 auto 0;}
    section .inner2 h1   /*------제목------*/
           { font: bold 3.5vmin "franklin gothic book";color: rgb(46, 46, 46);
	           text-align: center;letter-spacing: 0.15vmin;
	           margin-bottom: 5vmin;}        
    section .inner2 #clients
           { width: 123vmin;height: 40vmin;
             position:absolute;margin: 9vmin auto 0;}
                        /*------slide-------*/
    section .inner2 .content
           { /*컨텐츠 넓이지정*/
             width: 50%;height: 40vmin;
             position: center;margin: -20.5vmin auto 0;}
    section .inner2 .slides
           { /*슬라이드 아이템이 나올 뼈대 지정*/
             width: 50vmin;height: 40vmin;position: absolute;}
    section .inner2 .slide_item
           { /*슬라이드 아이템을 absolute로 겹쳐놓고 투명하게 하기*/
             width: 55vmin;height: 30vmin;background-color: rgb(255, 255, 255);
             opacity: 0;transition: all 0.3s;
             position: absolute;margin: 15vmin 0 0 0;}

    section .slide_item .gdaesung
           { display: inline-block;position: absolute;
             padding: 0vmin 7vmin;margin: -0.9vmin 0 0 0;}
    section .slide_item .SAMSUNGSDI
           { display: inline-block;position: absolute;
             padding: 0vmin 7vmin;margin: 0vmin 0 0 1.9vmin;}
    section .slide_item .daeduck
           { display: inline-block;position: absolute;
             padding: 0vmin 7vmin;margin: -0.5vmin 0 0 0;}                                     
    section .slide_item .OPTRONTEC
           { margin: 1.7vmin 0 0 1.5vmin;}
    section .inner2 .ontheSlide
           { /*현재 아이템에 붙여줄 클래스*/
             opacity: 1;transition: all 0.5s;}    

    /*---------------------------Footer--------------------------------*/
    footer 
           { width: 100%;background: rgb(16, 20, 34);
	           padding: 7vmin 0px;margin: 60vmin 0 0 0;}
    footer .inner 
           { width: 123vmin;padding-bottom: 10vmin;margin: 0px auto;}
    footer .inner .upper        /*--언더라인--*/
           { width: 100%;
	           border-bottom: 0.2vmin solid #777;
	           padding-bottom: 1.3vmin;}
    footer .inner .logo-footer  /*----로고----*/
           { width: 30vmin;display: inline-flex;
             padding-left: 2vmin;margin: -3vmin 0 0 -2.1vmin;}             
	  /*상단 영역 float해제*/    
    footer .inner .upper::after 
           { content: "";
	           display: block;
	           clear: both;}
    footer .inner .upper ul 
           { float: right;}
    footer .inner .upper ul li /*--policy terms ...--*/
           { float: left;
             margin-left: 1.5vmin;}
    footer .inner .upper ul li a/*--policy terms ...--*/ 
           { font: bold 1.3vmin "arial";color: rgb(205, 207, 214);}
    footer .inner .lower        /*----회사정보내용---*/ 
           { width: 100%;padding-top: 1.3vmin;}
    footer .inner .lower address 
           { width: 100%;
             font: 1.3vmin/2.3 "arial";color: rgb(205, 207, 214);
	           margin-bottom: 2vmin;}                                                  
    footer .inner .lower p 
           { width: 100%;
	           font: 1.3vmin/2.3 "arial";color: rgb(205, 207, 214);
             letter-spacing: 0.10vmin;margin-top: -2vmin;}
</style>
</head>

<body>
  <link href="(m)main.css" rel="stylesheet" media="screen and (min-width:  270px)and (max-width: 980px)"> 
  <link href="(t)main.css" rel="stylesheet" media="screen and (min-width: 600px)and (max-width: 1280px)">
  <link href="(l)main.css"rel="stylesheet" media="screen and (min-height:   0px)and (max-height: 800px)">
  <header>
    <nav class="navbar">
      <ul class="util">
        <li><a href="#">Contact</a></li>  
        <li><a href="#">   Help</a></li>  
        <li><a href="#">  Login</a></li>  
        <li><a href="#">   Join</a></li>  
        <li><a href="#">Sitemap</a></li>        
        </ul> 
        
        <a href="(2)main.html">
        <div class="navbar__logo"></div>
        </a>   
      
      <ul class="navbar__menu">
        <li><a href="(2)main.html">HOME</a></li>
        <li><a href="(2)회사소개.html">회사소개</a></li>
        <li><a href="(2)사업분야.html">사업분야</a></li>
        <li><a href="(2)보유기술소개.html">보유기술소개</a></li>
        <li><a href="(2)주요실적.html">주요실적</a></li>
        <li><a href="(2)외주개발실적.html">외주개발실적</a></li>
      </ul>
      <a href="#" class="menubar"></a>    
    </nav>   
  </header>  

   <!-----------------------------메인화면 그림----------------------------------->
<body>
<figure>

    <div class="background-color">    <!---배경색상--->
    <div class="grid"></div>          <!---배경Grid--->       
    </div>

    <div class="main"> 
      <div class="rotate1">
      <div id="rotate2">
    
          <article class="image1">  <!--1-->
            <div class="inner1">
                <div><img src="imagefile1/Machine Vision Solution (Classical Algorithm 기반,배경이미지).png"width="100%"></div>
            </div>
          </article>
    
          <article class="image2">
            <div class="inner1">  <!--8-->
                <div><img src="imagefile1/배경이미지3-1.gif"width="100%"></div>    
            </div>
          </article>
    
          <article class="image3">  <!--7-->
            <div class="inner1">
                <div><img src="imagefile1/NILTECH(favicon).png"width="100%"></div> 
            </div>
          </article>
    
          <article class="image4">  <!--6-->
            <div class="inner1">
                <div><img src="imagefile1/EESsolution(s-size).gif"width="100%"></div>   
            </div>
          </article>
    
          <article class="image5">  <!--5-->
            <div class="inner1">
                <div><img src="imagefile1/outsourced Solution(배경이미지).png"width="100%"></div>    
            </div>
          </article>
    
          <article class="image6">  <!--4-->
            <div class="inner1">
                <div><img src="imagefile1/ACS(AGV Control System 배경이미지2).png"width="100%"></div> 
            </div>
          </article>
    
          <article class="image7">	 <!--3-->
            <div class="inner1">
                <div><img src="imagefile1/CIM MES Solution(배경이미지).png"width="100%"></div> 
            </div>
          </article>
    
          <article class="image8"> <!--2-->
            <div class="inner1">
                <div><img src="imagefile1/Machine Vision Solution (AI 기반,배경이미지).png"width="100%"></div>   
            </div>
          </article>
      </div>
      </div>
      </div>	
   
    <!--------------------빛 장식---------------------> 
    <div class="dot-rotate1">
      <div id="dot-rotate2">
           <article class="dot1">
              <div class="inner2">
           <div class="dot1-1"></div>
              <div class="dot1-2"></div>
              <div class="dot1-3"></div>
              <div class="dot1-4"></div>
              <div class="dot1-5"></div>
              <div class="dot1-6"></div>
              <div class="dot1-7"></div>
              <div class="dot1-8"></div>
              <div class="dot1-9"></div>
              <div class="dot1-10"></div>
              </div>
          </article>
    
          <article class="dot2">
           <div class="inner2">
           <div class="dot2-1"></div>
              <div class="dot2-2"></div>
              <div class="dot2-3"></div>
              <div class="dot2-4"></div>
              <div class="dot2-5"></div>
              <div class="dot2-6"></div>
              <div class="dot2-7"></div>
              <div class="dot2-8"></div>
              <div class="dot2-9"></div>
              <div class="dot2-10"></div>
           </div>
          </article>
    
          <article class="dot3">
           <div class="inner2">
           <div class="dot3-1"></div>
              <div class="dot3-2"></div>
              <div class="dot3-3"></div>
              <div class="dot3-4"></div>
              <div class="dot3-5"></div>
              <div class="dot3-6"></div>
              <div class="dot3-7"></div>
              <div class="dot3-8"></div>
              <div class="dot3-9"></div>
              <div class="dot3-10"></div>
           </div>
           </article>
    
       </div>
      </div>  

    <!------------------------------------------------> 
    <div class="image">
                   <!--------톱니바퀴 그림------------> 
    <div class="img0">  
    <div class="img0-1"></div>
    <div class="img0-2"></div>
    </div> 

                   <!--------------지구---------------> 
    <div class="img1">
    <div class="img1-1"></div>
    </div>     
                   <!--------공장,해,달 그림------------>
    <div class="img2">
    <div class="img2-1"></div>
    <div class="img2-2"></div>
    </div>  
                   <!--------노트북 그림------------>                  
    <div class="img3">
    <div class="img3-1"></div>
    <div class="img3-2"></div>  
    <div class="img3-3"></div>  
    </div>
                   <!--------카메라 그림------------>
    <div class="img4">
    <div class="img4-1">
    <div class="img4-2"></div>
    </div>
    <div class="img4-3"></div>
    </div>


    </div>

   <!--------------------------로고,회사이름/문의하기----------------------------->
    <div class="inner">
     <div class="logo"></div>  
     <h1>NILTECH</h1>
     <p>Smart Factory, Complete Solution</p>

    </div>

   <!-------------------------------------NOTICE------------------------------------->    
    <div class="NOTICE">
    <div class="NOTICE-background">
    <div class="NOTICE-title">
    <div class="title-text">NOTICE</div>
    </div>
    <div class="H1">
    <div class="H2">
    </div></div>     
    

    </div>
    </div>

</figure>


   <!---------------------------------INFORMATION---------------------------------->
<section>
    <div class="inner">
      <h1>INFORMATION</h1>
    <!-------Email-------->
<article id="article1">
    <div class="wrap">
    <div class="pic1">
      <img src="imagefile1/Email2.gif" alt="Email아이콘"width="100%"class="Emailicon2">
      <img src="imagefile1/Email1.png" alt="Email아이콘"width="100%"class="Emailicon1">
      </div>
      <h2>E-MAIL</h2>
      <p>haniro@naver.com</p>
</div>
</article>
   <!-------Fax-------->
<article id="article2">
    <div class="wrap">
    <div class="pic2">
      <img src="imagefile1/Fax2.gif" alt="Fax아이콘"width="100%"class="Faxicon2">
      <img src="imagefile1/Fax1.png" alt="Fax아이콘"width="100%"class="Faxicon1">
    </div>
      <h2>FAX</h2>
      <p class="p1">02-554-2001</p>
</div>
</article>
    <!-------Tell-------->
<article id="article3">
    <div class="wrap">   
    <div class="pic3">
      <img src="imagefile1/Tell2.gif" alt="Tellicon1"width="100%"class="Tellicon2">
      <img src="imagefile1/Tell1.png" alt="Tellicon1"width="100%"class="Tellicon1">
    </div>
      <h2>TELL</h2>
      <p class="p1">031-554-2001</p>
</div>      
</article>
    <!-------Adress-------->
<article id="article4">
    <div class="wrap">
    <div class="pic4">
      <img src="imagefile1/Adress2.gif" alt="Adressicon1"width="100%"class="Adressicon2">
      <img src="imagefile1/Adress1.png" alt="Adressicon1"width="100%"class="Adressicon1">
    </div>
      <h2>ADRESS</h2>
      <p class="p2">경기도 화성시 동탄 문화센터로 아시아프라자 7F</p>
</div>
</article>
</div>

   <!---------------------------------CLIENTS---------------------------------->      
   <div class="inner2">
    <h1>CLIENTS</h1>
  <div id="clients">      
    <div class="content">
    <div class="slides">

      <div class="slide_item">
      <a href="https://www.semes.com">  
      <img src="imagefile1/자료/SEMES.png"alt="SEMES"width="55%"class="SEMES"> <!--슬라이드될 아이템들 -->
      </a>
      <a href="http://www.gdaesung.com">
      <img src="imagefile1/자료/(주)대성전기.png"alt="gdaesung"width="72%"class="gdaesung">
      </a>
      <a href="https://www.samsungsem.com">
      <img src="imagefile1/자료/SAMSUNG Electro.png"alt="SAMSUNGElectro"width="55%"class="SAMSUNGElectro">
      </a>
      <a href="https://www.samsungsdi.co.kr">
      <img src="imagefile1/자료/SAMSUNG SDI.png"alt="SAMSUNGSDI"width="67%"class="SAMSUNGSDI">
      </a>
      </div>

      <div class="slide_item">
      <a href="https://www.samsung.com">  
      <img src="imagefile1/자료/SAMSUNG.jpg"alt="SAMSUNG"width="55%"class="SAMSUNG">
      </a>
      <a href="https://www.daeduck.com">
      <img src="imagefile1/자료/대덕전자.png"alt="daeduck"width="67%"class="daeduck">
      </a>
      <a href="https://www.optrontec.net">
      <img src="imagefile1/자료/OPTRONTEC.png"alt="OPTRONTEC"width="45%"class="OPTRONTEC">
      </a>
      </div>
    </div>
      <div class="Thumbnail">
      <div class="thumbnail_item1"></div>
      <div class="thumbnail_item1"></div>
      </div>
  </div>
      <!----- Scripts ------>
      <script>
      function sliderOn () {
      const slides = document.querySelector('.slides'); // 슬라이드뼈대 감지
      const Content = document.querySelector('.Thumbnail'); //썸네일 뼈대 감지
      const item = slides.getElementsByClassName('slide_item'); // 슬라이드 아이템 획득
      const thumbnail = Content.getElementsByClassName('thumbnail_item1'); //썸네일 아이템 획득
      const firstEle = item[0]; // 첫번째 슬라이드 아이템
      const firstThumb = thumbnail[0]; // 첫번째 썸네일 아이템
      firstEle.classList.add('ontheSlide'); //첫번째 슬라이드 아이템에 ontheSlide 클래스 추가
      firstThumb.classList.add('ontheThumbnail'); // 첫번째 썸네일 아이템에 ontheThumbnail 클래스 추가
      const gogogo = setInterval(sliderGo, 2300);
      function sliderGo (isThat) {//isThat을 받아오기   
      if (isThat) {//isThat이 지정되어 있다면
      var nextOr = 'previous';} //이전 버튼을 누른 것.
      else { //isThat이 지정되지 않았다면
      var nextOr = 'next';} //다음 버튼을 누른 것.
      const currentItem = document.querySelector('.ontheSlide');
      const currentThumb = document.querySelector('.ontheThumbnail');
      currentItem.classList.remove('ontheSlide')
      currentThumb.classList.remove('ontheThumbnail')
      if (nextOr === 'next'){  // 다음버튼을 눌렀다면
      if (!currentItem.nextElementSibling) {//마지막 아이템일 경우
      item[0].classList.add('ontheSlide') //처음으로 슬라이드아이템 이동
      thumbnail[0].classList.add('ontheThumbnail') }//처음으로 썸네일 아이템 이동
          
      else { //그 외의 경우
      currentItem.nextElementSibling.classList.add('ontheSlide') //다음으로 슬라이드 아이템 이동
      currentThumb.nextElementSibling.classList.add('ontheThumbnail')}} //다음으로 썸네일 아이템 이동
      else if (nextOr === 'previous') { // 이전 버튼을 눌렀다면
      if (!currentItem.previousElementSibling) { //첫번재 아이템일 경우
      item[item.length-1].classList.add('ontheSlide') //마지막 슬라이드로 이동
      thumbnail[thumbnail.length-1].classList.add('ontheThumbnail')}  //마지막 썸네일로 이동
      else { //다른 경우
      currentItem.previousElementSibling.classList.add('ontheSlide') //이전 슬라이드 아이템으로 이동
      currentThumb.previousElementSibling.classList.add('ontheThumbnail')}}} //이전 썸네일 아이템으로 이동
              
      const nextButton = document.querySelector('.nextButton');//다음버튼 감지
      const prevButton = document.querySelector('.prevButton');//이전버튼 감지
      nextButton.addEventListener('click',function(){//다음 버튼을 누른다면
      clearInterval(gogogo)//자동이동을 중지하고
      sliderGo();})//수동으로 다음이동
      prevButton.addEventListener('click',function(){//이전 버튼을 누른다면
      clearInterval(gogogo)//자동이동을 중지하고
      sliderGo('1');})//수동으로 이전 이동  
      for (var i=0; i<thumbnail.length; i++) { // 썸네일 갯수만큼 for문 발동  
      thumbnail[i].setAttribute('data-number',i); // 썸네일에 data-number를 설정해 몇번째 아이템인지 설정
      thumbnail[i].addEventListener('click',function(event){ //썸네일 아이템을 클릭한다면
      clearInterval(gogogo) // 자동이동을 멈춘다.
      const currentItem = document.querySelector('.ontheSlide'); //현재 아이템 감지
      const currentThumb = document.querySelector('.ontheThumbnail'); //현재 썸네일 감지
      currentItem.classList.remove('ontheSlide') // 현재 아이템 비활성화
      currentThumb.classList.remove('ontheThumbnail') // 현재 썸네일 비활성화
      const number = event.target.getAttribute('data-number') // 몇 번째 썸네일을 클릭했는지 감지
      item[number].classList.add('ontheSlide')   // 썸네일과 같은 숫자의 아이템을 활성화
      event.target.classList.add('ontheThumbnail')})}} // 클릭한 썸네일을 활성화
      sliderOn(6);
      </script>
        
  </div>     

  </div>
</section>

      <!------------------------------footer-------------------------------------->
<footer>
  <div class="inner">
  <div class="upper">
    <img src="imagefile1/logo(흰색-s size).png"width="100%"class="logo-footer">
    <ul>
    <li><a href="">Policy</a></li>
    <li><a href="">Terms</a></li>
    <li><a href="">Family Site</a></li>
    <li><a href="">Sitemap</a></li>
    </ul>
  </div>

  <div class="lower">
    <address>
      회사명:&nbsp;&nbsp;&nbsp;(주)닐테크바이팅&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
      대표 :&nbsp;&nbsp;&nbsp;0 0 0&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
      사업자등록번호:&nbsp;&nbsp;&nbsp;000-00-00000&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<br> 
      Email :&nbsp;&nbsp;&nbsp;haniro@naver.com&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
      TEL :&nbsp;&nbsp;&nbsp;031-554-2001&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
      FAX :&nbsp;&nbsp;&nbsp;02-554-2001&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
      ADRESS :&nbsp;&nbsp;&nbsp;경기도 화성시 동탄 문화센터로 아시아프라자 7F<br>
                
    </address>
    <p>niltech &copy; copyright all right reserved.</p>
  </div>
</div>
</footer>

</div>
</body>
</html>
