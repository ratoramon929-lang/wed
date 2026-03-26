<!DOCTYPE html>
<html lang="es">
<head>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>AUXILIO MIRA PRO</title>

<style>

body{
margin:0;
background:black;
font-family:Arial;
color:white;
overflow:hidden;
}

/* MIRA */

.mira{
position:absolute;
top:50%;
left:50%;
transform:translate(-50%,-50%);
width:40px;
height:40px;
display:none;
}

.lineH{
position:absolute;
top:50%;
left:0;
width:40px;
height:2px;
background:#00ff66;
}

.lineV{
position:absolute;
left:50%;
top:0;
width:2px;
height:40px;
background:#00ff66;
}

/* PANEL */

.panel{
position:absolute;
top:20px;
left:20px;
width:250px;
background:rgba(0,0,0,0.8);
border-radius:15px;
padding:15px;
border:2px solid #00ff66;
}

.title{
font-size:20px;
color:#00ff66;
text-align:center;
margin-bottom:10px;
}

button{
width:100%;
padding:10px;
margin-top:10px;
background:#00ff66;
border:none;
border-radius:10px;
font-weight:bold;
}

input{
width:80px;
}

.footer{
position:absolute;
bottom:10px;
width:100%;
text-align:center;
color:#00ff66;
font-weight:bold;
}

</style>
</head>

<body>

<div class="panel">

<div class="title">NOVA IOS PREMIUM</div>

<p>🎯 AIM ASSIST 60%</p>
<p>🎯 AIMLOCK 50%</p>
<p>🔧 PRECISIÓN 30%</p>
<p>⚙️ MIRA REFORZADA</p>

<label>H:</label>
<input id="h" value="156">

<label>Y:</label>
<input id="y" value="400">

<button onclick="activar()">ACTIVAR</button>
<button onclick="desactivar()">DESACTIVAR</button>

</div>

<div class="mira" id="mira">

<div class="lineH"></div>
<div class="lineV"></div>

</div>

<div class="footer">
EESSGAMER2.0
</div>

<script>

function activar(){

document.getElementById("mira").style.display="block"

}

function desactivar(){

document.getElementById("mira").style.display="none"

}

</script>

</body>
</html>
