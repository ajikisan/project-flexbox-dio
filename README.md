<p>
<br>  Digital Innovation One 
<br>  Posicionando elementos com CSS Flexbox 
<br>  Instrutora: Karen Santos
<br>  Aluna: Mirian Ajiki Molicawa
<br>  Data:16/06/2022 
</p>

<h1> Flex Turismos </h1>
<p>
Com o projeto Flex Turismos realizado foi possível colocar em prática os fundamentos e aplicações da propriedade flexbox na criação de layouts responsivos, sem a necessidade a definição de valores fixos. </p>

<h2> Tecnologias </h2>
<br> - [x] Visual Studio Code 
<br> - [x] HTML5 e CSS 
<br> - [x] Edge & Google Chrome

<p>
<h2>Flex Container </h2>
É a tag que envolve os itens, ao qual foi aplicado a propriedade “display: flex”. 
<br> ● display 
<br> ● flex-direction 
<br> ● flex-wrap 
<br> ● flex-flow 
<br> ● justify-content 
<br> ● align-items 
<br> ● align-content
</p>
</br>


<p>
<h3>Flex-direction</h3> 
É a propriedade que estabelece o eixo principal do container, definindo assim a direção que os flex items são colocados no flex container.
<br> ● row (padrão): à direção do texto, esquerda para direita
<br> ● row-reverse: sentido oposto à direção do texto 
<br> ● column: ordenação de cima para baixo, em coluna unica 
<br> ● column-reverse: ordenação inversa, de baixo para cima
</br>
</p>

<p>
<h3>Flex-wrap </h3>
É a propriedade que define se os itens devem ou não quebrar a linha. Por padrão eles não quebram linhas, isso faz com que os flex itens sejam compactados além do limite do conteúdo.
<br> ● nowrap: é o padrão, não permite a quebra de linha. 
<br> ● wrap: permite a quebra de linha assim que um dos flex itens não puder mais ser compactado. 
<br> ● wrap-reverse permite a quebra de linha assim que um dos flex itens não puder mais ser compactado, porém na direção contrária da linha, acima.
<br>
</p>

<p>
<h3>Flex-flow </h3>
É um atalho para as propriedades flex-direction e flex-wrap. Porém seu uso não é tão comum, visto que, quando mudamos o flex-direction para column, mantemos o padrão do flex-wrap que é nowrap.
<br>
</p>

<p>
<h3>Justify Content </h3>
Essa propriedade vai se encarregar de alinhar os itens dentro do container de acordo com a direção pretendida e tratar da distribuição de espaçamento entre eles. 
OBS: caso seus itens esteja ocupando 100% de todo o container, ela não se aplica.
<br> ● flex-start: início do container. 
<br> ● flex-end: final do container. 
<br> ● center: ao centro do container. 
<br> ● space-between: cria um espaçamento igual entre os elementos. 
<br> ● space-around: os espaçamentos do meio são duas vezes maiores que o inicial e final. 
<br>
</p>

<p>
<h3>Align-items </h3>
Trata do alinhamento dos flex itens de acordo com o eixo do container. 
O alinhamento é diferente para quando os itens estão em colunas ou linhas. 
Permite o alinhamento central no eixo vertical. 
<br> ● center: alinhamento dos itens ao centro 
<br> ● stretch: padrão, e os flex itens cresçam igualmente 
<br> ● flex-start: alinhamento dos itens no início 
<br> ● flex-end: alinhamento dos itens no final
<br> ● baseline: alinhamento de acordo com a linha base da tipografia dos itens
<br>
</p>

<p>
<h3>Align-content </h3>
É a propriedade responsável por tratar o alinhamento das linhas do container em relação ao eixo vertical do container.
<br> ● center: alinhamento dos itens ao centro 
<br> ● stretch: é o padrão e os flex itens crescem igualmente 
<br> ● flex-start: alinhamento dos itens no início 
<br> ● flex-end: alinhamento dos itens no final 
<br> ● space-between: cria um espaçamento igual entre os elementos 
<br> ● space-around: os espaçamentos do meio são duas vezes maiores que o inicial e final
<br>
</p>

<h2>Flex Items</h2>
São os elementos filhos diretos do Flex Container. E também podem se tornar Flex Container.
<br> ● flex-grow 
<br> ● flax-basis 
<br> ● flex-shrink 
<br> ● flex 
<br> ● order 
<br> ● align-self
</br> 
</p>

<p>
<h3>Flex-grow </h3>
Define a proporcionalidade de crescimentos dos itens, respeitando o tamanho de seus conteúdos internos. 
<br> OBS: não irá funcionar caso tenhamos adicionado justify-content ao nosso flex container 
<br>
<br>
<h3>Flex-shrink </h3>
É a propriedade que estabelecer a capacidade de redução ou compressão do tamanho de um item. 
<br>
<br>
<h3>Flex </h3>
Esta propriedade é um atalho ou abreviação de escrita para as propriedades: grow, shrink e basis.
<br>
</p>

<p>
<h2>Align-self </h2>
É a propriedade que estabelece o alinhamento de modo individual sobre um determinado item.
<br> ● auto: valor padrão, irá respeitar a definição de align-items do container 
<br> ● flex-start: ao início do container 
<br> ● flex-end: ao final do container 
<br> ● center: relativo ao centro de acordo com o eixo 
<br> ● stretch: ocupa todo os espaço relativo 
<br> ● baseline: utiliza a linha base da tipografia
</p>