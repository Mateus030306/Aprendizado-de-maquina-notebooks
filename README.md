# Aprendizado-de-maquina-notebooks
Os notebooks guardados aqui são atividades passadas na disciplina de aprendizado de máquina, comparações entre a implementação bruta ensinada em sala e a implementação de bibliotecas de mercado como scikit learn e pytorch.
# Modelos utilizados
## Regressão linear múltipla
O modelo de regressão linear múltipla é o modelo inicial mais intuitivo na área de ML, a implementação foi feita utilizando o gradiente descendente simples e posteriormente comparando com a implementação usada no scikit learn, que utiliza o gradiente descendente estocástico. Também foi feita uma implementação utilizando os tensores da biblioteca pytorch. Gráficos e demais visualizações se encontram nos finais de seção do notebook. Foram testados diferentes learning rates e datasets.
## K-vizinhos mais próximos
O modelo do k-vizinhos mais próximos é um modelo não paramétrico bastante intuitivo e simples, a implementação foi feita considerando a distância euclidiana (ou a norma, no caso de vetores num espaço n-dimensional) e também comparando com a implementação feita pelo scikit-learn. Foram testados diferentes valores de k em diferentes datasets.
