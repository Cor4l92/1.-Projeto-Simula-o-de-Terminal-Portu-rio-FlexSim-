# Análise de Simulação de Terminal Portuário

Este projeto foi desenvolvido como um desafio técnico para a vaga de **Analista de Simulação**, utilizando o software FlexSim.

## 🎯 Objetivo

[cite_start]O objetivo foi construir e analisar um modelo de simulação para a operação de um terminal portuário ao longo de um ano (8.760 horas)[cite: 4]. [cite_start]A meta era avaliar os principais indicadores de desempenho do sistema para identificar sua viabilidade e possíveis gargalos[cite: 5].

## 🛠️ Parâmetros e Ferramentas

* **Software:** FlexSim
* [cite_start]**Tempo de Simulação:** 8.760 horas [cite: 4]
* [cite_start]**Fluxo de Chegada de Navios:** Distribuição Exponencial, com tempo médio de 8 horas entre chegadas[cite: 6].
* [cite_start]**Tempo de Serviço (Descarregamento):** Distribuição Triangular, com mínimo de 3 horas, moda de 5 horas e máximo de 10 horas[cite: 7, 8].

## 📊 Análise e Resultados Chave

[cite_start]A simulação revelou que o sistema opera em um estado de **sobrecarga crítica e instabilidade**[cite: 28]. Os principais indicadores foram:

* [cite_start]**Taxa de Ocupação do Porto:** 100% [cite: 24, 29]
* [cite_start]**Tamanho Médio da Fila:** 1.000 navios [cite: 25]
* [cite_start]**Tempo Médio de Espera na Fila:** 3.771,80 horas (aproximadamente 157 dias) [cite: 26, 30, 31]

## 💡 Conclusão e Recomendações

[cite_start]Conclui-se que o porto é um **gargalo severo** e sua capacidade de atendimento é insuficiente para a demanda atual[cite: 29, 32]. [cite_start]A fila de espera cresce de forma contínua, tornando a operação logisticamente inviável[cite: 30, 31].

[cite_start]**Recomendação Principal:** Seria imprescindível realizar investimentos para aumentar a capacidade do sistema, como a **adição de um novo berço de atracação** ou a otimização dos processos para reduzir o tempo de descarregamento[cite: 33].
