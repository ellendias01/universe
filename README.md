# Uni.Verse 

Nesse arquivo estão documentadas todas as Tags utilizadas no site e suas respectivas funções.


## 🚩 Tags em HTML 
| Nome | Descrição |
| --- | --- |
| `!DOCTYPE html` | Delclarar que o documento é do tipo HTML  |
| `HTML` | Marca o inicio do documento e define sua estrutura básica |
| `meta` |Define metadados, ou seja, informações sobre dados de um documento HTML. |
| `head` | Elemento contém meta informações sobre a página HTML|
| `link` | É utilizado para acessar recursos externos da página |
| `title` | Especifica um título para a página HTML (que é mostrado na barra de título do navegador ou na guia da página) |
| `body` | É onde fica todo o conteúdo de texto, imagem e vídeos, em que o usuário vê e interage, nele os conteúdos são estruturados pelas demais tags do HTML. |
| `header` | Define um cabeçalho para um documento ou seção |
| `div` | Define uma divisão ou seção em um documento HTML. |
| `a` | Define um hiperlink.  |
| `img` | É usada para incorporar uma imagem em uma página da web |
| `nav` | Define um conjunto de links de navegação |
| `ul` | Define uma lista não ordenada |
| `li` | Elementos da lista |
| `button` | Define um botão clicável |
| `main` | Especifica o conteudo principal de um documento |
| `section` | Define uma seção em um documento |
| `h1` | Define um título grande/ importante |
| `h2` |Indica uma hierarquia inferior de títulos em relação ao "h1"|
| `h3` | Indica uma hierarquia inferior de títulos em relação ao "h2" |
| `h4` | Indica uma hierarquia inferior de títulos em relação ao "h3" |
| `p` | Define um parágrafo |
| `br` | Define uma quebra de linha. |
| `span` |É um contêiner embutido usado para marcar uma parte de um texto ou parte de um documento. |
| `figure` | Especifica conteúdo independente, como ilustrações, diagramas, fotos, listagens de códigos, etc. |
| `footer` | Define um rodapé para um documento ou seção |
| `i` |Define uma parte do texto com uma voz ou humor alternativo |
| `input` | Elemento de formulário (dependendo do "type" tem uma função diferente ) |
| `audio` | É usado para reproduzir um arquivo de áudio em uma página da web. |
| `source` | Elemento permite que você especifique arquivos de midia (video ou música )alternativos que o navegador pode escolher. O navegador usará o primeiro formato reconhecido. |
| `script` | É usada para definir um script do lado do cliente (JavaScript). |
| `bloqckquote` |Define uma seção citada de outra fonte |
| `<!-->` |Para realizar comentários |

