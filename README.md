<!DOCTYPE html>
<html>
<body>
  <h1>Tratamento de Dados para modelo Machine Learning para previsão de lucros para investimento em conversão de leads</h1>
  <p>Este projeto visa desenvolver um modelo de Machine Learning para prever os lucros potenciais de investir em conversão de leads, com o objetivo de otimizar a estratégia de investimento e maximizar o retorno financeiro.</p>
  
  <h2>Objetivos</h2>
  <ul>
    <li>Limpar e preprocessar os dados para garantir consistência e qualidade.</li>
  </ul>
  
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
    <li>`sklearn`: para algoritmos de Machine Learning</li>
    <li>`from sklearn.model_selection import train_test_split`: Divisão de dados em treino/teste.</li>
    <li>`from sklearn.ensemble import RandomForestRegressor`: Modelo de regressão Random Forest.</li>
    <li>`from sklearn.metrics import mean_absolute_error, mean_squared_error, r2_score`: Métricas de erro.</li>
    <li>`from sklearn.model_selection import GridSearchCV`: Busca em grade para otimização de hiperparâmetros.</li>
    <li>`from sklearn.linear_model import LinearRegression`: Modelo de regressão linear.</li>
    <li>`from sklearn.preprocessing import StandardScaler`: Escalonamento de características.</li>
    <li>`from sklearn.preprocessing import PolynomialFeatures`: Criação de características polinomiais.</li>
    <li>`from sklearn.pipeline import make_pipeline`: Criação de pipelines de transformação e modelagem.</li>
    <li>`from sklearn.linear_model import Ridge`: Regressão Ridge.</li>
  </ul>
  
  <h2>Tratamento de Dados</h2>
  <p>Para preparar os dados para a análise, foram aplicadas as seguintes técnicas de tratamento:</p>
  <ul>
    <li>**TURNO**: valores em branco foram substituídos pela moda, pois a moda é uma medida de tendência central mais robusta para variáveis categóricas.</li>
    <li>**IDADE**: valores em branco foram substituídos pela média, pois a média é uma medida de tendência central mais adequada para variáveis numéricas.</li>
  </ul>
  <p>Essas técnicas foram escolhidas para minimizar a perda de informações a garantir a consistência dos dados.</p>
</body>
</html>
