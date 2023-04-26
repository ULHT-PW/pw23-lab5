**UNIVERSIDADE LUSÓFONA DE HUMANIDADES E TECNOLOGIAS**

# Lab 5/Projeto Parte I: Portfolio I ⛅

### Enquadramento

* O seu projeto de Programação Web será desenvolver o seu porfolio. Será um website que ficará online e será a sua carta de apresentação, onde poderá mostrar o que aprendeu, projetos que desenvolveu no curso e não só, e demonstrar as suas aptidões de programação Web. 
* Este projeto tem sido muito valorizado em entrevistas de emprego de colegas vossos, tendo possibilitado oportunidades de emprego muito interessantes. Vale a pena esmerarem-se nele a partir de agora e até ao final do curso, atualizando seus conteúdos. O projeto será realizado por partes, onde irão aplicar aspectos aprendidos. 

### Objetivos 

* Desenvolver uma aplicação Web com o seu portfolio que demonstre conhecimentos avançados de HTML, CSS e JS que adquiriu. Website dinâmico e responsivo que se adequa tanto a telemóvel como PC.
* Conceber de forma criativa e original o seu website e seu design, desenvolvendo tudo por si. Não deverá usar templates da Internet nem Bootstrap. 
* Aplicar as técnicas que tem vindo a aprender. Os requisitos técnicos serão publicados à parte, grelha que será usada para avaliação dos projetos, e que estará apresentada na própria aplicação sob a forma de uma página com a especificação das técnicas usadas.

