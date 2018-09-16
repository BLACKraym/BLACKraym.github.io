


 
 
<!DOCTYPE html>
<html lang="en-US">
  <head>
    <meta charset="utf-8">
    <title>Home page</title>
    <link href="styles/mystyle.css" rel="stylesheet" type="text/css">
    <link href='https://fonts.googleapis.com/css?family=Open+Sans' rel='stylesheet' type='text/css'>
    <style>
    /* all setup*/
    html,body{
    padding:0;
    margin:0;
    }
    html{
    font-size:10px;
    background-color:rgba(16,31,79,50);
    }
    body{
    
    max-width:900px;
    margin:0 auto;
    width:90%;
    }
    
    /*typography*/
    h1,h2{
    color:rgba(222,222,229,99);
    font-family: 'Cinzel Decorative', sans serif;
    }
    nav .ft-anchor{
    color:rgba(200,200,255,90);
    font-size:2.6rem;
    display:inline-block;
    text-transform:uppercase;
    text-decoration:none;
    
    }
    p,li,dd,span{
    color:rgba(200,200,255,90);
    font-family: 'Cinzel Decorative', sans serif;
    }
    h1,h2{
    font-size:4rem;
    text-align:center;
    text-shadow:3px 3px 10px rgba(16,31,79,255);
    }
    h2{
    text-align:center;
    font-size:1.5rem;
    }
    dt{
    font-size:1em;
    }
    p,li,dd,span{
     font-size:1em;
    }
    a{
    color:#aa23ff;
    }
    /*layout*/
     header{^
     margin-bottom:10px;
     display:flex;
     flex:row wrap;
     }
     body>*{
     background-color:rgba(199,103,149,.9);
     padding:1%;
     }
     nav,main{
     background-color:rgba(10,10,10,.4);
     padding:1%;
     }
     .article1{
     padding:1%;
     background-color:rgba(180,180,230,255);
     }
     .article,.article1 > h2,dt{
     color:rgba(16,31,79,255);
     }
     .article > p,dd{
     color:rgba(16,31,79,50);
     }
     .article{
     padding:1%;
     background-color:rgba(180,180,230,255);
     }
     aside{
     background-color:rgba( 200,200,255,50 );
     }
     header,footer{
     background-color:rgba(200,200,255,90);
     }
     h1{
     flex:10;
     text-transform:uppercase;
     }
     header img{
     display:block;
     height:80px;
     padding:20.77px;
     }
     nav{
     display:flex;
     flex:100%;
     height:50px;
     }
     nav ul{
     list-style-type:none;
     display:flex;
     padding:0;
     flex:2;
     }
     nav li{
     display:inline;
     flex:1;
     text-align:center;
     }
     main{
     display:flex;
     }
     article{
     flex:4;
     }
     
     aside{
     margin-left:10px;
     flex:1;
     padding:1%;
     }
     
     aside a{
     display:block;
     float:left;
     width:50%;
     }
     aside img{
     max-width:100%;
     }
     footer{
     display:flex;
     flex:10;
     }
    </style>
  </head>
  
  <body>
        <header>
       <h1>Poetry Camp</h1>
       <img src="dove.png" alt="logo">
       
    </header>
    
    <nav>
       <ul>
      
          <li><a class='ft-anchor' href="#"> home </a></li>
          <li><a class='ft-anchor' href="#"> Catalog </a></li>
          <li><a class='ft-anchor' href="#"> Events</a></li>
          <li><a class='ft-anchor' href="#"> Contact</a></li>
          <li><a class='ft-anchor' href="#"> About us</a></li>
        </ul>
  
</nav>
     <main>
        <article  class="article">
           <h2> Welcome to poet camp</h2>
             <p> Welcome to the new age world-class poets Camp.We do orgnise helpful events that developed one's Poetry potential as follow: Stage confidence, Expression,Speaking skills and many more.</p>
             <p>Some interesting we do are,</p>
                <dl>
                   
                   <dt>Poetry competition</dt>
                      <dd> We arranged Poetry competition every  early autumn, when its about time, the date will ne published <a href="#">here</a></dd>
                  
                    <dt> Stage Confidence</dt>
                       <dd>Million of Prominent world-class poets that are doing well on stage today in term of confidence was breeded here,feel free to <a href="#">join</a></dd>
                    
                    <dt>Expression</dt>
                       <dd> Good expression speak vivid message you want to pass to your audience, and also call the attention of your audience to look at you and automatically they will  like to listen at your words</dd>
                    <dt>Speaking skills</dt>
                        <dd>Many poets are wrestling with communicating to their audience. <a href="#">Here</a> we help many poets from different country around the world to communicate their minds to  their audience</dd>
                        
                  </dl>
                  <p>If you are interesting to join check <a href="#">our Catalog</a> to view our program list</p>
        </article>
        
        <article class="article1">
          <ul>
           <h2>Ongoing classes</h2>
           <li><a href="#">Developing stage confidence</a></li>
           <li><a href="#">Developing Speaking skills</a></li>
           <li><a href="#">Developing communicative expression</a></li>
         </ul>
         <>
         <ul>
         <h2>Ongoing events</h2>
           <li><a class='' href="#"> Shakeperian competition</a></li>
           <li><a class='' href="#"> 24 World country competition</a></li>
           <li><a class='' href="#"> 10 Winners competition</a></li>
          </ul>
         
        </article>
      
        <aside>
        
           <ul>
             <li><a href="#"><img src="images/Library.jpg" alt="  "></a></li>
             <li><a href="#"><img src="images/business.jpg" alt="  "></a></li>
             <li><a href="#"><img src="images/Library.jpg" alt="  "></a></li>
             <li><a href="#"><img src="images/business.jpg" alt="  "></a></li>
              
           </ul>
        </aside>
       
     </main>
     <footer>
     <ul>
        <li><a class='ft-anchor' href="#"> Catalog </a></li>
        <li><a class='ft-anchor' href="#"> Catalog </a></li>
        <li><a class='ft-anchor' href="#"> Catalog </a></li>
        <li><a class='ft-anchor' href="#"> Catalog </a></li>
     </ul>
     <ul>
        <li><a class='ft-anchor' href="#"> Catalog </a></li>
        <li><a class='ft-anchor' href="#"> Catalog </a></li>
        <li><a class='ft-anchor' href="#"> Catalog </a></li>
        <li><a class='ft-anchor' href="#"> Catalog </a></li>
        
     </ul>
      <ul>
        <li><a class='ft-anchor' href="#"> Catalog </a></li>
        <li><a class='ft-anchor' href="#"> Catalog </a></li>
        <li><a class='ft-anchor' href="#"> Catalog </a></li>
        <li><a class='ft-anchor' href="#"> Catalog </a></li>
     </ul>
      <ul>
        <li><a class='ft-anchor' href="#"> Catalog </a></li>
        <li><a class='ft-anchor' href="#"> Catalog </a></li>
        <li><a class='ft-anchor' href="#"> Catalog </a></li>
        <li><a class='ft-anchor' href="#"> Catalog </a></li>
     </ul>
        <p>©Copyright by Ray 2018 Allright reserved</p>
     </footer>
  <script src="script/main.js"></script>
  </body>
</html>

  

 
   
    
     
   
      
      
 
  
   
       
 
       
       
