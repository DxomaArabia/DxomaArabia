<h1 id="welcome">Welcome to Dxoma's Home</h1>

<style>
#welcome {
  text-align: center;
  font-size: 2.5em;
  font-family: sans-serif;
  animation: colorChange 2s infinite alternate;
}

@keyframes colorChange {
  0% { color: black; }
  100% { color: white; }
}

body {
  margin: 0;
  height: 100vh;
  background: #121212;
  overflow: hidden;
  position: relative;
}

.paper {
  position: absolute;
  width: 8px;
  height: 8px;
  background: rgba(255, 255, 255, 0.6);
  border-radius: 2px;
  pointer-events: none;
  animation-name: fall;
  animation-timing-function: linear;
  animation-iteration-count: infinite;
}

@keyframes fall {
  0% { transform: translateY(-10px) rotate(0deg); opacity: 0.6; }
  100% { transform: translateY(100vh) rotate(360deg); opacity: 0.2; }
}
</style>

<script>
const num = 200;
for (let i = 0; i < num; i++) {
  const p = document.createElement('div');
  p.classList.add('paper');
  p.style.left = Math.random() * window.innerWidth + 'px';
  p.style.top = Math.random() * -window.innerHeight + 'px';
  p.style.animationDuration = 5 + Math.random() * 5 + 's';
  p.style.width = 5 + Math.random() * 10 + 'px';
  p.style.height = 5 + Math.random() * 10 + 'px';
  p.style.opacity = 0.2 + Math.random() * 0.5;
  p.style.transform = `rotate(${Math.random() * 360}deg)`;
  document.body.appendChild(p);
}
</script>