Objetivos especificos desta primeira parte:
* Conceber um template que definirá o visual da sua aplicação. Trabalhar o HTML, estilização com CSS e funcionalidades JavaScript. Pode usar como conteúdo frases em latim [daqui](https://pl.lipsum.com/). Posteriormente substituirá refinando os seus conteúdos para a construir.
* Estruturar um conjunto de páginas, que poderá navegar através de um menu.
* A aplicação deverá ter um conjunto de páginas estruturadas. 
* Algumas páginas e conteúdos serão sugeridos, para garantir que aplica técnicas que aprenderá na segunda parte do projeto (e.g., armazenamento de informação numa base de dados). 
* O prazo de entrega da 1ª parte do projeto será dia 30 de abril.

### Recomendações
* Explore o seguinte material:
    * [slides da aula](https://moodle.ensinolusofona.pt/course/view.php?id=9482#section-1)
    * exemplos em [Code Pen](https://codepen.io/LucioStuder/collections/?grid_type=list)
    * videos das aulas e video-tutoriais
        * [vídeo-tutorial: Criando um layout responsivo com uma media query](https://educast.fccn.pt/vod/clips/23dbqe9keb/streaming.html?locale=pt)
        * [video-tutorial: posicionamento de elementos e seletores vários](https://educast.fccn.pt/vod/clips/1tmk0lmtww/html5.html?locale=en)
        * [vídeo-tutorial: construindo um layout com CSS Grid](https://educast.fccn.pt/vod/clips/1qib570kz7/html5.html?locale=en)
* Todos os conteúdos devem ser desenvolvidos por si. Não deverá usar templates nem estilizações copiadas. Na avaliação do projeto, tudo o que não conseguir desenvolver por si não será contabilizado.


## Hero Page 🦸‍♀️

1. crie uma hero page (*landing page*), página de entrada com alguns elementos por baixo. Será a sua "carta de apresentação". Lembre-se que um visitante cria uma opinião sobre um site em menos de 1 segundo!. O princípio é fazer algo ao estilo deste [exemplo sugestivo](https://codepen.io/LucioStuder/pen/vYpqwra), tendo no entanto liberdade total para fazer de outra forma, desde que seguindo bons princípios de design. Deverá ter: 
   1. uma fotografia ou video em background
   1. uma frase que goste ao lado, motivacional
   1. um menu em cima, com dropdown. 
   
2. crie um elemento `<article>` por baixo, que apareça se fizer scroll, e inclua um texto de apresentação. Para já, se quiser coloque algumas palavras [daqui](https://pl.lipsum.com/). A ideia será aprimorar uma breve apresentação sua, que fale por exemplo:
* de motivações para escolher o seu curso;
* daquilo que mais tem gostado de aprender no curso;
* de qualidades suas;
* de espectativas do que gostaria de fazer quando acabar o curso;
* de hobbies.

## JavaScript Playground
Integre os seguintes exercícios JavaScript e integre-os no seu site 
1. Crie um botão darkmode, posicionado no cabeçalho da sua página, para mudar as cores dos vários elementos (fundo, texto, títulos etc) de forma a ficar em "darkmode". Se voltar a premir, deverá repor a versão luminosa. Use um icon de [font Awesome](https://fontawesome.com). Pode usar uma lua e um sol, como botão. 
1. Crie uma calculadora. Use um elemento `input` para pedir para inserir uma expressão aritmética. Associe um botão que, quando premido calcula o valor da expressão usando a função [`eval()`](https://www.w3schools.com/js/js_date_methods.asp). Deverá apresentar o resultado num elemento em baixo do input. Crie um segundo botao que permita apagar o resultado.
1. Insira uma imagem que goste. Peça ao utilizador para escrever uma frase que a imagem o tenha inspirado, e coloque-a por cima da fotografia. 
1. Peça ao utilizador para inserir o nome e coloque-o em pelo menos 3 sítios diferentes.
1. Insira a data do dia de hoje (no formato '21 de março, 2023') num local à sua escolha da página. Para tal, utilize o método `Date()` [[1]](https://www.w3schools.com/js/js_date_methods.asp)
1. utilize o evento onmouseover e onmouseout para criar ações.

## Estrutura do seu Portfolio 

O seu portfolio, no final do semestre, poderá ter uma estrutura como em baixo, ou diferente, mas adequadamente estruturada como uma árvore, agrupando de forma coerente conteúdos. A navegação deverá ser clara através do menu sempre disponível. Exemplo de estrutura:

* landing page
* Sobre mim
   * Licenciatura
      * cadeiras 
   * Educação
      * escolas 
   * Aptidões e competências pessoais
      * técnicas
      * organizativas
      * sociais
      * linguisticas
   * Interesses e hobbies
   * Experiencia profissional
* projetos 
   * realizados em diversas UCs
   * realizados por mim 
   * projetos de fim de curso realizados que achou interessantes   
* programação Web   
   * tecnologias existentes
      * front-end
      * back-end
   * laboratórios 
   * notícias    
* Blog
* Sobre este website
   * tecnologias usadas
   * padrões usados     
* Contacto
* Rodapé

Nota: 
*  Muitos dos tópicos consistirão numa lista de elementos (por exemplo, a licenciatura terá uma lista de cadeiras). Esta informação será guardada numa base de dados, a desenvolver mais à frente. Pense num layout de items independentes / tipo postais, como feito nos laboratórios anteriores. Terão associados um titulo, imagem, texto e mais alguns atributos. 
* Conceba em HTML & CSS um template para listar elementos, e como exemplo crie alguns elementos (para já, podem ter texto inventado). Esse template poderá depois ser aplicado às restantes páginas, a construir mais adiante.


## Conteúdos dos vários items

Durante as próximas semanas deverá recolher algum material. Organize-o para já em pastas. Este depois será inserido na base de dados que construirá. Apresentam-se os tipos de conteúdos que poderá congregar para cada item de cada tópico. Podem não incluir alguns, ou escolher outros.

* **Educação**
   * educação, listar Formação, com campos curso, local, período logotipo da instituição
      * cursos superior
      * escolas no secundário
      * certificados
   * licenciatura, pagina que apresenta a lista de cadeiras do curso, organizada por semestre e anos. Quando clicada uma cadeira, aparece informação relativamente a: nome, ano, semestre, ECTS, ano letivo frequentado, topicos abordados, ranking de 1 a 5 estrelas (indicando se gostou ou não), professores (da classe Pessoa com campos nome e link para a sua pagina da lusofona e no linkedin), link para página da cadeira (se existir), lista de projetos realizados (classe projeto)

   * **licenciatura** será uma pagina do seu portfolio que apresenta a lista de cadeiras do seu curso, organizada por semestre e anos. Deverá apresentar os seguintes atributos: nome, ano, semestre, ECTS, ano letivo frequentado, topicos abordados, ranking de 1 a 5 estrelas (indicando se gostou ou não), professores (da classe Pessoa com campos nome e link para a sua pagina da lusofona e no linkedin), link para página da cadeira (se existir), lista de projetos realizados (classe projeto). Construa em HTML & CSS uma pagina licenciatura que liste 3 cadeiras, formatando devidamente os atributos identificados (para já, podem ter texto inventado). Esse template CSS poderá depois ser replicado nas restantes páginas. use por exemplo este formato de [items isolados](https://codepen.io/LucioStuder/pen/MWrKXdy), ou como [aqui](https://github.com/ULHT-PW/pw-lab4#1-capitais-europeias-com-flexbox) com imagens

   * **Aptidões e competências pessoais** (com atributos titulo, descrição curta, lista de projetos (Projeto) realizados onde foi aplicada essa competência caso se aplique, lista de disciplinas (Disciplina) onde foi trabalhada essa competência caso se aplique)
      * [Técnicas]( https://www.e-konomista.pt/competencias-tecnicas/): 
      * linguagens de programação ou tecnologias, relatórios word, apresentações powerpoint, realização de videos, protótipos
      * [Organizativas]( https://www.e-konomista.pt/competencias-de-organizacao/)
      * [Sociais](https://www.e-konomista.pt/aptidoes-e-competencias-sociais)
      * Linguísticas. lista de linguas estrangeiras faladas, com indicação de nível (proficiente, independente ou elementar), e referencia se existir a certificação obtida ou outra explicação (lingua materna, viveu noutro país)
   * interesses (com atributos titulo, descrição, fotografia e link (e.g., clube de fotografia) 
         * outras atividades
         * desporto
         * hobbies
         * voluntariado

* **Projetos**
   * realizados por mim: lista de projetos realizados, com atributos: titulo, descrição até 500 carateres, imagem, ano de realização, cadeira (classe Cadeira, caso tenha sido projeto associado a uma cadeira), participantes (da classe Pessoa, da classe Pessoa com atributos nome e link para a sua pagina no linkedin, e link para a aplicação portfolio do projeto PW), link para repositorio GitHub, link para video no youtube, tecnologias usadas, competencias (classe Competencia)
   * trabalhos de fim de curso: lista de 6 Trabalhos finais de Curso (TFCs) de anos passados realizados por colegas seus que achou interessantes (consultar [aqui](https://informatica.ulusofona.pt/defesas/trabalhos-finais-de-curso/)), onde TFC tem atributos: titulo, autor (multiplos), orientador (multiplos), ano de realização, sumário, resumo até 500 carateres, link para relatório, links para repositório github e vídeo no Youtube, se existentes. Será facultada uma pasta com relatórios de TFC dos últimos anos para escolher.
   * Construa em HTML & CSS uma pagina projetos que liste 3 projetos, formatando devidamente os atributos identificados (para já, podem ter texto inventado). Esse template CSS poderá depois ser replicado nas restantes páginas. Use por exemplo este formato de [items isolados](https://codepen.io/LucioStuder/pen/MWrKXdy), ou como [aqui](https://github.com/ULHT-PW/pw-lab4#1-capitais-europeias-com-flexbox) com imagens



* **Programação Web**
   * Tecnologias: Falar das seguintes Tecnologias, com os atributos: nome (por extenso), acrónimo (caso exista, e.g., CSS para Cascade Style Sheet), ano de criação, criador, logotipo, link para site oficial, descrição das principais características. 
         * Back-end: Laravel, ASP.NET, Spring MVC, Express, Django
         * Front-end: Angular, React, Vue, Svelte
         * Outras: WordPress, OutSystems, Weebly, Wix
   * Laboratórios: página que lista links para os laboratórios realizados na disciplina de PW, com o título e descrição dos tópicos abordados
   * Notícias: listagem de 10 noticias sobre artigos do medium.com que tenha gostado, com campos: título, 3 linhas de texto, imagem e link
   * exemplos de técnicas e efeitos que gosta, sites que gosta e de sites que acha maus, tendencias modernas de programação Web, aspectos obsoletos

* **Sobre**, informação sobre este website, incluindo
   * lista de tecnologias usadas na criação do website: HTML, CSS, Python, Django, Heroku, JavaScript). Tecnologia terá os seguintes atributos: nome (por extenso), acrónimo (caso exista, e.g., CSS para Cascade Style Sheet), ano de criação, criador, logotipo, imagem exemplificativa (excerto de código, e.g.) link para site oficial, descrição do que é e onde & como foi usado. 
   * lista de padrões usados: padrão arquitetural cliente-servidor HTTP, padrão de software MVC, padrão de comunicação assíncrona (AJAX) 

* **Contacto**
   * links para a sua conta linkedin. se não tiver, crie. Adicione à sua conta de colegas seus, amigos e professores e adira a grupos de interesse na sua área (DEISI)
   * link para o seu github
   * link para conta Instagram, facebook
   * nome da cidade onde vive
   * facebook, instagram

* **Rodapé**
   * link para Mapa do site
   * contacto
   * nome do autor
   * ano
   * universidade
   * logotipo
 
 
# Grelha de avaliação
Apresentam-se os aspectos que serão avaliados da aplicação desenvolvida, para aferir o grau de aplicação dos conhecimentos adquiridos sobre HTML, CSS e JavaScript.

### Páginas HTML

1.	A aplicação tem um conjunto de páginas estruturadas (elementar só com 2-3 páginas, ou detalhada)
2.	A aplicação estrutura-se de acordo com o esqueleto apresentado da aplicação final (Apresentação, Educação, Projetos, Programação Web, sobre, contacto)
3.	A aplicação tem uma hero page
4.	A aplicação tem um menu de navegação que permite viajar por todas as páginas do site
5.	Existe uma página que lista um conjunto de items independentes / tipo postais (como feito nos laboratórios anteriores) com título, imagem e texto.
6.	As páginas HTML utilizam elementos semânticos de HTML 5 (main, nav, article, header, footer), e não apenas div.

###	CSS

1.	A página usa um ficheiro CSS para estilizar as páginas do site
2.	O ficheiro CSS tem mais de 50 regras
3.	Existem pelo menos 5 seletores combinados (e.g., div > p, div + p)
4.	São usados selectores de pseudo-classe e pseudo-elemento
5.	É usado CSS flex
6.	É usado CSS grid
7.	É usada uma media query para alterar o layout do website quando se altera a largura do viewport 
8.	O layout é responsivo, i.e., se alterar a largura da página os elementos ficam adequadamente reformatados.
9.	O layout fica corretamente configurado quando visto no telemóvel
10.	O menu é responsivo ao telemóvel, ficando adequadamente adaptado 
11.	Existe uma animação feita com keyframes
12.	Existe um vídeo embebido
13.	É usado o efeito scrolling parallax
14.	É utilizada a propriedade transform
15.	Foi criado um elemento SVG
16.	Não usa bootstrap ou templates que se percebe que foram copiados da Internet 
17.	As imagens são leves (abaixo de 200kB) e o site carrega-as rapidamente

### JavaScript

1.	A aplicação tem um botão darkmode que configura o layout do site através dum script
2.	A aplicação tem uma calculadora implementada por um script 
3.	A aplicação permite ao utilizador escrever uma frase que fica sobreposta a uma imagem
4.	A aplicação pede para inserir o nome e coloca-o em pelo menos 3 sítios diferentes
5.	A aplicação insere numa página a data 
6.	Existe pelo menos um script que usa o evento onmouseover e onmouseout para criar ações

### Webdesign

1.	Boa navegação
2.	Boa hierarquia
3.	Esquema de cores agradável
4.	Boa organização
5.	Boa tipografia, com contraste
6.	São usados espaços em branco
7.	Design responsivo
8.	Estilo consistente
9.	Existem botões com chamadas de ação
10. Website criativo
