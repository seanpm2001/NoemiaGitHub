Olá! Eu sou a Noemia Jordania👋  
🔭 Atualmente, estou desenvolvendo projetos com foco em C# e .NET.  
🌱 Estou aprendendo arquitetura de microserviços, automação de testes com Selenium e aprimorando minhas habilidades com orientação a objetos.  
👯 Estou aberta a colaborar em projetos open-source e iniciativas de aprendizado em grupo.  
📫 Me encontre no LinkedIn: www.linkedin.com/in/noemia-jordania-53a022251  
😄 Pronomes: Ela/Dela  
⚡ Curiosidades: Sou apaixonada por tecnologia 💻 e passo a semana em plataformas de cursos para me aprimorar. Nas horas vagas, gosto de relaxar em Games de estratégia ♟️, RPGs 🧙‍♀️ e simuladores 🎮!

 name: Jobs to update datas
    runs-on: ubuntu-latest
    steps:
      # Summary Cards
      - uses: actions/checkout@v2
      - uses: vn7n24fzkq/github-profile-summary-cards@release
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
        with:
          USERNAME: ${{ github.repository_owner }}
      # Snake Animation
      - uses: Platane/snk@master
        id: snake-gif
