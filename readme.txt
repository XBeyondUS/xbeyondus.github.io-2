<!--ALL code below this text is for the indext/html page-->
<!DOCTYPE html> 
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
<!--Name of Website Page-->  <title>CroyosoftwareDesigns</title>
<!--Code to call css file-->    <link rel="stylesheet" type = "text/css" href="Style.css">
</head>
<body>
    <!--All code in the nav tags below are for the navigation bar to be displayed-->
    <nav>
     <ul>
 <!--Links to Index/home page-->      <li><a href="index.html">Home</a></li>
 <!--Links to pixel art page-->       <li><a href="pixel art.html">Pixel Art</a></li>
 <!--Links to various game projects page-->       <li><a href="various_game_projects.html">Various Game Projects</a></li>
<!--Links to contact page-->        <li><a href="contact_page.html">Contact</a></li>
     </ul>
    </nav>
     <br>
     <br>
     <br>
     <br>
     <br>
       <!--Image I made for My Logo--><img src="Images/Logo Image(final).png">
     <br>
     <br>
     <br>
     <br>
   <!--Code for the background image of this page I drew myself--><style> 
   body {
      background-image: url(Images/Background\ Image\ final.png) ;
      height:140vh;
    
      background-size: cover;
      background-position: center;
   }
</style>
 <br>
<!--Header 1's text--> <h1>Hello there and welcome to Croyosoftware Designs!</h1>
    <br>
    <br>
    <br>
  <!--ALL four paragraph codes below are the code to display the additional text below the logo on the page-->
    <p>My name is Caleb Garner and I am an aspiring indie game developer, digital artist, and game writer.</p>
    <p>This website CroyosoftwareDesigns, was created as a place to store my digital art creations, and video game projects.</p>
    <p>Everything you see now on this website will be subject to change as more updates are added in the future. </p>
    <br>
    <p>  Thank you for visiting, and have a good one!</p>

<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<!--ALL code below is for the footer at the bottom of the html-->
<footer class ="footer">
  <div class="container">
    <div class="row">
       <div class="footer-col">
 <!--Code for the text above the email link--> <h3>Email</h3>
       </div>
        <div>
              <i class="fa fa-enevlope"></i>
    <!--Code to Link to my email-->          <p><a href="mailto:garnercontact42@gmail.com">garnercontact42@gmail.com</a></p>
        </div>
        <div class = "footer-col">
  <!--copyright text-->        <h4>@2023. All images and logos on site Croyosoftware Deisgns, are property of its owner; Caleb Garner. All rights reserved.</h4>
        </div>
  </div>
</footer>
</body>
</html>
<!--End of index/html page code-->

<!--ALL code below is for the pixel art gallery page-->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
<!--Name of Website Page-->  <title>CroyosoftwareDesigns: Pixel art</title>
<!--Code to call css file-->    <link rel="stylesheet" type = "text/css" href="CSS Files/pixel art_page.css">
</head>
<body>
    <!--All code in the nav tags below are for the navigation bar to be displayed-->
    <nav>
     <ul>
<!--Links to index/home page-->       <li><a href="index.html">Home</a></li>
<!--Links to pixel art page-->       <li><a href="pixel art.html">Pixel Art</a></li>
<!--Links to game projects page-->        <li><a href="various_game_projects.html">Various Game Projects</a></li>
 <!--Contact page-->       <li><a href="contact_page.html">Contact</a></li>
     </ul>
    </nav>
     <br>
     <br>
     <br>
     <br>
   <!--Code for the background image of this page I drew myself--><style> 
   body {
      background-image: url(Images/Background\ Image\ final.png) ;
    
      background-size: cover;
      background-position: center;
   }
</style>
<h1>Image Gallery</h1>
<br>
<br>
<p>
      all images in the slideshow are pixel art designed over the years for either the few
      game projects that were never finished, or just for hobby reasons. 
