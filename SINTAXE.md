# SINTAXE
## ESTRUTURA BÁSICA
Aqui está um exemplo simples de como começar um projeto com MaterializeCSS:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Meu Projeto com MaterializeCSS</title>
  <!-- Compiled and minified CSS -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0/css/materialize.min.css">
</head>
<body>

  <!-- Navbar -->
  <nav>
    <div class="nav-wrapper">
      <a href="#" class="brand-logo">Logo</a>
      <ul id="nav-mobile" class="right hide-on-med-and-down">
        <li><a href="#">Home</a></li>
        <li><a href="#">Sobre</a></li>
        <li><a href="#">Contato</a></li>
      </ul>
    </div>
  </nav>

  <!-- Container principal -->
  <div class="container">
    <h1>Bem-vindo ao MaterializeCSS</h1>
    <p>Este é um exemplo básico de como começar a usar MaterializeCSS no seu projeto.</p>
    
    <!-- Botão -->
    <a class="waves-effect waves-light btn">Botão Exemplo</a>
    
    <!-- Card -->
    <div class="card">
      <div class="card-image">
        <img src="imagem.jpg" alt="Imagem Exemplo">
        <span class="card-title">Título do Card</span>
      </div>
      <div class="card-content">
        <p>Este é um exemplo de card usando MaterializeCSS.</p>
      </div>
      <div class="card-action">
        <a href="#">Este é um link</a>
      </div>
    </div>
  </div>

  <!-- Compiled and minified JavaScript -->
  <script src="https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0/js/materialize.min.js"></script>
</body>
</html>
```

Este exemplo ilustra a estrutura básica de um projeto utilizando MaterializeCSS, incluindo a importação dos arquivos CSS e JavaScript, a criação de uma navbar, um container principal com um título, um botão e um card. 

## COMPONENTES BÁSICOS
Aqui estão alguns exemplos de componentes básicos do MaterializeCSS.

### BOTÕES:
```html
<a class="waves-effect waves-light btn">Botão</a>
```

### GRID:
```html
<div class="row">
  <div class="col s12">Este div ocupa 12 colunas</div>
  <div class="col s6">Este div ocupa 6 colunas</div>
  <div class="col s6">Este div ocupa 6 colunas</div>
</div>
```

### NAVBAR:
```html
<nav>
  <div class="nav-wrapper">
    <a href="#" class="brand-logo">Logo</a>
    <ul id="nav-mobile" class="right hide-on-med-and-down">
      <li><a href="sass.html">Sass</a></li>
      <li><a href="badges.html">Components</a></li>
      <li><a href="collapsible.html">JavaScript</a></li>
    </ul>
  </div>
</nav>
```

### CARDS:
```html
<div class="card">
  <div class="card-image">
    <img src="image.jpg">
    <span class="card-title">Card Title</span>
  </div>
  <div class="card-content">
    <p>Eu sou um parágrafo dentro do card.</p>
  </div>
  <div class="card-action">
    <a href="#">Este é um link</a>
  </div>
</div>
```

### INICIALIZANDO COMPONENTES JAVASCRIPT
Alguns componentes, como modals e dropdowns, precisam ser inicializados com JavaScript. Aqui está um exemplo de como fazer isso:

```html
<!-- Modal Trigger -->
<a class="waves-effect waves-light btn modal-trigger" href="#modal1">Modal</a>

<!-- Modal Structure -->
<div id="modal1" class="modal">
  <div class="modal-content">
    <h4>Modal Header</h4>
    <p>A bunch of text</p>
  </div>
  <div class="modal-footer">
    <a href="#!" class="modal-close waves-effect waves-green btn-flat">Agree</a>
  </div>
</div>

<script>
  document.addEventListener('DOMContentLoaded', function() {
    var elems = document.querySelectorAll('.modal');
    var instances = M.Modal.init(elems);
  });
</script>
```

Esses são apenas exemplos básicos para começar. MaterializeCSS oferece muitos outros componentes e funcionalidades que podem ser explorados conforme suas necessidades. 