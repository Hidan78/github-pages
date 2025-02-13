<header>

<!--<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <title>A Jornada do Amor</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 0; padding: 20px; background: #fff0f6; }
    .section { padding: 40px 0; border-bottom: 1px solid #ccc; text-align: center; }
    .btn { display: inline-block; margin-top: 20px; padding: 10px 20px; background: #ff5a5f; color: #fff; text-decoration: none; border-radius: 5px; }
    video { max-width: 90%; height: auto; }
    img.qr { width: 150px; height: 150px; margin-top: 20px; }
  </style>
</head>
<body>

  <!-- Página Inicial: Vídeo de Introdução -->
  <div id="inicio" class="section">
    <h1>A Jornada do Amor</h1>
    <video controls>
      <source src="seu-video-intro.mp4" type="video/mp4">
      Seu navegador não suporta vídeo.
    </video>
    <p>Olá, meu amor! Preparei uma aventura digital para você relembrar nossos momentos mais especiais.</p>
    <!-- Aqui, em vez de um QR code físico, usamos um botão que leva à próxima seção -->
    <a href="#primeira-pista" class="btn">Iniciar Aventura</a>
  </div>

  <!-- Primeira Pista: Texto e Instrução para a Playlist -->
  <div id="primeira-pista" class="section">
    <h2>Primeira Pista</h2>
    <p>Lembra do nosso primeiro encontro? Reviva esse momento acessando nossa playlist exclusiva. Clique no botão abaixo para ouvir a faixa "Nosso Primeiro Olhar". Preste atenção no trecho entre 1:20 e 1:40 – lá, uma mensagem secreta aguarda.</p>
    <!-- Exemplo de QR Code gerado: substitua pela imagem baixada -->
    <a href="#playlist" class="btn">Ouvir Playlist</a>
    <!-- Ou, se preferir exibir o QR code: -->
    <!-- <img src="qr_primeira-pista.png" alt="QR Code Primeira Pista" class="qr"> -->
  </div>

  <!-- Página da Playlist -->
  <div id="playlist" class="section">
    <h2>Nossa Trilha do Amor</h2>
    <!-- Incorpore o player do Spotify ou YouTube -->
    <iframe src="https://open.spotify.com/embed/playlist/seu-playlist-id" width="300" height="380" frameborder="0" allowtransparency="true" allow="encrypted-media"></iframe>
    <p>Ouça a faixa "Nosso Primeiro Olhar" e atente-se ao trecho mencionado.</p>
    <a href="#segunda-pista" class="btn">Próxima Pista</a>
  </div>

  <!-- Segunda Pista: Vídeo Curto -->
  <div id="segunda-pista" class="section">
    <h2>Segunda Pista</h2>
    <video controls>
      <source src="seu-video-pista.mp4" type="video/mp4">
      Seu navegador não suporta vídeo.
    </video>
    <p>Lembra daquela viagem inesquecível? Clique no botão abaixo para ver uma foto especial e descobrir a próxima pista.</p>
    <a href="#foto-interativa" class="btn">Ver Foto Especial</a>
  </div>

  <!-- Terceira Pista: Foto Interativa -->
  <div id="foto-interativa" class="section">
    <h2>Terceira Pista</h2>
    <!-- Exiba a foto da memória com o QR code sobreposto (pode ser uma imagem editada) -->
    <img src="foto-memoria.jpg" alt="Nossa Viagem" style="max-width:90%; height:auto;">
    <p>Clique na imagem ou no QR code abaixo para revelar a última surpresa.</p>
    <!-- Botão que simula o clique no QR code -->
    <a href="#final" class="btn">Última Pista</a>
  </div>

  <!-- Página Final: Surpresa e Encontro Virtual -->
  <div id="final" class="section">
    <h2>Surpresa Final</h2>
    <p>Parabéns, meu amor! Você completou a nossa Jornada do Amor. Cada pista foi um pedacinho do nosso passado e do quanto você é especial para mim.</p>
    <p>Agora, prepare-se: vamos ter um encontro virtual surpresa! Clique no botão abaixo para ver os detalhes do nosso encontro.</p>
    <a href="link-para-videochamada-ou-detalhes.html" class="btn">Ver Detalhes do Encontro</a>
  </div>

</body>
</html>

  <<< Author notes: Course header >>>
  Include a 1280×640 image, course title in sentence case, and a concise description in emphasis.
  In your repository settings: enable template repository, add your 1280×640 social image, auto delete head branches.
  Add your open source license, GitHub uses MIT license.
-->

# GitHub Pages

_Create a site or blog from your GitHub repositories with GitHub Pages._

</header>

<!--
  <<< Author notes: Course start >>>
  Include start button, a note about Actions minutes,
  and tell the learner why they should take the course.
-->

## Welcome

With GitHub Pages, you can host project blogs, documentation, resumes, portfolios, or any other static content you'd like. Your GitHub repository can easily become its own website. In this course, we'll show you how to set up your own site or blog using GitHub Pages.

- **Who is this for**: Beginners, students, project maintainers, small businesses.
- **What you'll learn**: How to build a GitHub Pages site.
- **What you'll build**: We'll build a simple GitHub Pages site with a blog. We'll use [Jekyll](https://jekyllrb.com), a static site generator.
- **Prerequisites**: If you need to learn about branches, commits, and pull requests, take [Introduction to GitHub](https://github.com/skills/introduction-to-github) first.
- **How long**: This course takes less than one hour to complete.

In this course, you will:

1. Enable GitHub Pages
2. Configure your site
3. Customize your home page
4. Create a blog post
5. Merge your pull request

### How to start this course

<!-- For start course, run in JavaScript:
'https://github.com/new?' + new URLSearchParams({
  template_owner: 'skills',
  template_name: 'github-pages',
  owner: '@me',
  name: 'skills-github-pages',
  description: 'My clone repository',
  visibility: 'public',
}).toString()
-->

[![start-course](https://user-images.githubusercontent.com/1221423/235727646-4a590299-ffe5-480d-8cd5-8194ea184546.svg)](https://github.com/new?template_owner=skills&template_name=github-pages&owner=%40me&name=skills-github-pages&description=My+clone+repository&visibility=public)

1. Right-click **Start course** and open the link in a new tab.
2. In the new tab, most of the prompts will automatically fill in for you.
   - For owner, choose your personal account or an organization to host the repository.
   - We recommend creating a public repository, as private repositories will [use Actions minutes](https://docs.github.com/en/billing/managing-billing-for-github-actions/about-billing-for-github-actions).
   - Scroll down and click the **Create repository** button at the bottom of the form.
3. After your new repository is created, wait about 20 seconds, then refresh the page. Follow the step-by-step instructions in the new repository's README.

<footer>

<!--
  <<< Author notes: Footer >>>
  Add a link to get support, GitHub status page, code of conduct, license link.
-->

---

Get help: [Post in our discussion board](https://github.com/orgs/skills/discussions/categories/github-pages) &bull; [Review the GitHub status page](https://www.githubstatus.com/)

&copy; 2023 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)

</footer>
