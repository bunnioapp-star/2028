# 2028 项目

&gt; 一句话标语：Bunnio App 的星级评分组件（示例）。

## 功能
- 展示星级评分
- 支持半星、鼠标悬停、点击回调
- 纯前端，零依赖

## 快速开始
1. 克隆仓库  
   ```bash
   git clone https://github.com/bunnioapp-star/2028.git
<!-- GitHub 个人主页特效版 -->
<!-- 把下面所有内容一次性复制到 *你的用户名*/*你的用户名*/README.md -->

<h1 align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=40&pause=1000&color=00F5FF&width=435&lines=Hi+%F0%9F%91%8B%2C+%E6%88%91%E6%98%AF%E6%98%9F%E4%B8%89" alt="Typing"/>
</h1>

<!-- 像素画：星三 -->
<pre align="center">
█████  ██ ██    ██ ██ ██
 ██   ██ ██  ██  ██ ██
 ██   ██ ██  ██  ██ ██
 ██   ██ ██  ██  ██ ██
 ██   ██ ██  ██  ██ ██
 ██    ███   ███  ███
</pre>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=你的用户名&label=Profile%20Views&style=flat-square&color=00F5FF" alt="Views"/>
  <!-- 把上面“你的用户名”改成真实用户名 -->
</p>

<!-- 掉落星星特效 -->
<p align="center">
  <a href="javascript:;">
    <img src="https://avatars.githubusercontent.com/你的用户名?s=160" id="avatar" width="160" height="160" style="border-radius:50%;cursor:pointer"/>
  </a>
</p>

<!-- 时间卡片 -->
<p align="center" id="local-time-card">
  <img src="https://img.shields.io/badge/🕒-Loading%20local%20time...-blue?style=for-the-badge"/>
</p>

<!-- 社交徽章一行流 -->
<p align="center">
  <a href="https://twitter.com/你的Twitter" target="_blank">
    <img alt="Twitter" src="https://img.shields.io/badge/🐦-Twitter-1DA1F2?style=flat-square&logo=twitter"/>
  </a>
  <a href="mailto:你的邮箱" target="_blank">
    <img alt="Mail" src="https://img.shields.io/badge/📧-Mail-D14836?style=flat-square&logo=gmail"/>
  </a>
  <a href="https://你的个人网站" target="_blank">
    <img alt="Website" src="https://img.shields.io/badge/🌍-Website-00F5FF?style=flat-square&logo=firefox"/>
  </a>
  <a href="https://www.linkedin.com/in/你的Linkedin" target="_blank">
    <img alt="LinkedIn" src="https://img.shields.io/badge/💼-LinkedIn-0077B5?style=flat-square&logo=linkedin"/>
  </a>
</p>

<!-- 掉落星星 JS -->
<script>
document.getElementById('avatar').onclick = function (e) {
  const kinds = ['✨','🌟','💫','⭐'];
  for(let i=0;i<18;i++){
    const s = document.createElement('span');
    s.innerText = kinds[Math.floor(Math.random()*4)];
    s.style.position = 'fixed';
    s.style.left = e.clientX + 'px';
    s.style.top  = e.clientY + 'px';
    s.style.fontSize = (16+Math.random()*16)+'px';
    s.style.pointerEvents = 'none';
    s.style.transition = 'all 1.2s linear';
    document.body.appendChild(s);
    setTimeout(()=>{
      s.style.transform = `translate(${(Math.random()-.5)*200}px,${Math.random()*150+100}px) scale(0)`;
      s.style.opacity = 0;
    },50);
    setTimeout(()=>s.remove(),1200);
  }
};
</script>

<!-- 本地时间脚本 -->
<script>
const card = document.getElementById('local-time-card');
const now = new Date();
const offset = now.getTimezoneOffset();
const hours = String(-offset/60).padStart(2,'+');
card.innerHTML = `<img src="https://img.shields.io/badge/🕒-Local%20time%20${now.toLocaleTimeString()}-blue?style=for-the-badge"/>`;
</script>

---

### 🧩 技能栈
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=flat-square&logo=node.js&logoColor=white)

### 📊 GitHub 统计
<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=你的用户名&show_icons=true&theme=radical" alt="stats"/>
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=你的用户名&layout=compact&theme=radical" alt="langs"/>
</p>
