# Landing Page Jullanar

Este projeto apresenta uma página de um restaurante marroquino chamado **Jullanar**. 

O restaurante não existe e serve apenas para o propósito desse projeto. 

### Estrutura do Projeto
1. `./index.html`: Página inicial em HTML.

2. `./html/sobrenos.html`: Breve descrição do histórico do restaurante com a localização integrada em um mapa disponibilizado pelo google maps.

3. `./html/cardapio.html`: Contém uma tabela com duas refeições completas: tipo de refeição, nome, descrição e preço.

4. `./html/contato.html`: Botões contendo as redes sociais do restaurante e duas opções de contato: um formulário e um botão que leva ao WhatsApp do restaurante.

5. `./css/style.css`: Definições de estilo CSS para a landing page.

### Descrição das Seções em HTML

1. `head`, `meta`, `title` e`link`: Tag que inclui metadados, título de cada página e links.

2. `body`: Contém todo o corpo principal das páginas, incluindo `header` e `footer`.

3. `header`, `nav` e `a`: Cabeçalho contendo a navegação entre as páginas com links ancorados dentro da tag.

4. `main`: Corpo principal de tags contendo os elementos pertinentes de cada uma das páginas.

5. `section`: Seções distintas que agrupam tags com semânticas que sejam congruentes, utilizadas aqui para dividir as diferentes seções do corpo principal.

6. `h1`, `h2` e`p`: Tags de cabeçalhos de texto e parágrafos.

7. `footer` e `small`: Tag de rodapé contendo endereço e contatos do restaurante.

8. `table`, `tr`, `th` e `td`: Tags para a criação e organização de uma tabela, utilizada aqui para os cardápios.
    - th: Define os cabeçalhos da tabela e organiza as colunas;
    - tr: Organização das linhas da tabela;
    - td: Preenche as células.

9. `div` e `iframe`: Tag utilizada como contêiner para a centralização do documento apresentado como mapa.

10. `ul` e `li`: Definição de listas não-ordenadas.

11. `form`, `label`, `input`, `textarea` e `button`: Tags utilizadas para o formulário de contato, contendo os rótulos, elementos de entrada e o botão de submissão.

### Descrição dos Estilos em CSS

1. `*`: Define estilos para todos os elementos HTML. Reseta margens, preenchimentos e o modelo de caixa para todos os elementos.

2. `body`: Aplica estilos ao elemento `<body>` do documento HTML. Define a fonte padrão, configura o layout do corpo do documento e estabelece um layout de coluna flexível que abrange toda a altura visível do navegador (`min-height: 100vh`).

3. `header`: Estiliza o cabeçalho do documento. Fixa o cabeçalho no topo da janela do navegador (`position: fixed`) e adiciona uma sombra sutil (`box-shadow`) para distinguir o cabeçalho do restante do conteúdo.

4. `header nav`: Estiliza a barra de navegação dentro do cabeçalho. Centraliza os itens da barra de navegação horizontalmente e adiciona preenchimento (`padding`) para separar os itens.

5. `header nav a`: Estiliza os links dentro da barra de navegação. Padroniza a cor do texto, o espaçamento entre os links e a remoção do sublinhado.

6. `body > *:not(header)`: Aplica estilos a todos os elementos diretos do corpo que não sejam cabeçalhos. Propósito: Adiciona preenchimento ao topo desses elementos para garantir que eles não sejam obscurecidos pelo cabeçalho fixo.

7. `main`: Define que o elemento `<main>` ocupará o restante do espaço disponível no layout flexível (`flex: 1`) e permite a rolagem vertical quando o conteúdo excede a altura da janela (`overflow-y: auto`).

8. `section`: Estiliza as tags `<section>` do documento. Adiciona margem inferior para separar as seções do conteúdo.

9. `h1`, `h2`, `p`, `em`: Aplica estilos aos diferentes elementos de cabeçalho, parágrafos e ênfase. Define cores, alinhamento e espaçamento de texto para diferentes elementos de texto.

10. `table`: Estiliza a tag `<table>`. Define largura total, espaçamento interno e externo, bem como estilos de borda para tabelas, tornando-as mais legíveis e esteticamente agradáveis.

11. `footer`: Estiliza o rodapé do documento. Define a cor de fundo, cor do texto e alinhamento do texto para o rodapé.

12. `.iframe-container`: Estiliza especificamente o contêiner do elemento em `<iframe>`.

13. `.social-media`, `.social-media li`, `.social-btn`**: Aplica estilos às tags relacionadas às redes sociais.

14. `form`, `label`, `input`, `textarea`: Define os estilos dos elementos de formulário HTML. Define a largura máxima para o formulário, o espaçamento e as borda para rótulos, campos de entrada de texto e áreas de texto.