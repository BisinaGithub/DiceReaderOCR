# 🎲 DiceReaderOCR

**DiceReaderOCR** é um projeto de pesquisa com foco no reconhecimento automático de valores em dados físicos utilizados em jogos de RPG, como d4, d6, d8, d10, d12 e d20.  
O sistema utiliza **visão computacional** e **redes neurais convolucionais (CNNs)** para classificar os valores visíveis nas faces superiores dos dados a partir de imagens previamente capturadas.

Este projeto faz parte de um Trabalho de Conclusão de Curso (TCC) em Engenharia da Computação, buscando investigar a viabilidade técnica do uso de **aprendizado profundo** para otimizar o tempo de leitura e somatório de dados físicos em sessões de RPG, sem comprometer a experiência tradicional do jogo.

---

## 📌 Funcionalidades

- ✅ Reconhecimento multiclasse dos valores de 0 a 9 em dados físicos
- ✅ Pré-processamento de imagens com corte e limpeza de fundo
- ✅ Organização automática do dataset em treino/validação por valor
- ✅ Suporte a diferentes ângulos e tipos de dado (ex: d6, d10, d12)
- ✅ Treinamento e avaliação de uma CNN customizada usando TensorFlow/Keras

---

## 🚀 Tecnologias Utilizadas

- [Python 3.10+](https://www.python.org/)
- [TensorFlow / Keras](https://www.tensorflow.org/)
- [OpenCV](https://opencv.org/) – para corte e ajuste de imagens
- [Matplotlib](https://matplotlib.org/) – para visualização de amostras

---

## 📁 Estrutura do Projeto
projeto-tcc/
├── data/
│ ├── raw/ # Imagens brutas organizadas por valor/tipo de dado
│ ├── processed/ # Imagens tratadas com corte e limpeza
├── docs/
│ ├── monografia/ # Arquivos .tex, .bib e PDF da monografia
│ │  ├── build/ # Arquivo compilado do trabalho em PDF
│ │  ├── figuras/ # Imagens utilizadas na monografia
├── notebooks/ # Local onde o código está, tanto para o teste de caes e gatos quanto o de dados
├── requirements.txt  # Arquivo que cita as versões das dependencias utilizadas
└── README.md

---

## 📌 Status do Projeto

Este repositório está em desenvolvimento ativo como parte de um TCC.
Atualmente, a fase de coleta, tratamento e categorização de imagens foi concluída, e os experimentos com modelos convolucionais estão em fase de avaliação.

---

## 📷 Créditos das Imagens
As imagens utilizadas para treinamento foram gentilmente capturadas por Danielly Vitória Rodrigues, fotógrafa de estúdio, especialmente para este projeto. Seu apoio foi fundamental para garantir a qualidade visual do dataset.

---

## 📬 Contato
Para mais informações sobre o projeto, dúvidas ou contribuições, entre em contato:
📧 vini.bisin@gmail.com