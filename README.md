# Personal-Card
Card
 #HTML 
  <html>
    <head>
        <link rel="stylesheet" href="style.css">
    </head>
    <body>
        <div class="card">  
            <img class="pro-img border-blue" src="pro.jpeg"
             alt="Aman watching the sky and smiling">
           <div class="border-blue">  
            <h3 class="italic"> Aman Kushwaha</h3>
            <p>FrontEnd Developer</p>
            <h4>Kathmandu , Nepal</h4>
           </div>
        </div>
    </body>   
</html>

#CSS
body{

    margin: 20px;
    font-family: Verdana, Geneva, Tahoma, sans-serif;
}
.pro-img{
    width: 150px;
    border-radius: 20px;
}
.card{
    width: 400px;
   margin: 40px auto;
    padding: 20px;
    display: flex;
    justify-content: space-around;
    text-align: center;
    background-color: #ddebf8;
    border-bottom: 20px solid #d8cefe;
}
.italic{
    font-style: italic;
}
.border-bule{
    border: 2px dotted blue;
    text-shadow: #2b2839;
    
}
