<head>
<link rel="stylesheet" href="scripts/style.css">
</head>

<h2 id="inicio">Construção de páginas com HTML</h2>

<p>Este site contém os procedimentos para construirmos sites em HTML, foco da disciplina Fundamentos do Webdesign</p>
<p>A apostila está disponível no link: <a href="http://www.exatas.ufpr.br/portal/degraf_paulo/wp-content/uploads/sites/4/2014/09/tags001.pdf" target="_blank">apostila de Webdesign</a></p>
<p>Os materiais usados estão indicados nos links dos tópicos das atividades.</p>

<details>
  <summary id="basico">Estruturas básicas: pág. 1-10</summary>
   <img src="basico/tags001_0001.png" />
   <details class="sub"><summary>&#x1f4c3; Escolha de cores</summary>
	<p>Existem vários sites que mostram as escolhas de cores para usar em HTML. Vamos começar usando as cores com códigos HTML ou hexadecimais. Clique nos passos abaixo para ver como podemos escolher cores em 2 sites.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="slide001" name="slide" checked>
			   <label for="slide001"></label>
			   <img src="basico/01_01_01.png" />
			   <figcaption>Acessando o site <span class="code">http://html-color-codes.info/Codigos-de-Cores-HTML/</span>, você pode clicar em cores pré-definidas pelo site. Note que o código hexadecimal aparece logo abaixo das cores.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="slide002" name="slide">
			   <label for="slide002"></label>
			   <img src="basico/01_01_02.png" />
			   <figcaption>Logo abaixo, você encontra outra maneira de escolher cores neste mesmo site. Basta escolher o tom da cor e clicar sobre a cor escolhida.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="slide003" name="slide">
			   <label for="slide003"></label>
			   <img src="basico/01_01_03.png" />
			   <figcaption>Acessando o site <span class="code">https://color.adobe.com/pt/create/color-wheel/</span>, você pode escolher as cores de forma análoga. Note que aparecem os códigos hexadecimais e RGB logo abaixo do disco de cores.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="slide004" name="slide">
			   <label for="slide004"></label>
			   <img src="basico/01_01_04.png" />
			   <figcaption>Outro site interessante é <span class="code">https://celke.com.br/artigo/tabela-de-cores-html-nome-hexadecimal-rgb</span>, que além dos códigos RGB e hexadecimais mostra os nomes das cores usadas em HTML na primeira coluna da tabela.</figcaption>
		   </li>
		</ul>
		<img src="basico/01_01_00.png" class="fundo" style="visibility:hidden" />
  </details>
  <img src="basico/tags001_0001a.png" />
   <details class="sub"><summary>&#x1f4c3; Texto para testar layouts</summary>
	<p>Muitas vezes, nosso foco é de testar somente o layout de um site. Podemos preenchê-lo com textos e listas usando o site mostrado nesta página. Clique nos passos abaixo para ver como produzir estes conteúdos.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="slide005" name="slide">
			   <label for="slide005"></label>
			   <img src="basico/01_02_01.png" />
			   <figcaption>Acessando o site <span class="code">http://br.lipsum.com/</span>, você pode criar blocos de textos ou listas, usados para testarmos layouts.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="slide006" name="slide">
			   <label for="slide006"></label>
			   <img src="basico/01_02_02.png" />
			   <figcaption>Escolha a criação de 2 parágrafos para fazermos um teste. Copie e cole este texto produzido no programa <span class="code">Notepad</span> (<span class="code">Bloco de Notas</span>) do Windows.</figcaption>
		   </li>
		</ul>
		<img src="basico/01_02_00.png" class="fundo"/>
  </details>
  <p class="topop"><a href="#basico" class="topo">voltar ao topo</a></p>
  <img src="basico/tags001_0002.png" />
  <details class="sub"><summary>&#x1f4c3; Texto para testar layouts</summary>
	<p>Vamos salvar nosso arquivo em uma pasta chamada <span class="code">webdesign</span>.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="slide007" name="slide">
			   <label for="slide007"></label>
			   <img src="basico/02_01_00.png" />
			   <figcaption>Escolha a opção do Bloco de Notas <span class="code">Salvar como</span>. Salve o arquivo como <span class="code">pagina1.htm</span>. Uma dica importantíssima é de <b>não usar acentuação para nomear as páginas</b>!!!</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="slide008" name="slide">
			   <label for="slide008"></label>
			   <img src="basico/02_01_01.png" />
			   <figcaption>É muito importante lembrar que a extensão do arquivo deve ser <span class="code">.htm</span> ou <span class="code">.html</span>. Abra o arquivo em um navegador de internet. Como não foram feitas as marcações dos parágrafos, vamos colocá-las no arquivo.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="slide009" name="slide">
			   <label for="slide009"></label>
			   <img src="basico/02_01_02.png" />
			   <figcaption>Antes de cada parágrafo, devemos colocar a tag <span class="code">&lt;p&gt;</span>. Logo após o parágrafo, colocamos a tag de fechamento de parágrafo <span class="code">&lt;/p&gt;</span>. Faça isso nos 2 parágrafos e visualize a página em um navegador.</figcaption>
		   </li>
		</ul>
		<img src="basico/02_01_00.png" class="fundo"/>
  </details>
  <img src="basico/tags001_0002a.png" />
  <p class="topop"><a href="#basico" class="topo">voltar ao topo</a></p>
  <img src="basico/tags001_0003.png" />
  <details class="sub"><summary>&#x1f4c3; Layout básico de uma página</summary>
	<p>O layout básico de uma página HTML tem as seguintes partes: cabeçalho (<span class="code">head</span>) e corpo da página (<span class="code">body</span>). Vamos ver os elementos de cada parte:</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="slide010" name="slide">
			   <label for="slide010"></label>
			   <img src="basico/03_01_01.png" />
			   <figcaption>O cabeçalho <span class="code">&lt;head&gt;</span> contém informações autorais, título, codificação de caracteres, palavras-chave, scripts e referências externas. Nem todos os elementos desta tag são visíveis para os visitantes da página.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="slide011" name="slide">
			   <label for="slide011"></label>
			   <img src="basico/03_01_02.png" />
			   <figcaption>Dentro da tag do corpo da página <span class="code">&lt;body&gt;</span> devemos colocar todos os contéudos visíveis para os visitantes.</figcaption>
		   </li>
		</ul>
		<img src="basico/03_01_00.png" class="fundo"/>
  </details>
  <img src="basico/tags001_0003a.png" />
  <details class="sub"><summary>&#x1f4c3; Fundo da página, alinhamentos</summary>
	<p>Vamos deixar todos os arquivos desta disciplina organizados. Podemos criar uma pasta chamada <span class="code">pagina1</span> para colocar todos os arquivos desta primeira página. É importante deixar os arquivos sempre organizados em pastas para usarmos as referências corretas na hora de montar o site.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="slide012" name="slide">
			   <label for="slide012"></label>
			   <img src="basico/03_02_01.png" />
			   <figcaption>Crie uma pasta dentro da pasta <span class="code">pagina1</span> para colocarmos as imagens. Podemos chamá-la de <span class="code">imagens</span>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="slide012a" name="slide">
			   <label for="slide012a"></label>
			   <img src="basico/03_02_02.png" />
			   <figcaption>Podemos escolher uma imagem para colocar no fundo da página (<span class="code">background</span>). Escolha uma com largura maior do que 1000px, para cobrir todo o fundo da página, e salve na pasta que criamos <span class="code">/imagens</span>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="slide013" name="slide">
			   <label for="slide013"></label>
			   <img src="basico/03_02_02.png" />
			   <figcaption>Na tag do corpo da página, colocamos o caminho da imagem salva: <span class="code">&lt;body background="imagens/fundo.jpg"&gt;</span>. Salve e veja a página renderizada em um navegador.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="slide014a" name="slide">
			   <label for="slide014a"></label>
			   <img src="basico/03_02_03.png" />
			   <figcaption>Os alinhamentos dos parágrafos podem ser definidos dentro de cada tag. Por exemplo, se você quiser deixar o primeiro parágrafo justificado, basta usar a tag <span class="code">&lt;p align="justify"&gt;</span>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="slide014" name="slide">
			   <label for="slide014"></label>
			   <img src="basico/03_02_04.png" />
			   <figcaption>Para destacar partes do texto, podemos mudar cores e tamanhos. Neste exemplo, dois trechos estão destacados com cores diferentes usando a tag <span class="code">&lt;font&gt;</span>. Dentro desta tag, você muda cor, tamanho e família da fonte (face). Note que ela precisa de fechamento para o fim do destaque: <span class="code">&lt;/font&gt;</span></figcaption>
		   </li>
		   <li>
			   <input type="radio" id="slide015" name="slide">
			   <label for="slide015"></label>
			   <img src="basico/03_02_05.png" />
			   <figcaption>Se você quiser que a página toda tenha uma configuração específica de fonte, basta abrir a tag no começo do corpo da página, e fechá-la antes do fechamento da tag <span class="code">&lt;/body&gt;</span>. No exemplo, foi colocada a fonte <b>Verdana</b> na página toda.</figcaption>
		   </li>
		</ul>
		<img src="basico/03_02_03.png" class="fundo" style="visibility:hidden"/>
  </details>
  <img src="basico/tags001_0003b.png" />
  <details class="sub"><summary>&#x1f4c3; Barra separadora e títulos</summary>
	<p>Podemos separar conteúdos usando uma tag simples de barra horizontal. Além disso, podemos destacar trechos do texto colocando negrito, itálico ou sublinhado. Títulos de seções também podem ser feitos com tags simples mostradas a seguir:</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="slide016" name="slide">
			   <label for="slide016"></label>
			   <img src="basico/03_03_01.png" />
			   <figcaption>Usando a tag <span class="code">&lt;hr&gt;</span>, podemos separar conteúdos na página. Essa tag não precisa ser fechada! Você pode configurar a altura, largura e cor. A largura em percentual é muito usada para deixar o site responsivo, ou seja, que abre em qualquer dispositivo.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="slide017" name="slide">
			   <label for="slide017"></label>
			   <img src="basico/03_03_02.png" />
			   <figcaption>Os títulos de seções podem ser definidos com as tags h1, h2, ..., h6. No exemplo, usamos o título com a tag <span class="code">&lt;h3&gt;</span>. Quanto maior o número, menor o tamanho da fonte desta tag. Experimente mudar essa tag para h1 e h6.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="slide018" name="slide">
			   <label for="slide018"></label>
			   <img src="basico/03_03_03.png" />
			   <figcaption>A tag de negrito <span class="code">&lt;b&gt;</span> foi usada neste exemplo para um trecho do texto. Não esqueça de fechá-la para que seu site apareça corretamente. Salve a página renderizada em um navegador.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="slide019" name="slide">
			   <label for="slide019"></label>
			   <img src="basico/03_03_04.png" />
			   <figcaption>Neste exemplo, foi usada uma tag por dentro da outra (aninhada). Um trecho foi destacado em negrito e itálico com as tags <span class="code">&lt;b&gt;&lt;i&gt;</span>. Note que ambas precisam ser fechadas.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="slide020" name="slide">
			   <label for="slide020"></label>
			   <img src="basico/03_03_05.png" />
			   <figcaption>Se você quiser destacar um trecho do texto deixando-o riscado, basta usar a tag <span class="code">&lt;strike&gt;Sed sit amet pharetra leo.&lt;/strike&gt;</span>. Essa tag é usada em sites para mostrar preços de produtos.</figcaption>
		   </li>
		</ul>
		<img src="basico/03_03_00.png" class="fundo"/>
  </details>
  <p class="topop"><a href="#basico" class="topo">voltar ao topo</a></p>
  <img src="basico/tags001_0004.png" />
  <details class="sub"><summary>&#x1f4c3; Listas</summary>
	<p>Agora vamos criar uma outra página, dentro da pasta da disciplina, crie a pasta <span class="code">webdesign/pagina2/</span>. Nesta página, vamos criar elementos de listas.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="slide021" name="slide">
			   <label for="slide021"></label>
			   <img src="basico/04_01_01.png" />
			   <figcaption>Dependendo do servidor usado para hospedar sua página, devemos modificar a codificação de caracteres charset de <b>UTF-8</b> para <b>ISO-8859-1</b>. Porém, a maioria dos servidores usa o <b>UTF-8</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="slide022" name="slide">
			   <label for="slide022"></label>
			   <img src="basico/04_01_02.png" />
			   <figcaption>Usando a tag <span class="code">&lt;ul&gt;</span>, podemos criar listas na página. Este exemplo mostra os marcadores circulares da lista.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="slide023" name="slide">
			   <label for="slide023"></label>
			   <img src="basico/04_01_03.png" />
			   <figcaption>Os itens das listas têm tags <span class="code">&lt;li&gt;</span>. Note que cada tag de item precisa ser fechada, depois que você coloca o conteúdo. Para mudar de cor, coloque a tag de fonte aninhada na tag de item da lista. Mude as cores dos outros itens.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="slide024" name="slide">
			   <label for="slide024"></label>
			   <img src="basico/04_01_04.png" />
			   <figcaption>As listas ordenadas têm a mesma estrutura da lista norma, com a tag principal <span class="code">&lt;ol&gt;</span>. Estas tags podem ser numéricas ou com letras. Neste exemplo, a lista com letras começa na 4<sup>a</sup> letra, ou seja, a letra <b>D</b>.</figcaption>
		   </li>
		</ul>
		<img src="basico/04_01_00.png" class="fundo"/>
  </details>
  <img src="basico/tags001_0004a.png" />
  <p class="topop"><a href="#basico" class="topo">voltar ao topo</a></p>
  <img src="basico/tags001_0005.png" />
  <details class="sub"><summary>&#x1f4c3; Imagens</summary>
	<p>Agora vamos criar uma outra página, dentro da pasta da disciplina: crie a pasta <span class="code">webdesign/pagina3/</span>. Nesta página, vamos inserir imagens, por isso, crie uma pasta <span class="code">webdesign/pagina3/imagens</span> para colocarmos todas as imagens do site. Escolha 3 imagens e coloque nesta pasta. As extensões podem ser <b>png</b>, <b>jpg</b> ou <b>jpeg</b>. Preste atenção no atributo <span class="code">src</span>, que contém o caminho da imagem.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="slide025" name="slide">
			   <label for="slide025"></label>
			   <img src="basico/05_01_01.png" />
			   <figcaption>A tag de imagem pode ser colocada no meio do texto usando o código <span class="code">&lt;img</span>. Todos os atributos desta tag ficam dentro da <span class="code">&lt;img</span>, não precisando ser fechada. A largura em percentual é importante para deixar o site responsivo.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="slide026" name="slide">
			   <label for="slide026"></label>
			   <img src="basico/05_01_02.png" />
			   <figcaption>Neste segundo exemplo, a imagem também está misturada com o texto, alinhada no meio do texto. Não recomenda-se o uso das imagens misturadas, pois o layout da página fica prejudicado.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="slide026a" name="slide">
			   <label for="slide026a"></label>
			   <img src="basico/05_01_02.png" />
			   <figcaption>Os atributos <span class="code">hspace</span> e <span class="code">vspace</span> criam margens horizontais e verticais em torno da imagem. São ótimas para não deixar outros elementos "grudados" nas imagens.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="slide027" name="slide">
			   <label for="slide027"></label>
			   <img src="basico/05_01_03.png" />
			   <figcaption>De uma forma bem mais organizada, podemos criar a tag-mãe <span class="code">&lt;figure&gt;</span>, que contém a imagem, e logo depois uma tag de legenda <span class="code">&lt;figcaption&gt;</span>. Neste caso, a tag de parágrafo centralizado foi usada para deixar a legenda alinhada com a imagem.</figcaption>
		   </li>
		</ul>
		<img src="basico/05_01_00.png" class="fundo"/>
  </details>
  <img src="basico/tags001_0005a.png" />
  <details class="sub"><summary>&#x1f4c3; Links</summary>
	<p>Usando a mesma <span class="code">pagina3.htm</span>, vamos criar links. Os links podem ser criados em textos ou imagens.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="slide028" name="slide">
			   <label for="slide028"></label>
			   <img src="basico/05_02_01.png" />
			   <figcaption>A tag de link é <span class="code">&lt;a</span>, e precisa de fechamento para você limitar o que o visitante clica para visitar uma outra página. Neste primeiro exemplo, o link está em um texto.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="slide029" name="slide">
			   <label for="slide029"></label>
			   <img src="basico/05_02_01.png" />
			   <figcaption>O atributo <span class="code">href</span> é obrigatório, e indica o endereço da página que será visitada. O atributo <span class="code">target="_blank"</span> indica que a página será aberta em outra aba.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="slide030" name="slide">
			   <label for="slide030"></label>
			   <img src="basico/05_02_02.png" />
			   <figcaption>Para inserir um link em uma imagem, basta deixar a tag <span class="code">&lt;a</span> aninhada com a tag <span class="code">&lt;img</span>, como mostra este segundo exemplo. Crie os links, salve a página e teste em um navegador.</figcaption>
		   </li>
		</ul>
		<img src="basico/05_02_00.png" class="fundo"/>
  </details>
  <p class="topop"><a href="#basico" class="topo">voltar ao topo</a></p>
  <img src="basico/tags001_0006.png" />
  <details class="sub"><summary>&#x1f4c3; Áudios</summary>
	<p>Usando a mesma <span class="code">pagina3.htm</span>, vamos inserir tags de áudios. Quando você salvar a página e visualizar em um navegador, a opção com controles fornece um "frame" para o vídeo que fica similar à seguinte imagem:</p>
	<p align="center"><img src="basico/06_01_04.png" width="40%" /></p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="slide031" name="slide">
			   <label for="slide031"></label>
			   <img src="basico/06_01_00.png" />
			   <figcaption>Na mesma pasta da nossa<span class="code">pagina3</span>, podemos criar uma subpasta chamada <span class="code">audios</span>. Assim, a estrutura de arquivos da nossa página fica organizada.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="slide032" name="slide">
			   <label for="slide032"></label>
			   <img src="basico/06_01_01.png" />
			   <figcaption>Podemos usar a tag <span class="code">audio</span> em uma única linha, com todas as propriedades definidas dentro desta tag. Esta maneira é comum quando apenas um arquivo é inserido. Os navegadores atuais suportam arquivos com extensão <span class="code">mp3</span>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="slide033" name="slide">
			   <label for="slide033"></label>
			   <img src="basico/06_01_02.png" />
			   <figcaption>Em navegadores muito antigos, por precaução, podemos definir os formatos <span class="code">mp3</span> e <span class="code">ogg</span>. Esta tag é do tipo aninhada, com os caminhos (src) dos 2 arquivos definidos.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="slide034" name="slide">
			   <label for="slide034"></label>
			   <img src="basico/06_01_03.png" />
			   <figcaption>O atributo <span class="code">controls</span> serve para mostrar os controles para o visitante interagir com o audio. O atributo <span class="code">autoplay</span> define a reprodução automática do arquivo.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="slide034a" name="slide">
			   <label for="slide034a"></label>
			   <img src="basico/06_01_05.png" />
			   <figcaption>Você pode colocar links para áudios em uma página. Acessando o site <span class="code">open.spotify.com</span>, você pode selecionar as músicas e copiar seus links.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="slide034b" name="slide">
			   <label for="slide034b"></label>
			   <img src="basico/06_01_05a.png" />
			   <figcaption>Você pode criar também os links para álbuns, da mesma maneira mostrada para músicas. Na página HTML usamos a tag de link <span class="code">&lt;a</span> para os álbuns.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="slide034c" name="slide">
			   <label for="slide034c"></label>
			   <img src="basico/06_01_06.png" />
			   <figcaption>Usando a tag de link <span class="code">&lt;a</span>, você insere os links de músicas em sua página.</figcaption>
		   </li>
		</ul>
		<img src="basico/06_01_00.png" class="fundo" style="visibility:hidden"/>
  </details>
  <img src="basico/tags001_0006a.png" />
  <details class="sub"><summary>&#x1f4c3; Vídeos</summary>
	<p>Vamos criar uma nova pasta chamada <span class="code">webdesign/pagina4</span>. Dentro desta pasta, crie as subpastas de <span class="code">imagens</span> e de <span class="code">videos</span>. Quando você salvar a página e visualizar em um navegador, a opção com controles fornece uma imagem similar à esta:</p>
	<p align="center"><img src="basico/06_02_05.png" width="60%" /></p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="slide035" name="slide">
			   <label for="slide035"></label>
			   <img src="basico/06_02_01.png" />
			   <figcaption>Escolha um arquivo de imagem (pode ser no google) para colocar como um banner da nossa <span class="code">pagina4.htm</span>. Cuidado com a extensão da imagem (jpg, png, jpeg) para indicar o caminho no código HTML.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="slide036" name="slide">
			   <label for="slide036"></label>
			   <img src="basico/06_02_02.png" />
			   <figcaption>Podemos usar a tag <span class="code">video</span> em uma única linha, com todas as propriedades definidas dentro desta tag. Esta maneira é comum quando apenas um arquivo é inserido. A maioria dos navegadores atuais suportam arquivos com extensões <span class="code">mp4</span>, <span class="code">webm</span> e <span class="code">ogv</span>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="slide037" name="slide">
			   <label for="slide037"></label>
			   <img src="basico/06_02_03.png" />
			   <figcaption>Por precaução, podemos definir os formatos <span class="code">mp4</span>, <span class="code">webm </span>e <span class="code">ogv</span> dentro de uma tag de vídeo. Esta tag é do tipo aninhada, com os caminhos (src) dos 3 arquivos de vídeo.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="slide038" name="slide">
			   <label for="slide038"></label>
			   <img src="basico/06_02_04.png" />
			   <figcaption>O atributo <span class="code">controls</span> serve para mostrar os controles para o visitante interagir com o vídeo. O atributo <span class="code">autoplay</span> define a reprodução automática do vídeo.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="slide039" name="slide">
			   <label for="slide039"></label>
			   <img src="basico/06_02_04.png" />
			   <figcaption>Quando inserimos vídeos em uma página, é importante definirmos a altura <span class="code">height</span> e a largura <span class="code">width</span> do vídeo. Estas medidas podem ser indicadas em % ou pixels.</figcaption>
		   </li>
		</ul>
		<img src="basico/06_02_00.png" class="fundo" style="visibility:hidden"/>
  </details>
  <img src="basico/tags001_0006b.png" />
  <details class="sub"><summary>&#x1f4c3; Vídeos do Youtube</summary>
	<p>Para inserir um vídeo do Youtube, usamos a tag <span class="code">iframe</span>. Vamos usar a mesma <span class="code">pagina4.htm</span> para inserir esta tag de vídeo.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="slide040" name="slide">
			   <label for="slide040"></label>
			   <img src="basico/06_03_00.png" />
			   <figcaption>Na página do vídeo escolhido, clique em <span class="code">compartilhar</span>, no link que fica logo abaixo da janela do vídeo.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="slide041" name="slide">
			   <label for="slide041"></label>
			   <img src="basico/06_03_01.png" />
			   <figcaption>Selecione a opção <span class="code">incorporar</span>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="slide042" name="slide">
			   <label for="slide042"></label>
			   <img src="basico/06_03_02.png" />
			   <figcaption>Agora é só copiar a tag <span class="code">iframe</span> criada. Note que aparecem as medidas que já usamos na tag de <span class="code">video</span>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="slide043" name="slide">
			   <label for="slide043"></label>
			   <img src="basico/06_03_03.png" />
			   <figcaption>Cole a tag criada na posição da página que você quer mostrar o vídeo. O atributo <span class="code">frameborder</span> tem padrão com valor <b>0</b>. Se você quiser uma borda, basta digitar qualquer valor diferente de <b>0</b> neste atributo.</figcaption>
		   </li>
		</ul>
		<img src="basico/06_03_00.png" class="fundo" style="visibility:hidden"/>
  </details>
  <img src="basico/tags001_0006c.png" />
  <details class="sub"><summary>&#x1f4c3; Detalhes da Atividade</summary>
	<p>Usando todas as tags que vimos até agora, vamos montar uma página htm com os elementos descritos abaixo. Crie uma pasta chamada <span class="code">webdesign/atividade1</span> para inserir os arquivos desta atividade. O arquivo principal HTML será chamado de <span class="code">index.htm</span>.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="slide044" name="slide">
			   <label for="slide044"></label>
			   <img src="basico/06_04_00.png" />
			   <figcaption>Na parte superior da página, que terá um formato tipo blog, coloque uma imagem como <span class="code">banner</span>, textos de informações e curiosidades sobre a banda ou o cantor escolhido.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="slide045" name="slide">
			   <label for="slide045"></label>
			   <img src="basico/06_04_00.png" />
			   <figcaption>Insira imagens, uma imagem de fundo <span class="code">background</span>. Lembre-se de colocar as medidas de altura e largura da imagem na página. Use as tags de linhas horizontais <span class="code">&lt;hr&gt;</span> para separar conteúdos.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="slide046" name="slide">
			   <label for="slide046"></label>
			   <img src="basico/06_04_01.png" />
			   <figcaption>Na parte inferior da página, crie links para áudios e vídeos da banda ou do cantor escolhido. Use links do Spotify ou Youtube. Lembre-se de usar as medidas para criar os <span class="code">iframes</span> dos vídeos.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="slide047" name="slide">
			   <label for="slide047"></label>
			   <img src="basico/06_04_01.png" />
			   <figcaption>No rodapé, você pode colocar informações de copyright com seu nome, usando o código do símbolo &copy;: <span class="code">&amp;copy;</span>.</figcaption>
		   </li>
		</ul>
		<img src="basico/06_04_00.png" class="fundo" style="visibility:hidden"/>
  </details>
  <p class="topop"><a href="#basico" class="topo">voltar ao topo</a></p>
  <img src="basico/tags001_0007.png" />
  <details class="sub"><summary>&#x1f4c3; Tabelas</summary>
	<p>Crie uma pasta chamada <span class="code">webdesign/pagina5</span> para inserir os arquivos da nossa próxima página, com tabelas. O arquivo principal HTML será chamado de <span class="code">index.htm</span>.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="slide048" name="slide">
			   <label for="slide048"></label>
			   <img src="basico/07_01_00.png" />
			   <figcaption>Usamos <span class="code">table</span> como a tag-mãe das células da tabela. Logo, vamos "aninhar" as tags das células da tabela dentro da tag <span class="code">table</span>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="slide049" name="slide">
			   <label for="slide049"></label>
			   <img src="basico/07_01_01.png" />
			   <figcaption>Toda vez que vamos criar uma linha de tabela, usamos a tag <span class="code">&lt;tr&gt;</span>. Esta tag, por sua vez, terá as tags das células das colunas <span class="code">&lt;td&gt;</span> ou <span class="code">&lt;th&gt;</span> "aninhadas". Dentro destas tags colocamos conteúdos de textos ou imagens.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="slide050" name="slide">
			   <label for="slide050"></label>
			   <img src="basico/07_01_02.png" />
			   <figcaption>As tags <span class="code">&lt;th&gt;</span> podem ser usadas na primeira linha de uma tabela, como linha de títulos. Os textos, podemos digitar diretamente sem tags, como mostra o exemplo. Para colocar imagens, colocamos a tag <span class="code">&lt;img</span> dentro da tag <span class="code">&lt;td</span>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="slide051" name="slide">
			   <label for="slide051"></label>
			   <img src="basico/07_01_03.png" />
			   <figcaption>Os atributos <span class="code">border</span> e <span class="code">bordercolor</span> definem a espessura e a cor da borda de cada célula, respectivamente. O atributo <span class="code">bgcolor</span> pode ser usado para mudar a cor de fundo de uma célula ou de uma linha. No exemplo, o atributo deixa a primeira linha com fundo verde.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="slide052" name="slide">
			   <label for="slide052"></label>
			   <img src="basico/07_01_04.png" />
			   <figcaption>Os atributos <span class="code">cellpadding</span> e <span class="code">cellspacing</span> são as margens interna e externa de cada célula, respectivamente. Salve a página e visualize em um navegador.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="slide053" name="slide">
			   <label for="slide053"></label>
			   <img src="basico/07_01_05.png" />
			   <figcaption>Esta é a função da criação de margens em tabelas. Geralmente usamos o padrão do HTML, com <span class="code">cellspacing="0"</span>.</figcaption>
		   </li>
		</ul>
		<img src="basico/07_01_00.png" class="fundo" style="visibility:hidden"/>
  </details>
  <img src="basico/tags001_0007a.png" />
  <details class="sub"><summary>&#x1f4c3; Galeria de imagens</summary>
	<p>Você pode usar a mesma pasta da Atividade 1: <span class="code">webdesign/atividade1</span>. Insira imagens na pasta de <span class="code">webdesign/atividade1/imagens</span>, para criar nossa Galeria.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="slide054" name="slide">
			   <label for="slide054"></label>
			   <img src="basico/07_02_01.png" />
			   <figcaption>Podemos criar a tabela que ocupe <b>100%</b> da largura da página. Se criarmos uma galeria com 4 imagens, cada célula terá <b>25%</b> da largura da linha da tabela. Estas dimensões só precisam ser colocadas nas células da primeira linha da tabela. As outras linhas herdarão os valores informados na primeira linha.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="slide055" name="slide">
			   <label for="slide055"></label>
			   <img src="basico/07_02_02.png" />
			   <figcaption>Agora você pode "aninhar" as tags de imagem <span class="code">&lt;img</span> dentro de tags de link <span class="code">&lt;a</span>, que estará dentro das respectivas tags de célula <span class="code">&lt;td</span>. Cuidado com as extensões e os caminhos dos arquivos!</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="slide056" name="slide">
			   <label for="slide056"></label>
			   <img src="basico/07_02_02.png" />
			   <figcaption>Este é um exemplo de 8 imagens colocadas em uma tabela de 2 linhas e 4 colunas. Experimente outros formatos. Note que não foram usadas as bordas da tabela neste exemplo. Se necessário, ajuste as alturas das imagens, caso fiquem diferentes na galeria. Salve e teste a página em um navegador.</figcaption>
		   </li>
		</ul>
		<img src="basico/07_02_00.png" class="fundo"/>
  </details>
  <img src="basico/tags001_0007b.png" />
  <details class="sub"><summary>&#x1f4c3; Galeria de vídeos e áudios</summary>
	<p>Você pode usar a mesma pasta da Atividade 1: <span class="code">webdesign/atividade1</span>. Insira arquivos de áudio na pasta de <span class="code">webdesign/atividade1/audios</span>, para criar nossa Galeria.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="slide057" name="slide">
			   <label for="slide057"></label>
			   <img src="basico/07_03_01.png" />
			   <figcaption>Podemos criar a tabela que ocupe <b>100%</b> da largura da página. Se criarmos uma galeria com 3 áudios em uma linha e 3 vídeos na outra linha, cada célula terá <b>33%</b> da largura da linha da tabela.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="slide058" name="slide">
			   <label for="slide058"></label>
			   <img src="basico/07_03_02.png" />
			   <figcaption>Agora você pode "aninhar" as tags <span class="code">&lt;audio</span> dentro das respectivas tags de célula <span class="code">&lt;td</span>. Cuidado com as extensões e os caminhos dos arquivos!</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="slide059" name="slide">
			   <label for="slide059"></label>
			   <img src="basico/07_03_03.png" />
			   <figcaption>Na linha de vídeos, você pode pegar as estruturas das tags <span class="code">&lt;iframe</span> do Youtube, ou criar tags <span class="code">&lt;video</span>. Estas tags devem estar "aninhadas" nas respectivas tags de célula <span class="code">&lt;td</span>.</figcaption>
		   </li>
		</ul>
		<img src="basico/07_03_00.png" class="fundo"/>
  </details>
  <p class="topop"><a href="#basico" class="topo">voltar ao topo</a></p>
  <img src="basico/tags001_0008.png" />
  <details class="sub"><summary>&#x1f4c3; Tabela de nutrientes</summary>
	<p>Vamos criar uma pasta para alguns exercícios: <span class="code">webdesign/exercicios</span>. Crie a página do primeiro exercício com o nome <span class="code">webdesign/exercicios/index.htm</span>.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="slide060" name="slide">
			   <label for="slide060"></label>
			   <img src="basico/08_01_01.png" />
			   <figcaption>Cada célula da tabela tem margem iterna <span class="code">cellpadding</span> de <b>15px</b>, borda na cor <b>cinza</b>. O atributo <span class="code">cellspacing</span> está com valor 0 para não deixar espaços entre as células.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="slide061" name="slide">
			   <label for="slide061"></label>
			   <img src="basico/08_01_01.png" />
			   <figcaption>As tags para criar a primeira linha da tabela usam linha de título <span class="code">&lt;th&gt;</span>, com alinhamento <b>centralizado</b>, fonte com a cor branca e o fundo de cada célula vermelho.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="slide062" name="slide">
			   <label for="slide062"></label>
			   <img src="basico/08_01_02.png" />
			   <figcaption>A segunda linha tem 2 células mescladas na primeira coluna. Para fazer esta operação em HTML usamos o atributo <span class="code">rowspan</span>, indicando quantas linhas serão mescladas. Neste caso, usamos <span class="code">rowspan="2"</span>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="slide063" name="slide">
			   <label for="slide063"></label>
			   <img src="basico/08_01_02.png" />
			   <figcaption>Temos as outras 3 células da linha 2 normalmente. Como a primeira célula da terceira linha foi mesclada, precisamos apenas das outras 3 células nesta linha.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="slide064" name="slide">
			   <label for="slide064"></label>
			   <img src="basico/08_01_03.png" />
			   <figcaption>A linha dos legumes não tem células mescladas, e os elementos são criados com tags <span class="code">&lt;td&gt;</span>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="slide065" name="slide">
			   <label for="slide065"></label>
			   <img src="basico/08_01_04.png" />
			   <figcaption>Na linha dos cereais, podemos mesclar as três células da primeira coluna com o atributo <span class="code">rowspan="3"</span>. As outras 2 linhas da tabela tem 3 células com os valores indicados no exemplo. Agora complete esta tabela, que vamos utilizar na próxima Atividade.</figcaption>
		   </li>
		</ul>
		<img src="basico/08_01_04.png" class="fundo" style="visibility:hidden"/>
  </details>
  <img src="basico/tags001_0008a.png" />
  <details class="sub"><summary>&#x1f4c3; Pesquisa fumantes</summary>
	<p>Este exercício é parecido com o anterior. Na mesma pasta, crie um arquivo: <span class="code">webdesign/exercicios/fumantes.htm</span>.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="slide066" name="slide">
			   <label for="slide066"></label>
			   <img src="basico/08_02_01.png" />
			   <figcaption>A primeira célula da primeira linha será mesclada com a célula de baixo. Logo, vamos usar o atributo <span class="code">rowspan="2"</span>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="slide067" name="slide">
			   <label for="slide067"></label>
			   <img src="basico/08_02_02.png" />
			   <figcaption>A segunda célula da primeira linha será mesclada com a célula do lado. Logo, vamos usar o atributo <span class="code">colspan="2"</span>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="slide068" name="slide">
			   <label for="slide068"></label>
			   <img src="basico/08_02_03.png" />
			   <figcaption>O mesmo acontece com a quarta célula da primeira linha: <span class="code">colspan="2"</span>. Agora prossiga para concluir a página HTML com esta tabela.</figcaption>
		   </li>
		</ul>
		<img src="basico/08_02_00.png" class="fundo"/>
  </details>
  <img src="basico/tags001_0008b.png" />
  <p class="topop"><a href="#basico" class="topo">voltar ao topo</a></p>
  <img src="basico/tags001_0009.png" />
  <details class="sub"><summary>&#x1f4c3; Tabela de cores</summary>
	<p>Neste exercício vamos criar uma tabela de cores. O exemplo mostra apenas alguns nomes de cores usados em HTML. Na mesma pasta, crie um arquivo: <span class="code">webdesign/exercicios/cores.htm</span>.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="slide069" name="slide">
			   <label for="slide069"></label>
			   <img src="basico/09_01_01.png" />
			   <figcaption>Temos duas formas de fazer esta tabela. A primeira é usando exatamente o layout mostrado no exercício. Dessa forma, criaremos sempre 1 linha que mostra somente as cores, e a linha de baixo mostra apenas os nomes das cores.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="slide070" name="slide">
			   <label for="slide070"></label>
			   <img src="basico/09_01_02.png" />
			   <figcaption>Na segunda maneira, podemos criar na mesma célula o nome da cor, com o fundo de mesma cor. Escolha um dos layouts e faça a página completa com a tabela de cores.</figcaption>
		   </li>
		</ul>
		<img src="basico/09_01_02.png" class="fundo" style="visibility:hidden"/>
  </details>
  <img src="basico/tags001_0009a.png" />
  <details class="sub"><summary>&#x1f4c3; Detalhes da Atividade</summary>
	<p>A partir desta página, vamos utilizar o software <b>NOTEPAD++</b> para criar nossos próximos projetos. Acesse o endereço <span class="code">https://notepad-plus-plus.org/downloads/v7.8.8/</span> e instale a versão correspondente do seu computador: 32 ou 64 bits. Crie uma pasta <span class="code">webdesign/atividade2</span> para criar os arquivos da próxima atividade. A página principal será <span class="code">index.htm</span></p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="slide071" name="slide">
			   <label for="slide071"></label>
			   <img src="basico/09_02_01.png" />
			   <figcaption>O layout da página do nosso site principal da Atividade 2 será feito usando tabelas. A estrutura está mostrada neste exemplo. A primeira tag, logo após começar o corpo da página será <span class="code">&lt;table</span>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="slide072" name="slide">
			   <label for="slide072"></label>
			   <img src="basico/09_02_02.png" />
			   <figcaption>O banner da página ocupará o espaço de 2 células, e por isso aplicamos o atributo <span class="code">colspan="2"</span>. Na segunda linha da tabela, criamos uma célula para o conteúdo principal, e outra para a barra lateral com as tags <span class="code">&lt;tr</span> e <span class="code">&lt;td</span></figcaption>
		   </li>
		   <li>
			   <input type="radio" id="slide073" name="slide">
			   <label for="slide073"></label>
			   <img src="basico/09_02_02.png" />
			   <figcaption>Para finalizar, colocamos o rodapé da página. Este item será inserido com as tags <span class="code">&lt;tr</span> e <span class="code">&lt;td</span> usando o atributo de <span class="code">colspan="2"</span> para usar a largura toda da página.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="slide074" name="slide">
			   <label for="slide074"></label>
			   <img src="basico/09_02_04.png" />
			   <figcaption>A tag de fonte pode ser usada antes da tabela de layout da página. O <b>Notepad++</b> coloca em destaque quando reconhece tags fechadas, facilitando muito a programação da página.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="slide075" name="slide">
			   <label for="slide075"></label>
			   <img src="basico/09_02_05.png" />
			   <figcaption>As propriedades <span class="code">cellspacing</span> e <span class="code">cellpadding</span> são usadas para fazer as margens interna e externa de cada parte do layout da página. A largura da tabela deve ser de <b>100%</b> para distribuir todo o conteúdo na tela do navegador.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="slide076" name="slide">
			   <label for="slide076"></label>
			   <img src="basico/09_02_06.png" />
			   <figcaption>A primeira linha, indicada com a tag <span class="code">&lt;tr</span> contém o banner, com o atributo <span class="code">colspan="2"</span> dentro da tag da célula <span class="code">&lt;td</span>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="slide077" name="slide">
			   <label for="slide077"></label>
			   <img src="basico/09_02_08.png" />
			   <figcaption>A segunda linha da tabela contém a primeira célula do conteúdo principal da página, com a largura de <b>70%</b> e a barra lateral com largura de <b>30%</b>. Dentro das tags <span class="code">&lt;td</span> podemos inserir os textos e imagens da página.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="slide078" name="slide">
			   <label for="slide078"></label>
			   <img src="basico/09_02_10.png" />
			   <figcaption>Note que o conteúdo da barra lateral geralmente é menor do que o conteúdo principal da página. Por isso, podemos usar o atributo de alinhamento vertical <span class="code">valign="top"</span> para deixar estas partes do site alinhadas. Repare no link para acessar a página de nutrientes.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="slide079" name="slide">
			   <label for="slide079"></label>
			   <img src="basico/09_02_10.png" />
			   <figcaption>Usando o layout dessa página, você pode criar a página <span class="code">nutrientes.htm</span> na mesma pasta da página <span class="code">index.htm</span>. Pegue todo o código da tabela que fizemos dos nutrientes e insira na tag principal desta página (a que tem <b>70%</b> de largura).</figcaption>
			   </li>
		   <li>
			   <input type="radio" id="slide080" name="slide">
			   <label for="slide080"></label>
			   <img src="basico/09_02_11.png" />
			   <figcaption>O layout mostrado neste exemplo fica desta forma. Usando a estrutura mostrada neste exemplo, crie o site de um restaurante.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="slide081" name="slide">
			   <label for="slide081"></label>
			   <img src="basico/09_02_12.png" />
			   <figcaption>O layout mostrado neste exemplo fica desta forma. Usando a estrutura mostrada neste exemplo, crie o site de um restaurante.</figcaption>
		   </li>
		</ul>
		<img src="basico/09_02_02.png" class="fundo" style="visibility:hidden"/>
  </details>
  <img src="basico/tags001_0009b.png" />
  <p class="topop"><a href="#basico" class="topo">voltar ao topo</a></p>
  <img src="basico/tags001_0010.png" />
  <p class="topop"><a href="#basico" class="topo">voltar ao topo</a></p>
</details>
<details><summary>CSS: Cascading Style Sheets</summary>
	<p>página 11...</p>
</details>
<br>&#x1f4bb; &#x1f4c2;
<p><b>site desenvolvido por:</b></p> 
<p>Paulo Henrique Siqueira</p>  
<p><b>contato:</b> paulohscwb@gmail.com </p> 

<p><br><b>Referências:</b></p>
