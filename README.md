# <p O uso de Machine Learning na classificação de textos com ênfase em Fake News </p>


<hr>
A deflagração de notícias falsa, popularmente chamadas de fake news, tornaram-se uma grande preocupação devido à sua capacidade de criar impactos devastadores no que se refere às desinformações que são disseminadas no mundo virtual.
As aplicações de aprendizado de máquina têm tido sucesso no reconhecimento de padrões, por isso estão sendo cada vez mais utilizada para a análise de textos.

Este trabalho comparou os algoritmos de classificação Random Forest, Árvore de Decisão e Regressão Logística na classificação de notícias descritas como fake news visando a exploração desses modelos e sua efetividade.
<hr>

# DESENVOLVIMENTO DO PROJETO

A base de dados utilizada para treinamento e testes dos algoritmos neste estudo é da Kaggle.com, uma plataforma de comunidade online da Google para cientistas de dados que, disponibiliza conjuntos de dados de notícias falsas e reais para trabalhos e pesquisas, todos os artigos e notícias retirados da base de dados para este trabalho são de origem norte americana de língua inglesa

- Link para a base de dados  -> https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset?select=True.csv 
![image](https://user-images.githubusercontent.com/48418418/205399356-25ecfba5-7eca-4338-8c3f-432401d75750.png)


O conjunto de dados contém 3 arquivos no formato .CSV denominados Train.csv para treinamento, Fake.csv e True.csv para teste. Todo o conjunto de dados de notícias contém 23 mil linhas de notícias descritas como sabidamente falsas e 21 mil linhas de notícias sabidamente verdadeiras. Os dados referem-se às categorias de notícias variadas de política, governo e mundo, demonstradas em porcentagem na Figura 1.


<hr>

# Resultados.

Ao medir a performance dos modelos com as técnicas de Acuracidade, Erro, Recall, Precisão e F1-Score, vistos na Tabela 1. Identificou-se uma precisão de 0,99 em todos os modelos analisados quanto a precisão,  além do F1-Score que obteve 0,99 para Árvore de decisão e 0,98 para Random Forest e Regressão Lógica. Estes valores de precisão poderão ser entendidos como modelos de precisão alta, poucas taxas de falso positivo e falso negativo, vistos na matriz de confusão, figura 2. Destaca-se a acuracidade do modelo Árvore de decisão com 99,61%, seguido dos modelos de Random Forest 98,93%  e Regressão Lógica 98,73%. 

Resultados da Matriz de Confusão

Comparação da performance para todos os três modelos.

# Conclusão 

O presente trabalho buscou comparar os algoritmos de classificação Random forest, Árvore de decisão e Regressão logística na classificação de notícias descritas como fake news. Visando a exploração desses modelos e sua efetividade. 
	Ao analisar os resultados obtidos pode-se concluir que, dentre os algoritmos selecionados, a Árvore de decisão foi o que demonstrou o melhor desempenho na classificação de fake news da base supervisionada, registrando uma acuracidade de 99,61% e obtendo um bom desempenho na matriz de confusão com os menores erros. Não muito distantes a acuracidade registradas nos modelos Random Forest e Regressão Lógica foram de 98,93% e 98,73% respectivamente. 
	Estes valores poderão ser entendidos como modelos de precisão alta, em comparação com os resultados obtidos por Uma Sharma et al., (2021) utilizando o Twitter como fonte de dados, a Regressão Logística e Random Forest tiveram precisão de 65% e 59% respectivamente. De acordo com outras obras utilizadas como base para o projeto e analisando seus resultados, a variedade de algoritmos de aprendizagem de máquinas demonstram uma grande capacidade de detectar fake news. É possível que no futuro as técnicas de aprendizado de máquinas se tornarão um método padrão na identificação de notícias intencionalmente falsas.


<hr>

### AUTORES DO PROJETO
29
<ul>
30
<li>Paulo Henrique Apro - TIA: 41723457</li>
31
  <li>Marco Polo - TIA: 41703170 </li>
32
  
33
</ul>
