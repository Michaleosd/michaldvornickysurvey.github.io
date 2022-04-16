<!DOCTYPE html>
<html>
  <head>
    <base target="_top">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <style>
    body {
      margin: 0;           
    }
    iframe {
      display: block;       
      background: #ffffff;
      border: none;        
      height: 100vh;      
      width: 100vw;
    }
    </style>
 </head>
 <body>
   <iframe id='framey' frameborder = 0></iframe>
 </body>
 <script>
   var webpages = [];
   //---------------just change the webpage URLs
   //the webpages need to hosted on https sites - if you want more than two just create a new line using the same code as below
   //just change the link to the google form
   webpages.push("https://survey.au.dk/LinkCollector?key=K3XV92Q9S631");
   webpages.push("https://survey.au.dk/LinkCollector?key=ZGXV36QFLN95");
   webpages.push("https://survey.au.dk/LinkCollector?key=5ZGPU5WFJ196");
   //------------------------------------------
   var random_page = webpages[Math.floor(Math.random()*webpages.length)];
   document.getElementById("framey").src = random_page;
 </script>
</html>
