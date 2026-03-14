<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>For Rupashree ❤️</title>

<style>

body{
margin:0;
font-family:Arial, sans-serif;
text-align:center;
background:linear-gradient(135deg,#ff9a9e,#fad0c4);
color:#fff;
height:100vh;
display:flex;
align-items:center;
justify-content:center;
flex-direction:column;
}

h1{
font-size:40px;
}

p{
font-size:20px;
max-width:500px;
}

button{
padding:12px 25px;
font-size:18px;
border:none;
border-radius:25px;
background:#ff4d6d;
color:white;
cursor:pointer;
margin:10px;
transition:0.3s;
}

button:hover{
transform:scale(1.1);
background:#ff1e4d;
}

.hidden{
display:none;
}

.heart{
font-size:40px;
animation:heartbeat 1s infinite;
}

@keyframes heartbeat{
0%{transform:scale(1)}
50%{transform:scale(1.3)}
100%{transform:scale(1)}
}

</style>
</head>

<body>

<!-- Sorry Section -->

<div id="sorry">
<h1>Rupashree I'm Sorry 💔</h1>

<p>
I know I made mistakes and hurt you.  
But you are very special to me.  
Please listen to my heart once.
</p>

<button onclick="showProposal()">Forgive Me ❤️</button>
</div>


<!-- Proposal Section -->

<div id="proposal" class="hidden">

<h1>Rupashree 🌹</h1>

<p>
You are my **Pasandida Aurat** ❤️  
You make my world beautiful.

I want to make new memories with you.

Will you give me another chance?
</p>

<button onclick="yes()">YES ❤️</button>
<button onclick="moveNo(this)">NO 😢</button>

</div>


<!-- Final Message -->

<div id="final" class="hidden">

<h1 class="heart">❤️</h1>

<h1>Thank You Rupashree</h1>

<p>
You are the most special person in my life.
</p>

</div>


<script>

function showProposal(){
document.getElementById("sorry").style.display="none";
document.getElementById("proposal").style.display="block";
}

function yes(){
document.getElementById("proposal").style.display="none";
document.getElementById("final").style.display="block";
}

function moveNo(btn){
btn.style.position="absolute";
btn.style.left=Math.random()*80+"%";
btn.style.top=Math.random()*80+"%";
}

</script>

</body>
</html>
<!DOCTYPE html>
<html>
<head>
<title>For Rupashree ❤️</title>
<meta name="viewport" content="width=device-width, initial-scale=1">

<style>

body{
margin:0;
height:100vh;
display:flex;
justify-content:center;
align-items:center;
flex-direction:column;
font-family:Arial;
text-align:center;
background:linear-gradient(135deg,#ff758c,#ff7eb3);
color:white;
}

button{
padding:12px 25px;
font-size:18px;
border:none;
border-radius:30px;
background:white;
color:#ff4d6d;
margin:10px;
cursor:pointer;
transition:0.3s;
}

button:hover{
transform:scale(1.1);
}

.hidden{
display:none;
}

</style>

</head>

<body>

<div id="sorry">

<h1>Rupashree I'm Sorry 💔</h1>

<p>
I know I hurt you.  
But you are my **Pasandida Aurat ❤️**
</p>

<button onclick="next()">Forgive Me ❤️</button>

</div>


<div id="proposal" class="hidden">

<h1>Rupashree 🌹</h1>

<p>
You make my world beautiful.  
Will you give me another chance?
</p>

<button onclick="yes()">YES ❤️</button>
<button onclick="move(this)">NO 😢</button>

</div>


<div id="love" class="hidden">

<h1>I Love You Rupashree ❤️</h1>

<p>You are the most special person in my life</p>

</div>


<script>

function next(){
document.getElementById("sorry").style.display="none"
document.getElementById("proposal").style.display="block"
}

function yes(){
document.getElementById("proposal").style.display="none"
document.getElementById("love").style.display="block"
}

function move(btn){
btn.style.position="absolute"
btn.style.left=Math.random()*80+"%"
btn.style.top=Math.random()*80+"%"
}

</script>

</body>
</html>