## 🎨 Tags em CSS
| Nome | Descrição |
| --- | --- |
| 💚 `css.css` | Uni.Verse |
| `*` | Estilo geral do site, para padronizar o tamanho|
| `body` | Cor e tamanho do fundo |
| `.inteface` | Padronizar o conteúdo do site|
| `.geral` | Edição de coisas expecificas sem alterar as demais |
| `h2.titulo` |Cor, posição e tamanho de h2|
| `h2.titulo span` | Cor da span |
| `header` | Estilo do Cabeçalho |
| `header> .interface` | Para não interferi nos demais elementos do header que não precisam de um display flex |
| `header a` | Para conseguir fazer o efito trasform funcionar, pois é line level e tirar a linha do link |
| `header a:houver` | Efeito quando o mouse passa por cima e só funciona em block level |
| `header nav ul` | Tira as bolinhas da lista |
| `header nav ul li` | Para ficarem uma ao lado da outra com espaçamento |
| `header .bnt-contato button` | Configurações do botão |
| `header .bnt-contato button:hover` | Sombreado no botão quando o mouse passaer por cima |
| `.carousel-container` | Posção do carrosel e para que o conteúdo não ultrapasse os limites  |
| `.carousel-slide` | Display e animação do carrosel |
| `carousel-slide img` | Evita a distorção das imagens |
| `@keyframe carousel` | Controle da animação |
| `section.topo-do-site` | Espaçamento nas laterias e leve borda nas extremidades |
| `section.topo-do-site.geral` | Alterações exclusivas para o topo, alinhamneto e espaço entre imagem e texto |
| `.topo-do-site .texto-site-up h1` | Cor, tamanho e distância entre as linhas do texto |
| `.topo-do-site .texto-site-up p` | Cor, tamanho e distância entre as linhas do texto |
| `.topo-do-site .imagem-topo img` | Posição, tamanho, borda e flutuagem suave da imagem |
| `@keyframes flu` | Animação de efeito flutuar |
| `section.definicao` | Espaçamento nas laterias e leve borda nas extremidades |
| `.flex` | Display flex e espaçamento entre imagem e texto |
| `.definicao-box` | Cor, posição, borda do box e trasnisção |
| `.definicao .definicao-box:hover` | Sombreado no botão e animação quando o mouse passaer por cima |
| `.definicao .definicao-box h3` | Tamnaho e posição em relação a margem |
| `.definicao .definicao-box p` | Tamnaho e posição em relação a margem |
| `section.curiosidade` | Sombreado |
| `section.curiosidade .text h2` | Tamanho, cor e centralização do texto |
| `.container` | Posição e espaçamento do container  |
| `.container .card` | Posição, tamanho, cor, borda, sombreado, e animação do container |
| `.container .card:hover` | Em caso de passar o mouse ele "creser" |
| `.container .card .img-box` | Posição, tamanho, borda e animação das imagens dentro do box |
| `.container .card:hover .img-box` | Efeito de sombra com animação quando passar o mouse |
| `.conrainer .card .imag-box img` | Posição e forma da imagem |
| `.container .card .content` | Posição dos conteúdo de texto do box |
| `.container .card:hover .content ` | Animação dos conteúdos de texto quando passar o mouse |
| `.container .card .content h2` | Tamanho, negrito e cor da letra |
| `.container .card .content p` | Cor de p |
| `.container .card .content a` | Posição, display, cor, retirada da linha de link e espessura um pouco grossa |
| `.container .card .content a:hover` | Efeito do link quando clicado  |
| `@media` | Animação dos containers |
| `section.sobre` | Espaçamento nas laterias e leve borda nas extremidades |
| `section.sobre .interface` | Configurações de Interface aplicadas aqui e alinhamento |
| `section.sobre .interface h2` | Cor, tamanho e centralização de h2|
| `section.sobre .interface span` | Cor, tamanho e centralização de span |
| `section.sobre .interface .geral .texto p` | Cor, tamanho e posição de p |
| `.geral .gif img` | Tamanho, posição, borda e flutuação  |
| `footer .logobaixo` | Container flex e alinhar os itens|
| `footer .logobaixo img` | Tamanho, e posição da imagem |
| `footer .logobaixo h2` | Posição e cor de h2 |
| `@import url` | Importação de fonte via url |
| -- | -- |
| ❤️ `sty.css` , `bu.css` e `s.css` | Via Láctea, Andrômeda e Buraco Negro |
| `*` | Tamanho total e sem seleção pelo usuário |
| `a` | Cor do Link e sem traço |
| `body` | Posição, tamanho, cor, letras em caixa alta e fonte das letras |
| `h2` | Tamaho da letra, espaçamento, cor e centralização |
| `header` | Posição, display, tamaho da letra, espaçamento, cor e centralização |
| `section` | Tamanho, posição, fixa o conteúdo e deixa ele invisivel inicialmente |
| `section .outer, section.inner` | Tamanho e oculta a barra de rolagem |
| `section .bg` | Posição, tamanho, display e dimenciona a imagem do fundo  |
| `section .bg h2` | Ordem de empilhamento do elemento, para que ele fique acima dos outos  |
| `section .bg h4` | Posição, tamanho e cor de fundo |
| `section .bg .clip-text` | Conteúdo que excede as dimensões do elemento deve ser oculto |
| `.fist .bg`,`.second .bg` ,`.third .bg` ,`.fourth .bg` ,`.fifth .bg`  | Esses estilos definem imagens de fundo para elementos, o gradiente linear é usado para criar uma sobreposição escura (com transparência) sobre a imagem de fundo, dando um efeito de sobreposição |
| `h2 *` | Melhorar o desempenho da animação, permitindo ao navegador otimizar o processo de renderização desses elementos quando ocorrem transformações. |
| -- | -- |
| 💛 `login.css` | Cosmonalte-se |
| `*` | Tamanho total, posição e fonte |
| `body` | Display,tamanho, gif de fundo, sem repetição, sem distorção e centralizado |
| `.box` | Posição, tamanho, cor e borda redonda |
| `.box i` | Posição dos elementos, borda e animação  |
| `.box i:nth-child(1)`, `.box i:nth-child(2)` e `.box i:nth-child(3)` | Forma e tipo de animação |
| `.box:hover i` | Passar o mouse, as cores serão ativadas e as sombras também |
| `@keyframes animate` | Definição da animação |
| `.login` | Alinha os box e deixa um ao lado do outro e em coluna, com espaçamento entre o texto |
| `.login h2` | Tamanho e cor de h3 |
| `.login .info input` | Posição, tamanho, cor da letra do botão e da escrita do usuário  |
| `.login .info input[type="submit"]` | Tamanho, cor e resposta ao clique do usuário |
| `.login .info input::placeholder` | Cor que fica antes do usuário escrever algo  |
| `.login .links` | Posição, display(um ao lado do outro), centralização e tamanho |
| `.login .link a` | Cor e retirada do traço embaixo  |
| `.info .minhaMusica` | Para ficar sem aparecer, sem display |

