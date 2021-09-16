<head title="Coletivo Amígdalas"></head>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
.fa {
border:0;
font-size:30px!important;
margin:10px 5px;
padding:10px;
width:50px;
cursor: pointer;
}

.footer {
background-color:#1a1a1a;
border-top:1px dotted #333;
bottom:0;
left:0;
position:absolute;
right:0;
}

.logo {
background-color:transparent !important;
}

.mainDiv {
background:#1a1a1a;
color:#a03232;
font-family:Helvetica, sans-serif;
font-size:10px;
height:100%;
left:0;
margin:0;
overflow:hidden;
position:absolute;
text-align:center;
top:0;
width:100%;
}

.titleCard{
color:#c1282d;
z-index:10;
}

.markdown-body p {
    margin-top: 0;
    margin-bottom: 0px;
}

a::before, a::after {
content: "  ★  ";
color: #c1282d;
font-size: 7px;
position: relative;
bottom: 2px;
}

.header {
margin-top: -14px;
}
.header::before, .header::after {
content: "    ";
}

.no-after::after, .no-after::before{
content:"";
  }

a, x {
font-weight: 700;
border:1px dotted #333;
color:#fff;
display:block;
font-size:12px;
height:100%;
min-height:35px;
padding:20px 2px;
position:relative;
text-align:center;
text-decoration:none!important;
width:100%;
}
a {
    margin: -8px 0;
    top: 14px;
    overflow: hidden;
    text-overflow: ellipsis;
    white-space: nowrap;
}

body {
text-transform: uppercase;
background:#1a1a1a;
}

del > a {
color:#666 !important;
}
</style>

<div class="mainDiv" markdown="1">
<a class="header"><img class="logo" src="./logo.svg" height="75"></a>
<br>
{% include_relative sites.md %}
<div class="footer">
<x onclick="window.location.href = 'https://www.instagram.com/coletivo_amigdalas/'" class="fa fa-instagram"></x>
<x onclick="window.location.href = 'https://www.facebook.com/Coletivo-Am%C3%ADgdalas-104712007882184/'" class="fa fa-facebook-f"></x>
<x onclick="window.location.href = 'https://www.youtube.com/channel/UCig7BqOgl6cLp-fJi2fRQFw'" class="fa fa-youtube"></x>
<x onclick="window.location.href = 'mailto:coletivoamigdalas2017@gmail.com'" class="fa fa-envelope"></x>
</div>
</div>
