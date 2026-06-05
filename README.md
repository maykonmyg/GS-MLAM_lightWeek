<img width="1312" height="488" alt="image" src="https://github.com/user-attachments/assets/0f3517bc-bb57-400c-8573-44c0dff0bf47" />

# 🚀 Global Solution - Análise de Dados Espaciais

Este repositório contém o projeto de análise estatística descritiva desenvolvido para a avaliação da Global Solution. O objetivo do projeto é analisar padrões da nova economia espacial utilizando dados reais da base **UCS Satellite Database**.

## 🎯 Objetivo do Projeto
Transformar dados brutos em informações úteis para apoio à tomada de decisão no setor aeroespacial, aplicando conceitos de estatística descritiva, análise exploratória e visualização de dados.

## 🛠️ Tecnologias Utilizadas
* **Python 3**
* **Pandas** (Manipulação e estruturação dos dados)
* **NumPy** (Cálculos numéricos)
* **Matplotlib & Seaborn** (Criação de gráficos estatísticos)
* **Jupyter Notebook / Google Colab** (Ambiente de desenvolvimento)

## 📊 Funcionalidades do Código
O arquivo `Gs-MLAMcode.ipynb` realiza as seguintes operações:
1. **Limpeza e Estruturação:** Trata os dados do arquivo CSV e define as variáveis de estudo (Ano de Lançamento como discreta; Massa em kg como contínua).
2. **Tabelas de Frequência:** Gera tabelas de distribuição contendo frequência absoluta (fi), relativa (fi%) e acumulada (Fi).
3. **Visualização de Dados:** Constrói um Histograma para analisar a distribuição de peso dos satélites e um Gráfico de Barras para visualizar a evolução dos lançamentos ao longo dos anos.
4. **Estatística Descritiva:** Calcula automaticamente:
   * **Tendência Central:** Média, Mediana e Moda.
   * **Dispersão:** Mínimo, Máximo, Amplitude, Variância e Desvio Padrão.
   * **Separatrizes:** Quartis (Q1, Q2/Mediana, Q3).

## 🚀 Como Executar o Projeto
1. Clone este repositório ou faça o download dos arquivos `Gs-MLAMcode.ipynb` e `UCS_Satellite_Database_12-1-2018-1.csv`.
2. Acesse o [Google Colab](https://colab.research.google.com/).
3. Vá em **Arquivo > Fazer upload de notebook** e envie o arquivo `.ipynb`.
4. No menu lateral esquerdo do Colab (ícone de pasta), faça o upload do arquivo `.csv`.
5. Execute as células do notebook de cima para baixo.

## 👥 Integrantes
* Felipe Pereira Restivo - RM: 570712
* Maykon de Lima Silva – RM: 574022
* Gabriel Rodrigues Zappelloni - RM: 572060
