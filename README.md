# Aprendizado Supervisionado no Neurônio Perceptron

Neste repositório você encontrará as atividades referentes à Atividade Avaliativa 2.1:  Aprendizado Supervisionado no Neurônio Perceptron, da disciplina Redes Neurais Artificiais ministrada pela professora Dra. Elloá B. Guedes, no curso de Sistemas de Informação da Escola Superior de Tecnologia (EST) da Universidade do Estado do Amazonas(UEA). 

## Equipe responsável: 
- [Ícaro Pereira](https://github.com/icarosun)
- [Jesus Dourado](https://github.com/jesusdourado)
- [Luiz Barros](https://github.com/LuizHenrique-BS)
- [Willians Oliveira](https://github.com/willianszwy)

## Resumo

Nesse projeto foi implementado o algoritmo de treinamento do neurônio Perceptron de Rosenblatt mediante aprendizado supervisionado. Para isso foram utilizadas as bibliotecas Numpy, Datatime, Matplotlib e Random.

### Parte 1

Na primeira parte do projeto é realizada a implementação do algortimo e o mesmo é utilizado para a resolução de um problema linearmente separável. Os dados usados nessa etapa para o treinamento estão contidos no arquivo *dataAll.txt*

### Parte 2 

Nesta segunda etapa, usando o arquivo *data1.txt*, o Neurônio Perceptron implementado na primeira parte é utilizado para testar 6 possibilidades distintas resultantes das combinações de três taxas de aprendizado (0.4, 0.1, 0.01) com dois intervalos de pesos {(-100, 100), (-0.5, 0.5)}. Cada configuração é testada por 10 iterações.

### Parte 3

O arquivo *dataHoldout.txt* contém dados de um problema Não-Linearmente Separável que são utilizados para treinamento do Neurônio nessa etapa. Esses dados foram divididos aleatoriamente em duas partições, uma para treinamento que corresponde a 70% desse conjunto, e outra para teste equivalente a 30%. O Neurônio foi treinado por 100 épocas para responder e evidenciar as questões levantadas nessa parte do experimento.

## Referências

1. Python 3.10.0 Documentation. https://docs.python.org/3/. Acessado 27 de outubro de 2021
2. Matplotlib 3.4.3 documentation. https://matplotlib.org/. Acessado 27 de outubro de 2021.
3. NumPy Documentation. https://numpy.org/doc/. Acessado 27 de outubro de 2021.
4. Seaborn: Statistical Data Visualization. https://seaborn.pydata.org/. Acessado 27 de outubro de 2021.
