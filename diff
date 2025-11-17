<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Happy Princess Day</title>

<style>
body{
  margin:0;
  background:linear-gradient(135deg,#b47fc9,#12001f);
  color:#d314d3;
  font-family:'Segoe UI',sans-serif;
  overflow:hidden;
}

/* floating sparkle animation */
@keyframes sparkle{
  0%{opacity:0;transform:translateY(0) scale(0.3);}
  50%{opacity:1;}
  100%{opacity:0;transform:translateY(-120px) scale(1.1);}
}
.sparkle{
  position:absolute;
  width:8px;height:8px;
  background:#ff7bf3;
  border-radius:50%;
  animation:sparkle 4s linear infinite;
}
.sparkle:nth-child(odd){background:#e4a8e4;animation-duration:5s;}
.sparkle:nth-child(3n){background:#ff66cc;animation-duration:6s;}

/* Main container */
.centerBox{
  position:absolute;
  top:50%;left:50%;
  transform:translate(-50%,-50%);
  text-align:center;
  width:85%;
  max-width:650px;
}

/* First popup section */
#popup{
  font-size:38px;
  font-weight:700;
  opacity:0;
  animation:fadeSlide 2.4s ease forwards;
}

@keyframes fadeSlide{
  0%{opacity:0;transform:translateY(25px);}
  100%{opacity:1;transform:translateY(0);}
}

#next{
  margin-top:50px;
  font-size:22px;
  line-height:1.55;
  display:none;
  animation:fadeText 1.8s ease forwards;
}

@keyframes fadeText{
  from{opacity:0;transform:translateY(25px);}
  to{opacity:1;transform:translateY(0);}
}

.button{
  margin-top:40px;
  display:inline-block;
  padding:14px 26px;
  background:#ff3fbb;
  color:white;
  border-radius:14px;
  font-size:18px;
  font-weight:600;
  text-decoration:none;
  cursor:pointer;
  box-shadow:0 0 18px #ff4fe2aa;
}

.qrBox{
  margin-top:45px;
  display:none;
}
.qrBox img{
  width:240px;
  border-radius:16px;
  box-shadow:0 0 25px #ff4fe2aa;
}

</style>
</head>

<body>

<div class="centerBox">

  <div id="popup">💖 Happy Princess Day 💖</div>

  <div id="next">
    <p>You are the quiet magic in my loud life…<br><br>
    You are a warmth that doesn’t fade, a feeling that turns ordinary days into something beautiful.<br><br>
    You are not just someone I adore – you are peace, comfort, and poetry breathing inside a heartbeat.</p>

    <p style="margin-top:14px;font-weight:700;font-size:26px;color:#ffb9ff">
    You will always be my World.</p>
  </div>

  <div class="qrBox" id="qrSection">
    <img src="QR_PLACEHOLDER">
  </div>

  <div><span id="btn" class="button" onclick="showNext()">💞 Continue 💞</span></div>

</div>

<!-- FLOATING SPARKLES -->
<script>
for(let i=0;i<45;i++){
  let s=document.createElement("div");
  s.className="sparkle";
  s.style.left=Math.random()*100+"%";
  s.style.top=Math.random()*100+"%";
  s.style.animationDelay=(Math.random()*4)+"s";
  document.body.appendChild(s);
}

function showNext(){
  document.getElementById("next").style.display="block";
  document.getElementById("qrSection").style.display="block";
  document.getElementById("btn").style.display="none";
}
</script>

</body>
</html>
