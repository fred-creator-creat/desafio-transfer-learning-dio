🐾 Classificador de Imagens: Gatos vs Cachorros (Transfer Learning)

<p align="center">
<img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" alt="TensorFlow" />
<img src="https://www.google.com/search?q=https://img.shields.io/badge/Python-3776AB%3Fstyle%3Dfor-the-badge%26logo%3Dpython%26logoColor%3Dwhite" alt="Python" />
<img src="https://www.google.com/search?q=https://img.shields.io/badge/Google_Colab-F9AB00%3Fstyle%3Dfor-the-badge%26logo%3Dgooglecolab%26logoColor%3Dwhite" alt="Google Colab" />
<img src="https://www.google.com/search?q=https://img.shields.io/badge/Status-Conclu%C3%ADdo-4c1%3Fstyle%3Dfor-the-badge" alt="Status" />
</p>

📖 Sobre o Projeto

Este projeto foi desenvolvido para o desafio de Transfer Learning da trilha de IA da DIO (Digital Innovation One). O objetivo foi criar uma solução de Visão Computacional de alta precisão capaz de diferenciar felinos de caninos em imagens digitais.

Diferente do treinamento tradicional, este projeto utiliza a técnica de Transferência de Aprendizado, permitindo alcançar resultados de nível industrial com baixo custo computacional e tempo reduzido.

🧠 Arquitetura do Modelo

A base deste projeto é a rede neural MobileNetV2, uma arquitetura otimizada para dispositivos móveis, pré-treinada no gigante dataset ImageNet.

Feature Extractor: MobileNetV2 (Pesos congelados).

Classifier: Camada de Global Average Pooling + Camada Densa Final (Neurônio único).

Otimizador: RMSprop com taxa de aprendizado de $0.0001$.

Função de Perda: Binary Cross-Entropy.

🚀 Performance e Resultados

Graças ao uso da GPU T4 no Google Colab, o treinamento foi extremamente eficiente.

Métrica

Resultado Obtido

Acurácia (Treino)

~98.5%

Acurácia (Validação)

~98.7%

Tempo por Época

~2 minutos

Taxa de Acerto Visual

100% (Amostras de Teste)

🛠️ Tecnologias e Ferramentas

Deep Learning: TensorFlow 2.x & Keras

Processamento de Dados: TensorFlow Datasets

Visualização: Matplotlib

Dataset: cats_vs_dogs (Milhares de imagens reais)

📂 Como Utilizar este Repositório

1. Execução no Colab

Você pode rodar este projeto diretamente no seu navegador clicando no botão abaixo:

Nota: Certifique-se de ativar a GPU em Ambiente de Execução > Alterar tipo de ambiente de execução.

2. O Modelo Salvo

O arquivo meu_modelo_gatos_caes.h5 gerado pode ser carregado em aplicações futuras ou sites web para fazer previsões em tempo real.

🎯 Conclusão

Este projeto demonstra como o Transfer Learning é uma ferramenta poderosa na caixa de ferramentas de um cientista de dados, permitindo que modelos complexos sejam adaptados para problemas específicos com precisão cirúrgica.

<p align="center">
Desenvolvido com ❤️ por <strong>Fred</strong> durante o Bootcamp de IA da <strong>DIO</strong>.
</p>
