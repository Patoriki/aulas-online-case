# Aulas Online: Plataforma de Cursos 🚧 em desenvolvimento

> Estudo de caso. O código-fonte é privado, porque a plataforma será comercializada. As imagens usam **dados fictícios**.

🔗 **Demonstração:** https://fancy-starship-da67eb.netlify.app

Projeto próprio. **Todo o desenvolvimento é meu**. A sócia **Larissa** <!-- link do LinkedIn dela, se ela quiser --> cuida da consultoria, dos negócios e do marketing.

## A ideia
Uma plataforma de cursos online em que **a mesma conta serve para aprender e para ensinar**. Qualquer pessoa pode estudar e também publicar os próprios cursos, sem cadastros separados.

## Funcionalidades
**Já disponível**
- 🌐 Landing page com catálogo de cursos em destaque, professores e chamada para cadastro
- 🔐 Login e área logada

**Em desenvolvimento**
- 🔄 **Modo aluno / modo professor** com um único perfil, alternado por um botão
- 🎓 **Área do aluno**: meus cursos, catálogo completo, favoritos e tags, caderno de anotações (com exportação em PDF) e comunidade
- 🧑‍🏫 **Área do professor**: criação e gestão de cursos
- 🎬 **Três tipos de aula**: gravada, ao vivo e prática (com vídeo e envio de arquivos pelo professor)
- 📝 **Avaliações**: provas em documento e trabalhos práticos
- 🏅 **Certificado com aprovação do professor**: o aluno conclui o curso e solicita, o professor autoriza, e o aluno pode contestar uma recusa
- 💬 **Comentários por curso**, no lugar da avaliação por estrelas

## Arquitetura
```
[ Front-end: Angular 17 ]  →  Netlify
          │
     API REST (Django)  →  Render
          │
     PostgreSQL (produção) / SQL Server (desenvolvimento)
```

## Minha participação
**Desenvolvi a plataforma inteira**, de ponta a ponta:
- 🎨 Layout, identidade visual e UX
- 🖥️ Front-end em Angular 17
- ⚙️ API em Django e modelagem do banco de dados
- 🚀 Deploy e infraestrutura (Netlify + Render + PostgreSQL)
- 🧠 Definição das regras do produto junto com a sócia

**Larissa**: consultoria, negócios e marketing.

## Tecnologias
**Front-end:** Angular 17 · TypeScript · Bootstrap 5 · Font Awesome
**Back-end:** Python · Django · PostgreSQL
**Deploy:** Netlify (front) · Render (API)

## Telas
<!-- prints na pasta /prints, por exemplo:
![Landing page](prints/landing.png)
![Área do aluno](prints/area-aluno.png)
![Modo professor](prints/modo-professor.png)
-->
