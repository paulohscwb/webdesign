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
			   <input type="radio" id="001" name="sl" checked>
			   <label for="001"></label>
			   <img src="basico/01_01_01.png"/>
			   <figcaption>Acessando o site <a href="http://html-color-codes.info/Codigos-de-Cores-HTML/" target="_blank">http://html-color-codes.info/Codigos-de-Cores-HTML/</a>, você pode clicar em cores pré-definidas pelo site. Note que o código hexadecimal aparece logo abaixo das cores.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="002" name="sl">
			   <label for="002"></label>
			   <img src="basico/01_01_02.png"/>
			   <figcaption>Logo abaixo, você encontra outra maneira de escolher cores neste mesmo site. Basta escolher o tom da cor e clicar sobre a cor escolhida.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="003" name="sl">
			   <label for="003"></label>
			   <img src="basico/01_01_03.png"/>
			   <figcaption>Acessando o site <a href="https://color.adobe.com/pt/create/color-wheel/" target="_blank">https://color.adobe.com/pt/create/color-wheel/</a>, você pode escolher as cores de forma análoga. Note que aparecem os códigos hexadecimais e RGB logo abaixo do disco de cores.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="004" name="sl">
			   <label for="004"></label>
			   <img src="basico/01_01_04.png" />
			   <figcaption>Outro site interessante é <a href="https://celke.com.br/artigo/tabela-de-cores-html-nome-hexadecimal-rgb" target="_blank">https://celke.com.br/artigo/tabela-de-cores-html-nome-hexadecimal-rgb</a>, que além dos códigos RGB e hexadecimais mostra os nomes das cores usadas em HTML na primeira coluna da tabela. 
			   </figcaption>
		   </li>
		   <li>
			   <input type="radio" id="004a" name="sl">
			   <label for="004a"></label>
			   <img src="basico/01_01_05.png" />
			   <figcaption>O site <a href="https://html-color.codes" target="_blank">https://html-color.codes</a> também é uma ótima opção para escolhermos cores para nossas páginas. As cores ficam separadas por tonalidades.
			   </figcaption>
		   </li>
		</ul>
		<img src="basico/01_01_00.png" class="fundo" style="visibility:hidden" />
  </details>
  <img src="basico/tags001_0001a.png" />
   <details class="sub"><summary>&#x1f4c3; Texto para testar layouts</summary>
	<p>Muitas vezes, nosso foco é de testar somente o layout de um site. Podemos preenchê-lo com textos e listas usando o site mostrado nesta página. Clique nos passos abaixo para ver como produzir estes conteúdos.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="005" name="sl">
			   <label for="005"></label>
			   <img src="basico/01_02_01.png" />
			   <figcaption>Acessando o site <a href="http://br.lipsum.com/" target="_blank">http://br.lipsum.com/</a>, você pode criar blocos de textos ou listas, usados para testarmos layouts.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="006" name="sl">
			   <label for="006"></label>
			   <img src="basico/01_02_02.png" />
			   <figcaption>Escolha a criação de 2 parágrafos para fazermos um teste. Copie e cole este texto produzido no programa <code>Notepad</code> (<code>Bloco de Notas</code>) do Windows.</figcaption>
		   </li>
		</ul>
		<img src="basico/01_02_00.png" class="fundo"/>
  </details>
  <p class="topop"><a href="#basico" class="topo">voltar ao topo</a></p>
  <img src="basico/tags001_0002.png" />
  <details class="sub"><summary>&#x1f4c3; Texto para testar layouts</summary>
	<p>Vamos salvar nosso arquivo em uma pasta chamada <code>webdesign</code>.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="007" name="sl">
			   <label for="007"></label>
			   <img src="basico/02_01_00.png" />
			   <figcaption>Escolha a opção do Bloco de Notas <code>Salvar como</code>. Salve o arquivo como <code>pagina1.htm</code>. Uma dica importantíssima é de <b>não usar acentuação para nomear as páginas</b>!!!</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="008" name="sl">
			   <label for="008"></label>
			   <img src="basico/02_01_01.png" />
			   <figcaption>É muito importante lembrar que a extensão do arquivo deve ser <code>.htm</code> ou <code>.html</code>. Abra o arquivo em um navegador de internet. Como não foram feitas as marcações dos parágrafos, vamos colocá-las no arquivo.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="009" name="sl">
			   <label for="009"></label>
			   <img src="basico/02_01_02.png" />
			   <figcaption>Antes de cada parágrafo, devemos colocar a tag <code>&lt;p&gt;</code>. Logo após o parágrafo, colocamos a tag de fechamento de parágrafo <code>&lt;/p&gt;</code>. Faça isso nos 2 parágrafos e visualize a página em um navegador.</figcaption>
		   </li>
		</ul>
		<img src="basico/02_01_00.png" class="fundo"/>
  </details>
  <img src="basico/tags001_0002a.png" />
  <p class="topop"><a href="#basico" class="topo">voltar ao topo</a></p>
  <img src="basico/tags001_0003.png" />
  <details class="sub"><summary>&#x1f4c3; Layout básico de uma página</summary>
	<p>O layout básico de uma página HTML tem as seguintes partes: cabeçalho (<code>head</code>) e corpo da página (<code>body</code>). Vamos ver os elementos de cada parte:</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="010" name="sl">
			   <label for="010"></label>
			   <img src="basico/03_01_01.png" />
			   <figcaption>O cabeçalho <code>&lt;head&gt;</code> contém informações autorais, título, codificação de caracteres, palavras-chave, scripts e referências externas. Nem todos os elementos desta tag são visíveis para os visitantes da página.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="011" name="sl">
			   <label for="011"></label>
			   <img src="basico/03_01_02.png" />
			   <figcaption>Dentro da tag do corpo da página <code>&lt;body&gt;</code> devemos colocar todos os contéudos visíveis para os visitantes.</figcaption>
		   </li>
		</ul>
		<img src="basico/03_01_00.png" class="fundo"/>
  </details>
  <img src="basico/tags001_0003a.png" />
  <details class="sub"><summary>&#x1f4c3; Fundo da página, alinhamentos</summary>
	<p>Vamos deixar todos os arquivos desta disciplina organizados. Podemos criar uma pasta chamada <code>pagina1</code> para colocar todos os arquivos desta primeira página. É importante deixar os arquivos sempre organizados em pastas para usarmos as referências corretas na hora de montar o site.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="012" name="sl">
			   <label for="012"></label>
			   <img src="basico/03_02_01.png" />
			   <figcaption>Crie uma pasta dentro da pasta <code>pagina1</code> para colocarmos as imagens. Podemos chamá-la de <code>imagens</code>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="012a" name="sl">
			   <label for="012a"></label>
			   <img src="basico/03_02_02.png" />
			   <figcaption>Podemos escolher uma imagem para colocar no fundo da página (<code>background</code>). Escolha uma com largura maior do que 1000px, para cobrir todo o fundo da página, e salve na pasta que criamos <code>/imagens</code>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="013" name="sl">
			   <label for="013"></label>
			   <img src="basico/03_02_02.png" />
			   <figcaption>Na tag do corpo da página, colocamos o caminho da imagem salva: <code>&lt;body background="imagens/fundo.jpg"&gt;</code>. Salve e veja a página renderizada em um navegador.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="014a" name="sl">
			   <label for="014a"></label>
			   <img src="basico/03_02_03.png" />
			   <figcaption>Os alinhamentos dos parágrafos podem ser definidos dentro de cada tag. Por exemplo, se você quiser deixar o primeiro parágrafo justificado, basta usar a tag <code>&lt;p align="justify"&gt;</code>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="014" name="sl">
			   <label for="014"></label>
			   <img src="basico/03_02_04.png" />
			   <figcaption>Para destacar partes do texto, podemos mudar cores e tamanhos. Neste exemplo, dois trechos estão destacados com cores diferentes usando a tag <code>&lt;font&gt;</code>. Dentro desta tag, você muda cor, tamanho e família da fonte (face). Note que ela precisa de fechamento para o fim do destaque: <code>&lt;/font&gt;</code></figcaption>
		   </li>
		   <li>
			   <input type="radio" id="015" name="sl">
			   <label for="015"></label>
			   <img src="basico/03_02_05.png" />
			   <figcaption>Se você quiser que a página toda tenha uma configuração específica de fonte, basta abrir a tag no começo do corpo da página, e fechá-la antes do fechamento da tag <code>&lt;/body&gt;</code>. No exemplo, foi colocada a fonte <b>Verdana</b> na página toda.</figcaption>
		   </li>
		</ul>
		<img src="basico/03_02_03.png" class="fundo" style="visibility:hidden"/>
  </details>
  <img src="basico/tags001_0003b.png" />
  <details class="sub"><summary>&#x1f4c3; Barra separadora e títulos</summary>
	<p>Podemos separar conteúdos usando uma tag simples de barra horizontal. Além disso, podemos destacar trechos do texto colocando negrito, itálico ou sublinhado. Títulos de seções também podem ser feitos com tags simples mostradas a seguir:</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="016" name="sl">
			   <label for="016"></label>
			   <img src="basico/03_03_01.png" />
			   <figcaption>Usando a tag <code>&lt;hr&gt;</code>, podemos separar conteúdos na página. Essa tag não precisa ser fechada! Você pode configurar a altura, largura e cor. A largura em percentual é muito usada para deixar o site responsivo, ou seja, que abre em qualquer dispositivo.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="017" name="sl">
			   <label for="017"></label>
			   <img src="basico/03_03_02.png" />
			   <figcaption>Os títulos de seções podem ser definidos com as tags h1, h2, ..., h6. No exemplo, usamos o título com a tag <code>&lt;h3&gt;</code>. Quanto maior o número, menor o tamanho da fonte desta tag. Experimente mudar essa tag para h1 e h6.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="018" name="sl">
			   <label for="018"></label>
			   <img src="basico/03_03_03.png" />
			   <figcaption>A tag de negrito <code>&lt;b&gt;</code> foi usada neste exemplo para um trecho do texto. Não esqueça de fechá-la para que seu site apareça corretamente. Salve a página renderizada em um navegador.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="019" name="sl">
			   <label for="019"></label>
			   <img src="basico/03_03_04.png" />
			   <figcaption>Neste exemplo, foi usada uma tag por dentro da outra (aninhada). Um trecho foi destacado em negrito e itálico com as tags <code>&lt;b&gt;&lt;i&gt;</code>. Note que ambas precisam ser fechadas.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="020" name="sl">
			   <label for="020"></label>
			   <img src="basico/03_03_05.png" />
			   <figcaption>Se você quiser destacar um trecho do texto deixando-o riscado, basta usar a tag <code>&lt;strike&gt;Sed sit amet pharetra leo.&lt;/strike&gt;</code>. Essa tag é usada em sites para mostrar preços de produtos.</figcaption>
		   </li>
		</ul>
		<img src="basico/03_03_00.png" class="fundo"/>
  </details>
  <p class="topop"><a href="#basico" class="topo">voltar ao topo</a></p>
  <img src="basico/tags001_0004.png" />
  <details class="sub"><summary>&#x1f4c3; Listas</summary>
	<p>Agora vamos criar uma outra página, dentro da pasta da disciplina, crie a pasta <code>webdesign/pagina2/</code>. Nesta página, vamos criar elementos de listas.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="021" name="sl">
			   <label for="021"></label>
			   <img src="basico/04_01_01.png" />
			   <figcaption>Dependendo do servidor usado para hospedar sua página, devemos modificar a codificação de caracteres charset de <b>UTF-8</b> para <b>ISO-8859-1</b>. Porém, a maioria dos servidores usa o <b>UTF-8</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="022" name="sl">
			   <label for="022"></label>
			   <img src="basico/04_01_02.png" />
			   <figcaption>Usando a tag <code>&lt;ul&gt;</code>, podemos criar listas na página. Este exemplo mostra os marcadores circulares da lista.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="023" name="sl">
			   <label for="023"></label>
			   <img src="basico/04_01_03.png" />
			   <figcaption>Os itens das listas têm tags <code>&lt;li&gt;</code>. Note que cada tag de item precisa ser fechada, depois que você coloca o conteúdo. Para mudar de cor, coloque a tag de fonte aninhada na tag de item da lista. Mude as cores dos outros itens.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="024" name="sl">
			   <label for="024"></label>
			   <img src="basico/04_01_04.png" />
			   <figcaption>As listas ordenadas têm a mesma estrutura da lista norma, com a tag principal <code>&lt;ol&gt;</code>. Estas tags podem ser numéricas ou com letras. Neste exemplo, a lista com letras começa na 4&ordf; letra, ou seja, a letra <b>D</b>.</figcaption>
		   </li>
		</ul>
		<img src="basico/04_01_00.png" class="fundo"/>
  </details>
  <img src="basico/tags001_0004a.png" />
  <p class="topop"><a href="#basico" class="topo">voltar ao topo</a></p>
  <img src="basico/tags001_0005.png" />
  <details class="sub"><summary>&#x1f4c3; Imagens</summary>
	<p>Agora vamos criar uma outra página, dentro da pasta da disciplina: crie a pasta <code>webdesign/pagina3/</code>. Nesta página, vamos inserir imagens, por isso, crie uma pasta <code>webdesign/pagina3/imagens</code> para colocarmos todas as imagens do site. Escolha 3 imagens e coloque nesta pasta. As extensões podem ser <b>png</b>, <b>jpg</b> ou <b>jpeg</b>. Preste atenção no atributo <code>src</code>, que contém o caminho da imagem.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="025" name="sl">
			   <label for="025"></label>
			   <img src="basico/05_01_01.png" />
			   <figcaption>A tag de imagem pode ser colocada no meio do texto usando o código <code>&lt;img&gt;</code>. Todos os atributos desta tag ficam dentro da <code>&lt;img&gt;</code>, não precisando ser fechada. A largura em percentual é importante para deixar o site responsivo.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="026" name="sl">
			   <label for="026"></label>
			   <img src="basico/05_01_02.png" />
			   <figcaption>Neste segundo exemplo, a imagem também está misturada com o texto, alinhada no meio do texto. Não recomenda-se o uso das imagens misturadas, pois o layout da página fica prejudicado.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="026a" name="sl">
			   <label for="026a"></label>
			   <img src="basico/05_01_02.png" />
			   <figcaption>Os atributos <code>hspace</code> e <code>vspace</code> criam margens horizontais e verticais em torno da imagem. São ótimas para não deixar outros elementos "grudados" nas imagens.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="027" name="sl">
			   <label for="027"></label>
			   <img src="basico/05_01_03.png" />
			   <figcaption>De uma forma bem mais organizada, podemos criar a tag-mãe <code>&lt;figure&gt;</code>, que contém a imagem, e logo depois uma tag de legenda <code>&lt;figcaption&gt;</code>. Neste caso, a tag de parágrafo centralizado foi usada para deixar a legenda alinhada com a imagem.</figcaption>
		   </li>
		</ul>
		<img src="basico/05_01_00.png" class="fundo"/>
  </details>
  <img src="basico/tags001_0005a.png" />
  <details class="sub"><summary>&#x1f4c3; Links</summary>
	<p>Usando a mesma <code>pagina3.htm</code>, vamos criar links. Os links podem ser criados em textos ou imagens.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="028" name="sl">
			   <label for="028"></label>
			   <img src="basico/05_02_01.png" />
			   <figcaption>A tag de link é <code>&lt;a&gt;</code>, e precisa de fechamento para você limitar o que o visitante clica para visitar uma outra página. Neste primeiro exemplo, o link está em um texto.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="029" name="sl">
			   <label for="029"></label>
			   <img src="basico/05_02_01.png" />
			   <figcaption>O atributo <code>href</code> é obrigatório, e indica o endereço da página que será visitada. O atributo <code>target="_blank"</code> indica que a página será aberta em outra aba.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="030" name="sl">
			   <label for="030"></label>
			   <img src="basico/05_02_02.png" />
			   <figcaption>Para inserir um link em uma imagem, basta deixar a tag <code>&lt;a&gt;</code> aninhada com a tag <code>&lt;img&gt;</code>, como mostra este segundo exemplo. Crie os links, salve a página e teste em um navegador.</figcaption>
		   </li>
		</ul>
		<img src="basico/05_02_00.png" class="fundo"/>
  </details>
  <p class="topop"><a href="#basico" class="topo">voltar ao topo</a></p>
  <img src="basico/tags001_0006.png" />
  <details class="sub"><summary>&#x1f4c3; Áudios</summary>
	<p>Usando a mesma <code>pagina3.htm</code>, vamos inserir tags de áudios. Quando você salvar a página e visualizar em um navegador, a opção com controles fornece um "frame" para o vídeo que fica similar à seguinte imagem:</p>
	<p align="center"><img src="basico/06_01_04.png" width="40%" /></p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="031" name="sl">
			   <label for="031"></label>
			   <img src="basico/06_01_00.png" />
			   <figcaption>Na mesma pasta da nossa<code>pagina3</code>, podemos criar uma subpasta chamada <code>audios</code>. Assim, a estrutura de arquivos da nossa página fica organizada.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="032" name="sl">
			   <label for="032"></label>
			   <img src="basico/06_01_01.png" />
			   <figcaption>Podemos usar a tag <code>audio</code> em uma única linha, com todas as propriedades definidas dentro desta tag. Esta maneira é comum quando apenas um arquivo é inserido. Os navegadores atuais suportam arquivos com extensão <code>mp3</code>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="033" name="sl">
			   <label for="033"></label>
			   <img src="basico/06_01_02.png" />
			   <figcaption>Em navegadores muito antigos, por precaução, podemos definir os formatos <code>mp3</code> e <code>ogg</code>. Esta tag é do tipo aninhada, com os caminhos (src) dos 2 arquivos definidos.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="034" name="sl">
			   <label for="034"></label>
			   <img src="basico/06_01_03.png" />
			   <figcaption>O atributo <code>controls</code> serve para mostrar os controles para o visitante interagir com o audio. O atributo <code>autoplay</code> define a reprodução automática do arquivo.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="034a" name="sl">
			   <label for="034a"></label>
			   <img src="basico/06_01_05.png" />
			   <figcaption>Você pode colocar links para áudios em uma página. Acessando o site <code>open.spotify.com</code>, você pode selecionar as músicas e copiar seus links.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="034b" name="sl">
			   <label for="034b"></label>
			   <img src="basico/06_01_05a.png" />
			   <figcaption>Você pode criar também os links para álbuns, da mesma maneira mostrada para músicas. Na página HTML usamos a tag de link <code>&lt;a&gt;</code> para os álbuns.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="034c" name="sl">
			   <label for="034c"></label>
			   <img src="basico/06_01_06.png" />
			   <figcaption>Usando a tag de link <code>&lt;a&gt;</code>, você insere os links de músicas em sua página.</figcaption>
		   </li>
		</ul>
		<img src="basico/06_01_00.png" class="fundo" style="visibility:hidden"/>
  </details>
  <img src="basico/tags001_0006a.png" />
  <details class="sub"><summary>&#x1f4c3; Vídeos</summary>
	<p>Vamos criar uma nova pasta chamada <code>webdesign/pagina4</code>. Dentro desta pasta, crie as subpastas de <code>imagens</code> e de <code>videos</code>. Quando você salvar a página e visualizar em um navegador, a opção com controles fornece uma imagem similar à esta:</p>
	<p align="center"><img src="basico/06_02_05.png" width="60%" /></p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="035" name="sl">
			   <label for="035"></label>
			   <img src="basico/06_02_01.png" />
			   <figcaption>Escolha um arquivo de imagem (pode ser no google) para colocar como um banner da nossa <code>pagina4.htm</code>. Cuidado com a extensão da imagem (jpg, png, jpeg) para indicar o caminho no código HTML.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="036" name="sl">
			   <label for="036"></label>
			   <img src="basico/06_02_02.png" />
			   <figcaption>Podemos usar a tag <code>video</code> em uma única linha, com todas as propriedades definidas dentro desta tag. Esta maneira é comum quando apenas um arquivo é inserido. A maioria dos navegadores atuais suportam arquivos com extensões <code>mp4</code>, <code>webm</code> e <code>ogv</code>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="037" name="sl">
			   <label for="037"></label>
			   <img src="basico/06_02_03.png" />
			   <figcaption>Por precaução, podemos definir os formatos <code>mp4</code>, <code>webm </code>e <code>ogv</code> dentro de uma tag de vídeo. Esta tag é do tipo aninhada, com os caminhos (src) dos 3 arquivos de vídeo.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="038" name="sl">
			   <label for="038"></label>
			   <img src="basico/06_02_04.png" />
			   <figcaption>O atributo <code>controls</code> serve para mostrar os controles para o visitante interagir com o vídeo. O atributo <code>autoplay</code> define a reprodução automática do vídeo.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="039" name="sl">
			   <label for="039"></label>
			   <img src="basico/06_02_04.png" />
			   <figcaption>Quando inserimos vídeos em uma página, é importante definirmos a altura <code>height</code> e a largura <code>width</code> do vídeo. Estas medidas podem ser indicadas em % ou pixels.</figcaption>
		   </li>
		</ul>
		<img src="basico/06_02_00.png" class="fundo" style="visibility:hidden"/>
  </details>
  <img src="basico/tags001_0006b.png" />
  <details class="sub"><summary>&#x1f4c3; Vídeos do Youtube</summary>
	<p>Para inserir um vídeo do Youtube, usamos a tag <code>iframe</code>. Vamos usar a mesma <code>pagina4.htm</code> para inserir esta tag de vídeo.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="040" name="sl">
			   <label for="040"></label>
			   <img src="basico/06_03_00.png" />
			   <figcaption>Na página do vídeo escolhido, clique em <code>compartilhar</code>, no link que fica logo abaixo da janela do vídeo.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="041" name="sl">
			   <label for="041"></label>
			   <img src="basico/06_03_01.png" />
			   <figcaption>Selecione a opção <code>incorporar</code>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="042" name="sl">
			   <label for="042"></label>
			   <img src="basico/06_03_02.png" />
			   <figcaption>Agora é só copiar a tag <code>iframe</code> criada. Note que aparecem as medidas que já usamos na tag de <code>video</code>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="043" name="sl">
			   <label for="043"></label>
			   <img src="basico/06_03_03.png" />
			   <figcaption>Cole a tag criada na posição da página que você quer mostrar o vídeo. O atributo <code>frameborder</code> tem padrão com valor <b>0</b>. Se você quiser uma borda, basta digitar qualquer valor diferente de <b>0</b> neste atributo.</figcaption>
		   </li>
		</ul>
		<img src="basico/06_03_03.png" class="fundo" style="visibility:hidden"/>
  </details>
  <img src="basico/tags001_0006c.png" />
  <details class="sub"><summary>&#x1f4c3; Detalhes da Atividade</summary>
	<p>Usando todas as tags que vimos até agora, vamos montar uma página htm com os elementos descritos abaixo. Crie uma pasta chamada <code>webdesign/atividade1</code> para inserir os arquivos desta atividade. O arquivo principal HTML será chamado de <code>index.htm</code>.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="044" name="sl">
			   <label for="044"></label>
			   <img src="basico/06_04_00.png" />
			   <figcaption>Na parte superior da página, que terá um formato tipo blog, coloque uma imagem como <code>banner</code>, textos de informações e curiosidades sobre a banda ou o cantor escolhido.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="045" name="sl">
			   <label for="045"></label>
			   <img src="basico/06_04_00.png" />
			   <figcaption>Insira imagens, uma imagem de fundo <code>background</code>. Lembre-se de colocar as medidas de altura e largura da imagem na página. Use as tags de linhas horizontais <code>&lt;hr&gt;</code> para separar conteúdos.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="046" name="sl">
			   <label for="046"></label>
			   <img src="basico/06_04_01.png" />
			   <figcaption>Na parte inferior da página, crie links para áudios e vídeos da banda ou do cantor escolhido. Use links do Spotify ou Youtube. Lembre-se de usar as medidas para criar os <code>iframes</code> dos vídeos.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="047" name="sl">
			   <label for="047"></label>
			   <img src="basico/06_04_01.png" />
			   <figcaption>No rodapé, você pode colocar informações de copyright com seu nome, usando o código do símbolo &copy;: <code>&amp;copy;</code>.</figcaption>
		   </li>
		</ul>
		<img src="basico/06_04_00.png" class="fundo" style="visibility:hidden"/>
  </details>
  <p class="topop"><a href="#basico" class="topo">voltar ao topo</a></p>
  <img src="basico/tags001_0007.png" />
  <details class="sub"><summary>&#x1f4c3; Tabelas</summary>
	<p>Crie uma pasta chamada <code>webdesign/pagina5</code> para inserir os arquivos da nossa próxima página, com tabelas. O arquivo principal HTML será chamado de <code>index.htm</code>.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="048" name="sl">
			   <label for="048"></label>
			   <img src="basico/07_01_00.png" />
			   <figcaption>Usamos <code>table</code> como a tag-mãe das células da tabela. Logo, vamos "aninhar" as tags das células da tabela dentro da tag <code>table</code>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="049" name="sl">
			   <label for="049"></label>
			   <img src="basico/07_01_01.png" />
			   <figcaption>Toda vez que vamos criar uma linha de tabela, usamos a tag <code>&lt;tr&gt;</code>. Esta tag, por sua vez, terá as tags das células das colunas <code>&lt;td&gt;</code> ou <code>&lt;th&gt;</code> "aninhadas". Dentro destas tags colocamos conteúdos de textos ou imagens.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="050" name="sl">
			   <label for="050"></label>
			   <img src="basico/07_01_02.png" />
			   <figcaption>As tags <code>&lt;th&gt;</code> podem ser usadas na primeira linha de uma tabela, como linha de títulos. Os textos, podemos digitar diretamente sem tags, como mostra o exemplo. Para colocar imagens, colocamos a tag <code>&lt;img&gt;</code> dentro da tag <code>&lt;td&gt;</code>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="051" name="sl">
			   <label for="051"></label>
			   <img src="basico/07_01_03.png" />
			   <figcaption>Os atributos <code>border</code> e <code>bordercolor</code> definem a espessura e a cor da borda de cada célula, respectivamente. O atributo <code>bgcolor</code> pode ser usado para mudar a cor de fundo de uma célula ou de uma linha. No exemplo, o atributo deixa a primeira linha com fundo verde.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="052" name="sl">
			   <label for="052"></label>
			   <img src="basico/07_01_04.png" />
			   <figcaption>Os atributos <code>cellpadding</code> e <code>cellspacing</code> são as margens interna e externa de cada célula, respectivamente. Salve a página e visualize em um navegador.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="053" name="sl">
			   <label for="053"></label>
			   <img src="basico/07_01_05.png" />
			   <figcaption>Esta é a função da criação de margens em tabelas. Geralmente usamos o padrão do HTML, com <code>cellspacing="0"</code>.</figcaption>
		   </li>
		</ul>
		<img src="basico/07_01_00.png" class="fundo" style="visibility:hidden"/>
  </details>
  <img src="basico/tags001_0007a.png" />
  <details class="sub"><summary>&#x1f4c3; Galeria de imagens</summary>
	<p>Você pode usar a mesma pasta da Atividade 1: <code>webdesign/atividade1</code>. Insira imagens na pasta de <code>webdesign/atividade1/imagens</code>, para criar nossa Galeria.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="054" name="sl">
			   <label for="054"></label>
			   <img src="basico/07_02_01.png" />
			   <figcaption>Podemos criar a tabela que ocupe <b>100%</b> da largura da página. Se criarmos uma galeria com 4 imagens, cada célula terá <b>25%</b> da largura da linha da tabela. Estas dimensões só precisam ser colocadas nas células da primeira linha da tabela. As outras linhas herdarão os valores informados na primeira linha.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="055" name="sl">
			   <label for="055"></label>
			   <img src="basico/07_02_02.png" />
			   <figcaption>Agora você pode "aninhar" as tags de imagem <code>&lt;img&gt;</code> dentro de tags de link <code>&lt;a&gt;</code>, que estará dentro das respectivas tags de célula <code>&lt;td&gt;</code>. Cuidado com as extensões e os caminhos dos arquivos!</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="056" name="sl">
			   <label for="056"></label>
			   <img src="basico/07_02_02.png" />
			   <figcaption>Este é um exemplo de 8 imagens colocadas em uma tabela de 2 linhas e 4 colunas. Experimente outros formatos. Note que não foram usadas as bordas da tabela neste exemplo. Se necessário, ajuste as alturas das imagens, caso fiquem diferentes na galeria. Salve e teste a página em um navegador.</figcaption>
		   </li>
		</ul>
		<img src="basico/07_02_00.png" class="fundo"/>
  </details>
  <img src="basico/tags001_0007b.png" />
  <details class="sub"><summary>&#x1f4c3; Galeria de vídeos e áudios</summary>
	<p>Você pode usar a mesma pasta da Atividade 1: <code>webdesign/atividade1</code>. Insira arquivos de áudio na pasta de <code>webdesign/atividade1/audios</code>, para criar nossa Galeria.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="057" name="sl">
			   <label for="057"></label>
			   <img src="basico/07_03_01.png" />
			   <figcaption>Podemos criar a tabela que ocupe <b>100%</b> da largura da página. Se criarmos uma galeria com 3 áudios em uma linha e 3 vídeos na outra linha, cada célula terá <b>33%</b> da largura da linha da tabela.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="058" name="sl">
			   <label for="058"></label>
			   <img src="basico/07_03_02.png" />
			   <figcaption>Agora você pode "aninhar" as tags <code>&lt;audio&gt;</code> dentro das respectivas tags de célula <code>&lt;td&gt;</code>. Cuidado com as extensões e os caminhos dos arquivos!</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="059" name="sl">
			   <label for="059"></label>
			   <img src="basico/07_03_03.png" />
			   <figcaption>Na linha de vídeos, você pode pegar as estruturas das tags <code>&lt;iframe&gt;</code> do Youtube, ou criar tags <code>&lt;video&gt;</code>. Estas tags devem estar "aninhadas" nas respectivas tags de célula <code>&lt;td&gt;</code>.</figcaption>
		   </li>
		</ul>
		<img src="basico/07_03_00.png" class="fundo"/>
  </details>
  <p class="topop"><a href="#basico" class="topo">voltar ao topo</a></p>
  <img src="basico/tags001_0008.png" />
  <details class="sub"><summary>&#x1f4c3; Tabela de nutrientes</summary>
	<p>Vamos criar uma pasta para alguns exercícios: <code>webdesign/exercicios</code>. Crie a página do primeiro exercício com o nome <code>webdesign/exercicios/index.htm</code>.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="060" name="sl">
			   <label for="060"></label>
			   <img src="basico/08_01_01.png" />
			   <figcaption>Cada célula da tabela tem margem iterna <code>cellpadding</code> de <b>15px</b>, borda na cor <b>cinza</b>. O atributo <code>cellspacing</code> está com valor 0 para não deixar espaços entre as células.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="061" name="sl">
			   <label for="061"></label>
			   <img src="basico/08_01_01.png" />
			   <figcaption>As tags para criar a primeira linha da tabela usam linha de título <code>&lt;th&gt;</code>, com alinhamento <b>centralizado</b>, fonte com a cor branca e o fundo de cada célula vermelho.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="062" name="sl">
			   <label for="062"></label>
			   <img src="basico/08_01_02.png" />
			   <figcaption>A segunda linha tem 2 células mescladas na primeira coluna. Para fazer esta operação em HTML usamos o atributo <code>rowspan</code>, indicando quantas linhas serão mescladas. Neste caso, usamos <code>rowspan="2"</code>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="063" name="sl">
			   <label for="063"></label>
			   <img src="basico/08_01_02.png" />
			   <figcaption>Temos as outras 3 células da linha 2 normalmente. Como a primeira célula da terceira linha foi mesclada, precisamos apenas das outras 3 células nesta linha.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="064" name="sl">
			   <label for="064"></label>
			   <img src="basico/08_01_03.png" />
			   <figcaption>A linha dos legumes não tem células mescladas, e os elementos são criados com tags <code>&lt;td&gt;</code>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="065" name="sl">
			   <label for="065"></label>
			   <img src="basico/08_01_04.png" />
			   <figcaption>Na linha dos cereais, podemos mesclar as três células da primeira coluna com o atributo <code>rowspan="3"</code>. As outras 2 linhas da tabela tem 3 células com os valores indicados no exemplo. Agora complete esta tabela, que vamos utilizar na próxima Atividade.</figcaption>
		   </li>
		</ul>
		<img src="basico/08_01_04.png" class="fundo" style="visibility:hidden"/>
  </details>
  <img src="basico/tags001_0008a.png" />
  <details class="sub"><summary>&#x1f4c3; Pesquisa fumantes</summary>
	<p>Este exercício é parecido com o anterior. Na mesma pasta, crie um arquivo: <code>webdesign/exercicios/fumantes.htm</code>.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="066" name="sl">
			   <label for="066"></label>
			   <img src="basico/08_02_01.png" />
			   <figcaption>A primeira célula da primeira linha será mesclada com a célula de baixo. Logo, vamos usar o atributo <code>rowspan="2"</code>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="067" name="sl">
			   <label for="067"></label>
			   <img src="basico/08_02_02.png" />
			   <figcaption>A segunda célula da primeira linha será mesclada com a célula do lado. Logo, vamos usar o atributo <code>colspan="2"</code>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="068" name="sl">
			   <label for="068"></label>
			   <img src="basico/08_02_03.png" />
			   <figcaption>O mesmo acontece com a quarta célula da primeira linha: <code>colspan="2"</code>. Agora prossiga para concluir a página HTML com esta tabela.</figcaption>
		   </li>
		</ul>
		<img src="basico/08_02_00.png" class="fundo"/>
  </details>
  <img src="basico/tags001_0008b.png" />
  <p class="topop"><a href="#basico" class="topo">voltar ao topo</a></p>
  <img src="basico/tags001_0009.png" />
  <details class="sub"><summary>&#x1f4c3; Tabela de cores</summary>
	<p>Neste exercício vamos criar uma tabela de cores. O exemplo mostra apenas alguns nomes de cores usados em HTML. Na mesma pasta, crie um arquivo: <code>webdesign/exercicios/cores.htm</code>.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="069" name="sl">
			   <label for="069"></label>
			   <img src="basico/09_01_01.png" />
			   <figcaption>Temos duas formas de fazer esta tabela. A primeira é usando exatamente o layout mostrado no exercício. Dessa forma, criaremos sempre 1 linha que mostra somente as cores, e a linha de baixo mostra apenas os nomes das cores.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="070" name="sl">
			   <label for="070"></label>
			   <img src="basico/09_01_02.png" />
			   <figcaption>Na segunda maneira, podemos criar na mesma célula o nome da cor, com o fundo de mesma cor. Escolha um dos layouts e faça a página completa com a tabela de cores.</figcaption>
		   </li>
		</ul>
		<img src="basico/09_01_02.png" class="fundo" style="visibility:hidden"/>
  </details>
  <img src="basico/tags001_0009a.png" />
  <details class="sub"><summary>&#x1f4c3; Detalhes da Atividade</summary>
	<p>A partir desta página, vamos utilizar o software <b>NOTEPAD++</b> para criar nossos próximos projetos. Acesse o endereço <a href="https://notepad-plus-plus.org/downloads/v7.8.8/" target="_blank">https://notepad-plus-plus.org/downloads/v7.8.8/</a> e instale a versão correspondente do seu computador: 32 ou 64 bits. Crie uma pasta <code>webdesign/atividade2</code> para criar os arquivos da próxima atividade. A página principal será <code>index.htm</code></p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="071" name="sl">
			   <label for="071"></label>
			   <img src="basico/09_02_01.png" />
			   <figcaption>O layout da página do nosso site principal da Atividade 2 será feito usando tabelas. A estrutura está mostrada neste exemplo. A primeira tag, logo após começar o corpo da página será <code>&lt;table&gt;</code>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="072" name="sl">
			   <label for="072"></label>
			   <img src="basico/09_02_02.png" />
			   <figcaption>O banner da página ocupará o espaço de 2 células, e por isso aplicamos o atributo <code>colspan="2"</code>. Na segunda linha da tabela, criamos uma célula para o conteúdo principal, e outra para a barra lateral com as tags <code>&lt;tr&gt;</code> e <code>&lt;td&gt;</code></figcaption>
		   </li>
		   <li>
			   <input type="radio" id="073" name="sl">
			   <label for="073"></label>
			   <img src="basico/09_02_02.png" />
			   <figcaption>Para finalizar, colocamos o rodapé da página. Este item será inserido com as tags <code>&lt;tr&gt;</code> e <code>&lt;td&gt;</code> usando o atributo de <code>colspan="2"</code> para usar a largura toda da página.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="074" name="sl">
			   <label for="074"></label>
			   <img src="basico/09_02_04.png" />
			   <figcaption>A tag de fonte pode ser usada antes da tabela de layout da página. O <b>Notepad++</b> coloca em destaque quando reconhece tags fechadas, facilitando muito a programação da página.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="075" name="sl">
			   <label for="075"></label>
			   <img src="basico/09_02_05.png" />
			   <figcaption>As propriedades <code>cellspacing</code> e <code>cellpadding</code> são usadas para fazer as margens interna e externa de cada parte do layout da página. A largura da tabela deve ser de <b>100%</b> para distribuir todo o conteúdo na tela do navegador.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="076" name="sl">
			   <label for="076"></label>
			   <img src="basico/09_02_06.png" />
			   <figcaption>A primeira linha, indicada com a tag <code>&lt;tr&gt;</code> contém o banner, com o atributo <code>colspan="2"</code> dentro da tag da célula <code>&lt;td&gt;</code>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="077" name="sl">
			   <label for="077"></label>
			   <img src="basico/09_02_08.png" />
			   <figcaption>A segunda linha da tabela contém a primeira célula do conteúdo principal da página, com a largura de <b>70%</b> e a barra lateral com largura de <b>30%</b>. Dentro das tags <code>&lt;td&gt;</code> podemos inserir os textos e imagens da página.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="078" name="sl">
			   <label for="078"></label>
			   <img src="basico/09_02_09.png" />
			   <figcaption>Note que o conteúdo da barra lateral geralmente é menor do que o conteúdo principal da página. Por isso, podemos usar o atributo de alinhamento vertical <code>valign="top"</code> para deixar estas partes do site alinhadas. Repare no link para acessar a página de nutrientes.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="079" name="sl">
			   <label for="079"></label>
			   <img src="basico/09_02_10.png" />
			   <figcaption>Usando o layout dessa página, você pode criar a página <code>nutrientes.htm</code> na mesma pasta da página <code>index.htm</code>. Pegue todo o código da tabela que fizemos dos nutrientes e insira na tag principal desta página (a que tem <b>70%</b> de largura).</figcaption>
			   </li>
		   <li>
			   <input type="radio" id="080" name="sl">
			   <label for="080"></label>
			   <img src="basico/09_02_11.png" />
			   <figcaption>A tag da última linha da tabela contém o rodapé. Nesta tag <code>&lt;td&gt;</code> você pode modificar a cor, alinhamento ou colocar uma imagem de fundo, como foi feito no banner.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="081" name="sl">
			   <label for="081"></label>
			   <img src="basico/09_02_12.png" />
			   <figcaption>O layout mostrado neste exemplo fica desta forma. Usando a estrutura mostrada neste exemplo, crie o site de um restaurante.</figcaption>
		   </li>
		</ul>
		<img src="basico/09_02_04.png" class="fundo" style="visibility:hidden"/>
  </details>
  <img src="basico/tags001_0009b.png" />
  <p class="topop"><a href="#basico" class="topo">voltar ao topo</a></p>
  <img src="basico/tags001_0010.png" />
  <details class="sub"><summary>&#x1f4c3; Seletor de imagens</summary>
	<p>Neste exemplo, vamos criar uma página com o seletor de imagens mostrado na apostila. Crie um arquivo chamado <code>webdesign/exercicios/seletor.htm</code> na nossa pasta de exercícios. Dentro da pasta de imagens, coloque 4 arquivos. No exemplo, estes arquivos estão com os nomes Foto1.jpg, Foto2.jpg, Foto3.jpg e Foto4.jpg.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="082" name="sl">
			   <label for="082"></label>
			   <img src="basico/10_01_01.png" />
			   <figcaption>O rótulo <code>&lt;label&gt;</code> foi colocado antes da caixa de seleção.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="083" name="sl">
			   <label for="083"></label>
			   <img src="basico/10_01_02.png" />
			   <figcaption>Para que o javascript funcione corretamente, o nome <code>iframe1</code> deve ser o mesmo da tag <code>iframe</code>. Preste atenção nos nomes dos arquivos de imagens e seus caminhos para que a página funcione.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="084" name="sl">
			   <label for="084"></label>
			   <img src="basico/10_01_03.png" />
			   <figcaption>A tag do <code>&lt;iframe&gt;</code> deve conter informações de largura e altura, como fizemos nas páginas anteriores que usaram este recurso. Na próxima atividade, vamos usar a tag <code>&lt;select&gt;</code> para mudar páginas.</figcaption>
		   </li>
		</ul>
		<img src="basico/10_01_00.png" class="fundo"/>
  </details>
  <img src="basico/tags001_0010a.png" />
  <details class="sub"><summary>&#x1f4c3; Detalhes da Atividade</summary>
	<p>Vamos criar uma pasta <code>webdesign/atividade3</code> para trabalharmos neste projeto. Selecione 5 pontos turísticos, e cada um deles terá uma página, salva na mesma pasta que criamos. Use uma subpasta chamada <code>webdesign/atividade3/imagens</code> para os arquivos das fotos. Neste projeto vamos inserir mapas nos sites.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="085" name="sl">
			   <label for="085"></label>
			   <img src="basico/10_02_01.png" />
			   <figcaption>O layout da página principal do nosso site da Atividade 3 será feito usando tabelas. Coloque o nome de <code>index.htm</code> nesta págin, cuja estrutura está mostrada neste exemplo. A primeira tag, logo após começar o corpo da página será <code>&lt;table&gt;</code>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="086" name="sl">
			   <label for="086"></label>
			   <img src="basico/10_02_01.png" />
			   <figcaption>O banner da página fica na primeira linha da tabela. Na segunda linha da tabela, criamos uma célula para o conteúdo principal, que terá um seletor de páginas<code>&lt;select&gt;</code> seguido de um <code>&lt;iframe&gt;</code>, ideia parecida com a que usamos na página de Galeria de Fotos anterior.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="087" name="sl">
			   <label for="087"></label>
			   <img src="basico/10_02_10.png" />
			   <figcaption>No código da página em HTML, a primeira linha da tabela contém a tag do banner. Você pode criar uma imagem de fundo usando o atributo <code>background</code>, como já fizemos em outras páginas.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="088" name="sl">
			   <label for="088"></label>
			   <img src="basico/10_02_11.png" />
			   <figcaption>A estrutura da tag <code>&lt;select&gt;</code> foi usada para as 5 páginas dos pontos turísticos. Crie estas páginas na mesma pasta da página principal, com os nomes dos pontos turísticos. Não use acentuação, e procure criar nomes com poucos caracteres.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="089" name="sl">
			   <label for="089"></label>
			   <img src="basico/10_02_12.png" />
			   <figcaption>Para ajustar a altura da tag <code>&lt;iframe&gt;</code>, podemos usar um estilo com altura mínima de 150% da altura da tela: <code>min-height:150vh</code>. Mais adiante vamos trabalhar com estas formatações.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="090" name="sl">
			   <label for="090"></label>
			   <img src="basico/10_02_04.png" />
			   <figcaption>Agora vamos ver como fica o layout de uma das páginas dos pontos turísticos. Basicamente são 2 colunas: uma com as descrições e fotos, e outra com a localização, e o rodapé. Logo, precisamos de uma tabela com 2 células em uma linha, e duas células mescladas na segunda linha.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="091" name="sl">
			   <label for="091"></label>
			   <img src="basico/10_02_05.png" />
			   <figcaption>Podemos usar a célula com conteúdo principal com a largura de <b>65%</b> e a barra lateral com largura de <b>35%</b>. Dentro das tags <code>&lt;td&gt;</code> podemos inserir os textos e imagens de cada página.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="092" name="sl">
			   <label for="092"></label>
			   <img src="basico/10_02_06.png" />
			   <figcaption>É importante separar os parágrafos, e definir larguras de imagens. Neste caso, foi usada a largura de <b>75%</b> para imagens.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="093a" name="sl">
			   <label for="093a"></label>
			   <img src="basico/10_02_06a.png" />
			   <figcaption>A segunda célula com a barra lateral contém o <code>&lt;iframe&gt;</code> com a localização do ponto turístico. Vamos ver como conseguir esta tag na próxima imagem.</figcaption>
			</li>
		   <li>
			   <input type="radio" id="094" name="sl">
			   <label for="094"></label>
			   <img src="basico/10_02_02.png" />
			   <figcaption>Acesse o endereço <a href="https://www.google.com.br/maps/" target="_blank">www.google.com.br/maps/</a> e procure o ponto turístico. Depois, basta clicar em <code>compartilhar</code> e a opção de <code>Incorporar um mapa</code>. Copie e cole a tag criada na página do ponto turístico.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="093" name="sl">
			   <label for="093"></label>
			   <img src="basico/10_02_07.png" />
			   <figcaption>Voltando ao código da página, a linha de rodapé tem 2 células mescladas, para usar a largura toda da página. Por isso, usamos o atributo <code>colspan="2"</code>. Com a estrutura da página de um ponto turístico pronta, crie as páginas dos outros 4 pontos turísticos.</figcaption>
			</li>
		   <li>
			   <input type="radio" id="095" name="sl">
			   <label for="095"></label>
			   <img src="basico/10_02_13.png" />
			   <figcaption>O layout mostrado neste exemplo fica desta forma. Lembre-se de cuidar com os nomes das páginas, para ver se são iguais aos nomes colocados na página <code>index.htm</code>.</figcaption>
		   </li>
		</ul>
		<img src="basico/10_02_06.png" class="fundo" style="visibility:hidden"/>
  </details>
  <p class="topop"><a href="#basico" class="topo">voltar ao topo</a></p>
