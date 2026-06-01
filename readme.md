from pathlib import Path

content = """# Olá, eu sou Caio 👋

Sou estudante do **1º período de Ciência da Computação** e estou iniciando minha jornada como desenvolvedor. Tenho interesse em aprender cada vez mais sobre programação, lógica computacional, desenvolvimento de software e boas práticas de código.

## Sobre mim

- 🎓 Estudante de Ciência da Computação
- 💻 Desenvolvedor em formação
- 📚 Atualmente estudando lógica de programação, algoritmos e fundamentos da computação
- 🚀 Buscando evoluir por meio de projetos práticos e estudos contínuos

## Tecnologias que estou aprendendo

<div align="left">

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)

</div>

## Áreas de interesse

- Desenvolvimento de software
- Lógica de programação
- Algoritmos e estruturas de dados
- Desenvolvimento web
- Resolução de problemas com código

## Objetivos

Meu objetivo é construir uma base sólida em computação, desenvolver projetos práticos e evoluir como programador. Estou sempre buscando aprender novas tecnologias, melhorar minha lógica e aplicar meus conhecimentos em desafios reais.

## Projetos em desenvolvimento

Atualmente estou criando pequenos projetos para praticar:

- Programas em **Python**
- Scripts e páginas com **JavaScript**
- Exercícios e algoritmos em **C**

## Estatísticas do GitHub

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=SEU_USUARIO_AQUI&show_icons=true&theme=default)

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=SEU_USUARIO_AQUI&layout=compact&theme=default)

</div>

## Contato

- GitHub: [SEU_USUARIO_AQUI](https://github.com/SEU_USUARIO_AQUI)
- LinkedIn: [SEU_LINKEDIN_AQUI](SEU_LINKEDIN_AQUI)
- E-mail: SEU_EMAIL_AQUI

---

> “A melhor forma de aprender programação é praticando, errando, corrigindo e tentando novamente.”
"""

path = Path("/mnt/data/README_Caio_GitHub_Profile.md")
path.write_text(content, encoding="utf-8")
path.as_posix()
