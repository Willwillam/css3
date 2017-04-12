# css3
CSS3样式代码模板
@charset "utf-8";
/* CSS Document */
body{
    background:#000;
    }
  
h1 {
    text-align:center;
    color:#fff;
	font-size:48px;
   font-family: 'Fruktur', cursive;
   text-shadow: 1px  1px 1px #ccc,
                  0 0 10px #fff,
                   0 0 20px #fff,
                   0 0 30px #fff,
                   0 0 40px #ff00de,
                   0 0 70px #ff00de,
                   0 0 80px #ff00de,
                   0 0 100px #ff00de,
                   0 0 150px #ff00de;
				   
	transform-style: preserve-3d;
	-moz-transform-style: preserve-3d;
	-webkit-transform-style: preserve-3d;	
	-ms-transform-style: preserve-3d;			   
	-o-transform-style: preserve-3d;			   

   
        animation: run  ease-in-out 9s infinite;
   -moz-animation: run  ease-in-out 9s infinite ;	
-webkit-animation: run  ease-in-out 9s infinite;	
-ms-animation: run  ease-in-out 9s infinite;	

     -o-animation: run  ease-in-out 9s infinite;	
}

@keyframes run {
      0% {
        transform:rotateX(-5deg) rotateY(0);	
      }
    50% {
        transform:rotateX(0) rotateY(180deg);	
		 text-shadow: 1px  1px 1px #ccc,
                  0 0 10px #fff,
                   0 0 20px #fff,
                   0 0 30px #fff,
                   0 0 40px #3EFF3E,
                   0 0 70px #3EFFff,
                   0 0 80px #3EFFff,
                   0 0 100px #3EFFee,
                   0 0 150px #3EFFee;
                 
      }
      100% {
        transform:rotateX(5deg) rotateY(360deg);	
      }
    }

@-moz-keyframes run {
      0% {
        -moz-transform:rotateX(-5deg) rotateY(0);	

      }
    50% {
        -moz-transform:rotateX(0) rotateY(180deg);	
		 text-shadow: 1px  1px 1px #ccc,
                  0 0 10px #fff,
                   0 0 20px #fff,
                   0 0 30px #fff,
                   0 0 40px #3EFF3E,
                   0 0 70px #3EFFff,
                   0 0 80px #3EFFff,
                   0 0 100px #3EFFee,
                   0 0 150px #3EFFee;
                 
      }
      100% {
        -moz-transform:rotateX(5deg) rotateY(360deg);	
      }
    }

@-webkit-keyframes run {
      0% {
        -webkit-transform:rotateX(-5deg) rotateY(0);	

      }
    50% {
        -webkit-transform:rotateX(0) rotateY(180deg);	
		 text-shadow: 1px  1px 1px #ccc,
                  0 0 10px #fff,
                   0 0 20px #fff,
                   0 0 30px #fff,
                   0 0 40px #3EFF3E,
                   0 0 70px #3EFFff,
                   0 0 80px #3EFFff,
                   0 0 100px #3EFFee,
                   0 0 150px #3EFFee;
                 
      }
      100% {
        -webkit-transform:rotateX(5deg) rotateY(360deg);	
      }
    }
@-ms-keyframes run {
      0% {
        -ms-transform:rotateX(-5deg) rotateY(0);	

      }
    50% {
        -ms-transform:rotateX(0) rotateY(180deg);	
		
      }
      100% {
        -ms-transform:rotateX(5deg) rotateY(360deg);	
      }
    }


</style>