</p>
<section class="section">
      <div class="slider">
            <div class="slide">
                  <input type="radio" name="radio-btn" id="radio1">
                  <input type="radio" name="radio-btn" id="radio2">
                  <input type="radio" name="radio-btn" id="radio3">
                  <input type="radio" name="radio-btn" id="radio4">
                  <input type="radio" name="radio-btn" id="radio5">

                  <div class="st first">
                        <img src="Images/Images for Pixel art page/pixel rocket project.png" alt="">
                  </div>

                  <div class="st">
                        <img src="Images/Images for Pixel art page/Unnamed Character.png" alt="">
                  </div>

                  <div class="st">
                        <img src="Images/Images for Pixel art page/Drone - sprite sheet.png" alt="">
                  </div>

                  <div class="st">
                        <img src="Images/Images for Pixel art page/Unnamed Marine.png" alt="">
                  </div>
                  <div class="st">
                        <img src="Images/Images for Pixel art page/Evil dog.png" alt="">
                  </div>
            <br>
            <br>
            <br>
            <br>
                  <div class="nav-auto">
                        <div class="a-b1"></div>
                        <div class="a-b2"></div>
                        <div class="a-b3"></div>
                        <div class="a-b4"></div>
                        <div class="a-b5"></div>
                  </div>
            </div>

            <div class="nav-m">
                  <label for="radio1" class="m-btn"></label>
                  <label for="radio1" class="m-btn"></label>
                  <label for="radio1" class="m-btn"></label>
                  <label for="radio1" class="m-btn"></label>
                  <label for="radio1" class="m-btn"></label>
            </div>
      </div>
</section>
<script type="text/javascript">
      var counter=1;
      setInterval(function(){
            document.getElementById('radio'+counter).checked=true;
            counter++;
            if(counter > 5){
                  counter = 1;
            }
        },5000);
</script>
<br>
<!--ALL code below is for the footer at the bottom of the html-->
<footer class ="footer">
  <div class="container">
    <div class="row">
       <div class="footer-col">
 <!--Code for the text above the email link--> <h3>Email</h3>
       </div>
        <div>
              <i class="fa fa-enevlope"></i>
    <!--Code to Link to my email-->          <p><a href="mailto:garnercontact42@gmail.com">garnercontact42@gmail.com</a></p>
        </div>
        <div class = "footer-col">
  <!--copyright text-->        <h4>@2023. All images and logos on site Croyosoftware Deisgns, are property of its owner; Caleb Garner. All rights reserved.</h4>
        </div>
        
  </div>
</footer>
</body>
</html>
<!--End of code for the pixel art gallery page-->



<!--ALL code below is for the various game projects page-->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
<!--Name of Website Page-->  <title>CroyosoftwareDesigns</title>
<!--Code to call css file-->    <link rel="stylesheet" type = "text/css" href="CSS Files/Various_game_projects.css">
</head>
<body>
    <!--All code in the nav tags below are for the navigation bar to be displayed-->
    <nav>
     <ul>
  <!--Links to index/home page-->     <li><a href="index.html">Home</a></li>
  <!--Links to pixel art page-->      <li><a href="pixel art.html">Pixel Art</a></li>
   <!--Links to various game project page-->     <li><a href="various_game_projects.html">Various Game Projects</a></li>
   <!--Links to contact page-->     <li><a href="contact_page.html">Contact</a></li>
     </ul>
    </nav>
     <br>
     <br>
     <br>
     <br>
     <br>
     <br>
     <br>
     <br>
     <br>
     <br>
     <br>
     <br>
     <br>
     <br>
     <br>
     <br>
     <br>
     
 <!--header 1's text-->    <h1>IMAGE SLIDESHOW</h1>
     <!--ALL code below is for the sliders displayed on the page-->
     <div class="slidershow middle">
      <div class="slides">
        <input type="radio" name="r" id="r1" checked>
        <input type="radio" name="r" id="r2">
            <div class="slide s1">
            
            <video controls src="Videos/The Tales of Xallene Video.mp4" width="1040"></video>
            
            </div>
            <div class="slide">
                  <img src="Images/Images for Various Game Projects/Unammed Project.png" alt="">
            </div>
      </div>
     </div>
     <div class="navigation">
      <label for="r1" class="bar"></label>
      <label for="r2" class="bar"></label>
