# Network Twitter Mentions

Neste repositório é feito um estudo e uma rede de menções utilizando os nomes dos usuários e de menções que nos tweets desses usuários. Para isso foi usado a linguagem de programação Python e pacotes para manusear os dados e gerar gráficos. Para a construção da rede foi utilizado o Twitter API para pesquisar tweets com a hashtag #covid19 na língua portuguesa. A rede de menções é construida com os nós representando os usuários e uma aresta é adicionada quando o usuário criador do tweet menciona alguém nesse tweet, a aresta é direcionada do criador do tweet para o usuário mencionado.
  
## Network

<center><img width="600" src="https://github.com/matheusriv/network_twitter_mentions/blob/main/image/grafo.png"></center>
<center>
  
Para explorar o grafo visite esse [link](https://matheusriv.github.io/network_twitter_mentions/network/).
 
A página é uma visualização da rede criada usando o software Gephi, um pacote de software de código aberto para análise de redes e grafos. A rede foi exportada com o plug-in de exportação Sigma do Gephi.
