# P-s-Tech
Perguntas CRISP-D
Entendimento do Negócio: O foco é identificar clientes de telecomunicações que podem cancelar o serviço (Churn). O objetivo técnico é criar uma Rede Neural MLP que ajude a empresa a agir antes da perda do cliente.

Entendimento dos Dados: Analisaremos um dataset com mais de 5.000 registos. Faremos uma Análise Exploratória (EDA) para entender quais características (como valor da fatura ou tempo de contrato) mais influenciam o cancelamento.

Preparação dos Dados: Limpeza de dados nulos e transformação de categorias em números. Usaremos pipelines e validação cruzada para garantir que os dados estejam prontos e equilibrados para o treino da IA.

Modelação: Criaremos modelos base (baselines) simples e o modelo principal em PyTorch (Rede Neural). Usaremos o MLflow para registar e comparar o desempenho de cada tentativa.

Avaliação: Compararemos os modelos através de métricas como AUC-ROC e F1-Score. O objetivo é garantir que o modelo não só acerta muito, mas que é financeiramente viável para a operadora.

Implantação: O projeto será organizado no GitHub e o modelo será servido através de uma API (FastAPI), permitindo que outros sistemas consultem as previsões de Churn em tempo real.
