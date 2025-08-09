# TelecomX - Análise de Churn

Este projeto tem como objetivo analisar a evasão de clientes (churn) na empresa fictícia TelecomX, a partir de dados reais e abordagens de ciência de dados. Por meio da identificação de padrões de cancelamento, pretende-se propor estratégias eficazes de retenção que auxiliem a empresa a reduzir perdas e fortalecer a relação com seus clientes.

## Estrutura do Projeto

- `TelecomX_BR.ipynb`: Notebook principal com todo o fluxo de extração, transformação, análise e visualização dos dados.
- `TelecomX_Dados.csv`: Base de dados processada.
- `TelecomX_Dados_Limpos.csv`: Base de dados transformados e limpos.
- `TelecomX_dicionario.md`: Dicionário de dados com explicação de cada coluna.
- `README.md`: Este arquivo.

## Instalação

1. **Clone o repositório:**
   ```sh
   git clone <url-do-repositorio>
   cd telecom-x
   ```

2. **Crie um ambiente virtual (opcional, recomendado):**
   ```sh
   python -m venv venv
   source venv/bin/activate  # Linux/Mac
   venv\Scripts\activate     # Windows
   ```

3. **Instale as dependências:**
   ```sh
   pip install pandas matplotlib seaborn
   ```

## Como Executar

1. Abra o arquivo [`TelecomX_BR.ipynb`](TelecomX_BR.ipynb) no Jupyter Notebook ou no Visual Studio Code.
2. Execute as células sequencialmente para realizar a extração, transformação, análise e visualizar os gráficos.
3. O arquivo [`TelecomX_Dados.csv`](TelecomX_Dados.csv) será gerado automaticamente durante o processo, assim como o arquivo [`TelecomX_Dados_Limpos.csv`](TelecomX_Dados_Limpos.csv)

## Dependências

- Python 3.7+
- pandas
- matplotlib
- seaborn

## Dicionário de Dados

Consulte [`TelecomX_dicionario.md`](TelecomX_dicionario.md) para detalhes sobre cada coluna do dataset.
