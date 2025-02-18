### Hi there, I'm Amirkhon! 👋
- 🅰️ Front-End Developer Angular
- 🔍 How to reach me: [Instagram](https://www.instagram.com/amirkhon_isomadinov/), [Telegram](https://t.me/Amirichvoker)


<div align="left">
  <img src="https://github-readme-stats.vercel.app/api?username=Amirkhon3223&show_icons=true&theme=blueberry" alt="GitHub Stats" height="180">&nbsp;&nbsp;
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Amirkhon3223&layout=compact&theme=blueberry" alt="Top Languages" height="180">
</div>


# Technologies

![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Vue](https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vue.js&logoColor=4FC08D)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![NPM](https://img.shields.io/badge/NPM-%23000000.svg?style=for-the-badge&logo=npm&logoColor=white)
![Yarn](https://img.shields.io/badge/yarn-%232C8EBB.svg?style=for-the-badge&logo=yarn&logoColor=white)  
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white) 
![Webpack](https://img.shields.io/badge/webpack-%238DD6F9.svg?style=for-the-badge&logo=webpack&logoColor=black) 
![HTMlL](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)

# Socials
[![Telegram](https://img.shields.io/badge/amirich-26A5E4?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/Amirichvoker)
[![Instagram](https://img.shields.io/badge/amirich-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/amirkhon_isomadinov/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/amirkhon-isomadinov-30a8561b8/)

<h2>📌 GitHub Gist</h2>

<a href="https://gist.github.com/Amirkhon3223" target="_blank">
  <table>
    <tr>
      <td>
        <img src="https://img.shields.io/badge/Gists-Loading...-blue?style=for-the-badge&logo=github" id="gist-count">
      </td>
    </tr>
    <tr>
      <td>
        <img src="https://img.shields.io/badge/Top%20Language-Loading...-green?style=for-the-badge" id="gist-lang">
      </td>
    </tr>
  </table>
</a>

<script>
  fetch("https://api.github.com/users/Amirkhon3223/gists")
    .then(res => res.json())
    .then(gists => {
      document.getElementById("gist-count").src = `https://img.shields.io/badge/Gists-${gists.length}-blue?style=for-the-badge&logo=github`;
      
      const langStats = {};
      gists.forEach(gist => {
        Object.values(gist.files).forEach(file => {
          langStats[file.language] = (langStats[file.language] || 0) + 1;
        });
      });

      const topLang = Object.entries(langStats).sort((a, b) => b[1] - a[1])[0];
      if (topLang) {
        document.getElementById("gist-lang").src = `https://img.shields.io/badge/Top%20Language-${topLang[0]}-green?style=for-the-badge`;
      }
    })
    .catch(err => console.error("Error loading Gist data:", err));
</script>

