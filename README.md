# HTML-CSS-PROJECT
<!DOCTYPE html>
<html lang="en">
  <style>
    *{
    margin: 0;
    padding: 0;
    
}
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@500&family=Mukta&display=swap');
nav{
    height: 720px;
    width: 250px;
    
    background-image: url(https://img.freepik.com/free-vector/halftone-background-with-circles_23-2148907689.jpg?size=626&ext=jpg&uid=R30936075&ga=GA1.1.230351433.1681914737&semt=sph);
    background-size: 1500px;
    /* background-color: #FA8BFF;
background-image: -webkit-linear-gradient(45deg, #FA8BFF 0%, #2BD2FF 52%, #2BFF88 90%);
background-image: -moz-linear-gradient(45deg, #FA8BFF 0%, #2BD2FF 52%, #2BFF88 90%);
background-image: -o-linear-gradient(45deg, #FA8BFF 0%, #2BD2FF 52%, #2BFF88 90%);
background-image: linear-gradient(45deg, #FA8BFF 0%, #2BD2FF 52%, #2BFF88 90%); */

    

    
    /* background: linear-gradient(320deg, rgba(166,27,178,1) 0%, rgba(0,0,0,1) 100%);
    background-image: url(https://img.freepik.com/free-vector/gradient-network-connection-background_23-2148865393.jpg?size=626&ext=jpg&uid=R30936075&ga=GA1.2.230351433.1681914737&semt=sph); 
    background-size: 1350px;    */
    position: fixed;
    background-repeat: no-repeat;
    top: 0;
    z-index: 1;
    
}
.nav-logo{
    height: 20px;
    width: 20px;
   
}

.tr{
    height: 180px;
    width: 180px;
    position: absolute;
    top: 50px;
    left: 30px;
    border-radius: 50%;
    border: solid rgb(255, 221, 221) 9px;
}



.nav-items{
    margin-top: 250px;
    display: flex;
    flex-direction: column;
    justify-content: left;
    align-items: left;
    line-height: 60px;
    margin-left: 70px;

}
.nav-items a{
    color: rgb(255, 255, 255);
    font-size: 22px;
    text-decoration: none;
    font-family: 'Montserrat', sans-serif;
    font-family: 'Mukta', sans-serif;
    text-shadow: 10px 10px 40px rgb(50, 50, 50);
}
.nav-items a:hover{
    font-size: 30px;
    text-shadow: 10px 10px 120px rgb(255, 255, 255);
   
    color: rgb(255, 255, 255);
}

.portifolio{
    display: flex;
    flex-direction: row;
    

}
.container{
    display: flex;
    flex-direction: column;
    width: 100%;
    height: 4320px;
    margin-left: 238px;     
}

    
.home{
    
    background-image: url("Screenshot\ \(14\).jpg");
            background-repeat: no-repeat;
            background-size: 1300px;
            background-blend-mode:difference;
            background-attachment:scroll;

    margin-left: 0px;
    height: 720px;
    width: 100%;
}
.home-text h1{
    font-family: 'Montserrat', sans-serif;
    font-family: 'Mukta', sans-serif;
    color: rgb(255, 255, 255);
    margin-top: 280px;
    margin-left: 100px;
    margin-right: 0px;
    font-size: 50px;
}
.home-sub{
    font-family: 'Montserrat', sans-serif;
    font-family: 'Mukta', sans-serif;
    color: rgb(255, 255, 255);
    margin-left: 107px;
    margin-right: 0px;
    font-size: 70px;
}

.jab{
    margin-left: 100px;
    color: chartreuse;

    overflow: hidden; /* Ensures the content is not revealed until the animation */
    border-right: .15em solid orange; /* The typwriter cursor */
    white-space:warp; /* Keeps the content on a single line */
    margin: 1 auto; /* Gives that scrolling effect as the typing happens */
    letter-spacing: .15em; /* Adjust as needed */
    animation: 
      typing 3.5s steps(40, end),
      blink-caret .75s step-end infinite;
 margin-top: 50px;   
    
}
  
  /* The typing effect */
  @keyframes typing {
    from { width: 0 }
    to { width: 50% }
  }
  
  /* The typewriter cursor effect */
  @keyframes blink-caret {
    from, to { border-color: transparent }
    50% { border-color: orange; }
  }



.qualifications{
  
    background-image:  #4158D0;
    background-image: -webkit-linear-gradient(43deg, #4158D0 0%, #C850C0 46%, #FFCC70 100%);
    background-image: -moz-linear-gradient(43deg, #4158D0 0%, #C850C0 46%, #FFCC70 100%);
    background-image: -o-linear-gradient(43deg, #4158D0 0%, #C850C0 46%, #FFCC70 100%);
    background-image: linear-gradient(43deg, #4158D0 0%, #C850C0 46%, #FFCC70 100%);
   
    
    
    margin-left: 0px;
    height: 720px;
    width: 100%
}
.qualifications-text{
    color: aliceblue;
    margin-top: 30px;
    margin-left: 50px;
    font-family: 'Montserrat', sans-serif;
    font-family: 'Mukta', sans-serif;
}

.cardone{
    margin-top: 70px;
    display: flex;
    flex-direction: row;
}

.skills{
    background-color: #21D4FD;
background-image: -webkit-linear-gradient(19deg, #21D4FD 0%, #B721FF 100%);
background-image: -moz-linear-gradient(19deg, #21D4FD 0%, #B721FF 100%);
background-image: -o-linear-gradient(19deg, #21D4FD 0%, #B721FF 100%);
background-image: linear-gradient(19deg, #21D4FD 0%, #B721FF 100%);

    margin-left: 0px;
    height: 720px;
    width: 100%
    
}
.skills-text{
    color: aliceblue;
    margin-top: 30px;
    margin-left: 50px;
    font-family: 'Montserrat', sans-serif;
    font-family: 'Mukta', sans-serif;
}
.cardtwo{
    margin-top: 70px;
    display: flex;
    flex-direction: row;
    
}

.project{
    background-color: #FBDA61;
background-image: -webkit-linear-gradient(45deg, #FBDA61 0%, #FF5ACD 100%);
background-image: -moz-linear-gradient(45deg, #FBDA61 0%, #FF5ACD 100%);
background-image: -o-linear-gradient(45deg, #FBDA61 0%, #FF5ACD 100%);
background-image: linear-gradient(45deg, #FBDA61 0%, #FF5ACD 100%);
background-image: url(https://media.giphy.com/media/eggmblcxyj4LJFXike/giphy.gif);
background-repeat: no-repeat;
background-size: cover;

    margin-left: 0px;
    height: 720px;
    width: 100%  
    
}


.project-text{
    color: aliceblue;
    margin-top: 30px;
    margin-left: 50px;
    font-family: 'Montserrat', sans-serif;
    font-family: 'Mukta', sans-serif;
}
.cardthree{
    margin-top: 70px;
    height: 500px;
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    
}


.cardfour{
    margin-top: 70px;
    height: 500px;
    display: flex;
    flex-wrap: wrap;

}
.contact{
    background-color: #FFDEE9;
    background-image: -webkit-linear-gradient(0deg, #FFDEE9 0%, #B5FFFC 100%);
    background-image: -moz-linear-gradient(0deg, #FFDEE9 0%, #B5FFFC 100%);
    background-image: -o-linear-gradient(0deg, #FFDEE9 0%, #B5FFFC 100%);
    background-image: linear-gradient(0deg, #FFDEE9 0%, #B5FFFC 100%);
    background-image: url(https://media1.giphy.com/media/pG5KYLoTE6d8e4Y76v/giphy.gif?cid=ecf05e473d92nlntd7enamxim4t4ec1uul6hunelqd1sjyta&ep=v1_gifs_related&rid=giphy.gif&ct=s);
  
    
    margin-top: 0%;
    height: 720px;
    width: 100% ;
    display: flex;
    flex-direction: column;
    
}
.contact img{
    
    height: 50px;
    width: 50px;
}

.card{
    margin-left: 15px;

}


.socialmedia{
   
    display: flex;
    flex-direction: row;
    flex-wrap: wrap;
    justify-content: space-evenly;
    margin-left: 350px;
    width: 500px;
    margin-top: 300px;
    
    
   
}

.sharetext{
    font-family: 'Montserrat', sans-serif;
    font-family: 'Mukta', sans-serif;
    color: rgb(163, 155, 155);
    margin-top: 50px;
    margin-left: 500px;
    font-size: 50px;

}

.info{
    background-color: #F4D03F;
background-image: -webkit-linear-gradient(132deg, #F4D03F 0%, #16A085 100%);
background-image: -moz-linear-gradient(132deg, #F4D03F 0%, #16A085 100%);
background-image: -o-linear-gradient(132deg, #F4D03F 0%, #16A085 100%);
background-image: linear-gradient(132deg, #F4D03F 0%, #16A085 100%);
background-image: url(https://media.giphy.com/media/h7uTwqEHysbd2lhyDP/giphy.gif);
    margin-top: 0%;
    height: 720px;
    width: 100% ;
    display: flex;
    flex-direction: column;
    
}

.info-text{
    color: aliceblue;
    margin-top: 30px;
    margin-left: 50px;
    font-family: 'Montserrat', sans-serif;
    font-family: 'Mukta', sans-serif;
}

.list{
   margin-top: 129px;
    margin-left: 300px;
    font-family: 'Montserrat', sans-serif;
    font-family: 'Mukta', sans-serif;
    font-size: 18px;
    height: 350px;
    width: 600px;
    background-color: rgb(255, 255, 255);
    border-radius: 2%;
 
}
.raw{
    margin-top: 50px;
    margin-left: 25px;
}
  </style>
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-rbsA2VBKQhggwzxH7pPCaAqO46MgnOM80zW1RWuH61DGLwZJEdK2Kadq2F9CUG65" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-kenU1KFdBIe4zVF0s0G1M5b4hcpxyD9F7jL+jjXkk+Q2h455rYXK/7HAuoJl+0I4" crossorigin="anonymous"></script>
    <title>PortFolio</title>
    
</head>
<link rel="stylesheet" href="portifolio.css">
<body>
   <div class="portifolio">
    <nav>
        <div class="nav-logo">
            <img src="ralki.jpg" alt="" class="tr"></div>
        <div class="nav-items">
            <a href="#home">Home</a>
            <a href="#qualifications">Qualification </a>
            <a href="#skills">Skills </a>
            <a href="#project">Project</a>
            <a href="#info">Info    </a>
            <a href="#contact">Contact</a>
        </div>
    </nav> 
  <div class="container">
       <div class="home" id="home">
          <div class="home-text"><h1><b>Gowtham Murukesh</b></h1>
          </div>
           <div class="home-sub">
           <h4> Full-stack Developer</h4>
          </div> 
           <div class="home-about">
             <!-- <p class="hal">
              "Hi, I'm Gowtham, a passionate and fresher full stack developer.</p> -->
              <p class="jab"> "Hi, I'm Gowtham, a passionate and fresher full stack developer.<br>With a strong background in both front-end and back-end development.</p>
           
             
           
           </div>
           
           
          
      
      </div>
     
       <div class="qualifications"id="qualifications">
          <div class="qualifications-text"><h1>Qualification</h1>
          </div>
          
          <div class="cardone">
          <div class="card" style="width: 18rem;">
            <div class="card-body">
              <!--ug-->
              <h5 class="card-title">UG</h5>
              <p class="card-text"><ul>
                <li><p>
                  B.E.Electronics and Communications
                </p></li>
                <li><p>Info Institute of Engineering</p></li>
                <li><p>CGPA : 7.5</p></li>
              </ul></p>
              
            </div>
          </div>
             <!--hss-->
          <div class="card" style="width: 18rem;">
            <div class="card-body">
              <h5 class="card-title">HSS</h5>
              <p class="card-text"><ul>
                    <li><p>Arogyamatha Higher Secondary
                       School, Kottathara, kerala</p></li>
                   <li><p>Percentage : 79%</p></li>
              </ul></p>
              <!--sslc-->
            </div>
          </div>
          <div class="card" style="width: 18rem;">
            <div class="card-body">
              <h5 class="card-title">SSLC</h5>
              <p class="card-text"><ul>
                <li><p>Bethany English Medium School, Vattalucky, kerala
                </p></li>
                <li><p>Percentage : 79%</p></li>
                </ul></p>
              
            </div>
          </div>
        </div>

       </div>


       <!-- skills -->

       <div class="skills" id="skills">



        <div class="skills-text"><h1>Skills</h1>
        </div>
        <div class="cardtwo">
        <div class="card" style="width: 18rem;">
          <div class="card-body">
            <!--languages-->
            <h5 class="card-title">Languages Known</h5>
            <p class="card-text"><ul>
              <li><p>
                Python
              </p></li>
              <li><p>C (basics)</p></li>
              <li><p>Java (basics)</p></li>
            </ul></p>
            
          </div>
        </div>
           <!--Web-tech-->
        <div class="card" style="width: 18rem;">
          <div class="card-body">
            <h5 class="card-title">Web-technology</h5>
            <p class="card-text"><ul>
                  <li><p>HTML 5</p></li>
                 <li><p>CSS 3</p></li>
                 <li><p>Javascript</p></li>
            </ul></p>
            <!--Graphic designing-->
          </div>
        </div>
        <div class="card" style="width: 18rem;">
          <div class="card-body">
            <h5 class="card-title">Graphic Designing</h5>
            <p class="card-text"><ul>
              <li><p>Photoshop <img src="" alt="">
              </p></li>
              <li><p>Adobe Illustrator</p></li>
              <li><p>Figma</p></li>
              <li><p>Lightroom</p></li>
              <li><p>Filmora</p></li>
              
              </ul></p>
            
          </div>
        </div>
        <div class="card" style="width: 18rem;">
          <div class="card-body">
            <h5 class="card-title">Database</h5>
            <p class="card-text"><ul>
              <li><p>Oracle SQL
              </p></li>
              
              
              </ul></p>
            
          </div>
        </div>
      </div>


        
        
      </div>

       
       <div class="project" id="project">
 <div class="project-text"><h1>Project</h1>
        </div>
        <div class="cardthree">
        <div class="card" style="width: 18rem; height: 200px">
          <div class="card-body">
            <!--languages-->
            <h5 class="card-title">Home Automation system by using Ardiuno.</h5>
            
          </div>
        </div>
           <!--Web-tech-->
        <div class="card" style="width: 18rem;height: 200px">
          <div class="card-body">
            <h5 class="card-title">RFID Sequrity system.</h5>
            <!--Graphic designing-->
          </div>
        </div>
        <div class="card" style="width: 18rem;height: 200px">
          <div class="card-body">
            <h5 class="card-title">File encryption and decryption using machine learning.</h5>
           
            
          </div>
        </div>
        <div class="card" style="width: 18rem;height: 200px">
          <div class="card-body">
            <h5 class="card-title">Web-technology projects</h5>
            <p class="card-text"><ul>
              <li><p>OTT website
              </p></li>
              <li><p>Portifolio website</p></li>
              
              
              </ul></p>
            
          </div>
        </div>
        <div class="card" style="width: 18rem;height: 200px;">
          <div class="card-body">
            <h5 class="card-title">UI/UX- Project </h5>
            <p class="card-text"><ul>
              <li><p>landing page
              </p></li>
              <li><p>Max Muller school Web-design</p></li>
              
              
              </ul></p>
            
          </div>
        </div>
       </div>
       <div class="info" id="info">
        <div class="info-text"><h1>Info</h1>
        </div>
        <div class="list">
           
          <ul  class="raw" style="color:rgb(0, 0, 0);">
          <li><p>Father's name : Murukesh. S</p></li>
          <li><p>Mother name : Jayachitra. S</p></li>
          <li><p>Nationality : Indian</p></li>
          <li><p>Languages Known : Tamil, Malayalam, Hindi, English
          </p></li>
          <li><p> Date of Birth : 27-08-2000</p> </li>
          <li><p>Address : GA House Kottathara Palakkad, Kerala,678581, Kottathara(P.O)</p></li>
          </ul>
      
          
        </div>
        





       </div>
       <!-- <div class="info" id="info">
        <div class="info-text"><h1>Info</h1>
        </div>
        
        
          <div class="list">
           
            <ul type="none" class="raw">
            <li><p>Father's name : Murukesh. S</p></li>
            <li><p>Mother name : Jayachitra. S</p></li>
            <li><p>Nationality : Indian</p></li><br>
            <li><p>Languages Known : Tamil, Malayalam, Hindi, English
            </p></li>
            <li><p> Date of Birth : 27-08-2000</p> </li>
            </ul>
        
            
          </div>
        
      </div>
        
       </div> --> 
      

       <div class="contact" id="contact">
            
            <div class="socialmedia">
             
              <a href="https://www.instagram.com/snapper_274/"><img src="instagram.png" alt=""></a>
              <a href="mailto:gowthammurukesh218@gmail.com"><img src="gmail.png" alt=""></a>
              <a href="https://www.linkedin.com/in/gowtham-murukesh-3099561a0"><img src="linkedin.png" alt=""></a>
              <a href="tel:9751133218"><img src="phone (1).png" alt=""></a>
              <a href="https://www.youtube.com/channel/UC1Lg7pgPh_oUvqKB_C7zOAw"><img src="youtube.png" alt=""></a>
            
          </div>
          <div class="sharetext"><h5>Click Icon to Contact</h5></div>
        </div>
        
       
       

       
    
  </div>
</div>     
   

 
     
   
</body>
</html>
