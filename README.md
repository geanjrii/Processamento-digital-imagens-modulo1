# Introdução ao Processamento Digital de Imagens
Este projeto é referente ao Módulo 1 do Trabalho Prático da disciplina de Processamento Digital de Imagens, ministrada pelo Professor Leonardo. O objetivo deste trabalho é desenvolver um sistema em uma linguagem de programação de escolha do aluno para abrir, exibir, manipular e salvar imagens RGB com 24 bits/pixel (8 bits/componente/pixel). É importante salientar que não é permitido o uso de bibliotecas ou funções especiais de processamento de imagens, exceto no item 5.

## Funcionalidades do sistema
O sistema deve possuir as seguintes funcionalidades:

1. Conversão RGB-YIQ-RGB (cuidado com os limites de R, G e B na volta!).
2. Negativo. Duas formas de aplicação devem ser testadas: em RGB (banda a banda) e na banda Y, com posterior conversão para RGB.
3. Correlação m x n sobre R, G e B, com offset, e filtro e pivô definidos em um arquivo (txt) a parte. Testar com filtros Média e Sobel horizontal e vertical, e explicar os resultados. Para visualização do resultado do Sobel, utilize valor absoluto seguido por expansão de histograma para [0, 255].
4. Filtro mediana m x n, com m e n ímpares, sobre a banda Y do YIQ.
5. Reproduzir o exemplo em https://la.mathworks.com/help/images/ref/normxcorr2.html?lang=en, com as imagens woman.png e woman_eye.png. Após localizar a região de correlação máxima, repetir a busca excluindo essa região, de modo a localizar a segunda região mais correlacionada com a máscara. É permitido o uso de todas as funcionalidades da linguagem de programação escolhida, incluindo bibliotecas avançadas. Para visualização, utilize valor absoluto seguido por expansão de histograma para [0, 255].

## Data de entrega
A entrega do projeto está prevista para o dia 27/04/2022.
