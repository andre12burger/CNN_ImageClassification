# Classificação de Imagens Usando Modelos de Redes Neurais Convolucionais com PyTorch

Este projeto tem como objetivo explorar três abordagens de classificação de imagens usando CNNs com PyTorch: 

  - Treinamento de uma rede do zero.
  - Uso de uma rede pré-treinada sem ajustes.
  - Fine-tuning de uma rede pré-treinada.
    
O dataset utilizado será o CIFAR-10, e as redes serão avaliadas com métricas como accuracy, precision, recall e F1-score.

## Índice
- [Modelos e Dataset](#modelos-e-dataset)
- [Estrutura do Projeto](#estrutura-do-projeto)
- [GIT](#GIT)

## Modelos e Dataset

### Dataset (**[CIFAR-10](https://pytorch.org/vision/stable/generated/torchvision.datasets.CIFAR10.html)**)
O CIFAR-10 (Canadian Institute For Advanced Research) é um conjunto de dados utilizado em tarefas de classificação de imagens e treinamento de modelos de aprendizado de máquina. Ele consiste em:

- **10 classes**: avião, automóvel, pássaro, gato, cervo, cachorro, sapo, cavalo, navio e caminhão.
- **60.000 imagens coloridas**, de 32x32 pixels.
  - **50.000 imagens** no conjunto de treinamento.
  - **10.000 imagens** no conjunto de teste.
- As imagens estão em formato **RGB**, e cada uma é associada a um rótulo de classe correspondente.
- As classes são mutuamente exclusivas e não possuem sobreposição entre as categorias.

Amostra de imgens CIFAR-10:

![imagens](images/cifar10_classes.png)


### MODELOS USADOS

| Membro       | Modelo       | Link colab   | Arquivo local |
|--------------|--------------|--------------|--------------|
| André Burger | ResNet | [Resnet Colab](https://colab.research.google.com/drive/1vvgenxL3_dBnvHvz9I-usvjb8H_G5t02](https://github.com/andre12burger/CNN_ImageClassification/tree/main))| [Resnet Notebook](notebooks/Andre_CNN_ImageClassification.ipynb) |
| Lucas Soares | Inception v3 | [Inception Colab](https://colab.research.google.com/drive/1hktJRINsbrDC2DUcVl4zQ8c4iNNBvc9x?authuser=1) | - |
| Pedro Flores | MaxVit | [MaxVit Colab](https://colab.research.google.com/drive/1Yfw5a8teZmHW33w4MfSsCCUnkSreMIMX?usp=sharing) | - |

## Estrutura do Projeto
Cada modelo foi treinado e inferido em uma estrutura padronizada, esse processo foi repetido para as três versões do mesmo modelo:
  - Treinamento de uma rede do zero.
  - Uso de uma rede pré-treinada sem ajustes.
  - Fine-tuning de uma rede pré-treinada.

### Estrutura
1. Download do dataset
2. Plotagem de imagens do dataset
3. Modelos, critérios e otimizadores das redes
4. Treino das redes
5. Plotagem das métricas de avaliação das redes

## GIT
Passo a passo de como usar os comandos de GIT para trabalhar em grupo no projeto.

1. Clone o repositório.
   
Cada participante deve clonar o repositório em sua máquina local:
```bash
git clone https://github.com/webdepp1/CNN_ImageClassification
```

2. Criar uma Branch para trabalhar.

Cada participante deve criar uma nova branch para trabalhar em suas alterações:
```bash
git checkout -b nome-da-sua-branch
```

3. Fazer alterações e commit.

Após realizar as alterações no código:
```bash
git add .
git commit -m "Descrição das mudanças feitas"
```

4. Sincronizar com o Repositório Remoto.

Antes de enviar suas alterações, é importante garantir que a branch principal (geralmente chamada de *main* ou *master*) esteja atualizada:
```bash
git checkout main
git pull origin main
git checkout nome-da-sua-branch
```

5. Mesclar Atualizações da Branch Principal.

Se houver atualizações na branch principal, você deve mesclá-las na sua branch:
```bash
git merge main
```

6. Enviar suas Alterações para o GitHub.

Agora, envie suas alterações para o repositório remoto:
```bash
git push origin nome-da-sua-branch
```

7. Atualizar a Branch Principal Localmente.

Após a mesclagem, atualize sua cópia local da branch principal:
```bash
git checkout main
git pull origin main
```

8. Remover a Branch Local.

Depois que suas alterações forem mescladas, você pode remover a branch localmente:
```bash
git branch -d nome-da-sua-branch
```

9. Repetir o processo.

Os participantes podem repetir esses passos para novas funcionalidades ou correções.










