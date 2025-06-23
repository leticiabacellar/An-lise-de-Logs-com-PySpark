# ⚡ Análise de Logs com PySpark

Este projeto utiliza o poder do **Apache Spark com PySpark** para processar e analisar grandes volumes de dados de log, demonstrando técnicas fundamentais de **ETL distribuído** e análise de comportamento de usuários com dados não estruturados.

---

## 🎯 Objetivo

Realizar uma análise eficiente de arquivos de log utilizando **PySpark**, com foco em:

- Processamento em larga escala
- Limpeza e transformação dos dados
- Extração de insights relevantes
- Exportação dos resultados para CSV

---

## 🛠️ Tecnologias e Bibliotecas

- Python 3.x
- Apache Spark (via PySpark)
- Google Colab / Jupyter Notebook
- Pandas (para validações finais)
- CSV como formato de entrada e saída

---

## 🗂️ Estrutura do Projeto

- `Análise de Logs com PySpark.ipynb` – Notebook principal com o pipeline completo.
- `/data/logs.csv` – Arquivo de log de exemplo (pode ser substituído por logs reais).
- `/output/` – Pasta onde os resultados processados são exportados como CSV.

---

## 📌 Etapas da Análise

1. **Leitura dos Dados**
   - Importação do arquivo de log em CSV com Spark.

2. **Limpeza e Pré-processamento**
   - Remoção de valores nulos ou inválidos
   - Conversão de tipos e datas

3. **Análises Realizadas**
   - 📅 Quantidade de acessos por dia
   - 📄 Top páginas mais acessadas
   - 📍 Agrupamentos por IP, data e rota

4. **Exportação de Resultados**
   - Salvando os resultados em formato `.csv` com particionamento se necessário

---

## 📊 Exemplos de Resultados

- **Top páginas acessadas:**
  ```plaintext
  /home
  /login
  /produtos
