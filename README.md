## <div align="center">SoftRobots Manipulator Dataset</div>
<div align="center">SRM DATASET</div>

<div align="center">
<br>
Este dataset, é constituído de imagens referentes ao manipulador, que é utilizado como base de estudo para o desenvolvimento de modelos de IA. O intuito principal das imagens e anotações aqui presentes, é treinar modelos de segmentação semântica, com isso, as imagens presentes neste dataset foram extraídas de um video disponibilizado pela célula de robótica.

<br>

~ Dataset desenvolvido pelos bolsistas do projeto: Jessica Duarte, Matheus Carvalho e Thauan Oliveira ~
</div>

<br>
<br>
<br>

<details>
  <summary>Estrutura do dataset</summary>
  <p>O dataset é estruturado da seguinte forma</p>

    srm_dataset
    ├── README.md
    ├── README.txt
    ├── train_data
    ├──────images
    │       ├── images.jpg
    │       
    ├──────labels
    │       ├── annotations.json
    │       ├── classes.csv     
    │
    ├──────masks 
    │       ├── masks.png
    │           
<br>

</details>

<details>
  <summary>Tutorial de importação</summary>
  Antes de realizar a importação, é importante ressaltar que todo processo que está sendo realizado é levando em consideração a utilização do <a href="https://colab.research.google.com/?utm_source=scs-index">Google Collaboratory </a>. 

```bash
%cd /content

!git clone https://github.com/thauanoliveiraa/srm_dataset.git  # clonando o repositório onde o dataset está contido

%cd /content/srm_dataset/  #especificando o diretório

!git pull https://github.com/thauanoliveiraa/srm_dataset  #Atualizando nosso repositório local a partir do repositório remoto

%cd /content  
```
<br>


</details>

<details>
  <summary>Tutorial de divisão em treino e teste</summary>

</details>

<details>
<summary>Tutorial de treinamento</summary>



</details>
<br>

<div align="center">
<br>
v1.0

</div>













