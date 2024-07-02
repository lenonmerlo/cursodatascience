# Análise de Notas de Filmes com Python 🎬📊

Este repositório contém os projetos e análises realizados durante o curso de Data Science da [Alura](https://www.alura.com.br/), ministrado pelo Prof. Guilherme Silveira.

## Descrição do Curso 📚

No curso, analisamos as notas de filmes utilizando a linguagem de programação Python. Aprendemos a manipular e explorar dados, criando gráficos e interpretando estatísticas para obter insights valiosos.

## Conteúdos Abordados 📈

- **Manipulação de Dados com Pandas:** Importação, limpeza e transformação de dados.
- **Visualização de Dados com Matplotlib e Seaborn:** Criação de gráficos para melhor entendimento dos dados.
- **Análise Estatística:** Cálculo de métricas estatísticas como média, mediana, desvio padrão, etc.
- **Estudo de Correlações:** Análise de correlações entre diferentes variáveis.
- **Operações Numéricas com NumPy:** Utilização de arrays e funções matemáticas para análise de dados.

## Ferramentas Utilizadas 🛠️

- **Python:** Linguagem de programação principal.
- **Pandas:** Biblioteca para manipulação de dados.
- **Matplotlib:** Biblioteca para visualização de dados.
- **Seaborn:** Biblioteca para visualização de dados baseada no Matplotlib.
- **NumPy:** Biblioteca para operações numéricas eficientes.

## Conclusões 📋

Através das análises realizadas, conseguimos identificar padrões e tendências nas notas dos filmes. Essas análises são fundamentais para entender o comportamento do público e a qualidade dos filmes.

## Autor 👨‍💻

- **Lenon Merlo**

Agradeço ao Prof. Guilherme Silveira e à Alura pelo excelente curso e pela oportunidade de aprimorar meus conhecimentos em Data Science.

## Exemplos de Gráficos Criados 📊

### Distribuição das Notas dos Filmes

```python
import pandas as pd
import seaborn as sns
import matplotlib.pyplot as plt
import numpy as np

# Carregar os dados
notas = pd.read_csv('notas.csv')

# Plotar a distribuição das notas
sns.histplot(notas['nota'], bins=10, kde=True)
plt.title('Distribuição das Notas dos Filmes')
plt.xlabel('Nota')
plt.ylabel('Frequência')
plt.show()

