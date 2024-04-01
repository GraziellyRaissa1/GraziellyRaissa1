### Olá! Eu sou a Grazielly Raissa 💀❤️
<br>


[![HTML](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://github.com/GraziellyRaissa1/PROJETOS-HTML-CSS)
[![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://github.com/GraziellyRaissa1/CSS-PROJ)
[![JAVASCRIPT](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)]()
[![C#](https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=c-sharp&logoColor=white)]()

![Linguagens](https://github-readme-stats.vercel.app/api?username=GraziellyRaissa1&show_icons=true&theme=midnight-purple) 

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=GraziellyRaissa1&layout=compact)

## Redes Sociais 🐈‍⬛


[![LINKEDIN](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/grazielly-raissa-pereira-b511342b6?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)
[![INSTAGRAM](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/grazyelly.rayssa?igsh=MTBvaHVtcnh3em9lcQ==)


### O crescimento pessoal e profissional está fora da zona de conforto. Aprenda a apreciar a zona de desconforto, pois é lá que o seu futuro é traçado.💭💡

ame: Generate Datas

on:
  schedule: # execute every 12 hours
    - cron: "* */12 * * *"
  workflow_dispatch:

jobs:
  build:
    name: Jobs to update datas
    runs-on: ubuntu-latest
    steps:
      # Snake Animation
      - uses: Platane/snk@master
        id: snake-gif
        with:
          github_user_name: rafaballerini
          svg_out_path: dist/github-contribution-grid-snake.svg

      - uses: crazy-max/ghaction-github-pages@v2.1.3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
