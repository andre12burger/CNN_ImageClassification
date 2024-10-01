# Classificação de Imagens Usando Modelos de Redes Neurais Convolucionais com PyTorch

Este projeto tem como objetivo explorar três abordagens de classificação de imagens usando CNNs com PyTorch: 

  - Treinamento de uma rede do zero.
  - Uso de uma rede pré-treinada sem ajustes.
  - Fine-tuning de uma rede pré-treinada.
    
O dataset utilizado será o CIFAR-10, e as redes serão avaliadas com métricas como accuracy, precision, recall e F1-score.

## Índice
- [Uso](#uso)
- [GIT](#GIT)

## Uso
Explicação de como atualizar o projeto:
1. Google colab

Os modelos criados por cada usuário serão hospedados em um ambiente colab.
Para atualizar esse repositório, deverão fazer o dowload da versão mais atualizada do arquivo 'ipynb' (quando houver mudança), e atualizar o arquivo usando a ferramenta GIT, seguindo o passo a passo, para que não haja incompatibilidade com versionamento e arquivos.
Além de poderem fixar no arquivo README.md os links de cada usuário de seus ambientes colab para estar sempre com a última versão do código.

### *MODELOS USADOS*

| Membro       | Modelo       | Link colab   |
|--------------|--------------|--------------|
| André        | ResNet       | [Colab André](https://colab.research.google.com/drive/1khViGNQdiuodyo981-JIzwcZ7LP9O1nH?authuser=2#scrollTo=zBfedif5NrgL)|
| Membro 2     | Faz Y        | Não          |

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










