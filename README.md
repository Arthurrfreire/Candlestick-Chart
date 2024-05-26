# Visualização de Gráfico de Candlestick de Ações

Este projeto Python permite visualizar gráficos de candlestick de ações usando as bibliotecas `yfinance` para obter dados financeiros e `mplfinance` para criar o gráfico.

## Estrutura do Projeto

- `README.md`: Este arquivo de documentação.
- `candlestick_chart.py`: Script Python que contém o código para gerar o gráfico.

## Dependências

Certifique-se de ter as seguintes bibliotecas Python instaladas:

- `yfinance` (para obter dados financeiros)
- `mplfinance` (para criar gráficos financeiros)

**Você pode instalá-las usando `pip`:**
  
    pip install yfinance mplfinance

## Como Usar

  Execute o script:
        Abra seu terminal e navegue até o diretório onde o script `candlestick_chart.py` está salvo.
        Execute o seguinte comando:
    
    python candlestick_chart.py

  **Insira o nome da ação:**
        O script solicitará que você digite o símbolo da ação (por exemplo, AAPL para Apple, GOOGL para Google, etc.).
        Digite o símbolo e pressione Enter.

  **Visualize o gráfico:**
        O script irá baixar os dados da ação para o período entre 1º de janeiro de 2022 e 13 de abril de 2024.
        Um gráfico de candlestick será exibido, mostrando a variação de preço da ação ao longo do tempo.

## Observações
* O estilo do gráfico é definido como 'yahoo', mas você pode personalizá-lo consultando a documentação do `mplfinance`.
  
* Certifique-se de ter uma conexão com a internet para que o `yfinance` possa baixar os dados da ação.
  
* O script está configurado para um intervalo de datas específico, mas você pode alterá-lo nas linhas 4 e 5 do código.

## Exemplo
   
    python candlestick_chart.py
    Enter Stock Name : AAPL 

Isso irá gerar um gráfico de candlestick para a ação da Apple.

**Observação:** Este projeto é apenas para fins educacionais e informativos. As informações fornecidas não constituem aconselhamento financeiro.
