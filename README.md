 <html>

   <head>
     <title>css potision</title>
     <link rel="stylesheet" type="text/css" href="style.css">
   </head>

   <body>
     <div id="header">шапка сайта</div>
     <div id="menu">меню</div>
     <div id="content">
       контент
       <div id="news">блок новостей</div>
     </div>
     <div id="footer">низ сайта</div>
   </body>

 </html>


2

body{
margin:0px;
}
     

#header{
background:darkred;
width:715px;
height:100px;
}

#menu{
background:oldlace;
width:190px;
height:300px;
}

#content{
background:oldlace;
width:525px;
height:300px;
position:absolute;
left:190px;
top:100px;
}

#footer{
background:darkred;
width:715px;
height:30px;
}

3


