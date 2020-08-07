# Repositorio da Disciplina de Redes Neurais Artificiais do curso de Pós Graduação da Unifacisa em Ciência de Dados, cuja matéria foi lecionada pelo professor Bruno Gama Catão. 


Requisitos
Antes de iniciarmos com a análise, será necessário efetuar o download:

Python 3.7
Anaconda
Jupyter Notebook
Efetuar download da base de dados no Kaggle: https://www.kaggle.com/c/dogs-vs-cats-redux-kernels-edition/data

Passo a passo para instalação:

Necessário abrir anaconda prompt (anaconda3) e executar esses comandos:

pip install tflearn
pip install tensorflow==1.15
pip install tqdm
As imagens são de cachorro (s) ou gato (s).

Iremos analisar e classificar as imagens que já foram rotuladas, posteriormente iremos alimentar através de uma rede neural convolucional para classificação.

Depois de baixar e extrair os dados, estaremos prontos para começar.

Primeiro, precisamos que todas as imagens tenham o mesmo tamanho e, em seguida, provavelmente também queremos apenas colocá-las em escala de cinza. Além disso, os rótulos de "gato" e "cachorro" não são úteis, queremos que sejam matrizes de uma só peça.
