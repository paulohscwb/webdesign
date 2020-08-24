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
			   <input type="radio" id="slide005" name="slide" checked>
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
			   <input type="radio" id="slide007" name="slide" checked>
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
			   <input type="radio" id="slide010" name="slide" checked>
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
			   <input type="radio" id="slide012" name="slide" checked>
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
			   <input type="radio" id="slide016" name="slide" checked>
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
			   <figcaption>Neste exemplo, foi usada uma tag por dentro da outra (aninhadas). Um trecho foi destacado em negrito e itálico com as tags <span class="code">&lt;b&gt;&lt;i&gt;</span>. Note que ambas precisam ser fechadas.</figcaption>
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
			   <input type="radio" id="slide021" name="slide" checked>
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
			   <input type="radio" id="slide025" name="slide" checked>
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
	<p>Usando a mesma página3.html, vamos criar links. Os links podem ser criados em textos ou imagens.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="slide028" name="slide" checked>
			   <label for="slide028"></label>
			   <img src="basico/05_02_01.png" />
			   <figcaption>A tag de link é <span class="code">&lt;a</span>, e ´precisa de fechamento para você limitar o que o visitante clica para visitar uma outra página. Neste primeiro exemplo, o link está em um texto.</figcaption>
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
  <p class="topop"><a href="#basico" class="topo">voltar ao topo</a></p>
  <img src="basico/tags001_0007.png" />
  <p class="topop"><a href="#basico" class="topo">voltar ao topo</a></p>
  <img src="basico/tags001_0008.png" />
  <p class="topop"><a href="#basico" class="topo">voltar ao topo</a></p>
  <img src="basico/tags001_0009.png" />
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
