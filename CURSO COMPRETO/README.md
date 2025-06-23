# INSTRUÇÕES

---
## INDICE
- [01) INTRODUÇÃO](./README.md#01-introdução)
- [02) ESTRUTURA DO PROJETO](./README.md#02-estrutura-do-projeto)
- [03) COR](./README.md#03-cor)
- [04) SHADOW](./README.md#04-shadow)
- [05) TYPOGRAPHY](./README.md#05-typography)
- [06) MEDIA](./README.md#06-media)
- [07) TABLE](./README.md#07-table)
- [08-09) GRID](./README.md#08-09-grid)
- [10) HELPERS](./README.md#10-helpers)
- [11) COMPONENTS (ICONS)](./README.md#11-components-icons)
- [12) COMPONENTS (BREADCRUMBS E PAGINATION)](./README.md#12-components-breadcrumbs-e-pagination)
- [13) COMPONENTS (BUTTONS)](./README.md#13-components-buttons)
- [14) COMPONENTS (COLLECTIONS)](./README.md#14-components-collections)
- [15) COMPONENTS (BADGES)](./README.md#15-components-badges)
- [16) COMPONENTS (PRELOADER)](./README.md#16-components-preloader)
- [17-21) COMPONENTS (NAVBAR)](./README.md#17-21-components-navbar)
- [22) COMPONENTS (FOOTER)](./README.md#22-components-footer)
- [23-26) COMPONENTS (CARD)](./README.md#23-26-components-card)
- [27-29) COMPONENTS (CHIPS)](./README.md#27-29-components-chips)
- [30) PULSE](./README.md#30-pulse)
- [31-33) COMPONENTS (FORMS)](./README.md#31-33-components-forms)
- [34) FORMS (SELECT, DATEPICKER E TIMEPICKER)](./README.md#34-forms-select-datepicker-e-timepicker)
- [35) FORMS (RADIO, CHECKBOX, INPUT FILE E RANGE)](./README.md#35-forms-radio-checkbox-input-file-e-range)
- [36) JAVASCRIPT (CAROUSEL)](./README.md#36-javascript-carousel)
- [37) JAVASCRIPT (PARALLAX)](./README.md#37-javascript-parallax)
- [38) JAVASCRIPT (WAVES)](./README.md#38-javascript-waves)
- [40) JAVASCRIPT (DROPDOWN)](./README.md#40-javascript-dropdown)
- [41) JAVASCRIPT (MATERIALBOX & SLIDER)](./README.md#41-javascript-materialbox--slider)
- [42) JAVASCRIPT (TRANSITIONS)](./README.md#42-javascript-transitions)
- [43) JAVASCRIPT (COLLAPSIBLE)](./README.md#43-javascript-collapsible)
- [44) JAVASCRIPT (MODAIS)](./README.md#44-javascript-modais)
- [45) JAVASCRIPT (TOASTS E TOOLTIPS)](./README.md#45-javascript-toasts-e-tooltips)
- [46) JAVASCRIPT (SCROLLFIRE)](./README.md#46-javascript-scrollfire)
- [47) JAVASCRIPT (SCROLLSPY)](./README.md#47-javascript-scrollspy)
- [48) JAVASCRIPT (TABS)](./README.md#48-javascript-tabs)
- [49) JAVASCRIPT (SIDENAV)](./README.md#49-javascript-sidenav)
- [50) JAVASCRIPT (PUSHPIN)](./README.md#50-javascript-pushpin)
- [51) JAVASCRIPT (FEATUREDISCOVERY)](./README.md#51-javascript-featurediscovery)
- [52) PROJETO FINAL](./README.md#52-projeto-final)
---

## 01) INTRODUÇÃO:
No mundo do desenvolvimento web, criar interfaces de usuário modernas, responsivas e visualmente atraentes é essencial para o sucesso de qualquer projeto. É aqui que entra o MaterializeCSS, um framework front-end baseado no Material Design do Google, projetado para simplificar o processo de desenvolvimento e garantir uma experiência de usuário consistente em todos os dispositivos.

O MaterializeCSS oferece uma vasta coleção de componentes CSS e JavaScript pré-estilizados, desde botões e formulários até modais e navbars, todos seguindo as diretrizes do Material Design. Isso significa que os desenvolvedores podem criar rapidamente layouts sofisticados e interativos, sem a necessidade de habilidades avançadas de design ou codificação complexa.

Nesta série de tutoriais, exploraremos os recursos e capacidades do MaterializeCSS, desde a instalação e configuração básica até a criação de interfaces de usuário personalizadas e funcionais. Ao longo do caminho, aprenderemos como utilizar eficientemente os componentes do MaterializeCSS para criar sites e aplicativos web que não apenas impressionam visualmente, mas também oferecem uma experiência de usuário intuitiva e agradável.

Se você é um desenvolvedor em busca de uma maneira simples e eficaz de implementar o design moderno do Material Design em seus projetos, você está no lugar certo. Vamos começar nossa jornada para dominar o MaterializeCSS e elevar o padrão das nossas criações web!

## 02) ESTRUTURA DO PROJETO:
Para um projeto utilizando o MaterializeCSS, a estrutura básica de arquivos pode seguir um padrão semelhante ao de qualquer projeto web. Aqui está uma estrutura de diretórios e arquivos que você pode considerar:

```
meu-projeto/
│
├── css/
│   ├── materialize.min.css
│   └── styles.css
│
├── fonts/
│   └── (fontes do MaterializeCSS)
│
├── js/
│   ├── materialize.min.js
│   └── scripts.js
│
├── img/
│   └── (imagens do projeto)
│
├── index.html
│
└── outros-arquivos.html
```

Aqui está uma breve descrição de cada pasta e arquivo:

- **css/**: Pasta para arquivos CSS. Além do arquivo principal do MaterializeCSS (materialize.min.css), você pode ter um arquivo adicional para estilos personalizados (styles.css), se necessário.

- **fonts/**: Pasta para armazenar as fontes utilizadas pelo MaterializeCSS. Normalmente, essas fontes já são incluídas no pacote do MaterializeCSS, então você pode apenas referenciá-las diretamente nos seus arquivos CSS.

- **js/**: Pasta para arquivos JavaScript. Além do arquivo principal do MaterializeCSS (materialize.min.js), você pode ter um arquivo adicional para scripts personalizados (scripts.js), se necessário.

- **img/**: Pasta para armazenar imagens utilizadas no projeto, como logos, ícones, etc.

- **index.html**: Arquivo HTML principal do seu projeto. Aqui você irá definir a estrutura básica da sua página e incluir os links para os arquivos CSS e JavaScript.

- **outros-arquivos.html**: Arquivos HTML adicionais, se o seu projeto tiver mais de uma página.

Essa é apenas uma estrutura básica e você pode ajustá-la de acordo com as necessidades específicas do seu projeto. Por exemplo, se você estiver usando um sistema de gerenciamento de pacotes como o npm, pode preferir manter os arquivos do MaterializeCSS e outros recursos diretamente na pasta de node_modules.

Lembre-se de que a estrutura do projeto é flexível e pode variar dependendo do tamanho e das necessidades do seu projeto específico. O importante é manter uma organização consistente para facilitar o desenvolvimento e a manutenção do código.

## 03) COR:
O MaterializeCSS oferece uma variedade de cores que podem ser facilmente aplicadas aos elementos do seu projeto. As cores são definidas por classes específicas que você pode adicionar aos elementos HTML para alterar sua aparência. Aqui estão algumas das classes de cores mais comuns no MaterializeCSS:

1. **Texto Colorido**:
   - `.text-primary`: Define a cor do texto como a cor primária definida no arquivo CSS.
   - `.text-secondary`: Define a cor do texto como a cor secundária definida no arquivo CSS.
   - `.text-accent`: Define a cor do texto como a cor de destaque definida no arquivo CSS.

2. **Fundo Colorido**:
   - `.bg-primary`: Define o fundo do elemento como a cor primária definida no arquivo CSS.
   - `.bg-secondary`: Define o fundo do elemento como a cor secundária definida no arquivo CSS.
   - `.bg-accent`: Define o fundo do elemento como a cor de destaque definida no arquivo CSS.

3. **Cores Específicas**:
   - `.red`, `.blue`, `.green`, `.yellow`, `.orange`, `.purple`, etc.: Define a cor do elemento como a cor especificada.
   - `.lighten-1`, `.lighten-2`, `.lighten-3`, `.lighten-4`, `.lighten-5`: Adiciona uma tonalidade mais clara à cor especificada.
   - `.darken-1`, `.darken-2`, `.darken-3`, `.darken-4`: Adiciona uma tonalidade mais escura à cor especificada.

4. **Texto/Background**:
   - `.text-lighten-1`, `.text-lighten-2`, `.text-lighten-3`, `.text-lighten-4`, `.text-lighten-5`: Define o texto com uma tonalidade mais clara.
   - `.text-darken-1`, `.text-darken-2`, `.text-darken-3`, `.text-darken-4`: Define o texto com uma tonalidade mais escura.
   - `.bg-lighten-1`, `.bg-lighten-2`, `.bg-lighten-3`, `.bg-lighten-4`, `.bg-lighten-5`: Define o fundo com uma tonalidade mais clara.
   - `.bg-darken-1`, `.bg-darken-2`, `.bg-darken-3`, `.bg-darken-4`: Define o fundo com uma tonalidade mais escura.

5. **Cores de Texto Padrão**:
   - `.black-text`: Define o texto como preto.
   - `.white-text`: Define o texto como branco.

Essas são apenas algumas das classes de cores disponíveis no MaterializeCSS. Você pode aplicá-las a qualquer elemento HTML para alterar sua aparência de acordo com as necessidades do seu projeto. Lembre-se de que você também pode personalizar as cores definindo variáveis CSS no seu próprio arquivo de estilo personalizado.

## 04) SHADOW:
No MaterializeCSS, você pode adicionar sombras aos elementos usando classes específicas de sombra. Essas classes aplicam estilos de sombra predefinidos aos elementos HTML para criar efeitos visuais de profundidade e realismo. Aqui estão algumas das classes de sombra mais comuns no MaterializeCSS:

1. **Sombra de Elevação**:
   - `.z-depth-1`, `.z-depth-2`, `.z-depth-3`, `.z-depth-4`, `.z-depth-5`: Adiciona uma sombra de elevação ao elemento com diferentes níveis de profundidade. Quanto maior o número, mais pronunciada é a sombra.

2. **Sombra Estática**:
   - `.z-depth-0`: Remove completamente a sombra do elemento, tornando-a plana.

Essas classes podem ser aplicadas a uma variedade de elementos HTML, como cards, botões, navbars e outros, para adicionar profundidade e realce visual. Aqui está um exemplo de como você pode usar as classes de sombra em um card:

```html
<div class="card z-depth-3">
  <div class="card-content">
    <span class="card-title">Card com Sombra</span>
    <p>Este é um exemplo de card com sombra no MaterializeCSS.</p>
  </div>
</div>
```

Neste exemplo, a classe `z-depth-3` é aplicada ao `<div class="card">`, adicionando uma sombra de elevação com um nível de profundidade de 3.

Experimente diferentes classes de sombra e níveis de profundidade para encontrar o efeito visual desejado para os elementos do seu projeto. Lembre-se de que as sombras podem ajudar a criar uma sensação de profundidade e dimensão em seu design, tornando-o mais atraente e envolvente para os usuários.

## 05) TYPOGRAPHY:
No MaterializeCSS, a tipografia é uma parte importante do design, e o framework oferece classes específicas para estilizar o texto de maneira consistente e atraente. Aqui estão algumas das classes de tipografia mais comuns no MaterializeCSS:

1. **Títulos**:
   - `.h1`, `.h2`, `.h3`, `.h4`, `.h5`, `.h6`: Define o tamanho do texto para títulos de diferentes níveis de hierarquia.

2. **Cabeçalhos de Página**:
   - `.header`: Estiliza o texto como um cabeçalho de página, adequado para títulos principais ou seções destacadas.

3. **Corpo de Texto**:
   - `.body-1`, `.body-2`: Define o tamanho e o estilo do texto para o corpo do conteúdo.

4. **Transformação de Texto**:
   - `.uppercase`: Transforma todo o texto em maiúsculas.
   - `.lowercase`: Transforma todo o texto em minúsculas.
   - `.capitalize`: Transforma a primeira letra de cada palavra em maiúscula.

5. **Espaçamento de Texto**:
   - `.flow-text`: Aumenta dinamicamente ou diminui o tamanho do texto com base no tamanho da viewport.

6. **Alinhamento de Texto**:
   - `.left-align`: Alinha o texto à esquerda.
   - `.right-align`: Alinha o texto à direita.
   - `.center-align`: Alinha o texto ao centro.

7. **Estilos de Texto**:
   - `.italic`: Aplica estilo itálico ao texto.
   - `.truncate`: Trunca o texto se ele for muito longo, exibindo reticências no final.

Essas são apenas algumas das classes de tipografia disponíveis no MaterializeCSS. Você pode aplicá-las diretamente aos elementos HTML em seu projeto para controlar o estilo e o layout do texto de acordo com as necessidades do design. Além disso, você pode combinar essas classes com outras classes de estilo, como cores e sombras, para criar efeitos visuais mais complexos e atraentes.

## 06) MEDIA:
No contexto do MaterializeCSS, o termo "media" geralmente se refere a consultas de mídia, que são usadas para aplicar estilos diferentes com base nas características do dispositivo em que o conteúdo está sendo exibido. Isso é especialmente importante para garantir que o layout e o design do seu site sejam responsivos e se adaptem adequadamente a diferentes tamanhos de tela.

No MaterializeCSS, você pode utilizar classes específicas para definir comportamentos responsivos. Aqui estão algumas das classes de mídia mais comuns:

1. **Ocultar e Exibir Conteúdo em Determinados Tamanhos de Tela**:
   - `.hide-on-small-only`, `.hide-on-med-only`, `.hide-on-large-only`: Oculta o elemento apenas em determinados tamanhos de tela.
   - `.hide-on-small-and-down`, `.hide-on-med-and-down`, `.hide-on-large-and-down`: Oculta o elemento em tamanhos de tela menores ou iguais ao especificado.
   - `.hide-on-small-and-up`, `.hide-on-med-and-up`, `.hide-on-large-and-up`: Oculta o elemento em tamanhos de tela maiores ou iguais ao especificado.
   - `.show-on-small`, `.show-on-medium`, `.show-on-large`: Exibe o elemento apenas em determinados tamanhos de tela.

2. **Grid Responsivo**:
   - `.col s12 m6 l4`: Define o número de colunas que o elemento ocupará em diferentes tamanhos de tela (pequeno, médio e grande).

3. **Alinhamento Responsivo**:
   - `.center-align`, `.left-align`, `.right-align`: Alinha o conteúdo do elemento de forma responsiva.

4. **Tipografia Responsiva**:
   - `.flow-text`: Aumenta ou diminui dinamicamente o tamanho do texto com base no tamanho da viewport.

5. **Imagens Responsivas**:
   - `.responsive-img`: Garante que as imagens sejam dimensionadas corretamente para se ajustar ao tamanho da tela.

Essas são apenas algumas das classes de mídia disponíveis no MaterializeCSS. Ao utilizá-las em conjunto com o sistema de grid e outros componentes responsivos, você pode criar layouts que se adaptam de forma eficaz a uma ampla variedade de dispositivos e tamanhos de tela. Isso garante uma experiência de usuário consistente e de alta qualidade, independentemente do dispositivo utilizado para acessar o seu site.

## 07) TABLE:
No MaterializeCSS, você pode criar tabelas com facilidade usando as classes fornecidas pelo framework. Aqui estão os passos básicos para criar uma tabela:

1. **Estrutura HTML**:
   - Comece criando a estrutura básica da sua tabela no arquivo HTML. Aqui está um exemplo simples:

```html
<table class="striped">
  <thead>
    <tr>
      <th>Nome</th>
      <th>Email</th>
      <th>Telefone</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>João</td>
      <td>joao@example.com</td>
      <td>(12) 3456-7890</td>
    </tr>
    <tr>
      <td>Maria</td>
      <td>maria@example.com</td>
      <td>(98) 7654-3210</td>
    </tr>
  </tbody>
</table>
```

2. **Adicionando Classes do MaterializeCSS**:
   - Você pode adicionar classes do MaterializeCSS para estilizar e tornar sua tabela mais interativa. No exemplo acima, a classe `striped` adiciona cores alternadas às linhas da tabela.

3. **Cabeçalho da Tabela**:
   - Use `<thead>` para definir o cabeçalho da tabela e `<th>` para os títulos das colunas.

4. **Corpo da Tabela**:
   - Use `<tbody>` para o corpo da tabela e `<tr>` para cada linha. Use `<td>` para os dados de cada célula.

Além da classe `striped`, o MaterializeCSS oferece outras classes que você pode adicionar para estilizar ainda mais sua tabela, como `bordered`, `highlight`, `responsive-table` e `centered`. Essas classes adicionam bordas, realces, tornam a tabela responsiva e centralizam o conteúdo, respectivamente.

Você também pode adicionar outras classes do MaterializeCSS conforme necessário para personalizar ainda mais o estilo e o layout da sua tabela, de acordo com as diretrizes de design do seu projeto. Experimente diferentes classes e veja como elas afetam a aparência da sua tabela!

## 08-09) GRID:
No MaterializeCSS, o sistema de grid é uma das características fundamentais que permite criar layouts responsivos de maneira fácil e eficiente. Aqui estão os conceitos básicos para usar o sistema de grid no MaterializeCSS:

### Estrutura Básica do Grid:
1. **Container**:
   - Comece com um elemento `<div>` com a classe `.container` para envolver todo o conteúdo do seu layout. Isso limita a largura do conteúdo e centraliza-o horizontalmente na página.

2. **Linhas e Colunas**:
   - Dentro do container, crie linhas (rows) com a classe `.row`. Cada linha pode conter até 12 colunas.

3. **Colunas**:
   - Adicione colunas (columns) dentro de cada linha usando classes como `.col` seguidas de um número para especificar quantas frações da largura total da linha a coluna deve ocupar. Por exemplo, `.col s12` ocupa 12 colunas, `.col s6` ocupa 6 colunas, e assim por diante.

### Exemplo de Uso:
```html
<div class="container">
  <div class="row">
    <div class="col s12">
      <!-- Conteúdo da coluna -->
    </div>
  </div>
  <div class="row">
    <div class="col s6">
      <!-- Conteúdo da primeira coluna -->
    </div>
    <div class="col s6">
      <!-- Conteúdo da segunda coluna -->
    </div>
  </div>
</div>
```

### Tamanhos de Dispositivos:
- Além dos tamanhos de coluna padrão, você também pode especificar diferentes tamanhos de coluna para diferentes tamanhos de tela. Por exemplo, `.col s12 m6 l4` significa que a coluna ocupará 12 frações de largura em telas pequenas (small), 6 frações de largura em telas médias (medium) e 4 frações de largura em telas grandes (large).

### Modificadores Adicionais:
- O MaterializeCSS também oferece classes adicionais para modificar o comportamento das colunas, como `push`, `pull` e `offset`, que permitem ajustar o posicionamento das colunas dentro da linha.

- O sistema de grid do MaterializeCSS é flexível e poderoso, permitindo que você crie layouts complexos e responsivos com facilidade. 

## 10) HELPERS:
No MaterializeCSS, os "helpers" são classes utilitárias que fornecem funcionalidades adicionais para estilizar e manipular elementos de forma rápida e fácil. Essas classes podem ser aplicadas diretamente aos elementos HTML para obter resultados específicos. Aqui estão alguns exemplos de helpers no MaterializeCSS:

1. **Floats**:
   - `.left`: Alinha o elemento à esquerda.
   - `.right`: Alinha o elemento à direita.
   - `.clearfix`: Limpa o float dos elementos filhos para evitar problemas de layout.

2. **Display**:
   - `.hide`: Esconde o elemento.
   - `.show`: Exibe o elemento.
   - `.invisible`: Torna o elemento invisível (ainda ocupa espaço na página).

3. **Texto**:
   - `.truncate`: Trunca o texto se ele for muito longo, exibindo reticências no final.
   - `.flow-text`: Aumenta dinamicamente ou diminui o tamanho do texto com base no tamanho da viewport.

4. **Espaçamento**:
   - `.margin-<valor>`: Adiciona margem ao elemento (por exemplo, `.margin-top-10` adiciona uma margem superior de 10px).
   - `.padding-<valor>`: Adiciona preenchimento ao elemento (por exemplo, `.padding-left-20` adiciona um preenchimento esquerdo de 20px).
   - `.no-margin`, `.no-padding`: Remove a margem ou o preenchimento do elemento.

5. **Outros**:
   - `.center-align`: Alinha o conteúdo do elemento ao centro horizontalmente.
   - `.valign-wrapper`: Alinha verticalmente o conteúdo do elemento.

Esses são apenas alguns exemplos de helpers disponíveis no MaterializeCSS. Eles são úteis para fazer ajustes rápidos no estilo e no layout dos elementos, economizando tempo e esforço durante o desenvolvimento. 

## 11) COMPONENTS (ICONS):
No MaterializeCSS, os ícones são um componente importante para adicionar elementos visuais e funcionalidades aos seus projetos web. O MaterializeCSS utiliza ícones da biblioteca de ícones do Google Material Icons para fornecer uma ampla variedade de ícones prontos para uso. Aqui está como você pode usar ícones no MaterializeCSS:

### Incluindo a Biblioteca de Ícones do Google Material Icons:
1. **Adicione o Link para a Fonte de Ícones**:
   ```html
   <link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">
   ```

### Utilizando Ícones nos Elementos HTML:
2. **Adicione os Ícones aos Elementos HTML**:
   - Use a classe `.material-icons` em qualquer elemento de texto para incluir um ícone.
   - Dentro do elemento, adicione o nome do ícone entre as tags de abertura e fechamento.

   Exemplo:
   ```html
   <i class="material-icons">account_circle</i>
   ```

### Ícones em Componentes do MaterializeCSS:
3. **Componentes do MaterializeCSS que Aceitam Ícones**:
   - Muitos componentes do MaterializeCSS, como botões, links, cards e barras de navegação, permitem que você adicione ícones.

   Exemplo de um botão com um ícone:
   ```html
   <a class="btn"><i class="material-icons left">cloud</i>Salvar</a>
   ```

### Pesquisando Ícones:
4. **Encontre os Ícones Disponíveis**:
   - Visite o [site do Google Material Icons](https://material.io/resources/icons/) para ver a lista completa de ícones disponíveis e seus nomes.

### Personalizando Ícones:
5. **Personalize a Aparência dos Ícones**:
   - Você pode alterar o tamanho, a cor e outros estilos dos ícones usando CSS.

### Exemplo Completo:
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ícones MaterializeCSS</title>
  <link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0/css/materialize.min.css">
</head>
<body>
  <a class="btn"><i class="material-icons left">cloud</i>Salvar</a>

  <script src="https://cdnjs.cloudflare.com/ajax/libs/materialize/1.0.0/js/materialize.min.js"></script>
</body>
</html>
```

Com essas etapas, você pode facilmente incorporar ícones do Google Material Icons em seus projetos MaterializeCSS para adicionar estilo e funcionalidade.

## 12) COMPONENTS (BREADCRUMBS E PAGINATION):
No MaterializeCSS, você pode usar os componentes de breadcrumbs e pagination para melhorar a navegação em seus sites. Aqui está como você pode usar esses componentes:

### Breadcrumbs:
1. **Estrutura Básica**:
   - Use a estrutura `<nav>` com a classe `.breadcrumb` para criar breadcrumbs.

   Exemplo:
   ```html
   <nav class="breadcrumb">
     <div class="nav-wrapper">
       <div class="col s12">
         <a href="#!" class="breadcrumb">Página Inicial</a>
         <a href="#!" class="breadcrumb">Produtos</a>
         <a href="#!" class="breadcrumb">Categoria 1</a>
         <a href="#!" class="breadcrumb">Produto 1</a>
       </div>
     </div>
   </nav>
   ```

### Pagination:
2. **Estrutura Básica**:
   - Use a estrutura `<ul>` com a classe `.pagination` para criar a paginação.

   Exemplo:
   ```html
   <ul class="pagination">
     <li class="disabled"><a href="#!"><i class="material-icons">chevron_left</i></a></li>
     <li class="active"><a href="#!">1</a></li>
     <li class="waves-effect"><a href="#!">2</a></li>
     <li class="waves-effect"><a href="#!">3</a></li>
     <li class="waves-effect"><a href="#!">4</a></li>
     <li class="waves-effect"><a href="#!">5</a></li>
     <li class="waves-effect"><a href="#!"><i class="material-icons">chevron_right</i></a></li>
   </ul>
   ```

### Personalização:
3. **Personalize os Componentes**:
   - Você pode personalizar a aparência dos breadcrumbs e da paginação usando classes CSS e ícones do Material Icons.

   Exemplo:
   ```css
   .breadcrumb {
     background-color: #fff;
     color: #333;
   }

   .pagination li.active {
     background-color: #26a69a;
   }
   ```

Com essas estruturas e personalizações básicas, você pode adicionar facilmente breadcrumbs e paginação aos seus projetos MaterializeCSS, melhorando a experiência de navegação para os usuários.

## 13) COMPONENTS (BUTTONS):
Os botões são elementos essenciais em qualquer interface de usuário, e no MaterializeCSS eles são fáceis de usar e altamente personalizáveis. Aqui está como você pode criar e personalizar botões usando o MaterializeCSS:

### Estrutura Básica de um Botão:
1. **Elemento HTML**:
   - Use um elemento `<a>` para criar um botão âncora ou um elemento `<button>` para criar um botão de formulário.

   Exemplo:
   ```html
   <a class="waves-effect waves-light btn">Botão</a>
   ```

### Estilos Pré-definidos:
2. **Classes de Estilo**:
   - O MaterializeCSS oferece várias classes predefinidas para estilizar os botões. Algumas das classes comuns incluem:
     - `.btn`: Aplica os estilos básicos do botão.
     - `.waves-effect`: Adiciona um efeito de onda ao clicar no botão.
     - `.waves-light`: Define a cor da onda como clara.
     - `.waves-dark`: Define a cor da onda como escura.

### Tamanhos:
3. **Classes de Tamanho**:
   - Você pode ajustar o tamanho do botão adicionando classes de tamanho, como `.btn-small`, `.btn-large`, etc.

   Exemplo:
   ```html
   <a class="waves-effect waves-light btn-small">Pequeno</a>
   ```

### Cores:
4. **Classes de Cor**:
   - O MaterializeCSS oferece classes para aplicar diferentes cores aos botões, como `.red`, `.blue`, `.green`, etc.

   Exemplo:
   ```html
   <a class="waves-effect waves-light btn red">Botão Vermelho</a>
   ```

### Ícones:
5. **Ícones do Material Icons**:
   - Você pode adicionar ícones aos botões usando a classe `.material-icons` e incluindo o nome do ícone entre as tags de abertura e fechamento do botão.

   Exemplo:
   ```html
   <a class="waves-effect waves-light btn"><i class="material-icons left">cloud</i>Salvar</a>
   ```

### Personalização Adicional:
6. **Personalize com CSS**:
   - Você pode personalizar ainda mais os botões adicionando suas próprias classes CSS ou sobrepondo as classes existentes.

   Exemplo:
   ```css
   .btn-custom {
     background-color: #ff0000;
     color: #fff;
   }
   ```

   ```html
   <a class="waves-effect waves-light btn btn-custom">Botão Personalizado</a>
   ```

Com essas opções de personalização e estilização, você pode criar botões visualmente atraentes e funcionais para seus projetos usando o MaterializeCSS.

## 14) COMPONENTS (COLLECTIONS):
No MaterializeCSS, as coleções são componentes que permitem exibir conjuntos de itens relacionados de forma organizada e compacta. Elas são úteis para exibir listas de elementos como links, ícones e imagens. Aqui estão alguns dos principais componentes de coleção no MaterializeCSS:

### Coleções de Links:
1. **Estrutura Básica**:
   - Use a classe `.collection` para envolver a coleção de links e a classe `.collection-item` para cada item da coleção.

   Exemplo:
   ```html
   <ul class="collection">
     <li class="collection-item">Item 1</li>
     <li class="collection-item">Item 2</li>
     <li class="collection-item">Item 3</li>
   </ul>
   ```

2. **Links com Ícones**:
   - Você pode adicionar ícones aos itens da coleção usando a classe `.icon` e incluindo o nome do ícone entre as tags de abertura e fechamento do item da coleção.

   Exemplo:
   ```html
   <ul class="collection">
     <li class="collection-item"><i class="material-icons">email</i>Email</li>
     <li class="collection-item"><i class="material-icons">phone</i>Telefone</li>
   </ul>
   ```

### Coleções de Imagens:
3. **Coleções de Imagens**:
   - Use a classe `.collection` para envolver a coleção de imagens e a classe `.collection-item` para cada item da coleção.

   Exemplo:
   ```html
   <ul class="collection">
     <li class="collection-item"><img src="imagem1.jpg">Descrição da Imagem 1</li>
     <li class="collection-item"><img src="imagem2.jpg">Descrição da Imagem 2</li>
   </ul>
   ```

### Links de Cabeçalho:
4. **Cabeçalhos de Coleção**:
   - Adicione um cabeçalho à coleção usando a classe `.collection-header`.

   Exemplo:
   ```html
   <ul class="collection with-header">
     <li class="collection-header"><h4>Cabeçalho da Coleção</h4></li>
     <li class="collection-item">Item 1</li>
     <li class="collection-item">Item 2</li>
   </ul>
   ```

### Personalização:
5. **Personalize com CSS**:
   - Você pode personalizar a aparência das coleções usando classes CSS adicionais ou criando suas próprias regras de estilo.

Com esses componentes de coleção, você pode exibir facilmente conjuntos de itens relacionados em seu site ou aplicativo web de maneira organizada e visualmente atraente usando o MaterializeCSS.

## 15) COMPONENTS (BADGES):
No MaterializeCSS, os badges são pequenos elementos visuais que podem ser usados para exibir informações como notificações, contagens, status, entre outros. Eles são úteis para chamar a atenção do usuário para determinados elementos ou para indicar algum tipo de informação relevante. Aqui está como você pode usar os badges no MaterializeCSS:

### Estrutura Básica de um Badge:
1. **Elemento HTML**:
   - Use um elemento `<span>` com a classe `.badge` para criar um badge.

   Exemplo:
   ```html
   <span class="badge">4</span>
   ```

### Estilos e Cores:
2. **Cores do Badge**:
   - Você pode aplicar diferentes cores aos badges usando classes como `.new`, `.red`, `.blue`, `.green`, entre outras.

   Exemplo:
   ```html
   <span class="badge red">7</span>
   ```

### Alinhamento e Posicionamento:
3. **Alinhamento e Posicionamento**:
   - Os badges podem ser alinhados e posicionados de várias maneiras usando classes de alinhamento e posicionamento do MaterializeCSS.

   Exemplo:
   ```html
   <span class="new badge" data-badge-caption="Nova">1</span>
   ```

### Notificações:
4. **Notificações**:
   - Além de exibir números, você também pode adicionar texto personalizado aos badges usando o atributo `data-badge-caption`.

   Exemplo:
   ```html
   <span class="badge" data-badge-caption="Mensagens">10</span>
   ```

### Personalização Adicional:
5. **Personalize com CSS**:
   - Você pode personalizar ainda mais os badges adicionando suas próprias classes CSS ou sobrepondo as classes existentes.

   Exemplo:
   ```css
   .custom-badge {
     background-color: #ff0000;
     color: #fff;
   }
   ```

   ```html
   <span class="badge custom-badge">Personalizado</span>
   ```

Com esses exemplos e opções de personalização, você pode usar badges de forma eficaz no MaterializeCSS para realçar informações importantes e melhorar a experiência do usuário em seu site ou aplicativo.

## 16) COMPONENTS (PRELOADER):
No MaterializeCSS, os preloader são componentes que indicam visualmente que um conteúdo está sendo carregado ou processado. Eles são úteis para informar aos usuários que algo está acontecendo nos bastidores e que eles precisam aguardar um momento. Aqui está como você pode usar os preloaders no MaterializeCSS:

### Estrutura Básica de um Preloader:
1. **Elemento HTML**:
   - Use a estrutura HTML apropriada para criar um preloader.

   Exemplo:
   ```html
   <div class="preloader-wrapper">
     <div class="spinner-layer">
       <div class="circle-clipper left">
         <div class="circle"></div>
       </div>
       <div class="gap-patch">
         <div class="circle"></div>
       </div>
       <div class="circle-clipper right">
         <div class="circle"></div>
       </div>
     </div>
   </div>
   ```

### Estilos e Cores:
2. **Cores do Preloader**:
   - Você pode aplicar diferentes cores ao preloader usando classes de cores do MaterializeCSS.

   Exemplo:
   ```html
   <div class="preloader-wrapper active">
     <div class="spinner-layer spinner-blue-only">
       <div class="circle-clipper left">
         <div class="circle"></div>
       </div>
       <div class="gap-patch">
         <div class="circle"></div>
       </div>
       <div class="circle-clipper right">
         <div class="circle"></div>
       </div>
     </div>
   </div>
   ```

### Tamanhos:
3. **Tamanhos do Preloader**:
   - O MaterializeCSS oferece classes para controlar o tamanho do preloader, como `.big`, `.small`, etc.

   Exemplo:
   ```html
   <div class="preloader-wrapper small active">
     <!-- Estrutura do Preloader -->
   </div>
   ```

### Personalização Adicional:
4. **Personalize com CSS**:
   - Você pode personalizar ainda mais os preloaders adicionando suas próprias classes CSS ou sobrepondo as classes existentes.

   Exemplo:
   ```css
   .custom-preloader {
     /* Personalize aqui */
   }
   ```

   ```html
   <div class="preloader-wrapper custom-preloader active">
     <!-- Estrutura do Preloader -->
   </div>
   ```

Com essas opções, você pode adicionar preloaders aos seus projetos MaterializeCSS para indicar visualmente o progresso do carregamento de conteúdo e melhorar a experiência do usuário.

## 17-21) COMPONENTS (NAVBAR):
A Navbar é um componente crucial em muitos sites e aplicativos, pois fornece uma maneira de navegar entre diferentes partes do site. No MaterializeCSS, a Navbar é fácil de implementar e altamente personalizável. Aqui está como você pode criar e personalizar uma Navbar usando o MaterializeCSS:

### Estrutura Básica de uma Navbar:
1. **Elemento HTML**:
   - Use a estrutura HTML apropriada para criar uma Navbar.

   Exemplo:
   ```html
   <nav>
     <div class="nav-wrapper">
       <a href="#!" class="brand-logo">Logo</a>
       <ul class="right hide-on-med-and-down">
         <li><a href="#">Link 1</a></li>
         <li><a href="#">Link 2</a></li>
         <li><a href="#">Link 3</a></li>
       </ul>
     </div>
   </nav>
   ```

### Estilos e Cores:
2. **Cores da Navbar**:
   - Você pode aplicar diferentes cores à Navbar usando classes de cores do MaterializeCSS.

   Exemplo:
   ```html
   <nav>
     <div class="nav-wrapper red">
       <!-- Conteúdo da Navbar -->
     </div>
   </nav>
   ```

### Ícones e Dropdowns:
3. **Ícones e Dropdowns**:
   - Você pode adicionar ícones e dropdowns à Navbar usando classes específicas do MaterializeCSS.

   Exemplo:
   ```html
   <nav>
     <div class="nav-wrapper">
       <a href="#!" class="brand-logo">Logo</a>
       <ul class="right hide-on-med-and-down">
         <li><a href="#">Link 1</a></li>
         <li><a href="#">Link 2</a></li>
         <li><a href="#">Link 3</a></li>
         <li><a href="#"><i class="material-icons">search</i></a></li>
         <li><a href="#"><i class="material-icons">more_vert</i></a></li>
       </ul>
     </div>
   </nav>
   ```

### Navbar Fixa e Responsiva:
4. **Navbar Fixa e Responsiva**:
   - Você pode fazer a Navbar ficar fixa na parte superior da página e torná-la responsiva para tamanhos menores de tela usando classes específicas do MaterializeCSS.

   Exemplo:
   ```html
   <nav class="nav-extended">
     <div class="nav-wrapper">
       <!-- Conteúdo da Navbar -->
     </div>
     <div class="nav-content">
       <!-- Conteúdo adicional da Navbar -->
     </div>
   </nav>
   ```

### Personalização Adicional:
5. **Personalize com CSS**:
   - Você pode personalizar ainda mais a aparência da Navbar adicionando suas próprias classes CSS ou sobrepondo as classes existentes.

   Exemplo:
   ```css
   .custom-navbar {
     /* Personalize aqui */
   }
   ```

   ```html
   <nav class="custom-navbar">
     <!-- Conteúdo da Navbar -->
   </nav>
   ```

Com essas opções de personalização e estilização, você pode criar Navbars altamente personalizadas e funcionais para seus projetos usando o MaterializeCSS.

## 22) COMPONENTS (FOOTER):
O footer, ou rodapé, é uma parte importante de qualquer layout de página da web, pois geralmente contém informações adicionais, links de navegação secundários, informações de contato, entre outros. No MaterializeCSS, criar um footer é simples e altamente personalizável. Aqui está como você pode criar e personalizar um footer usando o MaterializeCSS:

### Estrutura Básica de um Footer:
1. **Elemento HTML**:
   - Use a estrutura HTML apropriada para criar um footer.

   Exemplo:
   ```html
   <footer class="page-footer">
     <div class="container">
       <div class="row">
         <div class="col s12">
           <h5 class="white-text">Sobre</h5>
           <p class="grey-text text-lighten-4">Informações sobre a empresa ou o site.</p>
         </div>
       </div>
     </div>
     <div class="footer-content">
       <div class="container">
         <div class="row">
           <div class="col l6 s12">
             <h5 class="white-text">Links</h5>
             <ul>
               <li><a class="grey-text text-lighten-3" href="#!">Link 1</a></li>
               <li><a class="grey-text text-lighten-3" href="#!">Link 2</a></li>
               <li><a class="grey-text text-lighten-3" href="#!">Link 3</a></li>
             </ul>
           </div>
         </div>
       </div>
     </div>
     <div class="footer-bottom">
       <div class="container">
         <div class="row">
           <div class="col s12">
             <p class="grey-text text-lighten-4">© 2024 Nome da Empresa. Todos os direitos reservados.</p>
           </div>
         </div>
       </div>
     </div>
   </footer>
   ```

### Estilos e Cores:
2. **Cores do Footer**:
   - Você pode aplicar diferentes cores ao footer usando classes de cores do MaterializeCSS.

   Exemplo:
   ```html
   <footer class="page-footer teal">
     <!-- Conteúdo do footer -->
   </footer>
   ```

### Conteúdo Adicional:
3. **Conteúdo Adicional**:
   - Você pode adicionar conteúdo adicional ao footer, como links, informações de contato, logotipos de redes sociais, etc.

### Personalização Adicional:
4. **Personalize com CSS**:
   - Você pode personalizar ainda mais a aparência do footer adicionando suas próprias classes CSS ou sobrepondo as classes existentes.

   Exemplo:
   ```css
   .custom-footer {
     /* Personalize aqui */
   }
   ```

   ```html
   <footer class="page-footer custom-footer">
     <!-- Conteúdo do footer -->
   </footer>
   ```

Com essas opções de personalização e estilização, você pode criar footers visualmente atraentes e funcionais para seus projetos usando o MaterializeCSS.

## 23-26) COMPONENTS (CARD):
Os cartões (cards) são componentes versáteis e amplamente utilizados para exibir informações de forma organizada e visualmente atraente. No MaterializeCSS, os cards são fáceis de criar e personalizar. Aqui está como você pode criar e estilizar um card usando o MaterializeCSS:

### Estrutura Básica de um Card:
1. **Elemento HTML**:
   - Use a estrutura HTML apropriada para criar um card.

   Exemplo:
   ```html
   <div class="card">
     <div class="card-content">
       <span class="card-title">Título do Card</span>
       <p>Conteúdo do card.</p>
     </div>
   </div>
   ```

### Estilos e Cores:
2. **Cores do Card**:
   - Você pode aplicar diferentes cores ao card usando classes de cores do MaterializeCSS.

   Exemplo:
   ```html
   <div class="card blue">
     <!-- Conteúdo do card -->
   </div>
   ```

### Imagens e Ícones:
3. **Imagens e Ícones**:
   - Você pode adicionar imagens e ícones aos cards para torná-los mais visualmente atraentes.

   Exemplo com imagem:
   ```html
   <div class="card">
     <div class="card-image">
       <img src="imagem.jpg">
       <span class="card-title">Título da Imagem</span>
     </div>
     <div class="card-content">
       <p>Conteúdo do card.</p>
     </div>
   </div>
   ```

   Exemplo com ícone:
   ```html
   <div class="card">
     <div class="card-content">
       <i class="material-icons">face</i>
       <span class="card-title">Título do Ícone</span>
       <p>Conteúdo do card.</p>
     </div>
   </div>
   ```

### Ações e Botões:
4. **Ações e Botões**:
   - Você pode adicionar botões e ações aos cards para interatividade.

   Exemplo com botão:
   ```html
   <div class="card">
     <div class="card-content">
       <span class="card-title">Título do Card</span>
       <p>Conteúdo do card.</p>
     </div>
     <div class="card-action">
       <a href="#">Ação</a>
     </div>
   </div>
   ```

### Personalização Adicional:
5. **Personalize com CSS**:
   - Você pode personalizar ainda mais a aparência do card adicionando suas próprias classes CSS ou sobrepondo as classes existentes.

   Exemplo:
   ```css
   .custom-card {
     /* Personalize aqui */
   }
   ```

   ```html
   <div class="card custom-card">
     <!-- Conteúdo do card -->
   </div>
   ```

Com essas opções de personalização e estilização, você pode criar cartões visualmente atraentes e funcionais para seus projetos usando o MaterializeCSS.

## 27-29) COMPONENTS (CHIPS):
Os chips são componentes versáteis que representam uma entrada, atributo ou ação. Eles podem conter texto, ícones ou imagens e são úteis para representar tags, contatos, filtros, entre outros. No MaterializeCSS, os chips são fáceis de criar e personalizar. Aqui está como você pode criar e estilizar chips usando o MaterializeCSS:

### Estrutura Básica de um Chip:
1. **Elemento HTML**:
   - Use a estrutura HTML apropriada para criar um chip.

   Exemplo:
   ```html
   <div class="chip">
     Texto do Chip
   </div>
   ```

### Estilos e Cores:
2. **Cores do Chip**:
   - Você pode aplicar diferentes cores aos chips usando classes de cores do MaterializeCSS.

   Exemplo:
   ```html
   <div class="chip teal white-text">
     Texto do Chip
   </div>
   ```

### Ícones e Imagens:
3. **Ícones e Imagens**:
   - Você pode adicionar ícones ou imagens aos chips para torná-los mais informativos.

   Exemplo com ícone:
   ```html
   <div class="chip">
     <i class="material-icons">face</i> Nome do Contato
   </div>
   ```

   Exemplo com imagem:
   ```html
   <div class="chip">
     <img src="imagem.jpg" alt="Imagem">
     Nome da Imagem
   </div>
   ```

### Remoção de Chips:
4. **Remoção de Chips**:
   - Você pode adicionar funcionalidade para remover chips clicando em um botão de remoção.

   Exemplo com botão de remoção:
   ```html
   <div class="chip">
     Texto do Chip
     <i class="material-icons close">close</i>
   </div>
   ```

### Eventos e Ações:
5. **Eventos e Ações**:
   - Você pode adicionar eventos e ações aos chips para interatividade.

### Personalização Adicional:
6. **Personalize com CSS**:
   - Você pode personalizar ainda mais a aparência dos chips adicionando suas próprias classes CSS ou sobrepondo as classes existentes.

   Exemplo:
   ```css
   .custom-chip {
     /* Personalize aqui */
   }
   ```

   ```html
   <div class="chip custom-chip">
     Texto do Chip
   </div>
   ```

Com essas opções de personalização e estilização, você pode criar chips visualmente atraentes e funcionais para seus projetos usando o MaterializeCSS.

## 30) PULSE:
Para adicionar um efeito de pulsação (pulse) a um elemento no MaterializeCSS, você pode usar a classe CSS `pulse`. Este efeito cria uma animação sutil que faz o elemento expandir e contrair repetidamente, criando um efeito de pulsação. Aqui está como você pode aplicar o efeito de pulsação a um elemento:

```html
<a class="btn pulse">Botão Pulsante</a>
```

Neste exemplo, um botão `<a>` está sendo estilizado com a classe `btn` para parecer um botão e a classe `pulse` para adicionar o efeito de pulsação. Você pode aplicar este efeito a qualquer elemento HTML, como botões, ícones, imagens, etc., simplesmente adicionando a classe `pulse`.

## 31-33) COMPONENTS (FORMS):
Os formulários são uma parte fundamental de muitos sites e aplicativos, permitindo que os usuários insiram e enviem dados. No MaterializeCSS, os formulários são fáceis de criar e estilizar. Aqui está como você pode criar e estilizar formulários usando o MaterializeCSS:

### Estrutura Básica de um Formulário:
1. **Elemento HTML**:
   - Use a estrutura HTML apropriada para criar um formulário.

   Exemplo:
   ```html
   <form>
     <div class="input-field">
       <input id="nome" type="text" class="validate">
       <label for="nome">Nome</label>
     </div>
     <div class="input-field">
       <input id="email" type="email" class="validate">
       <label for="email">Email</label>
     </div>
     <button class="btn waves-effect waves-light" type="submit" name="action">Enviar</button>
   </form>
   ```

### Estilos e Cores:
2. **Estilos de Inputs**:
   - O MaterializeCSS fornece estilos predefinidos para inputs, como caixas de texto, e-mails, senhas, etc.

   Exemplo:
   ```html
   <div class="input-field">
     <input id="password" type="password" class="validate">
     <label for="password">Senha</label>
   </div>
   ```

### Selects e Dropdowns:
3. **Selects e Dropdowns**:
   - Você pode criar selects e dropdowns estilizados usando classes específicas do MaterializeCSS.

   Exemplo de select:
   ```html
   <div class="input-field">
     <select>
       <option value="" disabled selected>Escolha sua opção</option>
       <option value="1">Opção 1</option>
       <option value="2">Opção 2</option>
       <option value="3">Opção 3</option>
     </select>
     <label>Seleção</label>
   </div>
   ```

### Textareas:
4. **Textareas**:
   - Você pode estilizar textareas usando a classe `.materialize-textarea`.

   Exemplo:
   ```html
   <div class="input-field">
     <textarea id="textarea1" class="materialize-textarea"></textarea>
     <label for="textarea1">Textarea</label>
   </div>
   ```

### Checkbox e Radio Buttons:
5. **Checkbox e Radio Buttons**:
   - O MaterializeCSS oferece estilos predefinidos para checkbox e radio buttons.

   Exemplo de checkbox:
   ```html
   <label>
     <input type="checkbox" />
     <span>Checkbox</span>
   </label>
   ```

   Exemplo de radio button:
   ```html
   <label>
     <input name="group1" type="radio" />
     <span>Radio</span>
   </label>
   ```

### Personalização Adicional:
6. **Personalize com CSS**:
   - Você pode personalizar ainda mais a aparência dos formulários adicionando suas próprias classes CSS ou sobrepondo as classes existentes.

Com essas opções de personalização e estilização, você pode criar formulários visualmente atraentes e funcionais para seus projetos usando o MaterializeCSS.

## 34) FORMS (SELECT, DATEPICKER E TIMEPICKER):
Para criar selects, datepickers e timepickers no MaterializeCSS, você pode usar os componentes específicos fornecidos pela biblioteca. Aqui está como você pode adicionar esses componentes aos seus formulários:

### Selects:
1. **Elemento HTML**:
   - Use a estrutura HTML apropriada para criar um select.

   Exemplo:
   ```html
   <div class="input-field">
     <select>
       <option value="" disabled selected>Escolha sua opção</option>
       <option value="1">Opção 1</option>
       <option value="2">Opção 2</option>
       <option value="3">Opção 3</option>
     </select>
     <label>Seleção</label>
   </div>
   ```

### Datepicker:
2. **Inicialização do Datepicker**:
   - Inclua o script JavaScript e inicialize o datepicker usando JavaScript.

   Exemplo:
   ```html
   <input type="text" class="datepicker">
   ```

   ```javascript
   document.addEventListener('DOMContentLoaded', function() {
     var elems = document.querySelectorAll('.datepicker');
     var instances = M.Datepicker.init(elems, options);
   });
   ```

### Timepicker:
3. **Inicialização do Timepicker**:
   - Inclua o script JavaScript e inicialize o timepicker usando JavaScript.

   Exemplo:
   ```html
   <input type="text" class="timepicker">
   ```

   ```javascript
   document.addEventListener('DOMContentLoaded', function() {
     var elems = document.querySelectorAll('.timepicker');
     var instances = M.Timepicker.init(elems, options);
   });
   ```

### Personalização Adicional:
4. **Personalize com Opções**:
   - Você pode personalizar o comportamento dos selects, datepickers e timepickers usando várias opções disponíveis na documentação do MaterializeCSS.

Com essas opções e a documentação detalhada do MaterializeCSS, você pode adicionar facilmente selects, datepickers e timepickers aos seus formulários e personalizá-los de acordo com suas necessidades.

## 35) FORMS (RADIO, CHECKBOX, INPUT FILE E RANGE):
Para adicionar radio buttons, checkboxes, input file e range inputs aos seus formulários no MaterializeCSS, você pode usar os componentes específicos fornecidos pela biblioteca. Aqui está como você pode adicionar esses componentes aos seus formulários:

### Radio Buttons:
1. **Elemento HTML**:
   - Use a estrutura HTML apropriada para criar radio buttons.

   Exemplo:
   ```html
   <p>
     <label>
       <input name="group1" type="radio" />
       <span>Opção 1</span>
     </label>
   </p>
   <p>
     <label>
       <input name="group1" type="radio" />
       <span>Opção 2</span>
     </label>
   </p>
   ```

### Checkboxes:
2. **Elemento HTML**:
   - Use a estrutura HTML apropriada para criar checkboxes.

   Exemplo:
   ```html
   <p>
     <label>
       <input type="checkbox" />
       <span>Opção 1</span>
     </label>
   </p>
   <p>
     <label>
       <input type="checkbox" />
       <span>Opção 2</span>
     </label>
   </p>
   ```

### Input File:
3. **Elemento HTML**:
   - Use a estrutura HTML apropriada para criar um input file.

   Exemplo:
   ```html
   <div class="file-field input-field">
     <div class="btn">
       <span>Arquivo</span>
       <input type="file">
     </div>
     <div class="file-path-wrapper">
       <input class="file-path validate" type="text">
     </div>
   </div>
   ```

### Range Inputs:
4. **Elemento HTML**:
   - Use a estrutura HTML apropriada para criar um range input.

   Exemplo:
   ```html
   <p class="range-field">
     <input type="range" id="test5" min="0" max="100" />
   </p>
   ```

Com esses exemplos, você pode adicionar facilmente radio buttons, checkboxes, input file e range inputs aos seus formulários no MaterializeCSS. Personalize conforme necessário e consulte a documentação do MaterializeCSS para mais detalhes e opções de personalização.

## 36) JAVASCRIPT (CAROUSEL):
Para criar um carousel (carrossel) usando JavaScript no MaterializeCSS, você pode usar o componente de carousel fornecido pela biblioteca. Aqui está como você pode configurar um carousel usando JavaScript:

### Estrutura Básica do Carousel:
1. **Elemento HTML**:
   - Use a estrutura HTML apropriada para criar um carousel.

   Exemplo:
   ```html
   <div class="carousel">
     <a class="carousel-item" href="#one!"><img src="imagem1.jpg"></a>
     <a class="carousel-item" href="#two!"><img src="imagem2.jpg"></a>
     <a class="carousel-item" href="#three!"><img src="imagem3.jpg"></a>
   </div>
   ```

### Inicialização do Carousel:
2. **Inicialização com JavaScript**:
   - Inclua o script JavaScript e inicialize o carousel usando JavaScript.

   Exemplo:
   ```html
   <script>
     document.addEventListener('DOMContentLoaded', function() {
       var elems = document.querySelectorAll('.carousel');
       var instances = M.Carousel.init(elems, options);
     });
   </script>
   ```

### Opções de Configuração:
3. **Opções de Configuração**:
   - Você pode configurar várias opções do carousel, como duração da transição, distância do slide, etc.

   Exemplo de opções:
   ```javascript
   var options = {
     fullWidth: true,
     indicators: true
   };
   ```

   - `fullWidth`: Define se o carousel ocupa toda a largura do contêiner.
   - `indicators`: Define se os indicadores de slide são exibidos.

### Controles Manuais:
4. **Controles Manuais**:
   - Você pode adicionar botões de controle manual para avançar ou retroceder os slides.

   Exemplo de controles manuais:
   ```html
   <a class="carousel-control-prev" href="#carousel" role="button" data-slide="prev">
     <i class="material-icons">chevron_left</i>
   </a>
   <a class="carousel-control-next" href="#carousel" role="button" data-slide="next">
     <i class="material-icons">chevron_right</i>
   </a>
   ```

Com essas etapas, você pode configurar facilmente um carousel funcional usando JavaScript no MaterializeCSS. Personalize conforme necessário e consulte a documentação do MaterializeCSS para mais detalhes e opções avançadas.

## 37) JAVASCRIPT (PARALLAX):
Para adicionar um efeito de parallax a elementos no MaterializeCSS, você pode usar o componente de parallax fornecido pela biblioteca. O parallax cria um efeito em que diferentes camadas de elementos se movem em velocidades diferentes, criando uma sensação de profundidade e imersão. Aqui está como você pode configurar um efeito de parallax usando JavaScript:

### Estrutura Básica do Parallax:
1. **Elemento HTML**:
   - Use a estrutura HTML apropriada para criar um elemento com efeito de parallax.

   Exemplo:
   ```html
   <div class="parallax-container">
     <div class="parallax"><img src="imagem.jpg"></div>
   </div>
   ```

### Inicialização do Parallax:
2. **Inicialização com JavaScript**:
   - Inclua o script JavaScript e inicialize o parallax usando JavaScript.

   Exemplo:
   ```html
   <script>
     document.addEventListener('DOMContentLoaded', function() {
       var elems = document.querySelectorAll('.parallax');
       var instances = M.Parallax.init(elems);
     });
   </script>
   ```

### Controle de Velocidade:
3. **Controle de Velocidade**:
   - Você pode ajustar a velocidade do efeito de parallax usando a opção `responsiveThreshold`.

   Exemplo:
   ```javascript
   var options = {
     responsiveThreshold: 0
   };

   document.addEventListener('DOMContentLoaded', function() {
     var elems = document.querySelectorAll('.parallax');
     var instances = M.Parallax.init(elems, options);
   });
   ```

   - `responsiveThreshold`: Define o limite de largura da tela para ativar o parallax.

### Parallax em Vários Elementos:
4. **Parallax em Vários Elementos**:
   - Você pode aplicar o efeito de parallax a vários elementos em uma página.

   Exemplo:
   ```html
   <div class="parallax-container">
     <div class="parallax"><img src="imagem1.jpg"></div>
   </div>
   <div class="parallax-container">
     <div class="parallax"><img src="imagem2.jpg"></div>
   </div>
   ```

Com essas etapas, você pode adicionar facilmente o efeito de parallax a elementos no MaterializeCSS. Personalize conforme necessário e consulte a documentação do MaterializeCSS para mais detalhes e opções avançadas.

## 38) JAVASCRIPT (WAVES):
Para adicionar o efeito Waves (ondas) a elementos clicáveis no MaterializeCSS, você pode usar a função `Waves.attach()` fornecida pela biblioteca. Este efeito cria uma animação de onda que se espalha a partir do ponto de clique, dando feedback visual ao usuário. Aqui está como você pode configurar o efeito Waves usando JavaScript:

### Inicialização do Efeito Waves:
1. **Inicialização com JavaScript**:
   - Inclua o script JavaScript e inicialize o efeito Waves usando JavaScript.

   Exemplo:
   ```html
   <script>
     document.addEventListener('DOMContentLoaded', function() {
       Waves.attach('.btn', ['waves-light']); // Inicializa o efeito Waves para botões com classe 'btn'
       Waves.init(); // Inicializa o efeito Waves globalmente
     });
   </script>
   ```

### Opções de Configuração:
2. **Opções de Configuração**:
   - Você pode configurar várias opções do efeito Waves, como cor, duração da animação, etc.

   Exemplo de opções:
   ```javascript
   Waves.init({
     duration: 500,
     delay: 200
   });
   ```

   - `duration`: Define a duração da animação em milissegundos.
   - `delay`: Define o atraso antes do início da animação em milissegundos.

### Adicionando Classes de Efeito:
3. **Adicionando Classes de Efeito**:
   - Você pode adicionar classes específicas de efeito para personalizar o efeito Waves.

   Exemplo:
   ```html
   <a class="waves-effect waves-light btn">Botão</a>
   ```

   - `waves-effect`: Adiciona o efeito de onda ao elemento.
   - `waves-light`: Define a cor da onda como branca.

### Personalização Adicional:
4. **Personalize com CSS**:
   - Você pode personalizar ainda mais o efeito Waves adicionando suas próprias classes CSS ou sobrepondo as classes existentes.

Com essas opções de configuração, você pode adicionar facilmente o efeito Waves a elementos clicáveis no MaterializeCSS. Personalize conforme necessário e consulte a documentação do MaterializeCSS para mais detalhes e opções avançadas.

## 40) JAVASCRIPT (DROPDOWN):
Para adicionar funcionalidade de dropdown (menu suspenso) a elementos no MaterializeCSS, você pode usar o componente de dropdown fornecido pela biblioteca. Aqui está como você pode configurar um dropdown usando JavaScript:

### Inicialização do Dropdown:
1. **Inicialização com JavaScript**:
   - Inclua o script JavaScript e inicialize o dropdown usando JavaScript.

   Exemplo:
   ```html
   <script>
     document.addEventListener('DOMContentLoaded', function() {
       var elems = document.querySelectorAll('.dropdown-trigger');
       var instances = M.Dropdown.init(elems, options);
     });
   </script>
   ```

### Opções de Configuração:
2. **Opções de Configuração**:
   - Você pode configurar várias opções do dropdown, como alinhamento, direção de abertura, etc.

   Exemplo de opções:
   ```javascript
   var options = {
     alignment: 'right',
     coverTrigger: false
   };
   ```

   - `alignment`: Define o alinhamento do dropdown em relação ao elemento de gatilho ('left', 'right').
   - `coverTrigger`: Define se o dropdown deve cobrir o elemento de gatilho ou não.

### Gatilhos de Dropdown:
3. **Gatilhos de Dropdown**:
   - Adicione a classe `.dropdown-trigger` ao elemento que será o gatilho do dropdown.

   Exemplo:
   ```html
   <a class='dropdown-trigger btn' href='#' data-target='dropdown1'>Dropdown</a>
   ```

   - `data-target`: Especifica o ID do dropdown que será acionado.

### Estrutura do Dropdown:
4. **Estrutura HTML**:
   - Crie a estrutura HTML do dropdown.

   Exemplo:
   ```html
   <ul id='dropdown1' class='dropdown-content'>
     <li><a href='#'>Item 1</a></li>
     <li><a href='#'>Item 2</a></li>
     <li><a href='#'>Item 3</a></li>
   </ul>
   ```

   - Certifique-se de que o ID do dropdown (nesse caso, `dropdown1`) corresponda ao `data-target` definido no elemento de gatilho.

Com essas etapas, você pode configurar facilmente um dropdown funcional usando JavaScript no MaterializeCSS. Personalize conforme necessário e consulte a documentação do MaterializeCSS para mais detalhes e opções avançadas.

## 41) JAVASCRIPT (MATERIALBOX & SLIDER):
Para adicionar funcionalidade de Materialbox (lightbox) e Slider (carrossel de imagens) a elementos no MaterializeCSS, você pode usar os componentes fornecidos pela biblioteca. Aqui está como configurar cada um deles usando JavaScript:

### Materialbox (Lightbox):
1. **Inicialização com JavaScript**:
   - Inclua o script JavaScript e inicialize o Materialbox usando JavaScript.

   Exemplo:
   ```html
   <script>
     document.addEventListener('DOMContentLoaded', function() {
       var elems = document.querySelectorAll('.materialboxed');
       var instances = M.Materialbox.init(elems, options);
     });
   </script>
   ```

### Opções de Configuração do Materialbox:
2. **Opções de Configuração**:
   - Você pode configurar várias opções do Materialbox, como a duração da animação, o ícone de fechar, etc.

   Exemplo de opções:
   ```javascript
   var options = {
     inDuration: 300,
     outDuration: 200,
     onCloseEnd: function() {
       console.log('Materialbox fechado');
     }
   };
   ```

### Estrutura HTML do Materialbox:
3. **Estrutura HTML**:
   - Adicione a classe `.materialboxed` aos elementos de imagem que deseja que tenham a funcionalidade de Materialbox.

   Exemplo:
   ```html
   <img class="materialboxed" src="imagem.jpg" alt="Imagem">
   ```

### Slider (Carrossel de Imagens):
1. **Inicialização com JavaScript**:
   - Inclua o script JavaScript e inicialize o Slider usando JavaScript.

   Exemplo:
   ```html
   <script>
     document.addEventListener('DOMContentLoaded', function() {
       var elems = document.querySelectorAll('.slider');
       var instances = M.Slider.init(elems, options);
     });
   </script>
   ```

### Opções de Configuração do Slider:
2. **Opções de Configuração**:
   - Você pode configurar várias opções do Slider, como a duração da transição, indicadores, etc.

   Exemplo de opções:
   ```javascript
   var options = {
     indicators: true,
     interval: 3000
   };
   ```

### Estrutura HTML do Slider:
3. **Estrutura HTML**:
   - Crie a estrutura HTML do Slider.

   Exemplo:
   ```html
   <div class="slider">
     <ul class="slides">
       <li><img src="imagem1.jpg"></li>
       <li><img src="imagem2.jpg"></li>
       <li><img src="imagem3.jpg"></li>
     </ul>
   </div>
   ```

Com essas etapas, você pode configurar facilmente um Materialbox (lightbox) e Slider (carrossel de imagens) usando JavaScript no MaterializeCSS. Personalize conforme necessário e consulte a documentação do MaterializeCSS para mais detalhes e opções avançadas.

## 42) JAVASCRIPT (TRANSITIONS):
Para adicionar transições de página suaves entre diferentes elementos ou páginas no MaterializeCSS, você pode usar a biblioteca `smoothState.js`. Esta biblioteca oferece uma maneira fácil de adicionar transições de página usando AJAX, mantendo a navegação suave e rápida.

Aqui está como você pode configurar transições de página usando `smoothState.js`:

### Configuração do smoothState.js:
1. **Inclua a Biblioteca**:
   - Faça o download da biblioteca `smoothState.js` e inclua-a no seu projeto.

   Exemplo:
   ```html
   <script src="smoothState.min.js"></script>
   ```

2. **Inicialize o smoothState.js**:
   - Inicialize o `smoothState.js` para adicionar transições de página suaves.

   Exemplo:
   ```html
   <script>
     $(function(){
       $('#main').smoothState();
     });
   </script>
   ```

### Estrutura HTML:
3. **Estrutura HTML**:
   - Estruture seu HTML de forma que as transições de página sejam aplicadas a elementos específicos.

   Exemplo:
   ```html
   <div id="main" class="m-scene">
     <div class="m-landing scene_element scene_element--fadein">
       <!-- Conteúdo da página -->
     </div>
   </div>
   ```

### Estilos CSS (Opcional):
4. **Estilos CSS**:
   - Adicione estilos CSS para personalizar a aparência das transições de página, se necessário.

   Exemplo:
   ```css
   .m-landing {
     /* Estilos personalizados */
   }
   ```

### Opções de Configuração (Opcional):
5. **Opções de Configuração**:
   - Você pode configurar várias opções do `smoothState.js` para ajustar o comportamento das transições de página.

   Exemplo de opções:
   ```javascript
   $('#main').smoothState({
     onStart: {
       duration: 500,
       render: function () {
         $('#page-wrapper').addClass('is-exiting');
       }
     }
   });
   ```

Com essas etapas, você pode adicionar facilmente transições de página suaves entre diferentes elementos ou páginas no seu projeto MaterializeCSS usando `smoothState.js`. Personalize conforme necessário e consulte a documentação do `smoothState.js` para mais detalhes e opções avançadas.

## 43) JAVASCRIPT (COLLAPSIBLE):
Para adicionar funcionalidade de collapsible (retrátil) a elementos no MaterializeCSS, você pode usar o componente de collapsible fornecido pela biblioteca. Aqui está como configurar um collapsible usando JavaScript:

### Inicialização do Collapsible:
1. **Inicialização com JavaScript**:
   - Inclua o script JavaScript e inicialize o collapsible usando JavaScript.

   Exemplo:
   ```html
   <script>
     document.addEventListener('DOMContentLoaded', function() {
       var elems = document.querySelectorAll('.collapsible');
       var instances = M.Collapsible.init(elems, options);
     });
   </script>
   ```

### Opções de Configuração do Collapsible:
2. **Opções de Configuração**:
   - Você pode configurar várias opções do collapsible, como a duração da animação, o ícone de expansão, etc.

   Exemplo de opções:
   ```javascript
   var options = {
     accordion: false,
     onOpenStart: function() {
       console.log('Collapsible aberto');
     }
   };
   ```

   - `accordion`: Define se apenas um item do collapsible pode estar aberto por vez (`true` para sim, `false` para não).
   - `onOpenStart`: Callback chamado quando um item do collapsible é aberto.

### Estrutura HTML do Collapsible:
3. **Estrutura HTML**:
   - Crie a estrutura HTML do collapsible.

   Exemplo:
   ```html
   <ul class="collapsible">
     <li>
       <div class="collapsible-header">Item 1</div>
       <div class="collapsible-body">Conteúdo do Item 1</div>
     </li>
     <li>
       <div class="collapsible-header">Item 2</div>
       <div class="collapsible-body">Conteúdo do Item 2</div>
     </li>
   </ul>
   ```

   Certifique-se de que a estrutura HTML corresponda à inicialização do collapsible.

Com essas etapas, você pode configurar facilmente um collapsible funcional usando JavaScript no MaterializeCSS. Personalize conforme necessário e consulte a documentação do MaterializeCSS para mais detalhes e opções avançadas.

## 44) JAVASCRIPT (MODAIS):
Para adicionar funcionalidade de modais (janelas modais) a elementos no MaterializeCSS, você pode usar o componente de modais fornecido pela biblioteca. Aqui está como configurar um modal usando JavaScript:

### Inicialização do Modal:
1. **Inicialização com JavaScript**:
   - Inclua o script JavaScript e inicialize o modal usando JavaScript.

   Exemplo:
   ```html
   <script>
     document.addEventListener('DOMContentLoaded', function() {
       var elems = document.querySelectorAll('.modal');
       var instances = M.Modal.init(elems, options);
     });
   </script>
   ```

### Opções de Configuração do Modal:
2. **Opções de Configuração**:
   - Você pode configurar várias opções do modal, como a duração da animação, a direção da entrada, etc.

   Exemplo de opções:
   ```javascript
   var options = {
     opacity: 0.5,
     inDuration: 300,
     outDuration: 200,
     onCloseEnd: function() {
       console.log('Modal fechado');
     }
   };
   ```

   - `opacity`: Define a opacidade do fundo do modal.
   - `inDuration`: Define a duração da animação de entrada em milissegundos.
   - `outDuration`: Define a duração da animação de saída em milissegundos.
   - `onCloseEnd`: Callback chamado quando o modal é fechado.

### Estrutura HTML do Modal:
3. **Estrutura HTML**:
   - Crie a estrutura HTML do modal.

   Exemplo:
   ```html
   <div id="modal1" class="modal">
     <div class="modal-content">
       <h4>Título do Modal</h4>
       <p>Conteúdo do Modal</p>
     </div>
     <div class="modal-footer">
       <a href="#!" class="modal-close waves-effect waves-green btn-flat">Fechar</a>
     </div>
   </div>
   ```

   Certifique-se de que o ID do modal (nesse caso, `modal1`) corresponda ao seletor usado na inicialização do modal.

### Gatilhos do Modal:
4. **Gatilhos de Modal**:
   - Adicione a classe `.modal-trigger` aos elementos que abrirão o modal quando clicados.

   Exemplo:
   ```html
   <a class="waves-effect waves-light btn modal-trigger" href="#modal1">Abrir Modal</a>
   ```

   Certifique-se de que o `href` do gatilho corresponda ao ID do modal.

Com essas etapas, você pode configurar facilmente um modal funcional usando JavaScript no MaterializeCSS. Personalize conforme necessário e consulte a documentação do MaterializeCSS para mais detalhes e opções avançadas.

## 45) JAVASCRIPT (TOASTS E TOOLTIPS):
Para adicionar funcionalidade de toasts (mensagens temporárias) e tooltips (dicas de ferramentas) a elementos no MaterializeCSS, você pode usar os componentes fornecidos pela biblioteca. Aqui está como configurar toasts e tooltips usando JavaScript:

### Toasts:
1. **Inicialização do Toast**:
   - Inclua o script JavaScript e inicialize o toast usando JavaScript.

   Exemplo:
   ```html
   <script>
     document.addEventListener('DOMContentLoaded', function() {
       var options = {
         html: 'Exemplo de toast!'
       };
       var toastElement = document.querySelector('.toast');
       var toastInstance = M.Toast.init(toastElement, options);
       toastInstance.open();
     });
   </script>
   ```

### Opções de Configuração do Toast:
2. **Opções de Configuração**:
   - Você pode configurar várias opções do toast, como a duração, a classe de cor, etc.

   Exemplo de opções:
   ```javascript
   var options = {
     duration: 3000,
     classes: 'rounded'
   };
   ```

   - `duration`: Define a duração do toast em milissegundos.
   - `classes`: Define classes adicionais para estilizar o toast.

### Estrutura HTML do Toast:
3. **Estrutura HTML**:
   - Crie a estrutura HTML do toast.

   Exemplo:
   ```html
   <div class="toast">Exemplo de toast!</div>
   ```

### Tooltips:
1. **Inicialização do Tooltip**:
   - Inclua o script JavaScript e inicialize o tooltip usando JavaScript.

   Exemplo:
   ```html
   <script>
     document.addEventListener('DOMContentLoaded', function() {
       var elems = document.querySelectorAll('.tooltipped');
       var instances = M.Tooltip.init(elems, options);
     });
   </script>
   ```

### Opções de Configuração do Tooltip:
2. **Opções de Configuração**:
   - Você pode configurar várias opções do tooltip, como a posição, a duração, etc.

   Exemplo de opções:
   ```javascript
   var options = {
     position: 'top',
     duration: 300,
     html: 'Dica de Ferramenta'
   };
   ```

   - `position`: Define a posição do tooltip em relação ao elemento alvo ('top', 'right', 'bottom', 'left').
   - `duration`: Define a duração do tooltip em milissegundos.

### Estrutura HTML do Tooltip:
3. **Estrutura HTML**:
   - Adicione a classe `.tooltipped` ao elemento alvo e defina o texto do tooltip usando o atributo `data-tooltip`.

   Exemplo:
   ```html
   <a class="btn tooltipped" data-position="bottom" data-tooltip="Dica de Ferramenta">Botão</a>
   ```

Com essas etapas, você pode configurar facilmente toasts e tooltips usando JavaScript no MaterializeCSS. Personalize conforme necessário e consulte a documentação do MaterializeCSS para mais detalhes e opções avançadas.

## 46) JAVASCRIPT (SCROLLFIRE):
Para adicionar funcionalidade de ScrollFire (acionamento de eventos ao rolar) a elementos no MaterializeCSS, você pode usar o componente `ScrollFire` fornecido pela biblioteca. Isso permite que você execute ações específicas quando os elementos entram ou saem da visualização durante o rolar da página. Aqui está como configurar o ScrollFire usando JavaScript:

### Inicialização do ScrollFire:
1. **Inicialização com JavaScript**:
   - Inclua o script JavaScript e inicialize o ScrollFire usando JavaScript.

   Exemplo:
   ```html
   <script>
     document.addEventListener('DOMContentLoaded', function() {
       var options = [
         {
           selector: '.elemento',
           offset: 50,
           callback: function(el) {
             Materialize.toast('Elemento está na visualização!', 3000);
           }
         }
       ];
       var instances = Materialize.scrollFire(options);
     });
   </script>
   ```

### Opções de Configuração do ScrollFire:
2. **Opções de Configuração**:
   - Você pode configurar várias opções do ScrollFire, como o seletor do elemento, o deslocamento, a função de retorno de chamada, etc.

   Exemplo de opções:
   ```javascript
   var options = [
     {
       selector: '.elemento',
       offset: 50,
       callback: function(el) {
         // Ação a ser executada quando o elemento entra na visualização
       }
     }
   ];
   ```

   - `selector`: Seletor CSS do elemento alvo.
   - `offset`: Quantidade de pixels antes que o elemento entre na visualização.
   - `callback`: Função a ser chamada quando o elemento entra na visualização.

### Estrutura HTML do Elemento:
3. **Estrutura HTML**:
   - Adicione a classe `.elemento` ao elemento que você deseja monitorar para o ScrollFire.

   Exemplo:
   ```html
   <div class="elemento">Elemento a ser observado para o ScrollFire</div>
   ```

Com essas etapas, você pode configurar facilmente o ScrollFire para acionar eventos ao rolar a página usando JavaScript no MaterializeCSS. Personalize conforme necessário e consulte a documentação do MaterializeCSS para mais detalhes e opções avançadas.

## 47) JAVASCRIPT (SCROLLSPY):
Para adicionar funcionalidade de ScrollSpy (espionagem de rolagem) a elementos no MaterializeCSS, você pode usar o componente `ScrollSpy` fornecido pela biblioteca. O ScrollSpy destaca automaticamente os elementos de navegação à medida que a página é rolada para mostrar qual seção da página está atualmente visível para o usuário. Aqui está como configurar o ScrollSpy usando JavaScript:

### Inicialização do ScrollSpy:
1. **Inicialização com JavaScript**:
   - Inclua o script JavaScript e inicialize o ScrollSpy usando JavaScript.

   Exemplo:
   ```html
   <script>
     document.addEventListener('DOMContentLoaded', function() {
       var options = {
         scrollOffset: 50
       };
       var elems = document.querySelectorAll('.scrollspy');
       var instances = M.ScrollSpy.init(elems, options);
     });
   </script>
   ```

### Opções de Configuração do ScrollSpy:
2. **Opções de Configuração**:
   - Você pode configurar várias opções do ScrollSpy, como o deslocamento, etc.

   Exemplo de opções:
   ```javascript
   var options = {
     scrollOffset: 50
   };
   ```

   - `scrollOffset`: Define a quantidade de deslocamento em pixels do topo da janela para considerar ao ativar os elementos de navegação.

### Estrutura HTML dos Elementos de Navegação:
3. **Estrutura HTML**:
   - Adicione a classe `.scrollspy` aos elementos de navegação que deseja rastrear com o ScrollSpy.

   Exemplo:
   ```html
   <ul class="scrollspy">
     <li><a href="#section1">Seção 1</a></li>
     <li><a href="#section2">Seção 2</a></li>
     <li><a href="#section3">Seção 3</a></li>
   </ul>
   ```

### Estrutura HTML das Seções:
4. **Estrutura HTML**:
   - Adicione IDs às seções da página que deseja rastrear com o ScrollSpy.

   Exemplo:
   ```html
   <section id="section1">
     <!-- Conteúdo da seção 1 -->
   </section>
   <section id="section2">
     <!-- Conteúdo da seção 2 -->
   </section>
   <section id="section3">
     <!-- Conteúdo da seção 3 -->
   </section>
   ```

Com essas etapas, você pode configurar facilmente o ScrollSpy para destacar automaticamente os elementos de navegação à medida que o usuário rola a página no MaterializeCSS. Personalize conforme necessário e consulte a documentação do MaterializeCSS para mais detalhes e opções avançadas.

## 48) JAVASCRIPT (TABS):
Para adicionar funcionalidade de abas (tabs) a elementos no MaterializeCSS, você pode usar o componente de abas fornecido pela biblioteca. Aqui está como configurar abas usando JavaScript:

### Inicialização das Tabs:
1. **Inicialização com JavaScript**:
   - Inclua o script JavaScript e inicialize as abas usando JavaScript.

   Exemplo:
   ```html
   <script>
     document.addEventListener('DOMContentLoaded', function() {
       var options = {};
       var elems = document.querySelectorAll('.tabs');
       var instances = M.Tabs.init(elems, options);
     });
   </script>
   ```

### Opções de Configuração das Tabs:
2. **Opções de Configuração**:
   - Você pode configurar várias opções das abas, como o indicador de tab, etc.

   Exemplo de opções:
   ```javascript
   var options = {
     swipeable: true,
     duration: 300
   };
   ```

   - `swipeable`: Define se as abas podem ser alternadas por meio de gestos de deslize em dispositivos móveis.
   - `duration`: Define a duração da animação ao trocar de abas em milissegundos.

### Estrutura HTML das Tabs:
3. **Estrutura HTML**:
   - Crie a estrutura HTML das abas.

   Exemplo:
   ```html
   <ul class="tabs">
     <li class="tab"><a href="#tab1">Tab 1</a></li>
     <li class="tab"><a href="#tab2">Tab 2</a></li>
     <li class="tab"><a href="#tab3">Tab 3</a></li>
   </ul>
   <div id="tab1" class="col s12">Conteúdo da Tab 1</div>
   <div id="tab2" class="col s12">Conteúdo da Tab 2</div>
   <div id="tab3" class="col s12">Conteúdo da Tab 3</div>
   ```

   Certifique-se de que os IDs dos conteúdos das abas correspondam aos hrefs dos elementos de navegação.

Com essas etapas, você pode configurar facilmente abas funcionais usando JavaScript no MaterializeCSS. Personalize conforme necessário e consulte a documentação do MaterializeCSS para mais detalhes e opções avançadas.

## 49) JAVASCRIPT (SIDENAV):
Para adicionar funcionalidade de sidenav (barra lateral) a elementos no MaterializeCSS, você pode usar o componente de sidenav fornecido pela biblioteca. Aqui está como configurar uma sidenav usando JavaScript:

### Inicialização da Sidenav:
1. **Inicialização com JavaScript**:
   - Inclua o script JavaScript e inicialize a sidenav usando JavaScript.

   Exemplo:
   ```html
   <script>
     document.addEventListener('DOMContentLoaded', function() {
       var options = {};
       var elems = document.querySelectorAll('.sidenav');
       var instances = M.Sidenav.init(elems, options);
     });
   </script>
   ```

### Opções de Configuração da Sidenav:
2. **Opções de Configuração**:
   - Você pode configurar várias opções da sidenav, como a largura, a direção de abertura, etc.

   Exemplo de opções:
   ```javascript
   var options = {
     edge: 'left',
     draggable: true
   };
   ```

   - `edge`: Define o lado em que a sidenav será ancorada ('left' ou 'right').
   - `draggable`: Define se a sidenav pode ser arrastada para fora da tela em dispositivos móveis.

### Estrutura HTML da Sidenav:
3. **Estrutura HTML**:
   - Crie a estrutura HTML da sidenav.

   Exemplo:
   ```html
   <ul id="slide-out" class="sidenav">
     <li><a href="#!">Item 1</a></li>
     <li><a href="#!">Item 2</a></li>
     <li><a href="#!">Item 3</a></li>
   </ul>
   <a href="#" data-target="slide-out" class="sidenav-trigger"><i class="material-icons">menu</i></a>
   ```

   Certifique-se de que o `data-target` do gatilho corresponda ao ID da sidenav.

Com essas etapas, você pode configurar facilmente uma sidenav funcional usando JavaScript no MaterializeCSS. Personalize conforme necessário e consulte a documentação do MaterializeCSS para mais detalhes e opções avançadas.

## 50) JAVASCRIPT (PUSHPIN):
O componente Pushpin do MaterializeCSS permite fixar elementos conforme você rola a página. Isso é útil para manter elementos importantes visíveis enquanto o restante da página é rolado. Aqui está como configurar o Pushpin usando JavaScript:

### Inicialização do Pushpin:
1. **Inicialização com JavaScript**:
   - Inclua o script JavaScript e inicialize o Pushpin usando JavaScript.

   Exemplo:
   ```html
   <script>
     document.addEventListener('DOMContentLoaded', function() {
       var options = {
         top: 200,
         bottom: 100
       };
       var elems = document.querySelectorAll('.pushpin');
       var instances = M.Pushpin.init(elems, options);
     });
   </script>
   ```

### Opções de Configuração do Pushpin:
2. **Opções de Configuração**:
   - Você pode configurar várias opções do Pushpin, como a posição de início e fim, etc.

   Exemplo de opções:
   ```javascript
   var options = {
     top: 200,
     bottom: 100
   };
   ```

   - `top`: Define a posição em que o elemento começa a ser fixado.
   - `bottom`: Define a posição em que o elemento para de ser fixado.

### Estrutura HTML do Elemento Pushpin:
3. **Estrutura HTML**:
   - Adicione a classe `.pushpin` ao elemento que deseja fixar.

   Exemplo:
   ```html
   <div class="pushpin" data-top="200" data-bottom="100">
     <!-- Conteúdo do elemento a ser fixado -->
   </div>
   ```

   Certifique-se de que o `data-top` e o `data-bottom` correspondam às opções de configuração definidas.

Com essas etapas, você pode configurar facilmente o Pushpin para fixar elementos enquanto você rola a página no MaterializeCSS. Personalize conforme necessário e consulte a documentação do MaterializeCSS para mais detalhes e opções avançadas.

## 51) JAVASCRIPT (FEATUREDISCOVERY):
O Feature Discovery é uma ferramenta útil para orientar os usuários sobre os recursos de uma aplicação. Ele fornece uma maneira visualmente atraente de destacar elementos específicos e fornecer informações sobre como usá-los. Aqui está como configurar o Feature Discovery usando JavaScript no MaterializeCSS:

### Inicialização do Feature Discovery:
1. **Inicialização com JavaScript**:
   - Inclua o script JavaScript e inicialize o Feature Discovery usando JavaScript.

   ```html
   <script>
     document.addEventListener('DOMContentLoaded', function() {
       var elems = document.querySelectorAll('.tap-target');
       var instances = M.TapTarget.init(elems, options);
     });
   </script>
   ```

### Opções de Configuração do Feature Discovery:
2. **Opções de Configuração**:
   - Você pode configurar várias opções do Feature Discovery, como o texto, a posição, etc.

   ```javascript
   var options = {
     onOpen: function() {
       console.log('Feature Discovery aberto');
     },
     onClose: function() {
       console.log('Feature Discovery fechado');
     }
   };
   ```

   - `onOpen`: Callback chamado quando o Feature Discovery é aberto.
   - `onClose`: Callback chamado quando o Feature Discovery é fechado.

### Estrutura HTML do Feature Discovery:
3. **Estrutura HTML**:
   - Crie a estrutura HTML do Feature Discovery.

   ```html
   <div class="tap-target" data-target="feature-discovery">
     <div class="tap-target-content">
       <h5>Título</h5>
       <p>Descrição do recurso</p>
     </div>
   </div>
   ```

   Certifique-se de que o `data-target` corresponda ao ID do elemento que você deseja destacar.

### Gatilho do Feature Discovery:
4. **Gatilho**:
   - Adicione um botão ou outro elemento que ative o Feature Discovery.

   ```html
   <a class="btn btn-large" onclick="openFeatureDiscovery()">Mostrar Recurso</a>
   ```

   ```javascript
   function openFeatureDiscovery() {
     var instance = M.TapTarget.getInstance(document.querySelector('.tap-target'));
     instance.open();
   }
   ```

Com essas etapas, você pode configurar facilmente o Feature Discovery para destacar e orientar os usuários sobre os recursos da sua aplicação no MaterializeCSS. Personalize conforme necessário e consulte a documentação do MaterializeCSS para mais detalhes e opções avançadas.

## 52) PROJETO FINAL:
- [VEJA O PROJETO FINAL NO DIRETÓRIO "./CODIGO"](./CODIGO/index.html)
