<h1 id="welcome">Welcome to Dxoma's Home</h1>

<p>Welcome to my home! </br> I'm Dxoma, Fullstack developer from <img src="https://cdn.discordapp.com/attachments/1457475879994261606/1474855612830453983/iraq.png?ex=699b5dd3&is=699a0c53&hm=113afc61743228b65475873a8354171b963610e38518cd78b3369b6ed0ef9e07&" width="13"/> <b>Iraq</b></p>

<h3>Things I code with</h3>
<p>
  <img alt="React" src="https://img.shields.io/badge/-React-45b8d8?style=flat-square&logo=react&logoColor=white" />
  <img alt="Webpack" src="https://img.shields.io/badge/-Webpack-8DD6F9?style=flat-square&logo=webpack&logoColor=white" /> 
  <img alt="Docker" src="https://img.shields.io/badge/-Docker-46a2f1?style=flat-square&logo=docker&logoColor=white" />
  <img alt="Github Actions" src="https://img.shields.io/badge/-Github_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white" />
  <img alt="Google Cloud Platform" src="https://img.shields.io/badge/-Google_Cloud_Platform-1a73e8?style=flat-square&logo=google-cloud&logoColor=white" />
  <img alt="TypeScript" src="https://img.shields.io/badge/-TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white" />
  <img alt="Insomnia" src="https://img.shields.io/badge/-Insomnia-5849BE?style=flat-square&logo=insomnia&logoColor=white" />
  <img alt="Apollo GraphQL" src="https://img.shields.io/badge/-Apollo%20GraphQL-311C87?style=flat-square&logo=apollo-graphql&logoColor=white" />
  <img alt="Heroku" src="https://img.shields.io/badge/-Heroku-430098?style=flat-square&logo=heroku&logoColor=white" />
  <img alt="Redux" src="https://img.shields.io/badge/-Redux-764ABC?style=flat-square&logo=redux&logoColor=white" />
  <img alt="ReactiveX" src="https://img.shields.io/badge/-RxJs-B7178C?style=flat-square&logo=reactivex&logoColor=white" />
  <img alt="GraphQL" src="https://img.shields.io/badge/-GraphQL-E10098?style=flat-square&logo=graphql&logoColor=white" />
  <img alt="Sass" src="https://img.shields.io/badge/-Sass-CC6699?style=flat-square&logo=sass&logoColor=white" />
  <img alt="Styled Components" src="https://img.shields.io/badge/-Styled_Components-db7092?style=flat-square&logo=styled-components&logoColor=white" />
  <img alt="Git" src="https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white" />
  <img alt="NestJs" src="https://img.shields.io/badge/-NestJs-ea2845?style=flat-square&logo=nestjs&logoColor=white" />
  <img alt="Angular" src="https://img.shields.io/badge/-Angular-DD0031?style=flat-square&logo=angular&logoColor=white" />
  <img alt="NPM" src="https://img.shields.io/badge/-NPM-CB3837?style=flat-square&logo=npm&logoColor=white" />
  <img alt="HTML5" src="https://img.shields.io/badge/-HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" />
  <img alt="Brave Browser" src="https://img.shields.io/badge/-Brave_Browser-FB542B?style=flat-square&logo=brave&logoColor=white" />
  <img alt="Rollup" src="https://img.shields.io/badge/-Rollup-EC4A3F?style=flat-square&logo=rollup.js&logoColor=white" />
  <img alt="D3.js" src="https://img.shields.io/badge/-D3.js-F9A03C?style=flat-square&logo=d3.js&logoColor=white" />
  <img alt="Prettier" src="https://img.shields.io/badge/-Prettier-F7B93E?style=flat-square&logo=prettier&logoColor=white" />
  <img alt="MongoDB" src="https://img.shields.io/badge/-MongoDB-13aa52?style=flat-square&logo=mongodb&logoColor=white" />
  <img alt="Node.js" src="https://img.shields.io/badge/-Nodejs-43853d?style=flat-square&logo=Node.js&logoColor=white" />
</p>

<h3>My Projects</h3>
<table>
  <thead align="center">
    <tr><td><b>Projects</b></td></tr>
  </thead>
  <tbody>
    <tr><td>1</td></tr>
    <tr><td>2</td></tr>
    <tr><td>3</td></tr>
    <tr><td>4</td></tr>
    <tr><td>5</td></tr>
    <tr><td>6</td></tr>
  </tbody>
</table>

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
  background: rgba(255, 255, 255, 0.8);
  border-radius: 2px;
  pointer-events: none;
  animation-name: fall;
  animation-timing-function: linear;
  animation-iteration-count: infinite;
}

@keyframes fall {
  0% { transform: translateY(-10px) rotate(0deg); opacity: 0.8; }
  100% { transform: translateY(100vh) rotate(360deg); opacity: 0.2; }
}
</style>

<script>
const num = 150;
for (let i = 0; i < num; i++) {
  const p = document.createElement('div');
  p.classList.add('paper');
  p.style.left = Math.random() * window.innerWidth + 'px';
  p.style.animationDuration = 3 + Math.random() * 5 + 's';
  p.style.width = 5 + Math.random() * 10 + 'px';
  p.style.height = 5 + Math.random() * 10 + 'px';
  p.style.opacity = 0.3 + Math.random() * 0.7;
  document.body.appendChild(p);
}
</script>
