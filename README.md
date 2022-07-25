# Introdução às Redes Convolucionais

Nesse notebook vamos experimentar criar uma rede neural convolucional para classificar dados de uma série temporal de uma única variável. A base de dados que vamos usar se chama _GunPoint_. Dois voluntários participaram na geração desses dados. Eles estavam em pé e foram filmados de lado enquando faziam uma de duas possíveis ações: (1) sacar uma arma e apontar para frente, ou (2) simplesmente levantar o braço e apontar com o dedo para frente. Durante o gesto foi rastreada a posição $x,y$ da mão do ator, mas na base de dados foi registrada apenas a variável $x$. O problema consiste em, a partir apenas desse dado da posição da mão no eixo horizontal ao longo do tempo (variável $x$ como série temporal), tentar determinar se o ator estava sacando uma arma e apontando ela, ou apenas apontando com o dedo.

<img src="https://drive.google.com/uc?id=1fZ5j2rZDVyqBkqs66S4R-LqTIfdhbqD2" width="500"/>
