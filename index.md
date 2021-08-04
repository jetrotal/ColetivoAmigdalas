<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
.noBG {
background-color:transparent !important
       }
a{
       display: block;
       position: relative;
       width: 100%;
       height: 100%;
       padding: 7.5px;
       border-bottom: 1px dotted #333;
       text-align: center;
       min-height: 28.5px;
       text-decoration: none !important;
       font-size: 155% !important;
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
       width:70px;
       padding:20px;
       border-bottom:0;
       margin: 5px 2px;
}
</style>

<div class="mainDiv" markdown="1">
<a><img class="noBG" src="./logo.png" height="54"></a>
{% include_relative sites.md %}

<a href="javascript:void(0)" class="fa fa-facebook"></a>
<a href="javascript:void(0)" class="fa fa-youtube"></a>
<a href="javascript:void(0)" class="fa fa-instagram"></a>
</div>
