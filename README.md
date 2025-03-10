IMG:
em, px, pt, cm, in? Qual utilizar? Descreva as unidades de medida e quando utilizar cada uma delas.

As unidades de medida no CSS definem o tamanho dos elementos, incluindo imagens. Cada unidade tem um propósito específico e deve ser usada conforme a necessidade do design.

O pixel (px) é a unidade mais comum, pois representa um ponto fixo na tela. Ele é útil quando se deseja um tamanho exato e previsível, sem depender de outros fatores como a resolução da tela ou o tamanho da fonte.

Já o em é uma unidade relativa ao tamanho da fonte do elemento pai. Isso significa que, se a fonte do elemento pai for de 16 pixels, um tamanho de 2em será equivalente a 32 pixels. Essa unidade é útil quando se deseja que o tamanho da imagem se ajuste de acordo com o tamanho do texto, tornando o design mais flexível.

O rem funciona de forma semelhante ao em, mas em vez de se basear no elemento pai, ele sempre se baseia no tamanho da fonte do elemento `<html>`. Isso torna o uso do rem mais previsível, pois mantém uma referência fixa para todo o documento.

O pt (ponto) é uma unidade tradicional de tipografia, usada principalmente em impressão. Um ponto equivale a 1/72 de polegada e não é muito utilizado para imagens na web, sendo mais apropriado para documentos que serão impressos.

As unidades cm (centímetros) e in (polegadas) são medidas físicas e fazem mais sentido quando se trabalha com impressão. Como as telas de dispositivos variam em tamanho e densidade de pixels, essas unidades não são muito práticas para layouts web.

Além dessas, existem unidades baseadas na dimensão da tela, como vw (viewport width) e vh (viewport height). O vw representa uma fração da largura total da tela, e o vh uma fração da altura. Por exemplo, um valor de 50vw significa que o elemento ocupará 50% da largura da tela, tornando a imagem responsiva ao tamanho do dispositivo.
A escolha da unidade depende do objetivo. Se for necessário um tamanho fixo e preciso, o pixel é a melhor opção. Para um design flexível e responsivo, unidades relativas como em, rem e vw são mais recomendadas. Já para impressão, pt, cm e in são mais apropriadas.

O que e? Qual a funçao?
CSS (Cascading Style Sheets) é uma linguagem usada para estilizar páginas web. Sua função é definir como os elementos HTML devem ser exibidos, controlando coisas como cores, fontes, tamanhos, espaçamento e layout. Em resumo, o CSS dá o "visual" à página, deixando ela mais bonita e organizada.

Quais as formas de ultilizaçao?
O CSS pode ser utilizado de três formas: diretamente no elemento HTML com o atributo style, dentro da tag «style> no cabeçalho da página ou através de um arquivo externo css*, vinculado à página usando a tag *<link>. A escolha depende da organização e das necessidades do projeto.
