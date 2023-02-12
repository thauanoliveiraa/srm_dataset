#SoftRobots Manipulator Dataset

Este dataset, é constituído de imagens referentes ao manipulador, que é utilizado como base de estudo para o desenvolvimento de modelos de IA. O intuito principal das imagens e anotações aqui presentes, é treinar modelos de segmentação semântica, com isso, as imagens presentes neste dataset foram extraídas de um video disponibilizado pela célula de robótica.
 
Dataset desenvolvido pelos bolsistas do projeto: Jessica Duarte, Matheus Carvalho e Thauan Oliveira



#Estrutura do dataset

O dataset é estruturado da seguinte forma

srm_dataset
├── README.md
├── README.txt
├── train_data
├──────images
│       ├── images.jpg
│       
├──────labels
│       ├── annotations.json
│       ├── classes.csv     
│
├──────masks 
│       ├── masks.png
│           



#Tutorial de importação

Antes de realizar a importação, é importante ressaltar que todo processo que está sendo realizado é levando em consideração a utilização do Google Collaboratory .

%cd /content

!git clone https://github.com/thauanoliveiraa/srm_dataset.git  # clonando o repositório onde o dataset está contido

%cd /content/srm_dataset/  #especificando o diretório

!git pull https://github.com/thauanoliveiraa/srm_dataset  #Atualizando nosso repositório local a partir do repositório remoto

%cd /content  



#Tutorial de divisão em treino e teste



#Tutorial de treinamento



#v1.0