
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Challege#1</title>
    <style>
        *{
            padding: 0;
            margin: 0;
        }
        .heading{
            margin: 5px;
            padding: 20px 25px 10px 5px ;
        }
        .heading{
            color: green;
            font-style: italic;
            text-shadow:1px 2px 1px black 
        }
        .one{
            width: 24%;
            height: 25%;
            line-height: 4;
            background-color: aliceblue;
          padding-left: 10px;
          
          float: left;
          border: 1px solid aqua;
          font-style: italic;
          font-size: ;
        }
        .two{
            width: 24%;
            height: 25%;
            background-color: aliceblue;
            padding-left: 6px;
            line-height: 4;
            float: left;
            border: 1px solid aqua;
            font-style: italic;
        }
        .three{
            width: 24%;
            height: 25%;
            background-color: aliceblue;
            padding-left: 6px;
            line-height: 4;
            float: left;
            border: 1px solid aqua;
            font-style: italic;
        }
      
        
        .four{
            width: 24%;
            height: 25%;
            background-color: aliceblue;
            padding-left: 6px;
            line-height: 4;
            float: left;
            border: 1px solid aqua;
            font-style: italic;
        }
       @media all and (max-width:700px){
        .one,.two,.three,.four{
            width: 50%;
        }
       } 
       @media all and (max-width:500px){
       .one,.two, .three,.four{
            width: 75%;
        }
       }
    </style>
</head>
<body>
    <h1 class="heading">
        Meia Query for Coloumns-Increase or decrease the screen size to see the change
    </h1>
    <div id="box">
    <h4 class="one">
        NAME 1<br>
        I am Aman
    </h4>
    <h4 class="two">
        NAME 2<br>
        I am Sohaib
    </h4>
    <h4 class="three">
        NAME 3<br>
      I am Mussab
        
    </h4>
  
    
       <h4 class="four"> NAME 4
        <br>
        I am Asghar
    </h4>
</div>
</body>
</html>
