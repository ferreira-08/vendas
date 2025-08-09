# 📊 Sistema de Análise de Vendas

Este projeto realiza uma análise de dados de vendas a partir de uma planilha Excel (`Vendas.xlsx`) utilizando a biblioteca **Pandas**. Ele calcula o faturamento total, o faturamento por loja e o faturamento por produto dentro de cada loja.

## 🧰 Tecnologias Utilizadas

- Python 3.x
- Pandas
- Jupyter Notebook (opcional)
- Excel (.xlsx)

## 📦 Funcionalidades

- Importação de dados de vendas
- Cálculo do faturamento total
- Análise de faturamento por loja
- Detalhamento do faturamento por produto em cada loja

## 📁 Estrutura do Projeto
vendas/ 
├── vendas.py 
├──Vendas.xlsx 


## ▶️ Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/ferreira-08/vendas.git
   cd vendas
pip install pandas
Certifique-se de que o arquivo Vendas.xlsx está na mesma pasta que o script.

Execute o script:
python vendas.py

##📈 Exemplo de Saída

# Faturamento total
125000.00

# Faturamento por loja
ID Loja
Loja A    45000.00
Loja B    80000.00

# Faturamento por produto
ID Loja  Produto
Loja A   Produto X    30000.00
         Produto Y    15000.00
...



