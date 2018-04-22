## Introdução

Esse curso está sendo desenvolvido para pessoas que querem entender como o CSS e suas propriedades funcionam na prática e a fundo, deixando de lado todas as pegadinhas da linguagem e baseando-se no desenvolvimento orientado à boas práticas.

Lembrando que o foco do curso não é em metodologias, e sim no funcionamento do CSS cru na prática. Obaviamente, abordaremos assuntos como BEM, OOCSS, ITCSS, SMACSS mas ainda assim, não é o foco do curso.


### Surgimento do HTML

Em 1980 Tim Berners-Lee propôs um projeto baseado no conceito de hipertexto denominado ENQUIRE. Este projeto foi inicialmente todo desenvolvido em linguagem Pascal. Em 1989 Tim Berners-Lee com a ajuda de um estudante do CERN chamado Robert Cailliau conseguiu implementar a primeira comunicação bem sucedida entre um cliente HTTP e um servidor através da internet. Surgia então a World Wide Web.

A sigla HTML significa HyperText Markup Language em português, linguagem de marcação de hipertexto. A primeira versão do HTML foi baseada na linguagem SGML. O SGML era utilizado para a estruturação de documentos e foi dele que o HTML herdou diversas tags tais como: título <h1> ao <h6>, cabeçalho <head> e parágrafo <p>. A maior diferença entre essas duas linguagens de marcação é que o HTML implementava a tag <a> com o atributo href, permitindo assim a ligação (links) de uma página a outra. Esse conceito de interligação entre documentos é a base do funcionamento de toda Web.

O HTML surgiu em 1990 e até o seu quinto ano de vida sofreu várias revisões e alterações na sua especificação. Nesta época, quem controlava o padrão era o CERN e a IETF. Após 1995, o padrão passou a ser regularizado pela W3C, entidade que regula os padrões Web.

Hoje o HTML é o formato padrão para criação de páginas online e aplicações de web. Em conjunto com o CSS e Javascript, eles formam as pedras principais para a World Wide Web. Todos os navegadores atuais recebem documentos em HTML que sao processados renderização e apresentação do conteúdo online.

A tecnologia é fruto da junção entre os padrões HyTime e SGML, que não são mais utilizados.

### Necessidade de páginas estilosas - Surgimento do CSS

Com a evolução dos recursos de programação, as tecnologias estavam adotando cada vez mais estilos e variações para deixá-las mais elegantes e atrativas para os usuários. Com isto, linguagens de marcação simples como o HTML, que era destinada para apresentar os conteúdos, também precisaram ser aprimoradas.

Foram criadas novas tags e atributos de estilo para o HTML e em resumo, ele passou a exercer tanto a função de estruturar o conteúdo quanto de apresentá-lo para o usuário final. Entretanto, isto começou a trazer um problema para os desenvolvedores, pois não havia uma forma de definir, por exemplo, um padrão para todos os cabeçalhos ou conteúdos em diversas páginas. Ou seja, as alterações teriam que ser feitas manualmente, uma a uma.

A partir destas complicações, nasceu o CSS. Primariamente, foi desenvolvido para habilitar a separação do conteúdo e formato de um documento (na linguagem de formatação utilizada) de sua apresentação, incluindo elementos como cores, formatos de fontes e layout. Esta separação proporcionou uma maior flexibilidade e controle na especificação de como as características serão exibidas, permitiu um compartilhamento de formato e reduziu a repetição no conteúdo estrutural de um documento.

Com isto, as linguagens de marcação passaram novamente a exercer sua função de marcar e estruturar o conteúdo de um documento, enquanto o CSS encarregou-se da aplicação dos estilos necessários para a aparência dela. Isto é feito por meio da criação de um arquivo externo que contém todas as regras aplicadas e com isto, é possível fazer alterações de estilo em todas as páginas de um site e outros documentos que utilizam CSS de forma fácil e rápida.

Formatar informação dos sites não é algo novo. Por volta de 1970, no começo da trajetória do SGML, já se falava em algo parecido.

Quando o HTML foi criado, a intenção não era de forma alguma, formatar informação. A medida que o HTML foi se popularizando e evoluindo, foram incluídas em suas qualidades, o domínio de controlar algumas aparências para o documento. Isso fez com que a linguagem ficasse muito complexa, mais dificil para entender e manter.

Outro problema era que os browsers tinham diferenças de implementações, o que dificultava a visualização dos sites, trazendo menos controle na navegação pela web.

Por esse tempo apareceu o salvador da pátria. Håkon Wium Lie, vendo toda essa dificuldade, resolveu criar um jeito mais fácil para formatar a informação. Foi aí que ele propôs a criação do CSS ou Cascading Style Sheets… Esse era o ano de 1994.

Aceitando o convite feito pelo próprio Håkon, Bert Bos – que naquele tempo estava trabalhando em um browser chamado Argo – começou a trabalhar no projeto.

Os dois então, trabalharam juntamente no começo do desenvolvimento do CSS.

Em 1995 eles apresentaram sua proposta e finalmente, o W3C – World Wide Web Consortium – que estava acabando de nascer, se interessou pelo projeto e resolveu criar uma equipe, obviamente liderada por Håkon e Bert Bos.

O resultado apareceu logo, em 1996, eles lançaram a recomendação oficial pelo W3C do CSS Level 1 (CSS 1).

Dois anos depois, no dia 12 de Maio de 1998, eles lançaram a recomendação do CSS de nível 2. A segunda versão das Folhas de Estilo para web.

O CSS3 é a mais recente evolução da linguagem CSS que estende o CSS2.1. Ela trouxe uma série de novidades bastante esperadas, como cantos arredondados, sombras, gradientes , transições ou animações , bem como novos layouts como multi-colunas , caixas flexíveis ou layouts de grade. O vendor-prefixed são peças experimentais que deve ser evitado em ambientes de produção, ou usado com extrema cautela, pois tanto a sua sintaxe e semântica podem mudar no futuro.



###### fontes
[HTML](https://pt.wikipedia.org/wiki/HTML)
[A Histório do HTML](http://www.frontendbrasil.com.br/artigos/a-historia-do-html/)
[Uma breve história do CSS](https://tableless.com.br/uma-breve-historia-do-css/)
[CSS3](https://developer.mozilla.org/pt-BR/docs/Web/CSS/CSS3)
[Como o CSS funciona ?](https://developer.mozilla.org/pt-BR/docs/Aprender/CSS/Introduction_to_CSS/como_CSS_funciona)
[Manual CSS](http://tableless.github.io/iniciantes/manual/css/)