</details>

<details id="css1"><summary>CSS - Cascading Style Sheets: pág. 11-20</summary>
	<img src="css1/tags001_0011.png" />
	<p class="topop"><a href="#css1" class="topo">voltar ao topo</a></p>
	<img src="css1/tags001_0012.png" />
  <details class="sub"><summary>&#x1f4c3; Primeiro Layout com CSS</summary>
	<p>Vamos usar a nossa pasta de exercícios para criar a página <code>webdesign/exercicios/layoutCSS.htm</code>. Neste projeto vamos criar um layout em forma de tabela, parecido com as Atividades 2 e 3: serão 2 colunas na parte principal, com banner e um rodapé.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="096" name="sl">
			   <label for="096"></label>
			   <img src="css1/12_01_01.png" />
			   <figcaption>O layout da nossa primeira página com CSS será feito usando uma tabela. A primeira linha da tabela contém o banner da página, com o atributo <code>colspan="2"</code> para ocupar toda a largura da página. Insira uma imagem nesta tag.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="097" name="sl">
			   <label for="097"></label>
			   <img src="css1/12_01_02.png" />
			   <figcaption>A segunda linha da tabela contém uma barra lateral esquerda e o conteúdo principal com uma imagem inserida. Vamos testar os alinhamentos do texto e da imagem nesta página.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="098" name="sl">
			   <label for="098"></label>
			   <img src="css1/12_01_03.png" />
			   <figcaption>A terceira linha contém o rodapé, também com o atributo <code>colspan="2"</code> para usar a largura toda da página.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="099" name="sl">
			   <label for="099"></label>
			   <img src="css1/12_01_04.png" />
			   <figcaption>Agora vamos analisar a estrutura do CSS. Nestes primeiros exemplos, vamos usar as folhas de estilos por dentro das páginas, dentro do cabeçalho com a tag <code>&lt;style&gt;</code>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="100" name="sl">
			   <label for="100"></label>
			   <img src="css1/12_01_05.png" />
			   <figcaption>Podemos definir atributos gerais no CSS quando nos referimos ao corpo da página <code>body</code>. Estes atributos podem incluir tamanhos de fontes e cores de fundos. Modifique estes valores para visualizar o layout da sua página.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="101" name="sl">
			   <label for="101"></label>
			   <img src="css1/12_01_06.png" />
			   <figcaption>De uma maneira bem mais simples, definimos bordas, cores de fundo das células <code>td</code> com as folhas de estilos. Note que o tamanho da fonte foi colocado com <b>0.8em</b>, ou seja, corresponde a <b>80%</b> do tamanho de fonte da tag mãe <code>body</code>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="102" name="sl">
			   <label for="102"></label>
			   <img src="css1/12_01_07.png" />
			   <figcaption>Um atributo importante que usamos no CSS é da altura da página. Neste caso, foi colocado que a altura mede <b>100vh</b>, ou seja, <b>100%</b> da altura do navegador. Podemos usar no lugar do atributo <code>height:100vh;</code> o atributo <code>min-height:100vh;</code>, que deixaria a altura mínima com a altura do navegador. </figcaption>
		   </li>
		   <li>
			   <input type="radio" id="103" name="sl">
			   <label for="103"></label>
			   <img src="css1/12_01_08.png" />
			   <figcaption>Para imagens não ficarem "grudadas" nos textos, podemos definir as margens com CSS. Os atributos ficam valendo para todas as imagens que você insere na página. Modifique atributos nesta nossa página, para treinar para a próxima Atividade.</figcaption>
		   </li>
		</ul>
		<img src="css1/12_01_00.png" class="fundo"/>
  </details>
  <img src="css1/tags001_0012a.png" />
  <p class="topop"><a href="#css1" class="topo">voltar ao topo</a></p>
  <img src="css1/tags001_0013.png" />
  <p class="topop"><a href="#css1" class="topo">voltar ao topo</a></p>
  <img src="css1/tags001_0014.png" />
  <details class="sub"><summary>&#x1f4c3; Layout da Atividade 4</summary>
	<p>Vamos criar uma pasta para nosso próximo site chamada <code>webdesign/atividade4</code>. Neste projeto vamos criar um layout em forma de tabela, parecido com as Atividades 2 e 3, com formatação CSS. Como é um site com 3 páginas, vamos precisar de uma pasta de imagens:<code>webdesign/atividade4/imagens</code>.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="104" name="sl">
			   <label for="104"></label>
			   <img src="css1/14_01_01.png" />
			   <figcaption>O layout da nossa primeira página com CSS será feito usando uma tabela. A primeira linha da tabela contém uma célula com um ícone (logomarca ou pictograma) e na outra célula o banner da página, com o atributo <code>colspan="2"</code> para ocupar a largura restante da página (retirando a parte do ícone. Você pode inserir imagens nestas tags.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="104a" name="sl">
			   <label for="104a"></label>
			   <img src="css1/14_01_01.png" />
			   <figcaption>Note que já vamos criar classes para as partes das nossas páginas: <code>class="icone"</code> e <code>class="banner"</code> para formatação em CSS. Com o tema de Esportes, escolha um título para colocar no Banner da página que terá o nome <code>index.htm</code>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="105" name="sl">
			   <label for="105"></label>
			   <img src="css1/14_01_02.png" />
			   <figcaption>A segunda linha da tabela contém o menu, que ocupará a largura toda da página. Por isso, colocamos o atributo <code>colspan="3"</code> nesta célula, que possui classe definida como <code>class="menu"</code>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="106" name="sl">
			   <label for="106"></label>
			   <img src="css1/14_01_03.png" />
			   <figcaption>Na quarta linha, teremos 3 células: <code>class="galeria"</code>, que contém uma espécie de galeria de notícias e imagens; <code>class="principal"</code>, com o contéudo principal da página que ficará centralizado no layout; e <code>class="contato"</code>, com informações de contatos e redes sociais.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="107" name="sl">
			   <label for="107"></label>
			   <img src="css1/14_01_04.png" />
			   <figcaption>A última linha contém o rodapé, com atributo <code>colspan="3"</code> para usar a largura toda da página, e com a classe definida: <code>class="rodape"</code>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="108" name="sl">
			   <label for="108"></label>
			   <img src="css1/14_01_05.png" />
			   <figcaption>A tag dentro do cabeçalho <code>style</code> contém todos os atributos do CSS que vamos definir nestas páginas. Nesta primeira página <code>index.htm</code> vamos definir todos os estilos antes de criar as outras páginas do nosso site.</figcaption>
		   </li>
		</ul>
		<img src="css1/14_01_00.png" class="fundo"/>
  </details>
  <img src="css1/tags001_0014a.png" />
  <p class="topop"><a href="#css1" class="topo">voltar ao topo</a></p>
  <img src="css1/tags001_0015.png" />
  <details class="sub"><summary>&#x1f4c3; Banner da Atividade 4</summary>
	<p>Vamos formatar o banner e o ícone da página <code>index.htm</code> da Atividade 4 com CSS. A estrutura HTML já foi mostrada e comentada em detalhes na página anterior.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="109" name="sl">
			   <label for="109"></label>
			   <img src="css1/15_01_01.png" />
			   <figcaption>O corpo da página <code>body</code> foi definido com uma imagem de fundo (background) que mostra uma partida de vôlei. Note que deixamos as imagens na pasta <code>webdesign/atividade4/imagens</code>. Logo, podemos usar o atributo <code>url(imagens/banner.jpg)</code> que mostra o caminho do arquivo da imagem de fundo do site.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="109a" name="sl">
			   <label for="109a"></label>
			   <img src="css1/15_01_01.png" />
			   <figcaption>Em CSS podemos definir vários elementos para a tag <code>body</code>, que é a "mãe" de todas as tags. Largura, tamanho de fonte, margem automática (que deixa o conteúdo centralizado), além de <code>background-size</code> e <code>background-attachment</code> que deixam a imagem de fundo fixa e "cobrindo" todo o espaço da tela.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="110" name="sl">
			   <label for="110"></label>
			   <img src="css1/15_01_02.png" />
			   <figcaption>A tag de ícone pode conter uma imagem, como uma logomarca, ou podemos usar uma imagem pictográfica. No site <a href="http://www.degraf.ufpr.br/docentes/paulo/webdesign/pictograph.html" target="_blank">http://www.degraf.ufpr.br/docentes/paulo/webdesign/pictograph.html</a> você pode escolher uma imagem pictográfica para ficar nesta tag de ícone desta página.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="111" name="sl">
			   <label for="111"></label>
			   <img src="css1/15_01_03.png" />
			   <figcaption>Em cada página do nosso site, podemos escolher um destes símbolos pictográficos para inserir na tag de ícone. Visite a página indicada e escolha um símbolo que represente o esporte de cada página. O formato deste tipo de imagem é parecido com o de cores hexadecimais, mas sempre começa com o símbolo <b>&amp;</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="112" name="sl">
			   <label for="112"></label>
			   <img src="css1/15_01_04.png" />
			   <figcaption>Na tag do banner, podemos escolher uma imagem de fundo, inserindo-a como fizemos na imagem do fundo do site na tag <code>body</code>. Outra opção é usar efeitos de texto, como cores diferentes no contorno com o atributo <code>stroke-width</code> mostrado neste exemplo.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="113" name="sl">
			   <label for="113"></label>
			   <img src="css1/15_01_05.png" />
			   <figcaption>As tags <code>td</code> servem de estrutura para o layout do nosso site, e precisam de formatações. Margens internas, cor de fundo e imagem de fundo podem ser definidas no CSS. Note que as tags nativas do HTML não têm o símbolo de ponto . nas atribuições dos estilos. Somente colocamos ponto . nas classes criadas (banner, icone, menu,...).</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="114" name="sl">
			   <label for="114"></label>
			   <img src="css1/15_01_06.png" />
			   <figcaption>Outra tag importante para definirmos atributos no CSS é a <code>table</code>, que contém os espaçamentos das células para separar os blocos de conteúdos, cor de texto e a largura.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="115" name="sl">
			   <label for="115"></label>
			   <img src="css1/15_01_07.png" />
			   <figcaption>Com as propriedades definidas neste exemplo, nossa página fica com a parte superior desta forma. Formate o seu layout com as propriedades que você ache mais adequadas para esta atividade. Seguiremos com as outras partes desta atividade.</figcaption>
		   </li>
		</ul>
		<img src="css1/15_01_00.png" class="fundo" style="visibility:hidden"/>
  </details>
  <img src="css1/tags001_0015a.png" />
  <p class="topop"><a href="#css1" class="topo">voltar ao topo</a></p>
  <img src="css1/tags001_0016.png" />
  <details class="sub"><summary>&#x1f4c3; Menu da Atividade 4</summary>
	<p>Vamos formatar o menu da página <code>index.htm</code> da Atividade 4 com CSS. A estrutura HTML possui a tag <code>nav</code> descrita a seguir.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="116" name="sl">
			   <label for="116"></label>
			   <img src="css1/16_01_00.png" />
			   <figcaption>Dentro da tag <code>&lt;nav class="menu"&gt;</code> podemos criar uma tag de lista <code>&lt;ul&gt;</code>, com cada item <code>&lt;li&gt;</code> representando a página de um esporte desta atividade. Usamos a tag de link <code>&lt;a&gt;</code> para criar a navegação entre os links do menu. A página <code>index.htm</code> tem classe ativa que vamos configurar a seguir.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="117" name="sl">
			   <label for="117"></label>
			   <img src="css1/16_01_01.png" />
			   <figcaption>Agora vamos focar no cabeçalho da página para criar as propriedades do menu. Note que as propriedades do banner estão logo acima, dentro da mesma tag <code>&lt;style&gt;</code>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="118" name="sl">
			   <label for="118"></label>
			   <img src="css1/16_01_02.png" />
			   <figcaption>A lista dos itens do menu <code>ul</code> tem atributos de margens, estilo sem formato de lista e o <b>display flex</b> que pode ser usado para distribuir os itens dentro da célula da tabela. A direção deste display está em linha (row) pois o menu é horizontal.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="119" name="sl">
			   <label for="119"></label>
			   <img src="css1/16_01_03.png" />
			   <figcaption>Para que a lista não fique "grudada" nas outras partes da página, criamos margens top e bottom. Colocamos uma borda azul à direita e comprimento fixo de <b>100px</b>. Se necessário, ajuste este valor na sua página, para que os textos de todos os itens caibam no menu, sem quebras de linha.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="120" name="sl">
			   <label for="120"></label>
			   <img src="css1/16_01_04.png" />
			   <figcaption>O último item da lista <code>last-child</code> ficará sem borda, deixando bordas apenas internas entre os itens do menu.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="121" name="sl">
			   <label for="121"></label>
			   <img src="css1/16_01_05.png" />
			   <figcaption>Na tag <code>&lt;a&gt;</code> podemos configurar tamanho de fonte e o atributo <code>text-decoration:none;</code> remove aquelas configurações comuns de links (cor azul, sublinhado).</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="122" name="sl">
			   <label for="122"></label>
			   <img src="css1/16_01_06.png" />
			   <figcaption>Ao passar o cursor do mouse por cima de um item do menu, podemos criar alguns efeitos: mudanças de cor, de fundo, sublinhados ou sombras. Neste caso usamos sombra e mudança de cor da fonta para esse efeito. Escolha um efeito para sua página.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="123" name="sl">
			   <label for="123"></label>
			   <img src="css1/16_01_07.png" />
			   <figcaption>A página ativa, neste caso <code>index.htm</code>, pode ter alguma apresentação diferente no menu para destacar ao visitante que ele está nesta página. Quando construir as outras páginas, modifique a classe na tag <code>&lt;nav&gt;</code> o item ativo.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="124" name="sl">
			   <label for="124"></label>
			   <img src="css1/16_01_08.png" />
			   <figcaption>Este é o resultado parcial da página, com estas configurações de menu. Usando os atributos mostrados, modifique valores para a apresentação do seu site.</figcaption>
		   </li>
		</ul>
		<img src="css1/16_01_00.png" class="fundo" style="visibility:hidden"/>
  </details>
  <p class="topop"><a href="#css1" class="topo">voltar ao topo</a></p>
  <img src="css1/tags001_0017.png" />
  <p class="topop"><a href="#css1" class="topo">voltar ao topo</a></p>
  <img src="css1/tags001_0018.png" />
  <details class="sub"><summary>&#x1f4c3; Conteúdo da Atividade 4</summary>
	<p>Vamos formatar o conteúdo principal e a barra lateral galeria da página <code>index.htm</code> da Atividade 4 com CSS. Antes vamos ver a estrutura HTML destas partes da página.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="125" name="sl">
			   <label for="125"></label>
			   <img src="css1/18_01_00.png" />
			   <figcaption>A barra esquerda será a galeria de notícias <code>class="galeria"</code>. Podemos criar um cabeçalho <code>&lt;h3&gt;</code>, um parágrafo <code>&lt;p&gt;</code> com descrição do título da notícia, uma imagem <code>&lt;img&gt;</code> e um link <code>&lt;a&gt;</code>. Nesta barra podemos inserir 2 ou 3 notícias com estes elementos, separadas por uma tag <code>&lt;hr&gt;</code>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="126" name="sl">
			   <label for="126"></label>
			   <img src="css1/18_01_01.png" />
			   <figcaption>O conteúdo da página da tag <code>class="principal"</code> contém parágrafos <code>&lt;p&gt;</code> e imagens. Podemos criar uma div <code>class="imagem"</code> para formatar imagens dentro desta parte da página.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="127" name="sl">
			   <label for="127"></label>
			   <img src="css1/18_01_02.png" />
			   <figcaption>Na tag de estilo <code>&lt;style&gt;</code> vamos focar nos atributos das classes galeria e principal.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="128" name="sl">
			   <label for="128"></label>
			   <img src="css1/18_01_03.png" />
			   <figcaption>A classe <code>imagem</code> serve para alinhar as fotos com o texto na tag principal. Podemos definir margens para não deixar as fotos "grudadas" nos textos.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="129" name="sl">
			   <label for="129"></label>
			   <img src="css1/18_01_04.png" />
			   <figcaption>De maneira geral, as imagens das páginas podem ser colocadas com largura máxima de <b>100%</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="130" name="sl">
			   <label for="130"></label>
			   <img src="css1/18_01_05.png" />
			   <figcaption>O alinhamento <code>vertical-align:top;</code> faz com que o conteúdo da galeria fique alinhado com os conteúdos das outras barras: principal e contato. Podemos definir a largura da galeria: <b>20%</b>, por exemplo. Faça testes com os conteúdos de sua página para encontrar o melhor valor.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="131" name="sl">
			   <label for="131"></label>
			   <img src="css1/18_01_06.png" />
			   <figcaption>Defina o alinhamento do texto da tag principal da página. Você pode definir também cor de texto e mais efeitos no CSS. Vamos definir adiante os atributos das outras tags da página.</figcaption>
		   </li>
		</ul>
		<img src="css1/18_01_00.png" class="fundo" style="visibility:hidden"/>
  </details>
  <img src="css1/tags001_0018a.png" />
  <p class="topop"><a href="#css1" class="topo">voltar ao topo</a></p>
  <img src="css1/tags001_0019.png" />
  <details class="sub"><summary>&#x1f4c3; Contato e rodapé da Atividade 4</summary>
	<p>Vamos formatar os conteúdos da barra de contato e do rodapé da página <code>index.htm</code> da Atividade 4 com CSS. Antes vamos ver a estrutura HTML destas partes da página.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="132" name="sl">
			   <label for="132"></label>
			   <img src="css1/18_02_00.png" />
			   <figcaption>A barra direita será de contatos de email e de redes sociais <code>class="contato"</code>. Podemos criar links <code>&lt;a&gt;</code> para email e acesso às redes sociais. Insira imagens na pasta <code>webdesign/atividade4/imagens</code> de email, facebook e mais redes sociais para colocar dentro das tags de link as imagens <code>&lt;img&gt;</code>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="133" name="sl">
			   <label for="133"></label>
			   <img src="css1/18_02_01.png" />
			   <figcaption>A tag <code>class="rodape"</code> contém as informações que já usamos em outras páginas. Agora vamos ver as propriedades CSS destas partes da página.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="134" name="sl">
			   <label for="134"></label>
			   <img src="css1/18_02_03.png" />
			   <figcaption>A tag de contato tem o alinhamento vertical definido no topo da célula com o atributo <code>vertical-align:top;</code>. Se definirmos a largura desta barra como <b>10%</b>, teremos <b>70%</b> para o conteúdo principal (pois a galeria ficou com <b>20%</b>). Teste diferentes valores para o conteúdo de sua página.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="135" name="sl">
			   <label for="135"></label>
			   <img src="css1/18_02_04.png" />
			   <figcaption>As imagens dentro desta classe podem ser menores, pois funcionam como ícones de acesso. Logo, usamos o atributo <code>.contato img</code> que significa que as larguras de dentro da classe de contato terão larguras menores. Neste caso, usamos <b>50%</b>. Teste valores diferentes em sua página.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="136" name="sl">
			   <label for="136"></label>
			   <img src="css1/18_02_05.png" />
			   <figcaption>A tag de rodapé tem a configuração mais simples. Usamos as mesmas propriedades dos sites anteriores.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="137" name="sl">
			   <label for="137"></label>
			   <img src="css1/18_02_06.png" />
			   <figcaption>Com as propriedades definidas, a página <code>index.htm</code> fica com este layout. Teste medidas e cores para sua página. Depois de definir os valores mais adequados, você pode construir as outras 2 páginas: basta copiar e colar este código nos outros arquivos de esportes: no meu caso, <code>basquete.htm</code> e <code>natacao.htm</code>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="138" name="sl">
			   <label for="138"></label>
			   <img src="css1/18_02_06.png" />
			   <figcaption>Não esqueça de definir os menus das outras páginas com o item <code>active</code>. Coloque os 3 arquivos na mesma pasta, compartilhando a mesma pasta de imagens.</figcaption>
		   </li>
		</ul>
		<img src="css1/18_02_00.png" class="fundo" style="visibility:hidden"/>
  </details>
  <img src="css1/tags001_0019a.png" />
  <p class="topop"><a href="#css1" class="topo">voltar ao topo</a></p>
  <img src="css1/tags001_0020.png" />
  <details class="sub"><summary>&#x1f4c3; Formulário de Contato</summary>
	<p>Crie uma página na nossa pasta de exercícios <code>webdesign/exercicios</code> com nome <code>contato.htm</code>. Outro arquivo que vamos criar nesta pasta chama-se <code>enviar.php</code>, com o código mostrado na apostila. Vamos mostrar a criação e layout de uma página de formulário, sem a configuração de um servidor para receber os dados enviados.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="139" name="sl">
			   <label for="139"></label>
			   <img src="css1/20_01_00.png" />
			   <figcaption>Podemos criar uma tag "mãe" do formulário <code>class="formulario"</code> para atribuir as propriedades de seus componentes.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="140" name="sl">
			   <label for="140"></label>
			   <img src="css1/20_01_01.png" />
			   <figcaption>Cada entrada terá um rótulo "agredado" <code>&lt;label&gt;</code>. Este rótulo pode ser referenciado com o atributo <code>for</code>, com o nome da respectiva entrada.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="141" name="sl">
			   <label for="141"></label>
			   <img src="css1/20_01_02.png" />
			   <figcaption>As entradas são colocadas no HTML na sequência de cada um de seus rótulos. Se você quiser fazer o formulário com rótulos ao lado das entradas, pode usar uma tabela para ajudar a organizar os dados da página.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="141a" name="sl">
			   <label for="141a"></label>
			   <img src="css1/20_01_03.png" />
			   <figcaption>No final do formulário, criamos uma caixa de texto <code>&lt;textarea&gt;</code>, que pode ser deixada com mais linhas (neste caso, deixamos com 7 linhas).</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="142" name="sl">
			   <label for="142"></label>
			   <img src="css1/20_01_04.png" />
			   <figcaption>O botão de enviar tem o atributo <code>type="submit"</code> para caracterizá-lo com a interação com o visitante para enviar os dados.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="143" name="sl">
			   <label for="143"></label>
			   <img src="css1/20_01_05.png" />
			   <figcaption>Agora vamos formatar as tags da página com CSS. O corpo da página <code>body</code> tem margem automática e uma largura de <b>85%</b>. Formate os elementos principais da página nesta tag.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="144" name="sl">
			   <label for="144"></label>
			   <img src="css1/20_01_06.png" />
			   <figcaption>Os rótulos <code>label</code> têm atributo <code>display: block;</code>, que usa a linha inteira sem precisarmos de tags de parágrafos e de quebras de linhas para inserir as entradas <code>input</code>. Note que colocamos margens para não "grudar" os rótulos com as entradas.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="145" name="sl">
			   <label for="145"></label>
			   <img src="css1/20_01_07.png" />
			   <figcaption>A classe <code>formulario</code> serve como um "container" do formulário, onde podemos atribuir cor de fundo, margem interna e tipo de fonte.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="146" name="sl">
			   <label for="146"></label>
			   <img src="css1/20_01_08.png" />
			   <figcaption>As entradas com tags nativas <code>input</code> e <code>textarea</code> podem ter propriedades de largura, cor de fundo, sombras e margens internas. Neste exemplo, criamos bordas arredondadas com o atributo <code>border-radius</code>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="147" name="sl">
			   <label for="147"></label>
			   <img src="css1/20_01_09.png" />
			   <figcaption>A tag <code>textarea</code> pode ser inserida com largura maior do que as outras entradas. Por tratar-se de uma tag "elástica", que o visitante pode "abrir" com o cursor do mouse, colocamos também o tamanho de largura máxima <code>max-width</code>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="148" name="sl">
			   <label for="148"></label>
			   <img src="css1/20_01_10.png" />
			   <figcaption>Como o botão para enviar os dados tem <code>id="submit"</code> no código HTML, sua formatação usa a hashtag <code>#submit</code> para referência. Este botão pode ter uma opacidade definida (neste exemplo é de <b>85%</b>), que modifica quando o visitante passa o cursor do mouse por cima do botão. Colocamos também a sombra <code>box-shadow</code> para dar um efeito de 3D.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="149" name="sl">
			   <label for="149"></label>
			   <img src="css1/20_01_11.png" />
			   <figcaption>A página com contato fica com este layout. Modifique medidas, cores e crie sua página de contato. Vamos utilizá-la em próximas Atividades. </figcaption>
		   </li>
		</ul>
		<img src="css1/20_01_00.png" class="fundo" style="visibility:hidden"/>
  </details>
  <p class="topop"><a href="#css1" class="topo">voltar ao topo</a></p>
</details>

<details id="css2"><summary>CSS, Flexbox e Mapeamentos de imagens: pág. 21-27</summary>
	<img src="css2/tags001_0021.png" />
	<details class="sub"><summary>&#x1f4c3; FlexBox para itens</summary>
	<p>Crie uma página na nossa pasta de exercícios <code>webdesign/exercicios</code> com nome <code>itens.htm</code>. Dentro desta pasta, use a pasta de imagens para inserir fotos dos itens que vamos criar com o atributo FlexBox. É o mesmo que já usamos nos itens dos menus.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="150" name="sl">
			   <label for="150"></label>
			   <img src="css2/21_01_01.png" />
			   <figcaption>Usando a estrutura em tabela, vamos criar somente uma linha com a tag <code>&lt;tr&gt;</code> com duas barras: <b>lateral</b>, na primeira célula <code>&lt;td&gt;</code> e <b>conteúdo</b>, na segunda célula.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="151" name="sl">
			   <label for="151"></label>
			   <img src="css2/21_01_02.png" />
			   <figcaption>As tags podem ser referenciadas com as classes <code>class="barra"</code> e <code>class="conteudo"</code>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="153" name="sl">
			   <label for="153"></label>
			   <img src="css2/21_01_03.png" />
			   <figcaption>Dentro da célula de <b>conteúdo</b>, crie uma nova classe para formatarmos no CSS: <code>class="todos"</code>, que será a tag mãe dos itens.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="154" name="sl">
			   <label for="154"></label>
			   <img src="css2/21_01_04.png" />
			   <figcaption>Dentro desta <b>div</b>, podemos criar as tags filhas, que terão classe <code>class="item"</code>. Em cada uma, coloque um texto e a respectiva imagem que está salva na pasta de imagens. Crie 5 ou mais itens, para testarmos o layout que será usado na próxima Atividade.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="155" name="sl">
			   <label for="155"></label>
			   <img src="css2/21_01_05.png" />
			   <figcaption>Agora vamos formatar as tags da página com CSS. Nesta página somente foi atribuído o tamanho da fonte na tag <code>body</code>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="156" name="sl">
			   <label for="156"></label>
			   <img src="css2/21_01_06.png" />
			   <figcaption>Neste exemplo, foi usado <code>font-size:0.8em</code>, ou seja, teremos 80% do tamanho da fonte dentro das células. Atributos de cor de fundo e margens também podem ser colocados nesta tag <code>td</code>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="157" name="sl">
			   <label for="157"></label>
			   <img src="css2/21_01_07.png" />
			   <figcaption>A tag mãe das células, <code>table</code>, pode ser usada para a largura do layout, bordas e alinhamento de texto.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="158" name="sl">
			   <label for="158"></label>
			   <img src="css2/21_01_08.png" />
			   <figcaption>Use atributos para formatar a barra lateral. Neste caso, foi usado o alinhamento vertical <code>vertical-align:top</code> para deixá-la na mesma altura do conteúdo.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="159" name="sl">
			   <label for="159"></label>
			   <img src="css2/21_01_09.png" />
			   <figcaption>A tag de conteúdo pode ter atributo de alinhamento vertical configurado e largura. Se atribuirmos 70% de largura, automaticamente a barra lateral fica com os 30% restantes.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="160" name="sl">
			   <label for="160"></label>
			   <img src="css2/21_01_10.png" />
			   <figcaption>A tag com todos os itens ficou com atributo de <code>display:flex;</code>, distribuição em linha <code>flex-direction:row;</code> e o atributo <code>flex-wrap:wrap;</code> para deixar que os itens mudem de linha automaticamente se o navegador não conseguir exibí-los todos na mesma linha.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="161" name="sl">
			   <label for="161"></label>
			   <img src="css2/21_01_11.png" />
			   <figcaption>Os itens "herdam" a propriedade flex da tag mãe "todos". Os itens podem ter o atributo de largura mínima <code>min-width:150px;</code>, evitando que o respectivo conteúdo seja "espremido" demais para caber em uma linha só. Cor de fundo, borda e arredondamento de bordas podem ser atribuídos nos itens. Faça testes do layout do flexbox que criamos.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="162" name="sl">
			   <label for="162"></label>
			   <img src="css2/21_01_12.png" />
			   <figcaption>A página de itens fica com este layout. Modifique medidas, cores e crie sua página de itens, que será utilizada em próximas Atividades. Se as alturas das imagens ficarem muito diferentes, você pode usar altura mínima <code>min-height</code> ou editar as imagens externamente, deixando-as com mesmo tamanho.</figcaption>
		   </li>
		</ul>
		<img src="css2/21_01_00.png" class="fundo" style="visibility:hidden"/>
  </details>
	<img src="css2/tags001_0021a.png" />
	<p class="topop"><a href="#css2" class="topo">voltar ao topo</a></p>
	<img src="css2/tags001_0022.png" />
	<details class="sub"><summary>&#x1f4c3; Detalhes do site principal</summary>
	<p>Crie uma pasta chamada <code>webdesign/atividade5</code>, com a página principal com nome <code>index.htm</code>. Dentro desta pasta, crie a pasta de imagens para inserir fotos dos 12 itens que aparecem na página criada. Vamos usar muitos recursos da página que construímos com Flexbox.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="163" name="sl">
			   <label for="163"></label>
			   <img src="css2/21_02_00.png" />
			   <figcaption>A estrutura HTML desta Atividade terá 1 linha com o <b>ícone</b> e o <b>banner</b> da loja, uma linha com a <b>barra lateral</b> e o <b>menu</b>, na outra linha aparece o <b>conteúdo</b> com itens da loja e finalizamos com o <b>rodapé</b> na última linha.</figcaption>
		   </li>
		  <li>
			   <input type="radio" id="164" name="sl">
			   <label for="164"></label>
			   <img src="css2/21_02_01.png" />
			   <figcaption>Na <b>barra lateral</b>, podemos usar a mesma estrutura da Atividade 4, com email e links para redes sociais fictícias, da loja virtual que estamos criando.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="165" name="sl">
			   <label for="165"></label>
			   <img src="css2/21_02_02.png" />
			   <figcaption>O <b>menu</b> terá estrutura parecida com a que usamos na Atividade 4, inclusive na sua programação CSS.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="166" name="sl">
			   <label for="166"></label>
			   <img src="css2/21_02_03.png" />
			   <figcaption>Os itens da loja podem ser colocados dentro da tag <code>class="todos"</code>, que usamos na página anterior. Cada item aparece dentro de uma classe <code>class="item"</code>, one colocamos um título do produto, uma imagem e o preço, com a tag <code>&lt;strike&gt;</code> para os preços antigos de cada um dos 12 produtos.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="167" name="sl">
			   <label for="167"></label>
			   <img src="css2/21_02_04.png" />
			   <figcaption>A programação da página CSS tem itens que valem para a página principal e para as páginas filhas. A tabela está com fundo branco, com bordas em tom verde claro. O atributo <code>border-spacing</code> separa as partes das páginas.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="168" name="sl">
			   <label for="168"></label>
			   <img src="css2/21_02_05.png" />
			   <figcaption>O banner está referenciado com a altura da tela do navegador com o atributo <code>height:10vh;</code>, ou seja, <b>10%</b> da altura da tela. Uma imagem de fundo dos produtos e a cor do texto também podem ser configurados no CSS. Escolha um <a href="http://www.degraf.ufpr.br/docentes/paulo/webdesign/pictograph.html" target="_blank">pictograma</a> para colocar na tag de ícone.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="169" name="sl">
			   <label for="169"></label>
			   <img src="css2/21_02_06.png" />
			   <figcaption>A barra lateral e o menu também ficarão fixos, valendo para todas as páginas do site desta atividade. Você pode usar os mesmos atributos da Atividade 4, modificando cores e espaçamentos para a loja virtual</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="170" name="sl">
			   <label for="170"></label>
			   <img src="css2/21_02_07.png" />
			   <figcaption>O conteúdo pode ter propriedades diferentes em cada página do site. Nesta primeira página, estamos colocando os itens com atributos <b>flexbox</b> para os produtos da loja. Margens, cores e configurações de fonte podem ser modificadas nesta tag.Para deixar as imagens com mesmo tamanho, foi usada a propriedade de altura no atributo <code>.item img {}</code>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="171" name="sl">
			   <label for="171"></label>
			   <img src="css2/21_02_08.png" />
			   <figcaption>Os cabeçalhos dos produtos e o rodapé podem ser configurados em CSS.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="172" name="sl">
			   <label for="172"></label>
			   <img src="css2/21_02_09.png" />
			   <figcaption>Usando os atributos mostrados, a página <code>index.htm</code> fica com este layout. Monte a sua página da Atividade da loja virtual. Agora, vamos ver como criar as "páginas filhas".</figcaption>
		   </li>
		</ul>
		<img src="css2/21_02_14.png" class="fundo" style="visibility:hidden"/>
  </details>
  <details class="sub"><summary>&#x1f4c3; Detalhes das outras páginas</summary>
	<p>Na pasta chamada <code>webdesign/atividade5</code>, crie as páginas <code>sobrenos.htm</code> e <code>contato.htm</code>. Estas páginas usarão a mesma pasta de imagens criada para a página principal.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="173" name="sl">
			   <label for="173"></label>
			   <img src="css2/21_02_10.png" />
			   <figcaption>A página <code>sobrenos.htm</code> contém informações genéricas da loja virtual. Insira uma imagem e um pouco de texto sobre o atendimento da loja.</figcaption>
		   </li>
		  <li>
			   <input type="radio" id="174" name="sl">
			   <label for="174"></label>
			   <img src="css2/21_02_11.png" />
			   <figcaption>Podemos copiar toda a configuração CSS da página <code>index.htm</code>. A tag de conteúdo pode conter apenas atributos de alinhamento vertical e de largura nesta página.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="175" name="sl">
			   <label for="175"></label>
			   <img src="css2/21_02_12.png" />
			   <figcaption>O layout da página fica com esta configuração. Note que o ícone, banner, barra lateral, menu e rodapé ficam com mesmo layout da página <code>index.htm</code>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="176" name="sl">
			   <label for="176"></label>
			   <img src="css2/21_02_13.png" />
			   <figcaption>Na página de contato, podemos usar a mesma estrutura HTML usada na Atividade 4. Crie o arquivo <code>enviar.php</code> com mesmo código que usamos nos formulários de contato que já criamos.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="177" name="sl">
			   <label for="177"></label>
			   <img src="css2/21_02_14.png" />
			   <figcaption>Configure os atributos dos itens do formulário de acordo com as cores usadas no layout do site. Note que o conteúdo desta página de contato também pode ser configurado de forma simplificada, sem os itens dos produtos.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="178" name="sl">
			   <label for="178"></label>
			   <img src="css2/21_02_15.png" />
			   <figcaption>Com as propriedades e atributos mostrados, a página de contato fica com esse layout. Crie suas páginas de contato e "Sobre nós". A página de promoções é opcional, que pode mostrar alguns produtos em destaque.</figcaption>
		   </li>
		</ul>
		<img src="css2/21_02_14.png" class="fundo" style="visibility:hidden"/>
  </details>
	<img src="css2/tags001_0022a.png" />
	<p class="topop"><a href="#css2" class="topo">voltar ao topo</a></p>
	<img src="css2/tags001_0023.png" />
	<details class="sub"><summary>&#x1f4c3; Mapeamento de imagens</summary>
	<p>Vamos criar uma pasta chamada <code>webdesign/mapeamento</code>. Nesta pasta, crie um arquivo chamado <code>mapeamento.htm</code>. Escolha um dos arquivos para fazer o mapeamento: <a href="css2/menu_horizontal.png" download>menu verde</a>, <a href="css2/menu_horizontal1.png" download>menu branco</a> ou encontre outra imagem de um menu completo.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="179" name="sl">
			   <label for="179"></label>
			   <img src="css2/23_01_00.png" />
			   <figcaption>Um mapeamento de imagens usa a tag <code>&lt;map&gt;</code>, que contém os shapes com links. A primeira tag desta página é a imagem que será mapeada com a tag <code>&lt;img&gt;</code>.</figcaption>
		   </li>
		  <li>
			   <input type="radio" id="180" name="sl">
			   <label for="180"></label>
			   <img src="css2/23_01_01.png" />
			   <figcaption>Como precisamos referenciar qual será a imagem mapeada, usamos os atributos <code>usemap="#Map"</code> na tag <code>&lt;img&gt;</code> e o identificador <code>id="#Map"</code>. Desta forma, os shapes aparecerão por cima da imagem com identificador <code>#Map</code>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="181" name="sl">
			   <label for="181"></label>
			   <img src="css2/23_01_03.png" />
			   <figcaption>Neste exemplo, mostraremos o uso dos círculos para mapear. Eles criam uma área invisível para o visitante, mas que ao passar o cursor do mouse por cima da área na imagem, aparece o link. Os círculos possuem as coordenadas do centro <b>X</b> e <b>Y</b> e a medida do <b>RAIO</b>: <code>coords="X,Y,RAIO"</code>. Pegue as coordenadas da imagem de menu que você mapear em um editor de imagens.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="183" name="sl">
			   <label for="183"></label>
			   <img src="css2/23_01_04.png" />
			   <figcaption>Outras informações que precisamos inserir na tag de cada shape é do link e seu título: <code>href</code> e <code>title</code>. Crie o mapeamento, salve a página e teste o layout. Vamos fazer outros mapeamentos a seguir.</figcaption>
		   </li>
		</ul>
		<img src="css2/23_01_00.png" class="fundo" />
  </details>
	<img src="css2/tags001_0023a.png" />
	<p class="topop"><a href="#css2" class="topo">voltar ao topo</a></p>
	<img src="css2/tags001_0024.png" />
	<p class="topop"><a href="#css2" class="topo">voltar ao topo</a></p>
	<img src="css2/tags001_0025.png" />
	<details class="sub"><summary>&#x1f4c3; Mapeamento de imagens com SVG</summary>
	<p>Vamos usar a pasta <code>webdesign/mapeamento</code> para este exercício. Crie um arquivo chamado <code>mapeamento-svg.htm</code>. Escolha um dos arquivos para fazer o mapeamento: <a href="css2/menu_horizontal.png" download>menu verde</a>, <a href="css2/menu_horizontal1.png" download>menu branco</a> ou encontre outra imagem de um menu completo.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="184" name="sl">
			   <label for="184"></label>
			   <img src="css2/25_01_01.png" />
			   <figcaption>Usando SVG, nosso mapeamento ficará responsivo. Com a tag <code>&lt;svg&gt;</code>, crie a janela de visualização <code>viewBox</code> com as mesmas dimensões da imagem que será mapeada.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="185a" name="sl">
			   <label for="185a"></label>
			   <img src="css2/25_01_02.png" />
			   <figcaption>A estrutura com SVG é basicamente a mesma que usamos com tags HTML, modificando apenas a forma de escrever os comandos. Dentro de uma tag de link <code>&lt;a&gt;</code>, colocamos os shapes. Neste exemplo, são mostrados o círculo, o retângulo e o polígono com SVG.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="186" name="sl">
			   <label for="186"></label>
			   <img src="css2/25_01_03.png" />
			   <figcaption>Podemos usar atributos de opacidade nos shapes usando <code>fill-opacity:0;</code>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="187" name="sl">
			   <label for="187"></label>
			   <img src="css2/25_01_04.png" />
			   <figcaption>Quando o visitante passar o cursor do mouse sobre os mapeamentos, usamos o atributo <code>hover</code> de cada shape para definir linhas e opacidade diferente de 0. Teste o layout e os mapeamentos. Experimente diminuir o tamanho da tela do navegador para testar se o site fica responsivo.</figcaption>
		   </li>
		</ul>
		<img src="css2/25_01_00.png" class="fundo" />
  </details>
	<img src="css2/tags001_0025a.png" />
	<details class="sub"><summary>&#x1f4c3; Mapeamento com SVG e texto</summary>
	<p>Vamos usar a pasta <code>webdesign/mapeamento</code> para este exercício. Crie um arquivo chamado <code>mapeamento-svg-info.htm</code>, que usaremos para criar o mapeamento do menu com informações de texto. Escolha um dos arquivos para fazer o mapeamento: <a href="css2/menu_horizontal.png" download>menu verde</a>, <a href="css2/menu_horizontal1.png" download>menu branco</a> ou encontre outra imagem de um menu completo.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="188" name="sl">
			   <label for="188"></label>
			   <img src="css2/25_02_01.png" />
			   <figcaption>Neste exemplo, o menu branco foi usado. Note que a janela <code>viewBox</code> do SVG foi criada com altura um pouco maior, para que as informações de texto apareçam logo abaixo dos ícones do menu.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="189" name="sl">
			   <label for="189"></label>
			   <img src="css2/25_02_02.png" />
			   <figcaption>Dentro da mesma estrutura criada na página anterior, colocamos a tag <code>&lt;text&gt;</code> com respectivos shapes de retângulos. Para alinhar à esquerda o texto com o ícone, as coordenadas <b>x</b> do texto e dos retângulos são as mesmas. As coordenadas <b>y</b> serão iguais a 215px.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="190" name="sl">
			   <label for="190"></label>
			   <img src="css2/25_02_03.png" />
			   <figcaption>Definimos como padrão de visualização de retângulos e textos no CSS as opacidades nulas de tags <code>rect</code> e <code>text</code>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="191" name="sl">
			   <label for="191"></label>
			   <img src="css2/25_02_04.png" />
			   <figcaption>Quando o visitante passar o cursos do mouse por cima de uma região com tag mapeada <code>&lt;a&gt;</code>, os respectivos textos e retângulos aparecerão com a definição do atributo de opacidade em <code>a:hover > text</code> e <code>a:hover > rect</code>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="192" name="sl">
			   <label for="192"></label>
			   <img src="css2/25_02_05.png" />
			   <figcaption>Defina os atributos de cores de preenchimento, linhas, tipos de fonte e opacidade nula para os textos. A opacidade só ficará igual a 1 quando o atributo <code>hover</code> ficar ativo. Configure também o atributo <code>transition: 0.5s</code> para fazer uma transição de meio segundo na mudança de opacidade.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="193" name="sl">
			   <label for="193"></label>
			   <img src="css2/25_02_06.png" />
			   <figcaption>O layout do menu fica desta maneira. Configure outros valores e faça teste de layout no menu de sua página para usarmos em outras páginas a seguir.</figcaption>
		   </li>
		</ul>
		<img src="css2/25_02_00.png" class="fundo" style="visibility:hidden"/>
  </details>
	<img src="css2/tags001_0025b.png" />
	<p class="topop"><a href="#css2" class="topo">voltar ao topo</a></p>
	<img src="css2/tags001_0026.png" />
	<p class="topop"><a href="#css2" class="topo">voltar ao topo</a></p>
	<img src="css2/tags001_0027.png" />
	<details class="sub"><summary>&#x1f4c3; Mapeamento com div e texto</summary>
	<p>Vamos usar a pasta <code>webdesign/mapeamento</code> para este exercício. Crie um arquivo chamado <code>mapeamento-div-info.htm</code>, que usaremos para criar o mapeamento do menu com tags <code>div</code> e informações de texto. Escolha um dos arquivos para fazer o mapeamento: <a href="css2/menu_horizontal.png" download>menu verde</a>, <a href="css2/menu_horizontal1.png" download>menu branco</a> ou encontre outra imagem de um menu completo.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="194" name="sl">
			   <label for="194"></label>
			   <img src="css2/27_01_01.png" />
			   <figcaption>Neste exemplo, foi usado o menu branco. Criamos uma div "mãe" <code>class="Map"</code> que contém a imagem <code>&lt;img&gt;</code> e as <code>div</code> dos itens do menu.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="195" name="sl">
			   <label for="195"></label>
			   <img src="css2/27_01_02.png" />
			   <figcaption>A <b>div</b> <code>class="items"</code> agrupa cada item do menu. Definimos uma <b>div</b> de item, com o texto <code>&lt;p&gt;</code> e o link <code>&lt;a&gt;</code> para cada parte do menu.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="196" name="sl">
			   <label for="196"></label>
			   <img src="css2/27_01_03.png" />
			   <figcaption>Cada item tem uma posição específica no mapeamento. Logo, criamos as classes <code>class="i1"</code>, <code>class="i2"</code>, ..., <code>class="i6"</code> dos itens do menu.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="197" name="sl">
			   <label for="197"></label>
			   <img src="css2/27_01_04.png" />
			   <figcaption>Na programação CSS, definimos os atributos mais gerais, com a classe <code>.Map</code> com imagens de largura 100%, parágrafos sem margens e os itens escondidos, com o atributo <code>visibility:hidden;</code>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="198" name="sl">
			   <label for="198"></label>
			   <img src="css2/27_01_05.png" />
			   <figcaption>Ao ativar os itens com o cursor do mouse sobre cada um deles <code>items div:hover</code>, definimos que os itens serão visíveis, com bordas e opacidade de um fundo sobre cada parte do item, e o texto visível com atributo <code>visibility:visible;</code></figcaption>
		   </li>
		   <li>
			   <input type="radio" id="199" name="sl">
			   <label for="199"></label>
			   <img src="css2/27_01_06.png" />
			   <figcaption>A altura da posição do texto foi fixada em 95%, e os itens foram posicionados levando-se em conta que todos têm mesmo tamanho <code>width:calc(100%/6);</code>. Logo, o primeiro item fica em <code>left:0%;</code>, o segundo em <code>left:calc(100%/6);</code> e assim sucessivamente, até <code>left:calc(5*100%/6);</code></figcaption>
		   </li>
		   <li>
			   <input type="radio" id="200" name="sl">
			   <label for="200"></label>
			   <img src="css2/27_01_07.png" />
			   <figcaption>Para finalizar, os textos aparecem na posição <code>top:95%;</code>, e devemos deixá-los escondidos com <code>visibility:hidden;</code>. Colocando-se o <code>transition:05s;</code>, ocorre uma suavidade na mudança do estágio invisível para visível.</figcaption>
		   </li>
		</ul>
		<img src="css2/27_01_07.png" class="fundo" style="visibility:hidden"/>
  </details>
	<img src="css2/tags001_0027a.png" />
	<details class="sub"><summary>&#x1f4c3; Mapeamento lateral com div e texto</summary>
	<p>Vamos usar a pasta <code>webdesign/mapeamento</code> para este exercício. Crie um arquivo chamado <code>mapeamento-lateral-div-info.htm</code>, que usaremos para criar o mapeamento do menu lateral com tags <code>div</code> e informações de texto. Escolha um dos arquivos para fazer o mapeamento: <a href="css2/menu_horizontal.png" download>menu verde</a>, <a href="css2/menu_horizontal1.png" download>menu branco</a> ou encontre outra imagem de um menu completo.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="201" name="sl">
			   <label for="201"></label>
			   <img src="css2/27_02_01.png" />
			   <figcaption>Neste exemplo, foi usado o menu verde. Criamos uma div "mãe" <code>class="Map"</code> que contém a imagem <code>&lt;img&gt;</code> e as <code>div</code> dos itens do menu.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="202" name="sl">
			   <label for="202"></label>
			   <img src="css2/27_02_02.png" />
			   <figcaption>A <b>div</b> <code>class="items"</code> agrupa cada item do menu. Definimos uma <b>div</b> de item, com o texto <code>&lt;p&gt;</code> e o link <code>&lt;a&gt;</code> para cada parte do menu.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="203" name="sl">
			   <label for="203"></label>
			   <img src="css2/27_02_03.png" />
			   <figcaption>Cada item tem uma posição específica no mapeamento. Logo, criamos as classes <code>class="i1"</code>, <code>class="i2"</code>, ..., <code>class="i5"</code> dos itens do menu.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="204" name="sl">
			   <label for="204"></label>
			   <img src="css2/27_02_04.png" />
			   <figcaption>Na programação CSS, definimos os atributos mais gerais, com a classe <code>.Map</code> com imagens de largura 100%, parágrafos sem margens e os itens escondidos, com o atributo <code>visibility:hidden;</code>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="205" name="sl">
			   <label for="205"></label>
			   <img src="css2/27_02_05.png" />
			   <figcaption>Ao ativar os itens com o cursor do mouse sobre cada um deles <code>items div:hover</code>, definimos que os itens serão visíveis, com bordas e opacidade de um fundo sobre cada parte do item, e o texto visível com atributo <code>visibility:visible;</code></figcaption>
		   </li>
		   <li>
			   <input type="radio" id="206" name="sl">
			   <label for="206"></label>
			   <img src="css2/27_02_06.png" />
			   <figcaption>No menu lateral a posição do texto à esquerda foi fixada em 6%, e os itens foram posicionados levando-se em conta que todos têm mesmo tamanho <code>height:calc(80%/5);</code>. O primeiro item fica posicionado em <code>top:0%;</code>, o segundo em <code>top:calc(99%/5);</code> e assim sucessivamente, até <code>left:calc(4*99%/6);</code>. Como existem espaçamentos entre os itens, não usamos 100% nos cálculos.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="207" name="sl">
			   <label for="207"></label>
			   <img src="css2/27_02_07.png" />
			   <figcaption>Para finalizar, os textos aparecem na posição <code>left:6%;</code>, e devemos deixá-los escondidos com <code>visibility:hidden;</code>. A posição do primeiro item deste menu fica em <code>top:calc(80%/5);</code>, o segundo em <code>top:calc(180%/5);</code> e assim sucessivamente. Estas medidas seriam relativas a 100% do primeiro item se não existissem espaçamentos entre os itens do menu.</figcaption>
		   </li>
		</ul>
		<img src="css2/27_02_07.png" class="fundo" style="visibility:hidden"/>
  </details>
	<img src="css2/tags001_0027b.png" />
	<details class="sub"><summary>&#x1f4c3; Detalhes da Atividade</summary>
	<p>Crie a pasta <code>webdesign/atividade6</code> com o arquivo <code>index.htm</code>. Nesta atividade, podemos usar as estruturas dos exemplos anteriores para fazer o mapeamento de 3 personagens em uma imagem. Crie a pasta das imagens <code>webdesign/atividade6/imagens</code>.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="208" name="sl">
			   <label for="208"></label>
			   <img src="css2/27_03_01.png" />
			   <figcaption>Podemos criar a div "mãe" <code>class="Map"</code> que contém a imagem <code>&lt;img&gt;</code> dos personagens e as <code>div</code> de cada personagem que será mapeado. A div <code>class="items"</code> agrupa as div dos personagens.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="209" name="sl">
			   <label for="209"></label>
			   <img src="css2/27_03_02.png" />
			   <figcaption>Usando a programação CSS dos exemplos anteriores, podemos abrir a tag de parágrafo <code>&lt;p&gt;</code> que abriga o nome, uma imagem e uma breve descrição do personagem. A classe desta div será <code>class="i1"</code>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="210" name="sl">
			   <label for="210"></label>
			   <img src="css2/27_03_03.png" />
			   <figcaption>Os outros personagens têm a estrutura HTML igual: nome, imagem e descrição.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="211" name="sl">
			   <label for="211"></label>
			   <img src="css2/27_03_04.png" />
			   <figcaption>Na programação CSS, definimos os atributos mais gerais, com a classe <code>.Map</code> com imagens de largura 70%, parágrafos sem margens e os itens escondidos, com o atributo <code>visibility:hidden;</code>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="212" name="sl">
			   <label for="212"></label>
			   <img src="css2/27_03_05.png" />
			   <figcaption>Ao ativar os itens com o cursor do mouse sobre cada um deles <code>items div:hover</code>, definimos que os itens serão visíveis, com bordas e opacidade de um fundo sobre cada parte do item, e o texto visível com atributo <code>visibility:visible;</code></figcaption>
		   </li>
		   <li>
			   <input type="radio" id="213" name="sl">
			   <label for="213"></label>
			   <img src="css2/27_03_06.png" />
			   <figcaption>Em um editor de imagens, pegue as coordenadas <b>top</b>, <b>left</b>, <b>width</b> e <b>height</b> do mapeamento de cada personagem. Com estas coordenadas, calculamos as posições dos retângulos com as regras de três mostradas, relativas à largura e à altura da imagem de todos os personagens.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="213a" name="sl">
			   <label for="213a"></label>
			   <img src="css2/27_03_06.png" />
			   <figcaption>Neste exemplo, as medidas para o mapeamento do primeiro personagem são: <b>top=104</b>, <b>left=168</b>, <b>width=59</b>, <b>height=82</b>, e as dimensões da imagem dos personagens é <b>width=800</b> e <b>height=500</b>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="214" name="sl">
			   <label for="214"></label>
			   <img src="css2/27_03_07.png" />
			   <figcaption>Se você quiser deixar o texto alinhado à esquerda, basta usar a mesma medida à esquerda do retângulo <code>left:calc(168*100%/800);</code>. O atributo <b>top</b> do texto é definido pelo atributo <b>top</b> do retângulo (104) somado com a altura do retângulo (82). Logo, o cálculo fica: <code>top:calc((104 + 82)*100%/500);</code>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="215" name="sl">
			   <label for="215"></label>
			   <img src="css2/27_03_08.png" />
			   <figcaption>A posição vertical <b>top</b> pode ser calculada da mesma forma para todos os mapeamentos. Neste exemplo, estamos usando a largura dos textos como 20%. Logo, se você quiser deixar o texto centralizado, basta subtrair a metade da largura (10%) e somar com a metade do tamanho do retângulo (no caso do segundo personagem mede 60) proporcional a 50% do retângulo.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="215a" name="sl">
			   <label for="215a"></label>
			   <img src="css2/27_03_08.png" />
			   <figcaption>Portanto, para ficar centralizado com o retângulo, o texto do segundo personagem usamos <code>left:calc(357*100%/800 - 10% + 60*50%/800);</code>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="216" name="sl">
			   <label for="216"></label>
			   <img src="css2/27_03_09.png" />
			   <figcaption>Como exemplo, se você quiser alinhar o texto à direita, basta subtrair a largura do texto de 20% e somar com o tamanho proporcional da largura do retângulo. Logo, o alinhamento à direita do terceiro personagem fica: <code>left:calc(692*100%/800 - 20% + 80*100%/800);</code>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="217" name="sl">
			   <label for="217"></label>
			   <img src="css2/27_03_10.png" />
			   <figcaption>Para finalizar, os textos aparecem com a largura <code>width:20%;</code>, e devemos deixá-los escondidos com <code>visibility:hidden;</code>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="218" name="sl">
			   <label for="218"></label>
			   <img src="css2/27_03_11.png" />
			   <figcaption>O layout desta Atividade, com os atributos mostrados fica desta forma. Modifique atributos e escolha um dos alinhamentos de texto mostrados para fazer sua atividade.</figcaption>
		   </li>
		</ul>
		<img src="css2/27_03_08.png" class="fundo" style="visibility:hidden"/>
  </details>
	<p class="topop"><a href="#css2" class="topo">voltar ao topo</a></p>
</details>

<details id="css3"><summary>CSS e Animações: pág. 28-38</summary>
	<img src="css3/tags001_0028.png" />
	<p class="topop"><a href="#css3" class="topo">voltar ao topo</a></p>
	<img src="css3/tags001_0029.png" />
	<p class="topop"><a href="#css3" class="topo">voltar ao topo</a></p>
	<img src="css3/tags001_0030.png" />
	<p class="topop"><a href="#css3" class="topo">voltar ao topo</a></p>
	<img src="css3/tags001_0031.png" />
	<details class="sub"><summary>&#x1f4c3; Atividade 7: Menu superior</summary>
	<p>Crie a pasta <code>webdesign/atividade7</code> com os arquivos <code>index.htm</code> e <code>estilo.css</code>. Nesta atividade, podemos usar a estrutura que usamos nos exemplos anteriores para fazer o menu. Crie a pasta das imagens <code>webdesign/atividade7/imagens</code>. Vamos criar um site com páginas sobre filmes nesta atividade. Escolha arquivos de imagens sobre seu filme favorito. A logomarca terá efeito de animação com rotação, e deve ser uma imagem de fundo transparente e com formato redondo. <a href="css3/icone_filme.png" download>Neste link</a> pode pode baixar a imagem da logomarca usada nesta atividade.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="219" name="sl">
			   <label for="219"></label>
			   <img src="css3/30_01_01.png" />
			   <figcaption>No cabeçalho da página, colocamos a referência da folha de estilos com a tag <code>&lt;link&gt;</code>. Se salvarmos o arquivo <code>estilo.css</code> na mesma pasta do <code>index.htm</code>, o caminho fica como <code>href="estilo.css"</code>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="220" name="sl">
			   <label for="220"></label>
			   <img src="css3/30_01_02.png" />
			   <figcaption>A tag "mãe" do site é a <code>class="boxSite"</code>, que contém todas as outras <b>div</b>. A primeira div será chamada de <code>class="barra"</code>, que contém a logomarca, o menu e os itens para compartilhar a página.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="221" name="sl">
			   <label for="221"></label>
			   <img src="css3/30_01_03.png" />
			   <figcaption>Na div <code>class="logo"</code>, podemos colocar uma imagem ou um <a href="http://www.degraf.ufpr.br/docentes/paulo/webdesign/pictograph.html" target="_blank">pictograma</a>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="222" name="sl">
			   <label for="222"></label>
			   <img src="css3/30_01_04.png" />
			   <figcaption>A <code>class="menu"</code> contém uma lista, bem parecida com as que já usamos em outras páginas.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="223" name="sl">
			   <label for="223"></label>
			   <img src="css3/30_01_05.png" />
			   <figcaption>Como exemplo, vamos criar um menu chamado "dropdown": é aquele que tem subitens. Basta criar uma lista com tag <code>&lt;ul&gt;</code> logo abaixo do item do menu que tem a sublista. Neste exemplo, criamos a lista <code>&lt;ul class="subitens"&gt;</code> logo abaixo do item <code>href="pagina1.htm"</code>. Note que o fechamento deste item é feito depois do fechamento dos subitens.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="224" name="sl">
			   <label for="224"></label>
			   <img src="css3/30_01_06.png" />
			   <figcaption>Finalizando a nossa barra de menu, colocamos as imagens de compartilhamento. Os links podem ser colocados como fizemos nas Atividades 4 e 5.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="225" name="sl">
			   <label for="225"></label>
			   <img src="css3/30_01_07.png" />
			   <figcaption>No arquivo <code>estilo.css</code>, podemos usar o marcador <b>*</b> para definir uma propriedade que vale para todas as tags da página: tipos e tamanhos de fonte, cores e margens. O atributo <code>margin:auto;</code> serve para deixar o conteúdo centralizado nos navegadores.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="226" name="sl">
			   <label for="226"></label>
			   <img src="css3/30_01_08.png" />
			   <figcaption>A estrutura CSS do menu é praticamente a mesma que usamos anteriormente. Modifique cores, margens e bordas. Neste exemplo, estamos usando o menu com a borda direita, parecido com aquele que mostramos nas Atividades 4 e 5.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="227" name="sl">
			   <label for="227"></label>
			   <img src="css3/30_01_09.png" />
			   <figcaption>Os subitens ficam escondidos <code>opacity:0;</code>, e quando ativados têm a posição absoluta na tela. Colocamos <code>z-index:1;</code> para ter certeza de que aparecerão na frente dos outros elementos da página. O menu dropdown pode ser mostrado em linha ou em coluna. Neste caso, ficará em coluna com o atributo <code>flex-direction:column;</code>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="228" name="sl">
			   <label for="228"></label>
			   <img src="css3/30_01_10.png" />
			   <figcaption>Ao passar o cursor do mouse sobre o item do menu que tem subitem, a opacidade da lista dos subitens tem valor modificado para 1 com o atributo <code>.menu li:hover ul {opacity:1;}</code>. Foram colocadas bordas inferiores para separar os subitens. Teste estas propriedades no layout de sua página.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="229" name="sl">
			   <label for="229"></label>
			   <img src="css3/30_01_11.png" />
			   <figcaption>Foram colocados atributos de fundo gradiente e alinhamento centralizado para os itens das classes <code>.barra</code> e <code>.logo</code>. Teste valores para dimensionar a imagem da logomarca em <code>.logo img</code>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="230" name="sl">
			   <label for="230"></label>
			   <img src="css3/30_01_12.png" />
			   <figcaption>Nos links de compartilhamento, usamos atributos parecidos com os que usamos em páginas anteriores. Teste valores para dimensionar as imagens dos ícones de sua página. Em telas menores, a barra terá os itens dispostos em coluna <code>flex-direction:column;</code></figcaption>
		   </li>
		   <li>
			   <input type="radio" id="231" name="sl">
			   <label for="231"></label>
			   <img src="css3/30_01_13.png" />
			   <figcaption>Usando os atributos mostrados, o layout da barra de menu fica desta maneira. Configure a sua barra testando as melhores medidas e cores.</figcaption>
		   </li>
		</ul>
		<img src="css3/30_01_00.png" class="fundo" style="visibility:hidden"/>
  </details>
	<img src="css3/tags001_0031a.png" />
	<p class="topop"><a href="#css3" class="topo">voltar ao topo</a></p>
	<img src="css3/tags001_0032.png" />
	<p class="topop"><a href="#css3" class="topo">voltar ao topo</a></p>
	<img src="css3/tags001_0033.png" />
	<img src="css3/tags001_0033a.png" />
	<details class="sub"><summary>&#x1f4c3; Atividade 7: backgrounds e animações</summary>
	<p>Neste ponto, podemos criar animações nos itens que já estão programados. A imagem com um filme está disponível no link: <a href="css3/filme.png" download>filme</a>; e a imagem de nuvens, mostrada na apostila, está disponível no link: <a href="css3/clouds.png" download>nuvens</a>. Se você quiser encontrar outra imagem para colocar na barra superior da página, lembre-se que deve ser uma imagem bem larga, com altura reduzida.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="232" name="sl">
			   <label for="232"></label>
			   <img src="css3/32_01_01.png" />
			   <figcaption>Criando a <code>class="barra2"</code>, podemos definir um fundo desta tag. Ela pode ser colocada antes ou depois da <code>class="barra"</code>. Dentro da <code>class="logo"</code>, podemos inserir uma imagem ou <a href="http://www.degraf.ufpr.br/docentes/paulo/webdesign/pictograph.html" target="_blank">pictograma</a> como logomarca da página.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="233" name="sl">
			   <label for="233"></label>
			   <img src="css3/32_01_02.png" />
			   <figcaption>A estrutura do <b>toggle</b> deve ser colocada englobando a tag de menu. O <b>checkbox</b> fica antes da tag <code>&lt;label&gt;</code>, inserindo o <b>toggle</b> junto com o menu nesta tag de rótulo.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="234" name="sl">
			   <label for="234"></label>
			   <img src="css3/32_01_03.png" />
			   <figcaption>Na continuação do arquivo CSS, temos os atributos para esconder o <b>checkbox</b> e o <b>toggle</b> do menu. Eles só aparecem em navegadores com largura menor do que 800px. Redimensione o seu navegador para testar estes atributos.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="235" name="sl">
			   <label for="235"></label>
			   <img src="css3/32_01_04.png" />
			   <figcaption>Usando os atributos de <code>@media screen</code> com largura menor do que 800px, definimos que a tag <code>.barra</code> será mostrada com itens na vertical, e o <b>toggle</b> ficará visível. Neste caso, podemos atribuir propriedades para os itens visíveis (cor, tamanho, margem,...).</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="236" name="sl">
			   <label for="236"></label>
			   <img src="css3/32_01_05.png" />
			   <figcaption>Neste ponto está definido o critério para o menu e o toggle aparecerem: <code>#checkbox1:checked</code>, ou seja, quando o visitante clicar no menu. Definimos também qual será a altura máxima do menu: <code>max-height:50vh;</code>, ou seja, metade da altura do navegador.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="237" name="sl">
			   <label for="237"></label>
			   <img src="css3/32_01_06.png" />
			   <figcaption>No caso do <b>checkbox</b> não estar ativado, o menu terá a altura máxima como 0. Os itens estão com atributos escondidos <code>hidden</code>, em formato vertical (coluna).</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="238" name="sl">
			   <label for="238"></label>
			   <img src="css3/32_01_07.png" />
			   <figcaption>A classe <code>.barra2</code> está com a imagem de fundo definida, com repetição na horizontal <code>repeat-x</code>, com a altura igual à altura da imagem de 90px. A animação de deslocamento do fundo começa na posição 0% 0% e termina em 100% 0%. Modifique os valores, caso necessário, e escolha uma imagem para ficar no fundo desta tag.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="239" name="sl">
			   <label for="239"></label>
			   <img src="css3/32_01_08.png" />
			   <figcaption>Com todos os atributos mostrados até agora, o layout com as duas barras superiores fica desta maneira. O fundo da tag do menu foi modificado usando o atributo <code>linear-gradient</code>.</figcaption>
		   </li>
		</ul>
		<img src="css3/32_01_00.png" class="fundo" style="visibility:hidden"/>
  </details>
	<img src="css3/tags001_0033b.png" />
	<p class="topop"><a href="#css3" class="topo">voltar ao topo</a></p>
	<img src="css3/tags001_0034.png" />
	<details class="sub"><summary>&#x1f4c3; Atividade 7: banner e descrição</summary>
	<p>Neste ponto, podemos criar o banner e uma logo para colocar flutuando sobre o banner. Escolha uma imagem com boa resolução para ficar no banner, e uma logo do filme.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="240" name="sl">
			   <label for="240"></label>
			   <img src="css3/32_02_01.png" />
			   <figcaption>A tag <code>class="banner"</code> pode ser inserida logo após a tag <code>class="barra"</code>. Dentro desta tag, criamos a tag filha <code>class="descricao"</code> para criarmos uma logo flutuante sobre o banner.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="241" name="sl">
			   <label for="241"></label>
			   <img src="css3/32_02_02.png" />
			   <figcaption>Na continuação do arquivo CSS, temos os atributos da classe <code>.banner</code>, com o background que você escolheu (sem repetição), com as propriedades para cobrir a largura da tag. O alinhamento da tag <code>.descricao</code> ficará à esquerda pois <code>flex-direction:flex-start;</code>. Se você quiser colocá-la centralizada no banner, basta mudar para <code>center</code> ou à direita ficaria <code>flex-end</code>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="242" name="sl">
			   <label for="242"></label>
			   <img src="css3/32_02_03.png" />
			   <figcaption>Quando o visitante passar o cursor do mouse sobre o banner, ele sofre um deslocamento na vertical: vai para a coordenada 0% 48%. Note que colocamos o efeito <b>transition</b> nesta tag e na tag do banner sem hover. Assim, o efeito é suavidado tanto no momento de passar o cursor quanto de retirar o cursor de cima do banner.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="243" name="sl">
			   <label for="243"></label>
			   <img src="css3/32_02_04.png" />
			   <figcaption>A tag filha <code>.descricao</code> fica com posição relativa, com fundo com transparência usada na cor RGBA. Defina margem interna para que a imagem não fique "grudada" nos cantos.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="244" name="sl">
			   <label for="244"></label>
			   <img src="css3/32_02_05.png" />
			   <figcaption>Para dar um efeito de profundidade, podemos colocar uma sombra na tag mãe das páginas usando o atributo <code>box-shadow</code>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="245" name="sl">
			   <label for="245"></label>
			   <img src="css3/32_02_06.png" />
			   <figcaption>Com os valores dos atributos mostrados até agora, o site fica com este layout. Modifique os valores para a página do seu filme.</figcaption>
		   </li>
		</ul>
		<img src="css3/32_02_00.png" class="fundo" style="visibility:hidden"/>
  </details>
  <img src="css3/tags001_0034a.png" />
	<p class="topop"><a href="#css3" class="topo">voltar ao topo</a></p>
	<img src="css3/tags001_0035.png" />
	<details class="sub"><summary>&#x1f4c3; Atividade 7: conteúdos, fontes e rodapé</summary>
	<p>Neste ponto, podemos criar conteúdos em duas barras: uma principal e outra lateral. Escolha imagens do filme para ficarem como uma espécie de galeria. Outras imagens podem ser colocadas na barra lateral, com alguns personagens formando outra galeria.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="246" name="sl">
			   <label for="246"></label>
			   <img src="css3/34_01_01.png" />
			   <figcaption>A tag <code>class="barra3"</code> pode ser inserida logo após a tag <code>class="banner"</code>. Dentro desta tag, criamos as tags filhas <code>class="conteudo"</code> e <code>class="box"</code> que contém as imagens do filme. Colocamos também uma tag <code>class="titulo"</code> para usar nesta barra.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="247" name="sl">
			   <label for="247"></label>
			   <img src="css3/34_01_02.png" />
			   <figcaption>Escolha pelo menos 5 imagens para colocar nas tags <code>class="box"</code> dentro da tag de <code>class="conteudo"</code>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="248" name="sl">
			   <label for="248"></label>
			   <img src="css3/34_01_03a.png" />
			   <figcaption>A tag <code>class="lateral"</code> tem mesma estrutura da tag <code>class="conteudo"</code>: título e as tags <code>class="box"</code> com as imagens. Escolha pelo menos 5 personagens para colocar nesta barra lateral.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="249" name="sl">
			   <label for="249"></label>
			   <img src="css3/34_01_04.png" />
			   <figcaption>Podemos colocar as fontes online em nossas páginas. Acesse o site <a href="https://fonts.google.com/" target="_blank">fonts.google.com/</a>, escolha uma fonte e clique em <b>Select this style</b>. Você pode escolher mais de uma fonte. Note que as fontes escolhidas aparecem ao lado, com os links prontos para colocarmos no HTML e no CSS.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="249a" name="sl">
			   <label for="249a"></label>
			   <img src="css3/34_01_03.png" />
			   <figcaption>No cabeçalho da página em HTML colocamos o link das fontes escolhidas. Neste caso, eu escolhi a fonte <b>Kufam</b>, que será colocada naquela tag principal do CSS, que usamos com <b>*</b> no começo da Atividade 7.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="250" name="sl">
			   <label for="250"></label>
			   <img src="css3/34_01_05.png" />
			   <figcaption>Na continuação do nosso arquivo CSS, colocamos os atributos da classe <code>.barra3</code> com display flexbox e fundo com gradiente. Para alinhar os conteúdos na vertical, usamos o atributo <code>align-content:flex-start</code>, que tem a mesma função do <code>vertical-align</code> das tabelas.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="251" name="sl">
			   <label for="251"></label>
			   <img src="css3/34_01_06.png" />
			   <figcaption>As caixas com conteúdos <code>.box</code> tem os atributos: bordas arredondadas, margens, fundo gradiente, alinhamento de texto e tamanhos iguais de no mínimo 150px <code>flex:1 150px</code>. As imagens destas caixas têm larguras e alturas ajustadas de acordo com as dimensões do navegador. Ajuste os valores para as imagens de sua página.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="252" name="sl">
			   <label for="252"></label>
			   <img src="css3/34_01_07.png" />
			   <figcaption>Nesta página, ao invés de usar a tabela "zebrada", podemos usar os box com este atributo. Os pares (even) ficam com um tipo de fundo gradiente, e os ímpares (odd) ficam com outro tipo.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="253" name="sl">
			   <label for="253"></label>
			   <img src="css3/34_01_08.png" />
			   <figcaption>Os ajustes da tag <code>.lateral</code> são similares às caixas, com alinhamentos horizontais centralizados e verticais no topo (flex-start). Ajuste os valores das dimensões das imagens de sua página. No caso desta página, as imagens tem largura bem menor do que a altura, pois mostram apenas 1 personagem cada.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="254" name="sl">
			   <label for="254"></label>
			   <img src="css3/34_01_09.png" />
			   <figcaption>Os atributos dos títulos usam margens, cores e uma sombra de texto. O rodapé está com conteúdo centralizado, margem interna e fundo com gradiente.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="255" name="sl">
			   <label for="255"></label>
			   <img src="css3/34_01_10.jpg" />
			   <figcaption>O layout da página fica com esta visualização usando os atributos definidos até o momento. Configure a sua página com as novas tags de imagens nas galerias criadas.</figcaption>
		   </li>
		</ul>
		<img src="css3/34_01_03a.png" class="fundo" style="visibility:hidden"/>
  </details>
	<p class="topop"><a href="#css3" class="topo">voltar ao topo</a></p>
	<img src="css3/tags001_0036.png" />
	<p class="topop"><a href="#css3" class="topo">voltar ao topo</a></p>
	<img src="css3/tags001_0037.png" />
	<p class="topop"><a href="#css3" class="topo">voltar ao topo</a></p>
	<img src="css3/tags001_0038.png" />
	<details class="sub"><summary>&#x1f4c3; Detalhes finais e animações</summary>
	<p>Vamos criar efeitos de galeria na nossa página de filmes. Coloque os nomes dos filmes nos itens do menu.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="256" name="sl">
			   <label for="256"></label>
			   <img src="css3/37_01_01.png" />
			   <figcaption>A estrutura final do HTML, com itens anteriores recolhidos, fica desta maneira: dentro de <code>boxSite</code> temos <code>barra2</code>,  <code>barra</code>, <code>banner</code>, <code>barra3</code> e <code>rodape</code>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="257" name="sl">
			   <label for="257"></label>
			   <img src="css3/37_01_02.png" />
			   <figcaption>No CSS, podemos criar efeitos com transformações de escala, cisalhamento, rotação ou translação. Neste exemplo usamos uma escala com sombra nas imagens das tags <code>.box</code> quando passamos o cursor do mouse sobre as respectivas imagens.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="258" name="sl">
			   <label for="258"></label>
			   <img src="css3/37_01_03.png" />
			   <figcaption>Uma animação na logomarca de descrição do site que usa rotação e escalas está atribuída com nome <code>@keyframes AnimaDescr</code>. Dentro da tag <code>.descricao img</code> colocamos a duração de 7 segundo com alternância e duração constante.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="259" name="sl">
			   <label for="259"></label>
			   <img src="css3/37_01_04.png" />
			   <figcaption>A logomarca de filme, com formato redondo é ótima para usarmos a rotação de 0 a 360&deg;. Na tag <code>.logo img</code> colocamos o nome desta animação <code>AnimaLogo</code> com 7 segundos também. Ajuste valores e efeitos nas imagens de sua página.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="260" name="sl">
			   <label for="260"></label>
			   <img src="css3/37_01_05.png" />
			   <figcaption>Em telas de larguras menores do que 800px, ajustamos as barras flexbox com visualização em coluna, larguras de 100% e alinhamentos centralizados. As imagens das barras de conteúdo e lateral também podem ser redimensionadas para telas menores. Faça testes ajustanto a tela do seu navegador para escolher os melhores valores para as imagens de sua página.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="261" name="sl">
			   <label for="261"></label>
			   <img src="css3/37_01_06.png" />
			   <figcaption>Os efeitos de transformação, bordas laterais e a imagem da descrição do site também podem ficar com valores ajustados para telas menores. O tamanho do banner pode ser reduzido, assim como a largura da imagem de descrição da página.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="262" name="sl">
			   <label for="262"></label>
			   <img src="css3/37_01_08.png" />
			   <figcaption>Ao passar o cursor do mouse por cima de cada imagem das tags <code>.box</code>, o efeito do layout fica desta maneira.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="263" name="sl">
			   <label for="263"></label>
			   <img src="css3/37_01_07.jpg" />
			   <figcaption>Com os valores e atributos mostrados, a página da Atividade 7 fica com este layout. Ajuste os valores, cores e margens para sua página. Coloque os nomes de outros 4 filmes nos itens do menu do site.</figcaption>
		   </li>
		</ul>
		<img src="css3/37_01_03.png" class="fundo" style="visibility:hidden"/>
  </details>
	<img src="css3/tags001_0038a.png" />
	<details class="sub"><summary>&#x1f4c3; Detalhes da estrutura em HTML</summary>
	<p>Esta página tem estrutura HTML parecida com a que montamos na página da Atividade 7. Crie uma pasta chamada <code>webdesign/atividade8</code> com a página inicial <code>index.htm</code>. Vamos precisar também da pasta <code>webdesign/atividade8/imagens</code>.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="264" name="sl">
			   <label for="264"></label>
			   <img src="css3/37_02_01.png" />
			   <figcaption>A tag "mãe" do site será <code>class="boxSite"</code>, com a barra de menu <code>class="barra"</code>, onde colocaremos uma logo. Vamos fazer uma página de algum lugar com belas paisagens. Escolha um <a href="http://www.degraf.ufpr.br/docentes/paulo/webdesign/pictograph.html" target="_blank">pictograma</a> ou coloque uma imagem na tag <code>class="logo"</code>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="265" name="sl">
			   <label for="265"></label>
			   <img src="css3/37_02_02.png" />
			   <figcaption>A estrutura de menu será a mesma que usamos na atividade anterior. Alguns atributos CSS ficarão diferentes, pois da tag <code>&lt;label&gt;</code> está englobando os itens do menu.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="266" name="sl">
			   <label for="266"></label>
			   <img src="css3/37_02_03.png" />
			   <figcaption>Depois da tag <code>class="barra"</code>, podemos inserir a <code>class="banner"</code>, que contém a <code>class="descrição"</code>. Neste caso, coloque um texto ou uma imagem para ser o título da página.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="267" name="sl">
			   <label for="267"></label>
			   <img src="css3/37_02_04.png" />
			   <figcaption>A barra <code>class="compartilhar"</code> fica logo abaixo da <code>class="banner"</code>. Insira links para os itens desta barra.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="268" name="sl">
			   <label for="268"></label>
			   <img src="css3/37_02_05.png" />
			   <figcaption>Depois da barra <code>class="compartilhar"</code>, podemos criar a barra de contéudo <code>class="barra2"</code>, como se fosse uma galeria de imagens das paisagens que vamos inserir.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="269" name="sl">
			   <label for="269"></label>
			   <img src="css3/37_02_06.png" />
			   <figcaption>Insira o texto sobre o local escolhido em uma <code>&lt;div&gt;</code>, pois vamos distribuir os conteúdos usando <code>display:flex;</code> no CSS.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="270" name="sl">
			   <label for="270"></label>
			   <img src="css3/37_02_07.png" />
			   <figcaption>Crie títulos para cada imagem colocada em tag <code>class="box"</code>. Este título pode ficar antes ou depois da imagem.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="271" name="sl">
			   <label for="271"></label>
			   <img src="css3/37_02_08.png" />
			   <figcaption>Por último, a tag mais simples de nossas páginas: o rodapé.</figcaption>
		   </li>
		</ul>
		<img src="css3/37_02_00.png" class="fundo" style="visibility:hidden"/>
  </details>
  <details class="sub"><summary>&#x1f4c3; Detalhes da estrutura em CSS</summary>
	<p>A estrutura CSS desta página fica um pouco mais simplificada em relação à Atividade 7. Crie o arquivo de folha de estilos na pasta <code>webdesign/atividade8</code> com nome <code>estilo.css</code>.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="272" name="sl">
			   <label for="272"></label>
			   <img src="css3/37_02_10.png" />
			   <figcaption>Escolha a fonte do site <b>google fonts</b> e defina os elementos genéricos da página com o indicar <b>*</b>. Defina altura mínima do banner, posição, alinhamentos e efeitos com <code>hover</code>. Nesta página, vamos usar o atributo <code>overflow:auto;</code> que permite sobreposições de elementos.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="273" name="sl">
			   <label for="273"></label>
			   <img src="css3/37_02_11.png" />
			   <figcaption>Defina um valor grande para o <code>z-index</code> para deixar a barra de menu sobre o banner. para deixá-la alinhada na vertical, usamos <code>align-items:flex-start;</code>. A tag <code>label</code> é "mãe" do menu. Logo, definimos margem e tamanho <code>flex:3;</code> nesta tag. Para deixar o menu alinhado à direita, basta usar <code>justify-content:flex-end;</code>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="274" name="sl">
			   <label for="274"></label>
			   <img src="css3/37_02_12.png" />
			   <figcaption>Os itens do menu têm estrutura de programação CSS parecida com a que usamos na atividade 7. Escolha cores adequadas para ter um contraste com a imagem de fundo do banner. Neste caso, foi escolhida a cor branca com sombra de texto <code>text-shadow</code>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="275" name="sl">
			   <label for="275"></label>
			   <img src="css3/37_02_13.png" />
			   <figcaption>Para alinhar a <code>.logo</code> à esquerda usamos <code>justify-content:flex-start;</code>. Neste exemplo vamos utilizar um pictograma: logo, definimos <code>font-size</code> com tamanho maior do que o usual. A animação será a mesma da página da atividade anterior. A barra de compartilhamento pode ter os valores ajustados de acordo com as dimensões das imagens.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="276" name="sl">
			   <label for="276"></label>
			   <img src="css3/37_02_14.png" />
			   <figcaption>Ajuste os valores de todos os elementos programados para visualizar tanto em um navegador com mais e com menos de 800px de largura. A tag <code>.barra</code> tem o atributo <code>flex-direction:column;</code> em navegadores com larguras reduzidas.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="277" name="sl">
			   <label for="277"></label>
			   <img src="css3/37_02_15.png" />
			   <figcaption>Tanto o toggle quando o checkbox ficam invisíveis em telas maiores. Note que nas configurações de telas menores, estamos sem os subitens. Nesta página o menu é simplificado, com apenas itens principais.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="278" name="sl">
			   <label for="278"></label>
			   <img src="css3/37_02_16.png" />
			   <figcaption>Os atributos da <code>.barra2</code> e dos <code>.box</code> são similares aos que usamos na atividade anterior. Vamos usar a largura da barra menor, com 85%.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="279" name="sl">
			   <label for="279"></label>
			   <img src="css3/37_02_17.png" />
			   <figcaption>Atribua as propriedades para visualização dos títulos e do rodapé da página.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="280" name="sl">
			   <label for="280"></label>
			   <img src="css3/37_02_18.png" />
			   <figcaption>O efeito de transformação de imagens que usamos na atividade anterior pode ser usado nos <code>.box</code>. Assim, as imagens são ampliadas com os títulos, como se fossem legendas.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="281" name="sl">
			   <label for="281"></label>
			   <img src="css3/37_02_19.png" />
			   <figcaption>Defina as propriedades de animação da tag <code>.logo</code>. </figcaption>
		   </li>
		   <li>
			   <input type="radio" id="282" name="sl">
			   <label for="282"></label>
			   <img src="css3/37_02_20.png" />
			   <figcaption>Defina os atributos de visualizações das barras e das imagens da <code>.barra2 img</code>. Ajuste as dimensões das imagens em navegador com largura menor do que 800px. A disposição de elementos destas barras deve ser modificada para vertical (coluna).</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="283" name="sl">
			   <label for="283"></label>
			   <img src="css3/37_02_21.png" />
			   <figcaption>Ajuste também os efeitos de transformação e tamanhos de fontes das tags <code>.logo</code> e <code>.descricao</code>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="284" name="sl">
			   <label for="284"></label>
			   <img src="css3/37_02_22.jpg" />
			   <figcaption>O layout da página fica desta maneira. Ajuste os valores e atributos para a finalização desta atividade. Coloque nomes nos títulos das 3 páginas para que apareçam no menu.</figcaption>
		   </li>
		</ul>
		<img src="css3/37_02_00.png" class="fundo" style="visibility:hidden"/>
  </details>
	<p class="topop"><a href="#css3" class="topo">voltar ao topo</a></p>
</details>

<details id="css4"><summary>Imagens Vetoriais: pág. 39-54</summary>
	<img src="css4/tags001_0039.png" />
	<details class="sub"><summary>&#x1f4c3; Estrutura em HTML e CSS</summary>
	<p>Vamos criar uma pasta chamada <code>webdesign/atividade9</code>. Nesta pasta, crie os arquivos com nomes <code>index.htm</code> e <code>estilo.css</code>. Além disso, vamos criar uma pasta para inserir as imagens dos banners que vamos criar na Atividade 9, no caminho <code>webdesign/atividade9/imagens</code>.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="285" name="sl">
			   <label for="285"></label>
			   <img src="css4/39_01_01.png" />
			   <figcaption>No cabeçalho da página, insira as referências de fonte externa e do arquivo <code>estilo.css</code>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="286" name="sl">
			   <label for="286"></label>
			   <img src="css4/39_01_02.png" />
			   <figcaption>A tag mãe do site será <code>class="boxSite"</code>, com as tags que formam um banner dentro da tag <code>class="barra"</code>. Primeiro definimos a <code>class="logo"</code>, onde vamos desenhar algumas logomarcas com SVG.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="287" name="sl">
			   <label for="287"></label>
			   <img src="css4/39_01_03.png" />
			   <figcaption>Na tag <code>class="logo"</code>, criamos a janela de visualização de desenhos SVG. Vamos criar vários banners, então cada svg ficará em um elemento <code>class="boxSite"</code> diferente. Cada janela de tag <code>&lt;svg&gt;</code> será dimensionada de acordo com o tamanho do desenho que criaremos.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="288" name="sl">
			   <label for="288"></label>
			   <img src="css4/39_01_04.png" />
			   <figcaption>Logo após a div de logomarca, criamos a <code>class="banner"</code>, que pode ficar apenas com um título que será formatado no arquivo CSS.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="289" name="sl">
			   <label for="289"></label>
			   <img src="css4/39_01_05.png" />
			   <figcaption>Depois do banner, inserimos a estrutura básica de menu que já usamos nas duas últimas atividades. Este menu será usado apenas para visualizarmos os layouts com os desenhos SVG com uma estrutura de menu.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="290" name="sl">
			   <label for="290"></label>
			   <img src="css4/39_01_06.png" />
			   <figcaption>No arquivo <code>estilo.css</code>, definimos as tags principais, com fonte e margem automática.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="291" name="sl">
			   <label for="291"></label>
			   <img src="css4/39_01_07.png" />
			   <figcaption>Podemos colocar uma sombra na tag principal da página <code>.boxSite</code>. A tag <code>.barra</code> terá display flex, onde definimos o alinhamento, largura e a posição do background.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="292" name="sl">
			   <label for="292"></label>
			   <img src="css4/39_01_08.png" />
			   <figcaption>Como vamos criar várias estruturas <code>class="barra"</code> no arquivo HTML, podemos criar um background para cada "filha", usando o atributo <code>nth-child()</code>. O banner da primeira barra é o arquivo que está na pasta <code>imagens/banner.jpg</code>. Escolha uma imagem de paisagem para este primeiro banner.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="293" name="sl">
			   <label for="293"></label>
			   <img src="css4/39_01_09.png" />
			   <figcaption>Na tag <code>.logo</code>, podemos definir uma largura padrão usando o atributo <code>flex:1</code> e alinhamento à esquerda com <code>flex-start</code>. As tags svg podem ter largura máxima de 100% e altura máxima definida, que será igual à altura máxima da tag <code>.banner</code>. Assim, o layout não terá uma logomarca com tamanho muito diferente do banner. Defina também a fonte dos textos svg.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="294" name="sl">
			   <label for="294"></label>
			   <img src="css4/39_01_10.png" />
			   <figcaption>Na tag <code>.banner</code>, podemos definir a altura máxima (igual aos desenhos svg), tamanho <code>flex:1</code> e outros atributos de cor de fonte, alinhamento e <code>overflow:auto</code>, que permite a visualização de itens que ultrapassem as medidas do banner.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="295" name="sl">
			   <label for="295"></label>
			   <img src="css4/39_01_11.png" />
			   <figcaption>A estrutura do menu é a mesma que usamos nas atividades anteriores. Neste caso, o menu terá tamanho <code>flex:1</code> definido na tag <code>&lt;label&gt;</code> e alinhamento à direita. Configure medidas e cores para sua página de Atividade.</figcaption>
		   </li>
		</ul>
		<img src="css4/39_01_00.png" class="fundo" style="visibility:hidden"/>
  </details>
	<img src="css4/tags001_0039a.png" />
	<p class="topop"><a href="#css4" class="topo">voltar ao topo</a></p>
	<img src="css4/tags001_0040.png" />
	<p class="topop"><a href="#css4" class="topo">voltar ao topo</a></p>
	<img src="css4/tags001_0041.png" />
	<details class="sub"><summary>&#x1f4c3; Primeiro banner</summary>
	<p>Vamos criar nosso primeiro desenho SVG dentro da classe <code>class="logo"</code>. Este desenho usará apenas as tags <code>circle</code> e <code>line</code>.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="296" name="sl">
			   <label for="296"></label>
			   <img src="css4/41_01_01.png" />
			   <figcaption>Podemos definir a janela de visualização <code>viewBox</code> com tamanho de 200 x 200 pixels. Além disso, vamos usar uma tag de grupo <code>&lt;g&gt;</code> com os atributos comuns definidos nesta tag: cor da linha, espessura da linha e um nome para o grupo: <code>name="sol"</code>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="297" name="sl">
			   <label for="297"></label>
			   <img src="css4/41_01_02.png" />
			   <figcaption>O círculo tem centro no ponto de coordenadas (100,100) e raio 50. Defina também a cor do preenchimento com o atributo <code>fill</code> que pode ser informado com padrão RGB, Hexadecimal ou HTML. A primeira linha de raio de sol foi a que está mais acima do desenho, que começa no ponto (100,10) e termina em (100,40).</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="298" name="sl">
			   <label for="298"></label>
			   <img src="css4/41_01_03.png" />
			   <figcaption>Nosso desenho fica desta forma. Agora vamos usar rotações de 30&deg; da primeira linha do raio de sol para desenhar os outros raios.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="299" name="sl">
			   <label for="299"></label>
			   <img src="css4/41_01_04.png" />
			   <figcaption>Note que usamos exatamente a mesma tag do primeiro raio, adicionando a rotação de 30&deg; em torno do centro (100,100). O comando fica <code>transform="rotate(30,100,100)"</code>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="300" name="sl">
			   <label for="300"></label>
			   <img src="css4/41_01_05.png" />
			   <figcaption>Ótimo! Nosso segundo raio foi desenhado. Já coloquei a imagem de uma paisagem na pasta das imagens com o nome <code>banner.jpg</code>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="301" name="sl">
			   <label for="301"></label>
			   <img src="css4/41_01_06.png" />
			   <figcaption>Agora copiamos e colamos a tag da primeira rotação, substituindo apenas o valor do ângulo: 60, 90, 120,... até o ângulo de 330. Salve e visualize o banner. Coloque um título no HTML dentro da tag <code>class="banner"</code></figcaption>
		   </li>
		   <li>
			   <input type="radio" id="302" name="sl">
			   <label for="302"></label>
			   <img src="css4/41_01_07.png" />
			   <figcaption>Nosso primeiro banner fica desta forma. Modifique cores e formações do layout no CSS para testar se está ficando bom. As próximas barras serão inseridas abaixo desta que acabamos de construir.</figcaption>
		   </li>
		</ul>
		<img src="css4/41_01_00.png" class="fundo" style="visibility:hidden"/>
  </details>
	<img src="css4/tags001_0041a.png" />
	<details class="sub"><summary>&#x1f4c3; 2&deg; e 3&deg; banners</summary>
	<p>Vamos criar os outros 2 desenhos SVG dentro de classes <code>class="logo"</code> em novas classes <code>class="barra"</code>, colocadas logo após o fechamento da primeira tag que fizemos de <code>barra</code>.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="303" name="sl">
			   <label for="303"></label>
			   <img src="css4/41_02_00.png" />
			   <figcaption>Podemos definir a janela de visualização <code>viewBox</code> com tamanho de 100 x 100 pixels para o desenho da roda dentada. Coloque um título de Mecânica na tag <code>class="banner"</code> e escolha uma imagem desta área para inserir como <code>imagens/banner2.jpg</code>.</figcaption>
		   </li>
		  <li>
			   <input type="radio" id="304" name="sl">
			   <label for="304"></label>
			   <img src="css4/41_02_01.png" />
			   <figcaption>A parte interior do desenho será um círculo com espessura de linha de 5px. Desta forma, ele esconderá os encaixes dos trapézios que vamos desenhar usando o atributo <code>polygon</code>. Podemos digitar a sequência dos vértices adjacentes para o desenho do trapézio: (40,20); (60,20); (55,10) e (45,10).</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="305" name="sl">
			   <label for="305"></label>
			   <img src="css4/41_02_02.png" />
			   <figcaption>Neste ponto, o desenho fica desta forma. Note que o círculo cobre o trapézio e podemos continuar para desenhar os outros dentes da roda.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="306" name="sl">
			   <label for="306"></label>
			   <img src="css4/41_02_03.png" />
			   <figcaption>Da mesma maneira que fizemos com os raios do sol, usamos a mesma tag do primeiro dente e rotacionamos este desenho com ângulo de 30&deg; com centro de rotação no ponto (50,50): <code>transform="rotate(30,50,50)"</code>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="307" name="sl">
			   <label for="307"></label>
			   <img src="css4/41_02_04.png" />
			   <figcaption>O segundo dente da roda está desenhado. Agora podemos copiar e colar a tag de rotação para finalizar este desenho.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="308" name="sl">
			   <label for="308"></label>
			   <img src="css4/41_02_05.png" />
			   <figcaption>Lembre-se de modificar apenas o ângulo de rotação: de 30&deg; em 30&deg;.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="309" name="sl">
			   <label for="309"></label>
			   <img src="css4/41_02_06.png" />
			   <figcaption>Ótimo, o nosso banner fica com este layout. Agora vamos desenhar a estrela.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="310" name="sl">
			   <label for="310"></label>
			   <img src="css4/41_02_07.png" />
			   <figcaption>Logo após o fechamento da tag de barra da roda dentada, crie a nova tag <code>class="barra"</code> para desenharmos a estrela. Escolha uma imagem para ser o background desta barra em <code>imagens/banner3.jpg</code>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="311" name="sl">
			   <label for="311"></label>
			   <img src="css4/41_02_08.png" />
			   <figcaption>Podemos definir a janela de visualização <code>viewBox</code> com tamanho de 100 x 100 pixels para o desenho da estrela. O tom de azul <code>skyblue</code> foi definido como preenchimento. Usando mesmo raciocínio da roda dentada, desenhamos um círculo de raio 15 para a parte interior da estrela, e uma das pontas é o triângulo com as coordenadas desenhadas com a ferramenta <code>polygon</code>: (40,40); (50,10); (60,40).</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="312" name="sl">
			   <label for="312"></label>
			   <img src="css4/41_02_09.png" />
			   <figcaption>O desenho fica com o círculo e o triângulo encoberto na base. Podemos continuar para desenhar as outras pontas da estrela.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="313" name="sl">
			   <label for="313"></label>
			   <img src="css4/41_02_10.png" />
			   <figcaption>A segunda ponta será construída usando-se a rotação de 72&deg; em torno do centro (50,50).</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="315" name="sl">
			   <label for="315"></label>
			   <img src="css4/41_02_12.png" />
			   <figcaption>Agora basta rotacionar os outros triângulos de 72 em 72 graus.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="316" name="sl">
			   <label for="316"></label>
			   <img src="css4/41_02_13.png" />
			   <figcaption>E assim fica o desenho do nosso banner. Se necessário, mude configurações CSS e os arquivos dos backgrounds.</figcaption>
		   </li>
		</ul>
		<img src="css4/41_02_00.png" class="fundo" style="visibility:hidden"/>
  </details>
	<img src="css4/tags001_0041b.png" />
	<details class="sub"><summary>&#x1f4c3; 4&deg; e 5&deg; banners</summary>
	<p>Vamos criar os outros 2 desenhos SVG dentro de classes <code>class="logo"</code> em novas classes <code>class="barra"</code>, colocadas logo após o fechamento da tag da terceira <code>barra</code> que desenhamos com a estrela.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="317" name="sl">
			   <label for="317"></label>
			   <img src="css4/41_03_00.png" />
			   <figcaption>Podemos definir a janela de visualização <code>viewBox</code> com tamanho de 100 x 100 pixels para o desenho do símbolo de um átomo. Coloque um título na tag <code>class="banner"</code> e escolha uma imagem desta área para inserir como <code>imagens/banner4.jpg</code>. Lembre-se de arrumar o arquivo css com o atributo <code>.barra:nth-child(4) {background: url(imagens/banner4.jpg);}</code></figcaption>
		   </li>
		  <li>
			   <input type="radio" id="318" name="sl">
			   <label for="318"></label>
			   <img src="css4/41_03_01.png" />
			   <figcaption>Como vamos colocar um texto logo abaixo do desenho, fazemos uma translação de 8px para cima. O círculo terá raio 8px, com centro no meio da janela svg, ou seja, no ponto de coordenadas (50,50). Defina a espessura da linha e a cor, sem usar preenchimento. A primeira elipse pode ser desenhada com raios <code>rx="15"</code> e <code>ry="35"</code>. Experimente valores diferentes para seu desenho.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="318a" name="sl">
			   <label for="318a"></label>
			   <img src="css4/41_03_01a.png" />
			   <figcaption>As outras elipses podem ser desenhadas com duas rotações: de 60&deg; e de 120&deg; em torno do centro (50,50). O outro átomo pode ser feito com rotações de 45&deg;, 90&deg; e 135&deg;. Escolha um dos átomos para o seu banner.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="319" name="sl">
			   <label for="319"></label>
			   <img src="css4/41_03_02.png" />
			   <figcaption>Defina os atributos de cor e contorno do texto  desta logomarca. Se necessário, ajuste as coordenadas do texto. O tamanho e a família da fonte podem ser definidos apenas no arquivo CSS, no atributo <code>text {font-family:Calibri; font-size:25px;}</code>. Ajuste o tamanho ideal para seu desenho.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="320" name="sl">
			   <label for="320"></label>
			   <img src="css4/41_03_03.png" />
			   <figcaption>O banner fica com este layout. Teste os atributos de cores e tamanhos em seu desenho.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="321" name="sl">
			   <label for="321"></label>
			   <img src="css4/41_03_04.png" />
			   <figcaption>Vamos desenhar outro símbolo, com retângulos. Logo abaixo do fechamento da barra do átomo, crie uma nova tag de barra. Insira uma imagem para o fundo deste banner em <code>imagens/banner5.jpg</code>. A janela de visualização <code>viewBox</code> pode ser usada com 100 x 100 pixels.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="322" name="sl">
			   <label for="322"></label>
			   <img src="css4/41_03_05.png" />
			   <figcaption>Criamos um grupo com tag <code>&lt;g&gt;</code>, para definir atributos de cores e contornos do desenho. O primeiro retângulo foi desenhado na vertical, com largura 10px e altura 80px. Os cantos arredondados estão com <code>rx="2"</code>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="322a" name="sl">
			   <label for="322a"></label>
			   <img src="css4/41_03_05a.png" />
			   <figcaption>Os outros dois retângulos foram desenhados com rotações de 60&deg; e 120&deg; em torno do centro (50,50). Para que o desenho fique com o texto logo abaixo, foi feita uma translação de -8 pixels na coordenada y, ou seja, o desenho "subiu" 8px.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="323" name="sl">
			   <label for="323"></label>
			   <img src="css4/41_03_06.png" />
			   <figcaption>Ajuste os atributos do texto desta logomarca. As coordenadas sugeridas são <code>x="10"</code> e <code>y="98"</code>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="324" name="sl">
			   <label for="324"></label>
			   <img src="css4/41_03_07.png" />
			   <figcaption>O layout deste banner fica desta forma. Configure os atributos para fazer o seu banner.</figcaption>
		   </li>
		</ul>
		<img src="css4/41_03_00.png" class="fundo" style="visibility:hidden"/>
  </details>
	<img src="css4/tags001_0041c.png" />
	<p class="topop"><a href="#css4" class="topo">voltar ao topo</a></p>
	<img src="css4/tags001_0042.png" />
	<details class="sub"><summary>&#x1f4c3; Gradientes nos banners</summary>
	<p>Vamos colocar efeitos de gradiente nos preenchimentos e linhas dos desenhos que fizemos dos 5 primeiros banners.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="325" name="sl">
			   <label for="325"></label>
			   <img src="css4/42_01_00.png" />
			   <figcaption>Vamos criar o <code>id="efeito1"</code> como gradiente radial de um tom de laranja mais claro para um pouco mais escuro. O centro deste efeito está no ponto de coordenadas (50%,50%) com raio abrangendo 100% do desenho. Ajuste cores e valores para seu banner. Na tag do círculo, colocamos a referência do efeito no preenchimento: <code>fill="url(#efeito1)"</code>.</figcaption>
		   </li>
		  <li>
			   <input type="radio" id="326" name="sl">
			   <label for="326"></label>
			   <img src="css4/42_01_01.png" />
			   <figcaption>O desenho do sol fica com esse efeito. Ajuste os valores para seu desenho.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="327" name="sl">
			   <label for="327"></label>
			   <img src="css4/42_01_02.png" />
			   <figcaption>Na roda dentada, temos que criar 2 efeitos: um radial, para o círculo e outro linear, para os trapézios. Estes efeitos variam de uma tonalidade <code>darkred</code> para o <code>red</code>. Consulte o site <a href="https://html-color.codes/" target="_blank">https://html-color.codes/</a> para combinar tonalidades. O efeito linear começa em <code>x1="0%, y1="0%</code> e termina em <code>x2="0%, y2="100%</code>, ou seja, vai de cima para baixo.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="328" name="sl">
			   <label for="328"></label>
			   <img src="css4/42_01_03.png" />
			   <figcaption>O layout com gradiente no SVG fica desta forma. Ajuste valores e cores para seu banner.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="329" name="sl">
			   <label for="329"></label>
			   <img src="css4/42_01_04.png" />
			   <figcaption>O efeito gradiente da estrela também pode ser feito com um gradiente radial, para o círculo que desenhamos no meio da estrela, e outro linear para os triângulos. Escolha cores e coloque as referências nos preenchimentos para conseguir o efeito criado. Como estamos variando apenas 2 tons de cores, usamos apenas os atributos <code>&lt;stop offset="0%&gt;</code> e <code>&lt;stop offset="100%&gt;</code> para os tons de azul.O efeito linear começa em <code>x1="0%, y1="0%</code> e termina em <code>x2="0%, y2="100%</code>, ou seja, vai de cima para baixo.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="330" name="sl">
			   <label for="330"></label>
			   <img src="css4/42_01_05.png" />
			   <figcaption>O layout com gradiente fica desta forma. Ajuste cores e efeitos para seu desenho.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="331" name="sl">
			   <label for="331"></label>
			   <img src="css4/42_01_06.png" />
			   <figcaption>No desenho do átomo, criamos um efeito de gradiente linear para as elipses nos contornos <code>stroke</code> e um efeito de gradiente radial no círculo. Podemos usar o efeito de gradiente linear no texto também. Neste caso, são mostradas variações de tons de verde. Escolha cores e ajuste valores para o seu banner. O efeito linear começa de cima e vai para baixo.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="332" name="sl">
			   <label for="332"></label>
			   <img src="css4/42_01_07.png" />
			   <figcaption>O desenho com gradiente fica desta forma.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="333" name="sl">
			   <label for="333"></label>
			   <img src="css4/42_01_08.png" />
			   <figcaption>O último banner que desenhamos, do asterisco, pode ter um efeito gradiente linear. Neste caso, usamos tons de verde com transparência RGBA. O texto tem mesmo efeito de gradiente dos retângulos. O efeito linear começa em <code>x1="0%, y1="0%</code> e termina em <code>x2="100%, y2="0%</code>, ou seja, vai da esquerda para a direita.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="334" name="sl">
			   <label for="334"></label>
			   <img src="css4/42_01_09.png" />
			   <figcaption>O layout deste banner com gradiente fica desta forma. Ajuste cores e valores de gradiente para seu desenho de banner.</figcaption>
		   </li>
		</ul>
		<img src="css4/42_01_00.png" class="fundo" style="visibility:hidden"/>
  </details>
	<img src="css4/tags001_0042a.png" />
	<p class="topop"><a href="#css4" class="topo">voltar ao topo</a></p>
	<img src="css4/tags001_0043.png" />
	<details class="sub"><summary>&#x1f4c3; Filtros nos banners</summary>
	<p>Vamos colocar efeitos de filtros de sombras nos desenhos que fizemos dos 5 primeiros banners.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="335" name="sl">
			   <label for="335"></label>
			   <img src="css4/43_01_00.png" />
			   <figcaption>Vamos criar o <code>id="efeito10"</code> como filtro de sombra desfocada, com desvio padrão 0.5 e distâncias do gráfico com 1px à direita e abaixo do desenho. Temos que colocar indicação nos gráficos que terão este efeito com o atributo <code>filter="url(#efeito10)"</code>. Neste primeiro exemplo, os desenhos do 5&deg; banner estão com o filtro</figcaption>
		   </li>
		  <li>
			   <input type="radio" id="336" name="sl">
			   <label for="336"></label>
			   <img src="css4/43_01_01.png" />
			   <figcaption>O banner fica com esse efeito no SVG. Ajuste os valores do filtro para seu desenho. Vamos usar o mesmo efeito nos próximos desenhos.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="337" name="sl">
			   <label for="337"></label>
			   <img src="css4/43_01_02.png" />
			   <figcaption>Para usarmos o mesmo efeito nos outros desenhos, não precisamos inserir a tag <code>&lt;filter&gt;</code> novamente. Basta colocar a indicação deste filtro nos desenhos. O mesmo vale para os gradientes: se você quiser usar um mesmo efeito já definido em outra tag <code>&lt;svg&gt;</code>, basta colocar sua indicação.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="338" name="sl">
			   <label for="338"></label>
			   <img src="css4/43_01_03.png" />
			   <figcaption>O layout com filtro no SVG do banner de átomo fica desta maneira. Se necessário, ajuste valores e cores para o filtro. Caso precise de outro filtro, basta definir suas configurações e colocar outro nome id.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="339" name="sl">
			   <label for="339"></label>
			   <img src="css4/43_01_04.png" />
			   <figcaption>Colocando o filtro no desenho da estrela, basta indicar na tag de grupo <code>&lt;g&gt;</code> o nome do filtro.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="340" name="sl">
			   <label for="340"></label>
			   <img src="css4/43_01_05.png" />
			   <figcaption>O layout com filtro fica desta forma. Ajuste cores e efeitos para seu desenho.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="341" name="sl">
			   <label for="341"></label>
			   <img src="css4/43_01_06.png" />
			   <figcaption>Na roda dentada, temos um problema: se colocarmos o filtro, as sombras dos trapézios ficarão sobre o desenho do círculo. Para corrigir este erro, podemos colocar a tag <code>&lt;circle&gt;</code> depois da tag do grupo dos dentes da roda. Assim, não aplicamos o filtro no círculo, deixando o desenho sobrepondo as sombras dos dentes da roda.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="342" name="sl">
			   <label for="342"></label>
			   <img src="css4/43_01_07.png" />
			   <figcaption>O desenho com filtro fica desta forma. Ajuste valores e cores do filtro, e se necessário, crie outro filtro para este desenho.</figcaption>
		   </li>
		</ul>
		<img src="css4/43_01_00.png" class="fundo" style="visibility:hidden"/>
  </details>
	<img src="css4/tags001_0043a.png" />
	<p class="topop"><a href="#css4" class="topo">voltar ao topo</a></p>
	<img src="css4/tags001_0044.png" />
	<p class="topop"><a href="#css4" class="topo">voltar ao topo</a></p>
	<img src="css4/tags001_0045.png" />
	<p class="topop"><a href="#css4" class="topo">voltar ao topo</a></p>
	<img src="css4/tags001_0046.png" />
	<details class="sub"><summary>&#x1f4c3; 6&deg; e 7&deg; banners</summary>
	<p>Vamos desenhar nuvens com arcos nos dois banners deste exercício. Escolha imagens para colocar nos fundos destas tags: <code>imagens/banner6.jpg</code> e <code>imagens/banner7.jpg</code>.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="342a" name="sl">
			   <label for="342a"></label>
			   <img src="css4/46_01_00.png" />
			   <figcaption>Crie uma tag <code>class="barra"</code> e vamos desenhar a nuvem na tag <code>class="logo"</code>. O desenho da nuvem pode ser feito com apenas um caminho <code>&lt;path&gt;</code>, pois temos os raios e as coordenadas relativas das extremidades de cada arco.</figcaption>
		   </li>
		  <li>
			   <input type="radio" id="343" name="sl">
			   <label for="343"></label>
			   <img src="css4/46_01_01.png" />
			   <figcaption>O primeiro arco tem raio 11, sentido horário e termina em (20,-5) Logo, o comando fica <code>a11,11 0 0,1 20,-5</code>. Todos os arcos estão sem inclinação, são os menores e estão no sentido horário. Logo, a parte central dos comandos será igual para todos os arcos: <code>0 0,1</code>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="344" name="sl">
			   <label for="344"></label>
			   <img src="css4/46_01_02.png" />
			   <figcaption>O segundo arco tem raio 14 e termina no ponto de coordenadas relativas (25,5). Seu comando fica <code>a14,14 0 0,1 25,5</code>. Os outros arcos são feitos de maneira análoga.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="345" name="sl">
			   <label for="345"></label>
			   <img src="css4/46_01_03.png" />
			   <figcaption>Podemos criar um efeito gradiente radial para a nuvem, com transparência de cor com o comando RGBA. A linha também pode ter cor com transparência. Ajuste cores e a espessura das linhas para seu desenho.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="346" name="sl">
			   <label for="346"></label>
			   <img src="css4/46_01_04.png" />
			   <figcaption>O banner com desenho da primeira nuvem fica com esse layout.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="347" name="sl">
			   <label for="347"></label>
			   <img src="css4/46_01_05.png" />
			   <figcaption>Crie uma nova tag <code>class="barra"</code> para desenhar a próxima nuvem. O comando do primeiro arco, de raio 2, que termina no ponto de coordenadas relativas (0,-4) fica <code>a2,2 0 0,1 0,-4</code>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="348" name="sl">
			   <label for="348"></label>
			   <img src="css4/46_01_06.png" />
			   <figcaption>O comando do segundo arco, de raio 2, que termina no ponto de coordenadas relativas (3,-3) fica <code>a2,2 0 0,1 3,-3</code>. Os outros arcos são feitos de maneira análoga. Note que para finalizar a nuvem, com a linha horizontal usamos a letra <b>Z</b> depois das coordenadas do último arco.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="349" name="sl">
			   <label for="349"></label>
			   <img src="css4/46_01_07.png" />
			   <figcaption>Podemos usar o mesmo efeito de preenchimento da outra nuvem. Se necessário, crie outro efeito de gradiente para este desenho. Ajuste cores e espessura das linhas para seu desenho.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="350" name="sl">
			   <label for="350"></label>
			   <img src="css4/46_01_08.png" />
			   <figcaption>O desenho da nuvem no layout de banner fica desta forma.</figcaption>
		   </li>
		</ul>
		<img src="css4/46_01_00.png" class="fundo" style="visibility:hidden"/>
  </details>
	<p class="topop"><a href="#css4" class="topo">voltar ao topo</a></p>
	<img src="css4/tags001_0047.png" />
	<p class="topop"><a href="#css4" class="topo">voltar ao topo</a></p>
	<img src="css4/tags001_0048.png" />
	<details class="sub"><summary>&#x1f4c3; 8&deg; banner</summary>
	<p>Vamos desenhar uma xícara neste exercício. Escolha uma imagem de fundo e salve-a em <code>imagens/banner8.jpg</code>. Não esqueça de atualizar o arquivo CSS com o atributo <code>.barra: nth-child(8) {background: url(imagens/banner8.jpg);}</code>.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="351" name="sl">
			   <label for="351"></label>
			   <img src="css4/48_01_00.png" />
			   <figcaption>Crie uma tag <code>class="barra"</code> e vamos desenhar a xícara na tag <code>class="logo"</code>. A janela de visualização pode ficar com tamanho de 200 x 200 pixels.</figcaption>
		   </li>
		  <li>
			   <input type="radio" id="352" name="sl">
			   <label for="352"></label>
			   <img src="css4/48_01_01.png" />
			   <figcaption>Podemos criar um efeito gradiente para este desenho. Escolha as cores e crie o efeito. Neste caso, o efeito começa em <code>x1=0%, y1=0%</code> e termina em <code>x2="100%", y2="100%"</code>, ou seja, será feito na diagonal. Vamos criar duas elipses que formam o cabo: a maior com preenchimento igual ao da xícara e a menor com preenchimento branco.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="353" name="sl">
			   <label for="353"></label>
			   <img src="css4/48_01_02.png" />
			   <figcaption>A xícara será um retângulo com as medidas indicadas no desenho da apostila. Podemos colocar cantos arredondados com <code>rx="5"</code>. As elipses formam o cabo da xícara, com as medidas cos centros coincidentes, mudando apenas as medidas dos raios. Ajuste valores e cores no seu desenho.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="354" name="sl">
			   <label for="354"></label>
			   <img src="css4/48_01_03.png" />
			   <figcaption>No grupo <code>&lt;g id="fumaca"&gt;</code> podemos desenhar os arcos com comandos de curvas Bèzier, com as medidas indicadas na apostila. O primeiro arco tem ponto de controle em (-25,-25) e finaliza em (0,-50). Logo, o comando fica <code>q-25,-25 0,-50</code>. O comando <code>t0,-50</code> faz a parte simétrica da curva.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="355" name="sl">
			   <label for="355"></label>
			   <img src="css4/48_01_04.png" />
			   <figcaption>Os outros dois arcos podem ser feitos com translação à direita e à esquerda com 20px: <code>transform="translate(-20,0)"</code> e <code>transform="translate(20,0)"</code>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="356" name="sl">
			   <label for="356"></label>
			   <img src="css4/48_01_05.png" />
			   <figcaption>Se o fundo do banner for branco, não temos problemas com as elipses. Podemos substituí-las por caminhos de arcos <code>&lt;path&gt;</code> para que tenham o fundo transparente.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="357" name="sl">
			   <label for="357"></label>
			   <img src="css4/48_01_06.png" />
			   <figcaption>O caminho com arcos de elipse começa em <code>M160,120</code>, e tem o primeiro arco com raios 30 e 20, finalizando no ponto de coordenadas (0,40): <code>a30,20 0 0,1 0,40</code>. Depois temos uma linha vertical que sobe 10px e o arco menor, com raios 18 e 10, sentido anti-horário, que termina em (0,-20): <code>a18,10 0 0,0 0,-20</code>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="358" name="sl">
			   <label for="358"></label>
			   <img src="css4/48_01_07.png" />
			   <figcaption>O layout com o caminho de arcos fica assim. Ajuste cores de linhas e de preenchimentos para este banner.</figcaption>
		   </li>
		</ul>
		<img src="css4/48_01_00.png" class="fundo" style="visibility:hidden"/>
  </details>
	<img src="css4/tags001_0048a.png" />
	<p class="topop"><a href="#css4" class="topo">voltar ao topo</a></p>
	<img src="css4/tags001_0049.png" />
	<details class="sub"><summary>&#x1f4c3; Animações no 8&deg; banner</summary>
	<p>Vamos colocar efeitos de animações no banner da xícara.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="359" name="sl">
			   <label for="359"></label>
			   <img src="css4/49_01_00.png" />
			   <figcaption>Vamos aumentar a janela de visualização do SVG da xícara para 200 x 220 pixels, inserindo a tag <code>&lt;text&gt;</code> para a logomarca.</figcaption>
		   </li>
		  <li>
			   <input type="radio" id="360" name="sl">
			   <label for="360"></label>
			   <img src="css4/49_01_01.png" />
			   <figcaption>No grupo <code>id="xicara"</code>definimos o tracejado com 400 pixels e a animação de vai e vem, que começa o traçejado no ponto 400px, vai até 0px e retorna ao 400px. Assim, a animação é de desenhar o contorno da xícara. Note que o atributo <code>&lt;animate&gt;</code> fica dentro da tag de grupo da xícara.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="361" name="sl">
			   <label for="361"></label>
			   <img src="css4/49_01_02.png" />
			   <figcaption>Outra animação pode ser feita com a opacidade. No grupo <code>id="xicara"</code>, defina a opacidade com 0.8. A tag de animação pode variar a opacidade de 0.8 até 1, retornando a 0.8. O efeito de animação também é de vai e vem.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="362" name="sl">
			   <label for="362"></label>
			   <img src="css4/49_01_03.png" />
			   <figcaption>No grupo <code>id="fumaca"</code>, o efeito de desenhar os elementos necessita de um tracejado menor, de 150px. O mesmo efeito da xícara, de deslocamento do início do tracejado foi aplicado à fumaça e ao texto da logomarca.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="363" name="sl">
			   <label for="363"></label>
			   <img src="css4/49_01_04.png" />
			   <figcaption>Podemos definir efeito de opacidade na fumaça e no texto. Neste caso, foi colocada opacidade inicial de 0.5, com a animação variando entre 0.5 e 1.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="364" name="sl">
			   <label for="364"></label>
			   <img src="css4/49_01_05.png" />
			   <figcaption>O efeito no início da animação fica assim.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="365" name="sl">
			   <label for="365"></label>
			   <img src="css4/49_01_06.png" />
			   <figcaption>E no final, com opacidade e os desenhos dos contornos completos, fica dessa forma. Ajuste os valores para animação no seu banner da xícara.</figcaption>
		   </li>
		</ul>
		<img src="css4/49_01_00.png" class="fundo" style="visibility:hidden"/>
  </details>
	<p class="topop"><a href="#css4" class="topo">voltar ao topo</a></p>
	<img src="css4/tags001_0050.png" />
	<p class="topop"><a href="#css4" class="topo">voltar ao topo</a></p>
	<img src="css4/tags001_0051.png" />
	<details class="sub"><summary>&#x1f4c3; 9&deg; banner</summary>
	<p>Vamos criar o outro banner em uma nova classe: <code>class="banner2"</code>.</p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="366" name="sl">
			   <label for="366"></label>
			   <img src="css4/51_01_00.png" />
			   <figcaption>Neste banner, vamos criar a paisagem junto com a logomarca e o menu. Ao invés de usar <code>class="barra"</code>, vamos criar a estrutura <code>&lt;svg&gt;</code> dentro da tag <code>class="banner2"</code>.</figcaption>
		   </li>
		  <li>
			   <input type="radio" id="367" name="sl">
			   <label for="367"></label>
			   <img src="css4/51_01_01.png" />
			   <figcaption>No arquivo CSS, vamos definir os atributos da classe <code>.banner2</code>. A altura máxima será fixada em 470px, com largura <code>flex:3</code>. O fundo pode ter o mesmo efeito de gradiente usado no desenho SVG.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="368" name="sl">
			   <label for="368"></label>
			   <img src="css4/51_01_02.png" />
			   <figcaption>O menu terá largura <code>flex:1</code> e pode ser configurado na vertical (column) e com alinhamento à direita (flex-end). Veja qual configuração fica melhor no seu layout de banner. Podemos definir o tamanho da fonte da tag <code>textpath</code>, que usaremos adiante.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="369" name="sl">
			   <label for="369"></label>
			   <img src="css4/51_01_03.png" />
			   <figcaption>Podemos definir os efeitos gradientes do céu <code>id="linear2"</code>, variando de azul claro para branco. O retângulo que define o céu tem mesma dimensão da janela de visualização do svg: 150 x 76 pixels.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="370" name="sl">
			   <label for="370"></label>
			   <img src="css4/51_01_04.png" />
			   <figcaption>Definimos também os efeitos gradientes do perfil arquitetônico e do sol: <code>id="linear3"</code> e <code>id="radial1"</code>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="371" name="sl">
			   <label for="371"></label>
			   <img src="css4/51_01_05.png" />
			   <figcaption>Podemos definir um efeito gradiente para as nuvens <code>id="radial2"</code> e um filtro <code>id="filtro"</code> para desfocar o desenho e as sombras, com desvio padrão 0.1. Ajuste valores e cores para seu desenho de banner.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="372" name="sl">
			   <label for="372"></label>
			   <img src="css4/51_01_06.png" />
			   <figcaption>Com apenas uma tag de caminho <code>&lt;path&gt;</code> podemos definir o perfil arquitetônico: começando no ponto (5,75), a primeira linha é horizontal <code>h5</code>, que sobe com uma linha vertical <code>v-25</code>, passa por uma linha inclinada <code>l12,-8</code>, desce com a linha vertical <code>v24</code> e passa pela linha horizontal <code>h3</code>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="372a" name="sl">
			   <label for="372a"></label>
			   <img src="css4/51_01_06.png" />
			   <figcaption>Os arcos que aparecem têm raios iguais a 4 e 2 e são desenhados no sentido horário. Os comandos dos dois primeiros arcos ficam como: <code>a4,4 0 0,1 4,-4</code> e <code>a2,2 0 0,1 4,0</code>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="373" name="sl">
			   <label for="373"></label>
			   <img src="css4/51_01_07.png" />
			   <figcaption>Usando a animação que faz o efeito de desenhar o perfil, definimos o tracejado com 900px e a variação do ponto de início do tracejado de 900 para 0, voltando depois para 900. Note que precisamos fechar a tag <code>&lt;path&gt;</code>, pois inserimos a animação no caminho do desenho do perfil.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="374" name="sl">
			   <label for="374"></label>
			   <img src="css4/51_01_08.png" />
			   <figcaption>A tag <code>name="nuvem"</code> tem o gradiente indicado por <code>url(#radial2)</code>. O desenho é similar aos de nuvens que já fizemos: os dois primeiros arcos têm raios de 5px, sentido horário, e finalizam nos pontos com coordenadas relativas (7,-7) e (9,0). Os outros arcos são desenhados da mesma forma.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="374a" name="sl">
			   <label for="374a"></label>
			   <img src="css4/51_01_08.png" />
			   <figcaption>Podemos definir o tracejado do desenho da nuvem com 80px, e o efeito de desenhar a nuvem que começa em 80px, vai até 0 e volta para 80px. Esta tag de animação está dentro da tag de caminho da nuvem, que precisa ser fechada: <code>&lt;/path&gt;</code>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="375" name="sl">
			   <label for="375"></label>
			   <img src="css4/51_01_09.png" />
			   <figcaption>No desenho do sol, temos o efeito de gradiente <code>url(#radial1)</code> e o tracejado com tamanho 35px. Em cada <code>&lt;path&gt;</code> de raio, precisamos definir o tamanho do tracejado de 5px. Assim, a animação pode ser usada com valores de 0 a 5. Neste caso, estão com 3px, ou seja, os raios não sumirão. Se colocarmos 5px, os raios somem e voltam. Teste valores para a animação do seu banner.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="376" name="sl">
			   <label for="376"></label>
			   <img src="css4/51_01_10.png" />
			   <figcaption>Este é o layout do banner com as configurações mostradas. Ajuste cores e valores de atributos para o seu banner.</figcaption>
		   </li>
		</ul>
		<img src="css4/51_01_00.png" class="fundo" style="visibility:hidden"/>
  </details>
	<img src="css4/tags001_0051a.png" />
	<p class="topop"><a href="#css4" class="topo">voltar ao topo</a></p>
	<img src="css4/tags001_0052.png" />
	<details class="sub"><summary>&#x1f4c3; 10&deg; banner: animações</summary>
	<p>Vamos criar o outro banner usando: <code>class="barra"</code>. Insira uma imagem de fundo para este banner na pasta <code>imagens/banner10.jpg</code></p>
	  <ul class="slider">
		  <li>
			   <input type="radio" id="377" name="sl">
			   <label for="377"></label>
			   <img src="css4/52_01_01.png" />
			   <figcaption>Dentro da tag <code>class="logo"</code> vamos desenhar um dos retângulos com as medidas indicadas na apostila. Os cantos arredondados podem ser feitos com o atributo <code>rx="1"</code>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="378" name="sl">
			   <label for="378"></label>
			   <img src="css4/52_01_02.png" />
			   <figcaption>O segundo retângulo tem mesma tag do primeiro, sendo rotacionado com ângulo de 36&deg; em torno do centro (30,30). Mudamos a opacidade para <code>opacity="0.9"</code>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="379" name="sl">
			   <label for="379"></label>
			   <img src="css4/52_01_03.png" />
			   <figcaption>Os outros retângulos são rotacionados de 36&deg; em 36&deg;, até chegar em 324&deg;. Neste retângulo, colocamos <code>opacity="0.1"</code>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="380" name="sl">
			   <label for="380"></label>
			   <img src="css4/52_01_04.png" />
			   <figcaption>A primeira animação, comum neste tipo de desenho, é de rotação em torno do centro. Para ter o efeito vai e vem, usamos o atributo <code>values="0,30,30;360,30,30;0,30,30"</code>, que indica que a rotação começa no 0, vai até 360 e depois volta ao 0. Logo, o efeito será feito no sentido horário, e depois no sentido anti-horário.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="381" name="sl">
			   <label for="381"></label>
			   <img src="css4/52_01_05.png" />
			   <figcaption>Outros efeitos que podem ser usados são de escala (neste caso diminui de 1 para 0.9) e translação (neste caso, a figura "anda" 15px para a direita e depois retorna à posição original).</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="382" name="sl">
			   <label for="382"></label>
			   <img src="css4/52_01_06.png" />
			   <figcaption>Com os atributos mostrados, este é o layout do banner com o símbolo apresentado. Modifique valores e cores para fazer o seu banner.</figcaption>
		   </li>
		</ul>
		<img src="css4/52_01_00.png" class="fundo" style="visibility:hidden"/>
  </details>
	<p class="topop"><a href="#css4" class="topo">voltar ao topo</a></p>
	<img src="css4/tags001_0053.png" />
	<details class="sub"><summary>&#x1f4c3; 11&deg; banner</summary>
	<p>Usando as tags mostradas do lápis em uma <code>class="barra"</code>, temos o layout mostrado abaixo. Insira uma imagem de fundo para este banner na pasta <code>imagens/banner11.jpg</code> e coloque as tags do lápis em uma <code>class="logo"</code>.</p>
	<img src="css4/53_01_00.png"/>
  </details>
	<img src="css4/tags001_0053a.png" />
	<details class="sub"><summary>&#x1f4c3; 12&deg; banner</summary>
	<p>Vamos criar o outro banner usando <code>class="barra"</code>. Insira uma imagem de fundo para este banner na pasta <code>imagens/banner12.jpg</code></p>
	  <ul class="slider">
			<li>
			   <input type="radio" id="383" name="sl">
			   <label for="383"></label>
			   <img src="css4/53_02_00.png" />
			   <figcaption>Com as medidas do halteres que vamos desenhar, a janela de visualização <code>viewBox</code> pode ser definida com tamanho de 150 x 120 pixels.</figcaption>
		   </li>
		  <li>
			   <input type="radio" id="384" name="sl">
			   <label for="384"></label>
			   <img src="css4/53_02_01.png" />
			   <figcaption>Começando pelos dois retângulos menores, temos as coordenadas do primeiro vértice (5,25), e o segundo ficará na coordenada (135,25): 5px da coordenada do vértice + 10px da largura do primeiro retângulo + 5px da distância até a barra + 15px da largura da parte maior + 80px da largura total da barra + 15px da largura da parte maior à direita + 5px da distância = 135px.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="385" name="sl">
			   <label for="385"></label>
			   <img src="css4/53_02_02.png" />
			   <figcaption>A parte maior da barra pode ser feita com uma tag de caminho <code>&lt;path&gt;</code>: começando no ponto de coordenadas (20,5), usamos uma linha vertical v80, depois a largura com a horizontal h15, uma vertical subindo com v-30, a horizontal da largura da barra h80, seguida de uma vertical v30. Os outros comandos são similares.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="386" name="sl">
			   <label for="386"></label>
			   <img src="css4/53_02_03.png" />
			   <figcaption>Crie duas animações de transformação na barra. Neste exemplo, temos uma animação de rotação de 20&deg; para 0&deg; em torno do ponto de coordenadas (40,40) junto com a escala que começa em 0.7 e vai até 1.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="387" name="sl">
			   <label for="387"></label>
			   <img src="css4/53_02_04.png" />
			   <figcaption>Outra animação colocada dentro da tag de texto faz o desenho do texto e modifica a cor de preenchimento.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="388" name="sl">
			   <label for="388"></label>
			   <img src="css4/53_02_05.png" />
			   <figcaption>Com estas animações, o layout deste banner fica desta forma. Modifique valores de atributos e cores para criar o seu banner.</figcaption>
		   </li>
		</ul>
		<img src="css4/53_02_00.png" class="fundo" style="visibility:hidden"/>
  </details>
	<img src="css4/tags001_0053b.png" />
	<details class="sub"><summary>&#x1f4c3; Animações no 2&deg; banner</summary>
	<p>Vamos criar efeitos de animação no 2&deg; banner da nossa página. Podemos desenhar uma segunda roda, com outra cor, um pouco menor (usando scale) e deslocada para a direita (usando translate).</p>
	  <ul class="slider">
			<li>
			   <input type="radio" id="389" name="sl">
			   <label for="389"></label>
			   <img src="css4/53_03_00.png" />
			   <figcaption>Dentro da tag de grupo da primeira roda <code>&lt;g&gt;</code>, podemos inserir o efeito de animação.</figcaption>
		   </li>
		  <li>
			   <input type="radio" id="390" name="sl">
			   <label for="390"></label>
			   <img src="css4/53_03_01.png" />
			   <figcaption>A animação de rotação de 0&deg; a 360&deg; está definida no final da tag de grupo.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="391" name="sl">
			   <label for="391"></label>
			   <img src="css4/53_03_02.png" />
			   <figcaption>O desenho da segunda roda, com tons de verde, tem efeitos gradientes definidos com <code>id="efeito2a"</code> e <code>id="efeito3a"</code>. Criamos uma tag nova de grupo chamada <code>&lt;g name="roda2"&gt;</code> para usar os mesmos desenhos da roda original.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="392" name="sl">
			   <label for="392"></label>
			   <img src="css4/53_03_03.png" />
			   <figcaption>Fazendo a translação de 65px à direita e 65px para baixo junto com a escala de 0.8, temos a segunda roda desenhada.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="393" name="sl">
			   <label for="393"></label>
			   <img src="css4/53_03_04.png" />
			   <figcaption>O efeito de animação é o mesmo da primeira roda. Se você quiser inverter o sentido da rotação, basta trocar os limites para <code>from="360,50,50"</code> e <code>to="0,50,50"</code>.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="394" name="sl">
			   <label for="394"></label>
			   <img src="css4/53_03_05.png" />
			   <figcaption>O banner fica com este layout com as animações programadas. Ajuste atributos e cores para o seu layout.</figcaption>
		   </li>
		</ul>
		<img src="css4/53_03_00.png" class="fundo" style="visibility:hidden"/>
  </details>
  <details class="sub"><summary>&#x1f4c3; Animações no 9&deg; banner</summary>
	<p>Vamos criar animações de transformação no 9&deg; banner.</p>
	  <ul class="slider">
			<li>
			   <input type="radio" id="395" name="sl">
			   <label for="395"></label>
			   <img src="css4/53_04_00.png" />
			   <figcaption>No desenho da nuvem, podemos criar pequenas translações. Neste exemplo, a nuvem vai de 3px para a direita, depois volta ao ponto inicial; depois disso, vai para 3px à esquerda, retornando ao ponto inicial. A escala também foi usada variando de 0.95 a 1. Ajuste valores para fazer a animação do seu banner.</figcaption>
		   </li>
		  <li>
			   <input type="radio" id="396" name="sl">
			   <label for="396"></label>
			   <img src="css4/53_04_01.png" />
			   <figcaption>Podemos inserir uma animação de rotação nos raios do sol. Neste caso, foi colocada uma rotação que varia de 0&deg; a 30&deg; em torno do centro (55,15). Note que as tags de animações estão dentro das respectivas tags de grupos dos desenhos.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="397" name="sl">
			   <label for="397"></label>
			   <img src="css4/53_04_02.png" />
			   <figcaption>O layout fica desta forma. Ajuste valores e atributos de animação para seu banner.</figcaption>
		   </li>
		</ul>
		<img src="css4/53_04_00.png" class="fundo" style="visibility:hidden"/>
  </details>
	<p class="topop"><a href="#css4" class="topo">voltar ao topo</a></p>
	<img src="css4/tags001_0054.png" />
	<details class="sub"><summary>&#x1f4c3; Detalhes da Atividade</summary>
	<p>Agora você pode montar o 14&deg; banner. Use um dos logos que você desenhou, o banner e o menu para colocá-los na tag <code>class="banner2"</code>.</p>
	  <ul class="slider">
			<li>
			   <input type="radio" id="398" name="sl">
			   <label for="398"></label>
			   <img src="css4/54_01_00.png" />
			   <figcaption>Usando a <code>class="banner2"</code>, vamos colocar os elementos na ordem: logo, banner e menu. Tente outras configurações em seu banner da Atividade.</figcaption>
		   </li>
		  <li>
			   <input type="radio" id="399" name="sl">
			   <label for="399"></label>
			   <img src="css4/54_01_01.png" />
			   <figcaption>Usando o desenho do lápis, coloque-o em uma tag <code>class="logo"</code> que já configuramos no CSS.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="400" name="sl">
			   <label for="400"></label>
			   <img src="css4/54_01_02.png" />
			   <figcaption>Logo depois, colocamos a tag de <code>&lt;svg&gt;</code> do banner, com as devidas animações já programadas.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="401" name="sl">
			   <label for="401"></label>
			   <img src="css4/54_01_03.png" />
			   <figcaption>Depois do banner, antes de fechar a tag <code>&lt;svg&gt;</code>, crie uma curva <code>id="curva"</code>para desenharmos o título do banner alinhado com esta curva. Usando a tag <code>&lt;textpath&gt;</code>, coloque o título na página, com animação to tipo<code>startOffset</code>. Ajuste o valor inicial, pois depende do número de carcteres do título que você escolher.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="402" name="sl">
			   <label for="402"></label>
			   <img src="css4/54_01_04.png" />
			   <figcaption>Para finalizar o banner, insira a estrutura de menu da página.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="403" name="sl">
			   <label for="403"></label>
			   <img src="css4/54_01_05a.png" />
			   <figcaption>O banner fica com este layout com as animações programadas. Ajuste atributos e cores para o layout do seu banner.</figcaption>
		   </li>
		   <li>
			   <input type="radio" id="404" name="sl">
			   <label for="404"></label>
			   <img src="css4/54_01_05.png" />
			   <figcaption>No final da animação do texto, o banner fica desta forma.</figcaption>
		   </li>
		</ul>
		<img src="css4/54_01_00.png" class="fundo" style="visibility:hidden"/>
  </details>
	<p class="topop"><a href="#css4" class="topo">voltar ao topo</a></p>
</details>

<details id="css5" style="border-bottom: 1px solid #a2dec0;"><summary>Galerias de Imagens</summary>
	<p>página 55...</p>
</details>

<br>&#x1f4bb; &#x1f4c2;
<p><b>site desenvolvido por:</b></p> 
<p>Paulo Henrique Siqueira</p>  
<p><b>contato:</b> paulohscwb@gmail.com </p> 

<p><br><b>Referências:</b></p>
<ol>
	<li>W3Schools. <i>HTML - The language for building web pages:</i> <a href="https://www.w3schools.com/" target="_blank">https://www.w3schools.com/</a></li>
	<li>Origamid. <i>Flex Container:</i> <a href="https://origamid.com/projetos/flexbox-guia-completo/" target="blank">https://origamid.com/projetos/flexbox-guia-completo/</a></li>
	<li>Soueidan, S. <i>A Guide to SVG Animations (SMIL):</i> <a href="https://css-tricks.com/guide-svg-animations-smil/" target="_blank">https://css-tricks.com/guide-svg-animations-smil/</a></li>
	<li>Adams, C., Bolton, J., Johnson, D., Smith, S., Snook, J. <i>A arte e a ciência da
	CSS</i>. Sitepoint, 2009</li>
	<li>Marcotte, E. <i>Responsive Web Design</i>. A Book Apart. 2011</li>
	<li>Mazza, L. <i>HTML5 e CSS3: Domine a Web do futuro</i>. Casa do código, 2012</li>
	<li>Kalbach, J. <i>Design de navegação web: otimizando a experiência do usuário</i>. Porto
	Alegre, RS: Bookman, 2009</li>
	<li>Mathis, L. <i>Designed for Use: Usable Interfaces for Applications and the Web</i>. The
	Pragmatic Bookshelf, 2011</li>
	<li>Powers, D. <i>O guia essencial para dreamweaver CS4 com CSS, ajax e PHP</i>. Ed. Alta
	Books, 2009</li>
	<li>Souders, S. <i>High performance web sites: essential knowledge for frontend
	engineers</i>. Sebastopol; Farnham: O&#39;Reilly, 2007</li>
	<li>Zemel, T. <i>Web design responsivo: páginas adaptáveis para todos os
	dispositivos</i>. São Paulo, SP: Casa do Código, 2015</li>
<ol>