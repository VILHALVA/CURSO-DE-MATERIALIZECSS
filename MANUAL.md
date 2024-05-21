# MANUAL
## COMO INCLUIR MATERIALIZECSS NO SEU PROJETO?
Você pode incluir o MaterializeCSS no seu projeto de duas maneiras: via CDN (Content Delivery Network) ou baixando os arquivos e incluindo-os localmente.

### VIA CDN
Adicione as seguintes linhas dentro da tag `<head>` do seu HTML:

```html
<!DOCTYPE html>
<html>
<head>
  <!-- Compiled and minified CSS -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0/css/materialize.min.css">

  <!-- Compiled and minified JavaScript -->
  <script src="https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0/js/materialize.min.js"></script>
  
  <!-- jQuery (necessário para alguns componentes) -->
  <script src="https://code.jquery.com/jquery-3.3.1.min.js"></script>
</head>
<body>
  <!-- Seu conteúdo aqui -->
</body>
</html>
```

### LOCALMENTE
Baixe os arquivos de [MaterializeCSS](https://materializecss.com/getting-started.html) e inclua-os no seu projeto. Em seguida, adicione as seguintes linhas no seu HTML:

```html
<!DOCTYPE html>
<html>
<head>
  <!-- Compiled and minified CSS -->
  <link rel="stylesheet" href="path/to/materialize.min.css">

  <!-- Compiled and minified JavaScript -->
  <script src="path/to/materialize.min.js"></script>
  
  <!-- jQuery (necessário para alguns componentes) -->
  <script src="https://code.jquery.com/jquery-3.3.1.min.js"></script>
</head>
<body>
  <!-- Seu conteúdo aqui -->
</body>
</html>
```

