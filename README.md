

<br>

 
  <a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Afacad+flux&size=48&pause=1000&center=true&width=1920&height=100&lines=HELLO%2C+I+am+Vivek+Vibhuti;I'm+a+Full+Stack+Developer;I'm+a+Student;A+Passionate+Developer" alt="Typing SVG" />
</a>




<div align="right">
  <img src="https://visitor-badge.laobi.icu/badge?page_id=vivek-vibhuti.vivek-vibhuti&format=true" alt="Visitor Badge" style="border: 2px solid #FF6347; border-radius: 10px;">
</div>

---
name: Generate Snake Animation

on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:

jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: YOUR_GITHUB_USERNAME
          outputs: |
            ./github-contribution-grid-snake.svg
        env:
          COLOR_SNAKE: "#00ffcc"
          COLOR_DOTS: "#444444, #333333, #222222, #111111, #000000"
          BACKGROUND: "#000000"

      - uses: actions/upload-artifact@v4
        with:
          name: snake-animation
          path: ./github-contribution-grid-snake.svg

      - name: Push the snake
        run: |
          git config --global user.name 'github-actions'
          git config --global user.email 'github-actions@github.com'
          git add github-contribution-grid-snake.svg
          git commit -m "Generate dark snake animation"
          git push

<div align="center">
  <h2 style="color: #4682B4; text-shadow: 1px 1px #B0C4DE; font-family: 'Arial', sans-serif;">
    Let’s Get in Touch!
  </h2>
  <a href="mailto:vivekvibhutiofficial@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail Badge">
  </a>
  <a href="https://github.com/vivek-vibhuti">
    <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Badge">
  </a>
  <a href="YOUR_FACEBOOK_PROFILE_LINK_HERE">
    <img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white" alt="Facebook Badge">
  </a>
  <a href="YOUR_LINKEDIN_PROFILE_LINK_HERE">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn Badge">
  </a>
  <a href="YOUR_PORTFOLIO_LINK_HERE">
    <img src="https://img.shields.io/badge/Portfolio-8A2BE2?style=for-the-badge&logo=portfolio&logoColor=white" alt="Portfolio Badge">
  </a>
</div>

---

### 💻 **My Skills**
<div align="center">
  <h2 style="color: #32CD32; text-shadow: 2px 2px #98FB98; font-family: 'Georgia', serif;">
    Technologies I Love
  </h2>
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=python,java,javascript,tailwind,react,c,spring,express,mysql,mongodb,nodejs,html,css,django,illustrator,photoshop,canva,cplusplus" style="border-radius: 10px;"/>
  </a>
</div>

---

### 📈 **GitHub Stats**
<div align="center">
  <a href="https://git.io/streak-stats">
    <img src="https://streak-stats.demolab.com?user=vivek-vibhuti&theme=youtube-dark&border_radius=4.7" alt="GitHub Streak" />
  </a>
</div>

---

### 🌟 **Future Goals**
<div align="center">
  <h2 style="color: #20B2AA; text-shadow: 1px 1px #3CB371; font-family: 'Georgia', serif;">
    What I Aim to Achieve
  </h2>
  <ul style="list-style-type: none; padding: 0;">
    <li>🚀 Learn advanced AI and machine learning technologies.</li>
    <li>💡 Explore new frameworks and tools in web development.</li>
    <li>📈 Contribute to larger open-source projects and communities.</li>
    <li>🎤 Share my knowledge through workshops and presentations.</li>
  </ul>
</div>

---

### 🎉 **Thank You for Visiting!**
<div align="center">
  <p>Feel free to explore my projects, connect with me, and let's collaborate!</p>
</div>
