<!doctype html>
<html>
  <head>
    <title>possibly my chaotic desk</title>
    <link rel="shortcut icon" href="headshot_icon.png">
    <meta charset="UTF-8">
    <style>
     #headline {
        position: sticky;
        color:rgb(0, 0, 0);
        text-shadow: 5px 5px 5px rgb(89, 89, 89);
        /* border: 10px solid black; */
        width: 1000px;
        left: 100px;
        top: 100px;
        font-size: 300px;
        font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        text-align: left;
        z-index: 15;
        }

        #bodytext{
        position: sticky;
        top: 20px;
        left: 10%;
        width: fit-content;
        font-size: 30px;
        z-index: 100;

      }
    
        #idcard {
        position: sticky;
        top: 100px;
        left: 20px;
        width: 1000px;
        rotate: 20deg;
        opacity: 1;
        z-index: 13;
        }

      #casio {
        position: absolute;
        top:auto;
        left: 10px;
        width: 600px;
        rotate: -20deg;
        fill-opacity: 100%;
        z-index: 2;
      }


       #future video {
        position: sticky;
        width: 10vw;
        top: 0;
        left: 0vw;
        rotate: 50deg;
        border-radius: 10% 10% 10% 10%;
        z-index: 14;
    }


      #tagline{
        color: red;
        position:fixed;
        top:50%;
        right: 10%;
        width: fit-content;
        font-size: 100px;
        z-index: 1;

      }

      #links:link {
        color:yellowgreen;
        text-decoration: underline;
        font-style: italic;      
      }
      #links:visited {
        color:black;
        text-decoration: underline;
        font-style: italic;
      }       
      
      #links:hover {
        color:rgb(193, 107, 255);
        font-style: italic;
        /* font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif; */
        text-decoration:dashed;
        background-color: aqua;
        
      }

      #links:active {
        color:rgb(218, 255, 107);
        font-style: italic;
        /* font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif; */
        text-decoration:dashed;
        background-color: rgb(25, 35, 8);

      }

      #notebook{
        rotate: 10deg;
        z-index: -3;
      }

      #sharpie {
        position: absolute;
        width: 180px;
        rotate: -5deg;
        top: 100px;
      }


      #headshot {
        position: fixed;
        top:10%;
        right: 10%;
        width: 100px;
      }

      #headshot:hover{
        rotate: 10deg;
      }
      
      .things {
        transition: rotate 2s ease-in-out;
        rotate: -5deg; 
      }

      .things:hover{
        filter:invert(100%);
        rotate: 90deg;
      }



    </style>
  </head>
  <body>
    <div id="headline"> 
        things
    </div>

 
       <div id="tagline"> 
      buy more <a id= "links" href="https://amazon.com/">things</a> always!
    </div>



    <div id="bodytext"> 
      these are likely the things on my desk.
    </div>




    <a href="https://www.youtube.com/watch?v=wN-mZtbX2Pg">
    <img class= "things" id="casio" src="Scan 4.png">
    </a>

    <!-- <a href="https//:yuanzichen.com"> -->
      <img class= "things" id="notebook" src="Scan 5.png">
      <!-- </a> -->

      <img class= "things" id="idcard" src="Scan 8.png">
      <img class= "things" id="sharpie" src="Sharpie.png">


    <a href="https://yuanzichen.com/">
      <img id="headshot" src="headshot_icon.png"></a>



    <a href="headshot_icon.png">
      <video loop controls id="future" src="future_kanye_west.mp4"></video></a>



  </body>
</html>
