<h1>Codificador e Decodificador de texto</h1>

<h2>Utilizando HTML, CSS e JavaScript</h2>

<p>Este é o primeiro challenge do programa ONE - Oracle Next Education, com o objetivo de praticar os conteúdos estudados.
  O desafio é criar um codificador/decodificador de texto usando HTML, CSS e JavaScript. Foram disponibilizados
  cards no Trello para orientação e gerenciamento do projeto, além de um modelo de estilização no Figma..</p>

  <h3>Projeto</h3>
  
   <h4>Na estrutura HTML modifiquei:</h4>
   <ul>
     <li>o ícone, o título e a descrição da página;</li>
     <li>o header, onde coloquei o link da página no logo. Assim, ao clicar no logo, a página é recarregada. </li>
     <li> o aviso de "apenas letras minúsculas e sem acento" para aparecer somente se o usuário digitar letras maiúsculas ou acentuadas;</li>
     <li>Uma textarea readonly para mostrar o resultado da codificação/decodificação impede que o usuário altere o texto acidentalmente.</li>
     <li>o footer, onde adicionei meu nome e redes sociais;</li>
   </ul>

   <h3>No CSS modifiquei:</h3>
   <ul>
       <li>As cores do fundo (com um gradiente de azul-claro para azul-escuro) e das sombras;</li>
       <li>As animações dos links e dos botões (usei transform e opacity);</li>
   </ul>

   <h3>no JavaScript</h3>
   <ul>
      <li>Criei a função de codificar separando os caracteres do texto em um array (texto.value.split), substituindo com forEach e retornando com .join("");</li>
      <li>Criei a função de decodificar utilizando um array com a "chave" da codificação e utilizando replaceAll(chave[i][1]);</li>
      <li>Criei uma função para que, ao copiar o texto com o botão "copiar", as textareas sejam limpas e o input seja focado, facilitando a entrada de um novo texto.</li>
      <li>Criei uma função para mostrar uma mensagem de erro caso não fosse inserido texto;</li>
      <li>Criei uma funçao para que apenas letras minusculas e sem caracteres especiais sejam ultilizadas</li>
   </ul>
   
