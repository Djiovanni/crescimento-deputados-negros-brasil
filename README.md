# Análise de Dados: A cor da política: raça, representação e interseccionalidade no Legislativo

Este repositório contém o script de análise de dados (em formato Jupyter Notebook) utilizado no "Capítulo 2 – A cor da política: raça, representação e interseccionalidade no Legislativo", de autoria de Djiovanni Jonas França Marioto.

O capítulo faz parte do livro *A classe política do Brasil: poder, representação e desigualdade Sumário*, organizado pelos pesquisadores Prof. Dr. Adriano Codato e Prof. Dr. Nilton Sainz.

## 🎯 Objetivo da Análise

O script tem como objetivo analisar os dados dos deputados federais brasileiros a partir de 2014, buscando:

1.  Identificar se há uma tendência de crescimento na proporção de deputados pretos e pardos eleitos para a Câmara dos Deputados ao longo das três legislaturas analisadas.
2.  Identificar e comparar o perfil sociopolítico dos deputados federais pretos e pardos com o dos parlamentares brancos.

A disponibilização deste código visa promover a transparência e a reprodutibilidade da pesquisa.

## 💾 Fonte dos Dados

O conjunto de dados utilizado nesta análise não está incluído neste repositório. O banco de dados foi compilado pelo autor e pode ser solicitado diretamente através do e-mail: **djiovannimarioto@gmail.com**.

## 🚀 Como Rodar este Projeto

Para replicar a análise, siga os passos abaixo.

### 1. Pré-requisitos

* [Git](https://git-scm.com/)
* [Python 3.9+](https://www.python.org/downloads/)
* (Opcional, mas recomendado) [Anaconda](https://www.anaconda.com/download) ou [Miniconda](https://docs.conda.io/en/latest/miniconda.html) para gerenciamento de ambientes.

### 2. Clonar o Repositório

Abra seu terminal e clone este repositório para sua máquina local:

```bash
git clone [https://github.com/SEU-USUARIO/NOME-DO-REPOSITORIO.git](https://github.com/SEU-USUARIO/NOME-DO-REPOSITORIO.git)
cd NOME-DO-REPOSITORIO
```
(Lembre-se de trocar SEU-USUARIO e NOME-DO-REPOSITORIO pela URL real do seu projeto)

### 3. Criar um Ambiente Virtual (Recomendado)

É uma boa prática criar um ambiente virtual isolado para este projeto, garantindo que as versões das bibliotecas sejam as corretas.

Com venv (padrão do Python):

```Bash
# Criar o ambiente
python3 -m venv venv
# Ativar o ambiente (macOS/Linux)
source venv/bin/activate
# Ativar o ambiente (Windows)
.\venv\Scripts\activate
```

Com Conda:

```Bash
# Criar o ambiente
conda create -n politica-cor python=3.10
# Ativar o ambiente
conda activate politica-cor
```


### 4. Instalar as Dependências

Este projeto utiliza um número enxuto de bibliotecas. Instale-as usando o arquivo requirements.txt fornecido:

```Bash
pip install -r requirements.txt
```

### 5. Iniciar o Jupyter

Após instalar as dependências, inicie o Jupyter Notebook:

```Bash
jupyter notebook
```
Isso abrirá uma janela no seu navegador. Clique no arquivo ```analise_crescimento_deputados_negros_brasil_livro.ipynb``` para abrir a análise e execute as células.

## 📜 Licença
O código deste projeto está licenciado sob a Licença MIT. Veja o arquivo LICENSE para mais detalhes.

## ✍️ Autor
Djiovanni Jonas França Marioto

Contato: djiovannimarioto@gmail.com
