<!DOCTYPE html> <html> <body> <h1>Tratamento de Dados para Predição de Movimento em uma Academia de Dança</h1> <p>Este projeto visa tratar os dados para prever os momentos de maior movimento em uma academia de dança.</p> <h2>Objetivos</h2> <ul> <li>Limpar e preprocessar os dados para garantir consistência e qualidade.</li>

<h2>Requisitos</h2>
<p>Para executar este projeto, você precisará instalar as seguintes bibliotecas:</p>
<ul>
    <li>`xlsxwriter`: `pip install xlsxwriter`</li>
    <li>`pandas-profiling`: `pip install pandas-profiling==3.3.0`</li>
</ul>

<h2>Bibliotecas Utilizadas</h2>
<p>Este projeto utiliza as seguintes bibliotecas:</p>
<ul>
    <li>`pandas`: para manipulação de dados em formato de tabela</li>
    <li>`numpy`: para operações numéricas</li>
    <li>`scipy`: para estatística e análise de dados</li>
    <li>`xlsxwriter`: para criar e manipular arquivos Excel</li>
    <li>`matplotlib`: para criação de gráficos</li>
    <li>`seaborn`: para visualização de dados</li>
    <li>`scipy.stats`: para calcular a estatística de qui-quadrado</li>
    <li>`math`: para operações matemáticas</li>
    <li>`pandas-profiling`: para geração de relatórios de perfil de dados</li>
</ul>

<h2>Tratamento de Dados</h2>
<p>Para preparar os dados para a análise, foram aplicadas as seguintes técnicas de tratamento:</p>
<ul>
    <li>**TURNO**: valores em branco foram substituídos pela moda, pois a moda é uma medida de tendência central mais robusta para variáveis categóricas.</li>
    <li>**IDADE**: valores em branco foram substituídos pela média, pois a média é uma medida de tendência central mais adequada para variáveis numéricas.</li>
</ul>
<p>Essas técnicas foram escolhidas para minimizar a perda de informações e garantir a consistência dos dados.</p>
