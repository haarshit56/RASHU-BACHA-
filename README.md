# RASHU-BACHA-
Happy Girlfriend’s Day, my 😘 💕 🌹 This little page is made only for you because you deserve something special.... You are not just my girlfriend, you are my favourite person and one of the most precious parts of my life.. 💗❤️‍🩹 you are my Home rashu babe  🫶🏼💗♾️
<!DOCTYPE html>
<html>
<head>
<title>For Rashi ❤️</title>

<style>
body{
margin:0;
height:100vh;
overflow:hidden;
font-family:cursive;
background:linear-gradient(120deg,#ff9a9e,#fad0c4,#ffdde1);
color:white;
text-align:center;
}

.page{
display:none;
height:100vh;
padding:40px 20px;
animation:fade 1s;
}

.active{display:block;}

@keyframes fade{
from{opacity:0;transform:scale(.9);}
to{opacity:1;}
}

h1{
font-size:35px;
text-shadow:0 0 15px #ff2d75;
}

p{
font-size:21px;
background:rgba(255,255,255,.25);
padding:20px;
border-radius:25px;
}

button{
padding:14px 35px;
border:0;
border-radius:30px;
font-size:20px;
color:#ff4081;
background:white;
}

.gift{
font-size:100px;
animation:bounce 1s infinite;
}

@keyframes bounce{
50%{transform:translateY(-20px);}
}

.item{
font-size:70px;
animation:pop 2s infinite;
}

@keyframes pop{
50%{transform:scale(1.2);}
}

.fall{
position:absolute;
top:-20px;
font-size:25px;
animation:fall 6s linear;
}

@keyframes fall{
to{top:110%;transform:rotate(360deg);}
}
</style>
</head>


<body>

<div class="page active">
<h1>Hey Beautiful Mommy 🥺😭</h1>
<h2>Please open this ❤️</h2>
<button onclick="next()">Open 💌</button>
</div>


<div class="page">

<h1>A little gift for my Rashi 🎁</h1>

<div class="gift" onclick="next()">🎁</div>

<h2>Tap the gift box 🥺❤️</h2>

</div>


<div class="page">

<h1>For my beautiful Rashi 🌹</h1>

<div class="item">🌹🌷🌸</div>

<p>
Rashi, just like these flowers you bring colour,
happiness and sweetness everywhere you go ❤️

Your smile, your talks and your little things
make moments more special ✨

Never forget how amazing and precious you are 🥺💕
</p>

<button onclick="next()">Next ❤️</button>

</div>


<div class="page">

<h1>Something pretty for my pretty girl 💎</h1>

<div class="item">
💍 📿 ✨
</div>

<p>
If I could, I would bring you all the pretty things —
beautiful earrings, Kashmiri bangles, rings and pendants 💕

But the most beautiful thing will always be
your happiness and your smile ❤️

You deserve all the little surprises in this world ✨
</p>

<button onclick="next()">Next ❤️</button>

</div>


<div class="page">

<h1>Sweet things for my sweetest Rashi 🍫</h1>

<div class="item">
🍫💝
</div>

<p>
Dark chocolates and gifts are small things,
but the feelings behind them are huge 🥺

I made this tiny world just to remind you
that you are special and appreciated ❤️

Keep smiling always 🌎💕
</p>

<button onclick="next()">Final Surprise 💌</button>

</div>


<div class="page">

<h1>Happy Girlfriend's Day Rashi ❤️</h1>

<div class="item">❤️🌹❤️</div>

<p>
My Rashi,

Thank you for being such a beautiful part of my life.

This website may be small,
but every word here came with lots of care 🥺

Stay the same cute, amazing person you are ❤️
</p>

</div>


<script>

let pages=document.querySelectorAll(".page");
let current=0;

function next(){
pages[current].classList.remove("active");
current++;
pages[current].classList.add("active");
}


setInterval(()=>{
let f=document.createElement("div");
f.className="fall";

let things=["❤️","🌹","🌸","💕"];
f.innerHTML=things[Math.floor(Math.random()*things.length)];

f.style.left=Math.random()*100+"%";

document.body.appendChild(f);

setTimeout(()=>f.remove(),6000);

},300);

</script>


</body>
</html>
