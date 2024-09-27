<!-- Contenedor principal -->
<div style="position: relative; width: 100%; height: 500px; border: 1px solid black; padding: 20px;">
  
  <!-- Texto animado de bienvenida -->
  [![Typing SVG](https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=774FE8&width=435&lines=Hi%2C+my+name+is+Mario.+;Welcome+to+my+GitHub+profile.)](https://git.io/typing-svg)


  <!-- Tecnologías y herramientas -->
  <h3>Tecnologies and Tools:</h3>
  <div style="display: inline_block"><br>
    <img align="center" alt="Cris-Git" height="35" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/vscode/vscode-original.svg">
    <img align="center" alt="Cris-Git" height="35" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/mysql/mysql-original.svg">
    <img align="center" alt="Cris-Js" height="35" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original.svg">
    <img align="center" alt="Cris-PHP" height="35" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/cplusplus/cplusplus-original.svg">
    <img align="center" alt="Cris-PHP" height="35" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/rstudio/rstudio-original.svg">
    <img align="center" alt="Cris-VS" height="35" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/javascript/javascript-original.svg">
    <img align="center" alt= "Cris-Mysql" height="60" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/html5/html5-original.svg">       
    <img align="center" alt="Cris-Csharp" height="35" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/css3/css3-original.svg">
  </div><br>

  <!-- Contacto -->
  <h3>Contact</h3>
  <div> 
    <a href="https://www.linkedin.com/in/mariofengwu/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a> 
    <a href="mailto:mario.fengw@gmail.com"><img src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=white" target="_blank"></a>
  </div>

  <div style="position: absolute; bottom: 10px; right: 10px; text-align: center;">
    <img src="https://komarev.com/ghpvc/?username=MarioFengW&color=774FE8&&style=for-the-badge" align="center" />
  </div>

**github action**

```yaml
- uses: Platane/snk@v3
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ github.repository_owner }}

    # list of files to generate.
    # one file per line. Each output can be customized with options as query string.
    #
    #  supported options:
    #  - palette:     A preset of color, one of [github, github-dark, github-light]
    #  - color_snake: Color of the snake
    #  - color_dots:  Coma separated list of dots color.
    #                 The first one is 0 contribution, then it goes from the low contribution to the highest.
    #                 Exactly 5 colors are expected.
    outputs: |
      dist/github-snake.svg
      dist/github-snake-dark.svg?palette=github-dark
      dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9
```

```html
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="github-snake.svg" />
  <img alt="github-snake" src="github-snake.svg" />
</picture>
```
</div>
