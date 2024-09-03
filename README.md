# Projeto-ntrodu-o-ao-Processamento-Digital-de-Imagens

# Projeto de Processamento de Imagens RGB

Este projeto foi desenvolvido como parte de uma atividade acadêmica que visa implementar um sistema capaz de abrir, exibir, manipular e salvar imagens RGB com 24 bits/pixel (8 bits por componente). O objetivo principal é desenvolver algoritmos de processamento de imagens sem o uso de bibliotecas especializadas, como OpenCV ou PIL, permitindo um entendimento profundo dos conceitos fundamentais.

## Funcionalidades

1. **Correlação m x n com Offset**: 
   - Implementa a operação de correlação em imagens RGB usando filtros definidos pelo usuário, aplicados independentemente às bandas R, G e B. O filtro e o offset são especificados em um arquivo de configuração `.txt`.
   - Realiza testes com filtros comuns, como Gaussiano 5x5, Sobel horizontal e Sobel vertical, com extensão por zeros. Para o filtro Sobel, aplica-se valor absoluto seguido de uma expansão de histograma para uma visualização adequada.

2. **Filtro Pontual**:
   - Filtro aplicado diretamente aos valores RGB de cada pixel.
   - Filtro aplicado à banda Y do espaço de cores YIQ, com posterior conversão de volta para RGB.

## Estrutura do Projeto

- **Código Fonte**: Implementações desenvolvidas em [Linguagem de Programação Escolhida], incluindo manipulação de arquivos de imagem e operações de processamento de imagens.
- **Arquivo de Configuração**: Arquivo `.txt` que contém os filtros e offsets utilizados nas operações de correlação.
- **Relatório**: Documento PDF detalhando o processo de desenvolvimento, métodos utilizados, resultados obtidos e discussões sobre o desempenho dos algoritmos implementados.

## Objetivos

- Compreender e implementar operações básicas de processamento de imagens.
- Desenvolver um sistema que funcione de forma autônoma, sem depender de bibliotecas externas específicas de processamento de imagens.
- Realizar análises sobre o impacto de diferentes filtros no processamento de imagens.

---
