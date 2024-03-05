<h1 align="center">:file_cabinet:Projeto RH - Previsão de Demissão de Funcionários </h1>

## :memo: Descrição

Este projeto tem como objetivo prever se algum funcionário irá entrar com um pedido de demissão. A ideia por trás disso é que a contratação de novos funcionários é um processo caro para as empresas, portanto, prevendo a demissão, a empresa pode agir de forma antecipada para mitigar o impacto financeiro e organizacional da perda de um funcionário.

* Justificativa:
  * A contratação de um novo funcionário tem um custo médio de $7645 (em uma empresa com aproximadamente 500 funcionários).
  * Leva em média 52 dias para um novo funcionário ocupar efetivamente sua nova posição.
  * Uma empresa média perde entre 1% e 2.5% de sua receita total no tempo que leva para treinar um novo funcionário.
 
* Principais Métricas para Análise
  * Envolvimento com o trabalho
  * Escolaridade
  * Satisfação com o trabalho
  * Métricas de desempenho
  * Relacionamento
  * Equilíbrio entre atividades pessoais e profissionais
* Sobre a Base de Dados

  A base de dados possui informações sobre diversos aspectos dos funcionários, incluindo sua educação, satisfação com o trabalho, desempenho, satisfação com relacionamento e equilíbrio entre vida pessoal e          profissional. Alguns exemplos de variáveis na base de dados incluem:
  * Education: Nível de educação do funcionário (Below College, College, Bachelor, Master, Doctor).
  * EnvironmentSatisfaction: Nível de satisfação do funcionário com o ambiente de trabalho (Low, Medium, High, Very High).
  * JobInvolvement: Nível de envolvimento do funcionário com o trabalho (Low, Medium, High, Very High).
  * JobSatisfaction: Nível de satisfação do funcionário com o trabalho (Low, Medium, High, Very High).
  * PerformanceRating: Avaliação do desempenho do funcionário (Low, Good, Excellent, Outstanding).
  * RelationshipSatisfaction: Nível de satisfação do funcionário com os relacionamentos no trabalho (Low, Medium, High, Very High).
  * WorkLifeBalance: Equilíbrio entre vida pessoal e profissional do funcionário (Bad, Good, Better, Best).

## :books: Funcionalidades
* Previsão de Demissão de Funcionários: O projeto permite prever se um funcionário irá entrar com um pedido de demissão com base em várias características e métricas relacionadas ao seu desempenho e satisfação no trabalho.
* Análise de Métricas: Realiza uma análise detalhada das métricas mais relevantes para identificar padrões e tendências que possam influenciar a decisão de um funcionário de sair da empresa.
* Modelagem de Machine Learning: Utiliza algoritmos de classificação, como Regressão Logística, Random Forest ou Redes Neurais, para construir modelos de previsão de demissão de funcionários.
* Avaliação de Modelos: Avalia o desempenho dos modelos utilizando métricas como precisão, recall e F1-score para determinar a eficácia das previsões.
  
## :wrench: Tecnologias utilizadas
* Python
* Pandas
* NumPy
* Seaborn
* Matplotlib
* Scikit-learn (para modelagem de machine learning)
* TensorFlow (opcional, para redes neurais)
* Keras (opcional, para redes neurais)

## :rocket: Rodando o projeto
Para rodar o repositório é necessário clonar o mesmo, dar o seguinte comando para iniciar o projeto:
* Clone o repositório para sua máquina local:
```
git clone https://github.com/brendaverch/projeto_rh.git
```
* Navegue até o diretório do projeto:
```
cd projeto_rh
```
* Certifique-se de que você possui as dependências necessárias instaladas. Você pode instalá-las executando:
```
pip install pandas numpy seaborn matplotlib scikit-learn tensorflow keras
```
