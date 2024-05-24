<!DOCTYPE html>
<html lang="en">
  <head>
    <title>homepage | Celina Buenaventura</title>
    <meta charset="UTF-8">
    <meta name="viewport" content="width-device-width, initial scale-1.0">
    <link rel="stylesheet" href="css/homepage.css.css">  
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
  </head>
  <style>
    html{
    scroll-behavior: smooth;
}
body{
    margin: 0;
    font-family: Arial, Helvetica, sans-serif;
}
.topnav{
    display: flex;
    justify-content: flex-end;
    background-color: rgb(7, 7, 7);
    overflow: hidden;
    padding-top: 10px;
    padding-bottom: 10px;
}
.topnav a { 
    float: left;
    color: rgb(151, 113, 30);
    text-align: center;
    padding: 14px 30px;
    text-decoration: none;
    font-size: 17px;
}
.topnav a :hover { 
    background-color: #070707;
color: rgb(5, 5, 5);
}
.header {
background-image: url("../img/background.jpg");
background-repeat: no-repeat;
background-size: cover;
background-position: bottom;
background-color: rgb(255, 252, 252);
height: 600px;
padding: 100px;    
}
.overlay {
    text-align: center;
    color: black;
    padding: 80px;
} 
.about{ 
    padding: 200px 100px 200px 100px; 
    display: flex;
    justify-content: flex-start;
    background-color: black;
    color: #fff;
    text-align: center;
}
.content{ 
    place-self: center;
    text-align: left;
    line-height: 22px;
    padding: 50px 50px;
    width: 50%;
    letter-spacing: 0.8px;
}

.about-image{ 
    place-self: center;
    width: 50%;
}
.about-image img{ 
    width: 600px;
    height: auto;
    object-fit: cover;
    border: 2px solid #000000;
} 
.gallery-image { 
    padding: 100px 50px;
    color: white;
    height: auto;
    background-image:linear-gradient(to bottom, black, black),url("..img/gallery-background.jpg"); 
    background-position: bottom; 
} 

div.gallery img { 
    
    width: 100%; 
    height: 400px; 
    object-fit: cover;
    object-position: top; 
    border: 2px solid #020202;  
}

.responsive {
    padding: 6px 6px ; 
    display: inline-grid; 
    width: 33%; 
    box-sizing: border-box; 
}
.hobbies-interest{
  color: white;
  justify-content: flex-start;

}
  </style>
  </html>
  <body>
    <!-- Top Navigation Bar -->
    <div class="topnav">
        <a href="#home">Home</a>
        <a href="#about-myself">About-Myself</a>
        <a href="#gallery">My Gallery</a>
        <a href="#">Hobbies & Interest</a>
        </div>
        <!-- end -->

                  <!--Header Section-->
                 <div class="header">
                    <div class="overlay">
                     <img src="img/img5.jpg" alt="profile-picture" width="200px" height="200px"
                     style="border-radius: 100px; border:2px #ffffff;">
                     <h1 style="font-size: 45px"> Celina Buenaventura</h1>
        <h4>Professional Architect</h4>
              </div> 
            </div>

    
  <!--end-->

  <!--About Section-->
<div class="about" id="about-myself" >
  <div class="content">
    <h1 style="text-transform: uppercase;">about-myself</h1>
     <p>Celina H. Buenaventura </h1>
    <p> I am 19 years old from Longos Malabon City and i want to be an Architect or Professional Programmer soon 
     I went in Elementary in Longos Elementary School (LES) and i was Graduated in Year (2016-2017) and i studied 4th year High School in Longos National Highschool
     (LNHS) and i graduated year(2021-2022) and pandemic happens my parents doesn't have work that time so i dont know where i enroll for my Senior High School then month passed i enrolled in 
     Arellano University Elisa Esguerra Campus (AUEEC) because they have free tuition that time and voucher wayback year (2021) 
     and i choose STEM that time because i dont have a choice and 2 years passed(2021-2023) i graduate in Arellano University Elisa Esguerra Campus last June 6, 2023 and 
     my friend introduce me the Global Reciprocal Colleges(GRC) and i took the Entrance Exam and i passed the exam and now im currently taking Bachelor of Science in 
     Information Technology (BSIT) 
    </p>
  </div>

  <div class="about-image">
    <img src="img/profile.jpg" alt="About-Photo">
  </div>
</div>
 <!--end-->

<div class="gallery-image" id="gallery">
<h1 style="text-transform: uppercase;">MY GALLERY</h1>
  <div class="responsive">
      <div class="gallery">
        <img src="img/aa.jpg" alt="Cinque Terre" width="600" height="400">
      </div>
  </div>

  <div class="responsive">
    <div class="gallery">
      <img src="img/profile.jpg" alt="Forest" width="600" height="400">
    </div>
  </div>

<div class="responsive">
  <div class="gallery">
    <img src="img/img3.jpg" alt="Northern Lights" width="600" height="400">
  </div>
</div>

<div class="responsive">
  <div class="gallery">
    <img src="img/img4.jpg" alt="Mountains" width="600" height="400">
  </div>
</div>

<div class="responsive">
  <div class="gallery">
    <img src="img/img5.jpg" alt="Mountains" width="600" height="400">
  </div>
</div>

<div class="responsive">
  <div class="gallery">
    <img src="img/img6.jpg" alt="Mountains" width="600" height="400">
  </div>
    </div>
</div>
</div>

<script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.11.8/dist/umd/popper.min.js" integrity="sha384-I7E8VVD/ismYTF4hNIPjVp/Zjvgyol6VFvRkX/vR+Vc4jQkC+hVqc2pM8ODewa9r" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.min.js" integrity="sha384-0pUGZvbkm6XF6gxjEnlmuGrJXVbNuzT9qBBavbLwCsOGabYfZo0T0to5eqruptLy" crossorigin="anonymous"></script>
</body>
</html>











