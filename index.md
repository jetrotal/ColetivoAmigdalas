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
       padding = 10px;
       text-align:center;
       font-size: 14px;
       color: #666;
       height: 100%;
       overflow-x: hidden;
       font-family: "Helvetica", sans-serif;   
}
</style>

<div class="mainDiv" markdown="1">
<a>

<img class="noBG" src="./logo.png" height="54">
</a>

{% include_relative sites.md %}

</div>
