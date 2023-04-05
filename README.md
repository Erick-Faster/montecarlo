# Simulação de filas com Monte Carlo 🎲
Este projeto realiza a simulação de filas de peças em uma linha de produção utilizando a técnica de Monte Carlo 🎲. Basicamente, a ideia é gerar dados aleatórios para o tempo de processamento e tempo entre chegadas de elementos na fila, e a partir daí calcular o tempo de espera em fila para cada simulação.

# Como funciona? 🤔
O código utiliza a biblioteca NumPy para gerar dados aleatórios baseados em uma distribuição normal. São definidos parâmetros como a média e o desvio padrão do tempo de processamento e do tempo entre chegadas. A partir desses parâmetros, o código simula o tempo de processamento e tempo entre chegadas para cada simulação.

Com base nesses dados, o código calcula o tempo de espera em fila 🕰️ para cada simulação. O tempo de espera em fila é o tempo que um elemento fica esperando na fila até ser processado.

# Por que Monte Carlo? 🤔
A técnica de Monte Carlo é muito útil em simulações em que não é possível obter uma solução exata ou quando essa solução é muito difícil de ser encontrada. Nesse caso, a técnica de Monte Carlo é utilizada para gerar dados aleatórios e simular o comportamento da fila.

# Como utilizar? 🤔
Basta executar o código em um ambiente Python com as bibliotecas NumPy, Pandas e Matplotlib instaladas. É possível ajustar os parâmetros do modelo, como a quantidade de simulações, a média e o desvio padrão do tempo de processamento e tempo entre chegadas, para obter diferentes resultados.

# Resultados 📈
O código calcula a média e o desvio padrão do tempo de espera em fila para todas as simulações. Esses resultados são apresentados ao final do script. Além disso, o resultado da simulação é apresentado em um gráfico que exibe o tempo de espera em fila em relação à posição na fila. O eixo x representa a posição da peça na fila e o eixo y representa o tempo de espera em segundos.