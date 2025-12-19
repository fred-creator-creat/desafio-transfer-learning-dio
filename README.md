Classificação de Gatos e Cachorros com Transfer Learning 🐾

Este projeto foi desenvolvido como parte do desafio de Transfer Learning da DIO (Digital Innovation One). O objetivo foi criar uma Inteligência Artificial capaz de distinguir entre imagens de gatos e cachorros utilizando redes neurais profundas.

🚀 Tecnologias Utilizadas

Python: Linguagem principal.

TensorFlow / Keras: Frameworks de Deep Learning.

MobileNetV2: Modelo base pré-treinado utilizado para Transfer Learning.

Google Colab: Ambiente de desenvolvimento com suporte a GPU T4.

🧠 Como o Projeto Funciona

Em vez de treinar uma rede do zero (o que levaria dias), utilizei o conceito de Transfer Learning. Aproveitei o conhecimento da rede MobileNetV2, que já foi treinada em milhões de imagens, e "re-ensinei" apenas a camada final para focar na diferença específica entre felinos e caninos.

📈 Resultados Alcançados

Acurácia Final: ~98.7%

Tempo de Treinamento: Reduzido drasticamente de 1 hora para menos de 10 minutos com o uso de GPU.

Performance: A IA demonstrou 100% de acerto nas amostras visuais de teste após 3 épocas de ajuste.

🛠️ Como rodar o projeto

Abra o arquivo .ipynb no Google Colab.

Ative o acelerador de hardware para GPU T4.

Execute as células em ordem (Passos 1 ao 7).

O modelo treinado será salvo como meu_modelo_gatos_caes.h5.

Desenvolvido por Fred durante o bootcamp de IA da DIO.
