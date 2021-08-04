<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
.noBG {
background-color:transparent !important;
margin:-35px;
       }
a{
       display: block;
       position: relative;
       width: 100%;
       height: 100%;
       padding: 20px 2px;
       border-bottom: 1px dotted #333;
       text-align: center;
       min-height: 35px;
       text-decoration: none !important;
       font-size: 90% !important;
       color: #fff;
}

.mainDiv{
       Position:absolute;
       width:100%; 
       height:100%; 
       margin:0; 
       top:0; 
       left:0;
       background-color:#1a1a1a;
       padding: 10px !important;
       text-align:center;
       font-size: 14px;
       color: #666;
       height: 100%;
       overflow-x: hidden;
       font-family: "Helvetica", sans-serif;    
}
       .fa-facebook {
       background: #3B5998;
       color: white;
}
       .fa-youtube {
        background: #bb0000;
}
       .fa-instagram {
       background: #f40083;
}
       .fa {
font-size: 30px !important;
    width: 50px;
    padding: 10px;
    border-bottom: 0;
    margin: 10px 5px;
}
.footer{
       position: absolute;
       bottom:0;
       left:0;
       right:0;
}
</style>

<div class="mainDiv" markdown="1">
<a><img class="noBG" src="./logo.svg" height="125"></a>
{% include_relative sites.md %}
<div class="footer">
<a href="https://www.instagram.com/coletivo_amigdalas/" class="fa fa-instagram"></a>
<a href="https://www.facebook.com/Coletivo-Am%C3%ADgdalas-104712007882184/" class="fa fa-facebook"></a>
<a href="https://www.youtube.com/channel/UCig7BqOgl6cLp-fJi2fRQFw" class="fa fa-youtube"></a>
</div>
</div>
