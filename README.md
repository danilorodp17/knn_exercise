# KNN Exercise
Este projeto consiste na implementação do algoritmo K-Nearest Neighbors (KNN) utilizando a linguagem Python. Ele foi desenvolvido como parte de um exercício prático para aplicar conceitos de classificação supervisionada em Machine Learning.

O algoritmo KNN é um método simples e eficiente que classifica dados com base na proximidade dos exemplos rotulados mais próximos. Ao receber uma nova entrada, ele calcula a distância (geralmente Euclidiana) entre esse novo ponto e os pontos já existentes no conjunto de dados, determinando a classe com base na maioria dos vizinhos mais próximos.

O projeto é composto por um script principal que executa a lógica do algoritmo, um arquivo de dados (dataset.csv) e um script de teste para verificar a funcionalidade da implementação.

Como executar
Clone o repositório:
bash
Copiar
Editar
git clone https://github.com/seu-usuario/knn_exercise.git
cd knn_exercise

Execute o script principal:
nginx
Copiar
Editar
python knn.py

Não é necessário instalar bibliotecas externas, pois o código utiliza apenas recursos nativos do Python.

Estrutura
knn.py: implementação do algoritmo KNN.
dataset.csv: conjunto de dados utilizado para os testes.
test_knn.py: script de teste do algoritmo.
