<h1> Projeto final - Analise de um dataset sobre explaentas </h1>

<b> Projeto final do grupo "Torre de PROGRAMAção negra" da matéria Machine learning da curso de ciência e tecnologia da ILUM. </b>

<b> Membros do grupo: Eric Leandro Lima Mendonça (23014), Júlia Amancio Ferreira (23006), Vinícius André Oliveira Lima Moura (23011) e João Otávio de Ávila Nascimento (23022)  </b>

<h2>Objetivos da implementação: </h2>

O objetivo do projeto foi explorar e analisar um dataset com dados sobre exoplanetas catalogados pela NASA, utilizado as ferramantas aprendidas durante o semestre com a materia de aprendizado de maquina, é imprecindivel ressaltar a importancia de analisar dados como esse, pois a utilização de ferramentas de machine learning em conjunção com conjuntos de dados astronômicos é fundamental para a eficiente análise de vastas quantidades de informações provenientes de observações telescópicas, simulações e missões espaciais. Essas ferramentas possibilitam a rápida identificação de padrões complexos, a classificação automática de diversos tipos de objetos celestes, a previsão de eventos astronômicos e a exploração de relações intricadas entre variáveis. Além disso, a aplicação de algoritmos de machine learning melhora a precisão na redução de dados, reduzindo erros humanos e acelerando a produção de resultados. Em campos como a pesquisa de exoplanetas, esses algoritmos têm sido cruciais para identificar padrões nas curvas de luz estelar, indicando a presença de novos planetas fora do nosso sistema solar. Claro, não nos aprofundamos tanto, apenas fizemos analises fundamentais, como agrupamento e previsões.

<h2>Desenvolvimento: </h2>
Nesse notebook, existem variáveis definidas que podem ser alteradas e que são essenciais para a compreensão da análise como um todo. Para isso, tem-se que:

<li> df_tratado: basea-se no dataframe tratado que será utilizado para os demais tópicos do notebook <li>
</li> SEMENTE_ALEATORIA: é a semente fixa a qual os modelos passarão a prever os dados <li>
</li> TAMANHO_TESTE: é o tamanho de dados (em porcentagem) que será reservado para teste. 
<li> FEATURES: representa as colunas que podem ser modificadas e serem consideradas como features na análise</li>
<li> TARGET: representa a coluna que pode ser modificada para a previsão</li>
** Observação: é válido ressaltar que a análise dos dados abordado nesse notebook considerou um target categórico. Se o target for modificado para um numérico, os modelos de previsão precisarão ser modificados para *regressores* **
<li> VIZINHOS: número de vizinhos que pode ser modificado no modelo k-NN</li>
<li> NUM_GRUPOS: número de grupos finais que se deseja obter ao final
<li> RAIO_VIZINHANCA: o valor do raio para serem considerados os pontos para o agrupamento</li>
<li> NUM_MIN_VIZINHOS: o número de vizinhos a serem considerados a partir do raio definido anteriormente</li>
<li> METODO_DISTANCIA: método de calcular distâncias a ser aplicado</li>
<li> NIVEL_MAXIMO: se refere ao nível de divisões máximas possíveis de serem feitas</li>

Esses são os principais parâmetros em que podem ser modificados de maneira com que seja possível visualizar os diferentes comportamentos do dataset para cada tipo de análise que se deseja realizar. 

<h2>Bibliotes usadas: </h2>

<li> Bokeh </li>
<li> Numpy </li>
<li> Mathplotlib </li>
<li> Pandas </li>
<li> Seaborn </li>
<li> Kneed </li>
<li> Scikitlearn </li>
<li> Scipy </li>

<h2>Referências: </h2>

[1] Machine Learning in Astronomy: a practical overview - Dalya Baron. Disponível em: <http://ned.ipac.caltech.edu/level5/March19/Baron/Baron3.html>. Acesso em: 15 nov. 2023.

[2] KANG, H.; MANN, K. S. A Combinational Strategy for Clustering of Astronomical Datasets. International Journal for Research in Engineering Application & Management (IJREAM), v. 04, n. 06, p. 2454–9150, 2018.

[3] SpaceToday - YouTube. Disponível em: <https://youtube.com/@SpaceToday?si=GqPP9N4Kxd5RgZUq>. Acesso em: 15 nov. 2023.

‌[4] SCIKIT-LEARN. scikit-learn: machine learning in Python. Disponível em: <https://scikit-learn.org/stable/>.

‌[5] NUMPY. Overview — NumPy v1.19 Manual. Disponível em: <https://numpy.org/doc/stable/>.

[6] Overview of seaborn plotting functions — seaborn 0.12.0 documentation. Disponível em: <https://seaborn.pydata.org/tutorial/function_overview.html>.

[7] PANDAS. pandas documentation — pandas 1.0.1 documentation. Disponível em: <https://pandas.pydata.org/docs/>.

‌[8] MATPLOTLIB. Matplotlib: Python plotting — Matplotlib 3.3.4 documentation. Disponível em: <https://matplotlib.org/stable/index.html>.

‌[9] Welcome to kneed’s documentation! — kneed 0.8.5 documentation. Disponível em: <https://kneed.readthedocs.io/en/latest/>. Acesso em: 15 nov. 2023.

‌[10] CONTRIBUTORS, B. Bokeh documentation. Disponível em: <https://docs.bokeh.org/en/latest/>.

‌[11] Moodle USP: e-Disciplinas. Disponível em: <https://edisciplinas.usp.br/pluginfile.php/7509547/mod_resource/content/2/Classificac>. Acesso em: 16 nov. 2023.

‌[12] Prevendo Doenças do Coração com Python e Machine Learning - PARTE 2. Disponível em: <https://www.youtube.com/watch?v=5nS14oaOj1g>. Acesso em: 16 nov. 2023.

‌[13] AdaBoost Classifier Tutorial. Disponível em: <https://www.kaggle.com/code/prashant111/adaboost-classifier-tutorial>.

‌[14] Material disponibilizado pelo professor
