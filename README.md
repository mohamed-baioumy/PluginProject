I am creating a plugin for Overviwe for pubg game the plugin will display images with some setting  using timer and fade in and out options to adjust up to the user needs ,plugin have four option first one is arrow left to slide the images to the left second option will display images to  the right third option will be auto play will display images automatically forth option will stop the auto play  

requirements.
1-plugin.js file
2- HTML file.
3-lip.js file.
<script src="http://code.jquery.com/jquery-1.4.2.min.js" ></script>
    <script src="js.js" ></script>
    <script src="lip.js"></script>

4-Css file for styling to add style for html element styling.

   <link rel="stylesheet" href="style.css">
   
5-Folder for image.
6-audio folder with control button.
7-video folder playing in background auto play.

    <link rel="stylesheet" href="style.css">
    
    
    <video autoplay  loop id="myVideo">
        <source src="video/10.mp4" type="video/mp4">
      </video>

     

Html
1-h element for pubg overview.
2-Create html to contain div image.
3-Include dive for logo contain game logo.
4- link to css file.
5-link to jquery file.


plugin options
    $("#slideshow").slider({ 

    // to do adjust setting .

    // fadeOut:50000,
    // fadeIn:40000,
    // time:10000

 });

    

