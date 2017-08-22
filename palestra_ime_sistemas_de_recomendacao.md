## Sistemas de recomendação
IX Encontro do BCC - IME
* Matheus

> matheus.cesario@kekanto.com
> github.com/matheus-santos

------------
![Kekanto](../../assets/images/pisdr/kekanto.png "Kekanto)

* Fundado em 2009
* Guia colaborativo de cidades
* 1.9+ milhão de usuários
* 1.8+ milhão de lugares cadastrados
* 1.1+ milhão de opiniões

------------
## Explosão de dados
Crescimento exponencial em geração de conteúdo

* 20 petabytes por dia no Google [[1]](https://aci.info/2014/07/12/the-data-explosion-in-2014-minute-by-minute-infographic/)
* 480 mi de itens a venda na Amazon USA [[2]](https://export-x.com/2015/12/11/how-many-products-does-amazon-sell-2015/)
* 8k filmes e seriados na Netflix [[3]](http://time.com/4272360/the-number-of-movies-on-netflix-is-dropping-fast/)
* 1.8+ milhão de lugares cadastrados no Kekanto

---
## Problemas
Volume de informações cansa o usuário

* Excesso de conteúdo = conversão baixa
* Desinteresse

--- 
## Solução?
Minerar os dados em busca de conteúdo relevante

* Identificar interesses dos usuários
* Oferecer conteúdo personalizado

------------
## Sistemas de recomendação

* Gerar previsões baseado no comportamento
* Abordagens: 
    * Filtro colaborativo 
    * Baseado em conteúdo
    * Híbridos

---
## Filtro colaborativo
*"Qual sua nota para este filme?"*

* Comportamento dos usuários
* Presumir relacionamentos (**similaridade**)
* Algoritmos: filtro colaborativo, sim. vetores

---
## Baseado em conteúdo
*"Por que você comprou de X, te recomendamos Y"*

* Perfis de objetos e usuários (**keywords**)
* Previsão baseada nas descrições dos objetos
* Algoritmos: Bayes, clusters, *inverted index*, NN

------------
## > print("Hello world!")
Caixa de ferramentas:
* Bibliotecas: Scikit, Mahout, Hadoop, Keras, TensorFlow, Theano
* Linguagens: Python, R
* Viz: Jupyter, Matplotlib, Seaborn, D3js

---
## Receita para modelo ML

1. Definir o problema
2. Preparar os dados
3. Escolha do algoritmo
4. Melhorar resultados
5. Apresentar resultados

---
## Similaridade por coseno

- Planilha
- Jupyter Notebook

---
## SVD e factorização de matrizes
Decompor matriz `users x items` em duas matrizes `q` (representação do item) e `p` (representação do usuário). A previsão é dada pelo resultado do produto escalar entre dois vetores `qi` e `pj`.

- Jupyter Notebook
- [Vectorization: Low Rank Matrix Factorization](https://www.coursera.org/learn/machine-learning/lecture/CEXN0/vectorization-low-rank-matrix-factorization)

---
## Clusters
Além de avaliações, podemos olhar classficiar os objetos baseado em outras características como faixa de preço, pratos, localização, se tem estacionamento, tipo de lugar e etc.

- Nearest neighbor
- SVM
- NN

--- 
## Bayes e tf-idf
Podemos ainda utilizar Naive Bayes para lugares e avaliações

- Fórmula `P(A|B) = (P(B|A) * P(A))/P(B)`
- tf-idf _term frequency–inverse document frequency_: Solr, ElasticSearch
- Análise de sentimentos

------------
## Q&A
Dúvidas, críticas e sugestões

![Salvador Dalí](../../assets/images/pisdr/salvador-dali.jpg "Salvador Dalí")

------------
## Próximos passos

![Data Science Venn Diagram (fonte: http://drewconway.com/zia/2013/3/26/the-data-science-venn-diagram)](../../assets/images/pisdr/Data_Science_VD.png "Data Science Venn Diagram (fonte: http://drewconway.com/zia/2013/3/26/the-data-science-venn-diagram)")

------------
## Obrigado!
<TODO link pro repo>