</div>
   <!--Code for the background image of this page I drew myself--><style> 
   body {
      background-image: url(Images/Background\ Image\ final.png) ;
      height:130vh;
    
      background-size: cover;
      background-position: center;
   }
</style>



<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<!--ALL code below is for the footer at the bottom of the html-->
<footer class ="footer">
  <div class="container">
    <div class="row">
       <div class="footer-col">
 <!--Code for the text above the email link--> <h3>Email</h3>
       </div>
        <div>
              <i class="fa fa-enevlope"></i>
    <!--Code to Link to my email-->          <p><a href="mailto:garnercontact42@gmail.com">garnercontact42@gmail.com</a></p>
        </div>
        <div class = "footer-col">
  <!--copyright text-->        <h4>@2023. All images and logos on site Croyosoftware Deisgns, are property of its owner; Caleb Garner. All rights reserved.</h4>
        </div>
  </div>
</footer>
</body>
</html>
<!--End of code for various game projects page-->

<!--ALL code below this text is for the contact page-->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
<!--Name of Website Page-->  <title>CroyosoftwareDesigns</title>
<!--Code to call css file-->    <link rel="stylesheet" type = "text/css" href="CSS Files/Contact.css">
</head>
<body>
    <!--All code in the nav tags below are for the navigation bar to be displayed-->
    <nav>
     <ul>
<!--Links to index/home page-->       <li><a href="index.html">Home</a></li>
<!--Links to pixel art gallery page-->       <li><a href="pixel art.html">Pixel Art</a></li>
 <!--Links to various game projects-->       <li><a href="various_game_projects.html">Various Game Projects</a></li>
 <!--Links to contact page-->       <li><a href="contact_page.html">Contact</a></li>
     </ul>
    </nav>
     <br>
     <br>
     <br>
     <br>
     <br>
  <!--header 1's text-->   <h1>Website Owner: Caleb Garner</h1>
       <!--Image of me--><img src="Images/Image of Me.png">
     <br>
     <br>
     <br>
  <!--Header 2's text-->   <h2>Contact Information</h2>
  <!--ALL code below is for the table displayed on this page-->     
  <table border="5px" width="30%" height="9%">
        <tr>
          <th>Site Owner</th>
          <th>Email</th>
          <th>phone</th>
        </tr>
        <tr>
          <td>Caleb Garner</td>
          <td>garnercontact42@gmail.com</td>
          <td>864-612-7485</td>
        </tr>
       </table>
       
     
     
     
    

  
  
  
  <br>
  <br>
   <!--Code for the background image of this page I drew myself--><style> 
   body {
      background-image: url(Images/Background\ Image\ final.png) ;
      height:130vh;
    
      background-size: cover;
      background-position: center;
   }
</style>
<h1>COMING SOON</h1>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<br>
<!--ALL code below is for the footer at the bottom of the html-->
<footer class ="footer">
  <div class="container">
    <div class="row">
       <div class="footer-col">
 <!--Code for the text above the email link--> <h3>Email</h3>
       </div>
        <div>
              <i class="fa fa-enevlope"></i>
    <!--Code to Link to my email-->          <p><a href="mailto:garnercontact42@gmail.com">garnercontact42@gmail.com</a></p>
        </div>
        <div class = "footer-col">
  <!--copyright text-->        <h4>@2023. All images and logos on site Croyosoftware Deisgns, are property of its owner; Caleb Garner. All rights reserved.</h4>
        </div>
  </div>
</footer>
</body>
</html>
<!--End of code for the contact page-->