## 🔧 Tags em Java
| Nome | Descrição |
| --- | --- |
| `GSAP (GreenSock Animation Platform)` | Biblioteca importada |
| `wrap` | Uma função que envolve os índices das seções (usada para garantir que o índice permaneça dentro dos limites das seções). |
| `currentIndex` | É utilizado para armazenar o índice atual |
| `animating` | É utilizado para o controle de animação |
| `document.getElementById(id)` | É utilizado para acessar um elemento HTML |
| `yPercent` | Cria uma animação de entrada |
| `gotoSection` | Esta função é chamada para navegar entre as seções |
| `Observer.create` | Um observador de eventos é criado para eventos como rolagem de mouse, toque e movimento do ponteiro |
| `onDown` e `onUp` | Quando ocorre uma rolagem ou toque, essas funções são chamadas para navegar entre as seções |
| `sections` |  Armazena todas as tags <section> do documento |
| `images` | Armazena todos os elementos com a classe .bg |
| `headings` | Armazena todos os elementos com a classe .section-heading usando a função gsap.utils.toArray |
| `outerWrappers` |  Armazena todos os elementos com a classe .outer usando a função gsap.utils.toArray |
| `innerWrappers` | Armazena todos os elementos com a classe .inner usando a função gsap.utils.toArray|
| `splitHeadings` |  Cria uma matriz de objetos SplitText para dividir os elementos de .section-heading em caracteres, palavras e linhas. Isso é usado para animar o texto de maneira mais granular |
| `currentIndex` | Inicializado como -1, representando o índice atual da seção |
| `document.getElementById('botaoReproduzir')` | Código seleciona o elemento HTML com o id "botaoReproduzir"  |
| `addEventListener` | É usada para adicionar um ouvinte de evento de clique ao botão |
| `play()` | No elemento de áudio musica. Isso inicia a reprodução da música associada a esse elemento de áudio |



## ✨By Éllen Dias ✨
