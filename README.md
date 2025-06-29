
# Exercícios de Estatística com Python

Este repositório contém uma coleção de exercícios de estatística implementados em Python, usando principalmente bibliotecas como **NumPy**, **SciPy** e **Matplotlib**. Os exercícios abordam vários conceitos fundamentais em estatística, desde probabilidade básica e distribuições até testes de hipóteses e intervalos de confiança.

-----

## 🗂️ Conteúdo do Repositório

Cada exercício é projetado para ilustrar um conceito ou cálculo estatístico específico. Os arquivos `.ipynb` (Jupyter Notebook) contêm o código Python junto com explicações, facilitando a compreensão dos passos e a visualização dos resultados.

Aqui você encontrará exercícios que cobrem tópicos como:

  * **Distribuições de Probabilidade:** Normal (Gaussiana), Binomial.
  * **Z-Scores e P-valores:** Cálculo e interpretação.
  * **Teorema do Limite Central:** Demonstração do comportamento das distribuições amostrais.
  * **Intervalos de Confiança:** Para médias e proporções (com desvio padrão conhecido e desconhecido).
  * **Valores Críticos:** Z-crítico, t-crítico, Qui-Quadrado.
  * **Cálculo de Tamanho de Amostra:** Para médias e proporções.
  * **Testes de Hipóteses:** Formulação, cálculo de estatísticas de teste, valores críticos, p-valores e interpretação para diferentes tipos de testes (unilateral e bilateral).
  * **Erros Tipo I e Tipo II:** Análise de suas consequências.

-----

## 🚀 Como Usar o Repositório

Para rodar esses exercícios, você precisará ter o Python instalado em sua máquina e algumas bibliotecas essenciais. É **altamente recomendável** configurar um ambiente virtual para gerenciar as dependências, evitando conflitos com outros projetos Python.

### 💻 Pré-requisitos

Certifique-se de ter o [Python 3](https://www.python.org/downloads/) instalado.

### 🛠️ Configuração do Ambiente Virtual

Siga estes passos para configurar um ambiente virtual dedicado aos exercícios:

1.  **Navegue até a Pasta do Repositório:** Abra seu terminal (ou PowerShell no Windows) e navegue até o diretório `exercicios_estatistica`:

    ```bash
    cd C:\Users\rique\Documents\GitHub\meus_repositorios\exercicios_estatistica
    ```

    (Ajuste o caminho conforme necessário para o seu sistema)

2.  **Crie o Ambiente Virtual:**

    ```bash
    python -m venv venv
    ```

    Este comando cria uma pasta chamada `venv` no seu diretório atual, que conterá seu ambiente Python isolado.

3.  **Ative o Ambiente Virtual:**

      * **Windows (PowerShell):**
        ```powershell
        .\venv\Scripts\activate
        ```
        Se você encontrar um erro sobre a execução de scripts estar desabilitada, execute `Set-ExecutionPolicy RemoteSigned -Scope CurrentUser` em um **PowerShell como administrador** uma única vez. Depois, abra um **novo PowerShell normal** para ativar o ambiente.
      * **macOS / Linux:**
        ```bash
        source venv/bin/activate
        ```

    Você saberá que o ambiente está ativo quando `(venv)` aparecer no início do seu prompt do terminal.

4.  **Instale as Dependências Necessárias:**
    Com o ambiente virtual ativo, instale as bibliotecas necessárias:

    ```bash
    pip install scipy matplotlib numpy ipykernel notebook
    ```

    (Ou `pip install jupyterlab` se você preferir o JupyterLab ao invés do Jupyter Notebook)

5.  **Registre o Ambiente no Jupyter:**
    Para usar este ambiente dentro do Jupyter, você precisa registrá-lo como um kernel Jupyter:

    ```bash
    python -m ipykernel install --user --name=venv --display-name="Estatística Exercícios"
    ```

6.  **Inicie o Jupyter:**
    A partir do seu ambiente virtual ativo no terminal, inicie o Jupyter:

    ```bash
    jupyter notebook
    # ou
    jupyter lab
    ```

7.  **Selecione o Kernel no Jupyter:**
    Assim que o Jupyter abrir no seu navegador, abra qualquer um dos arquivos `.ipynb`. Em seguida, vá em **Kernel \> Mudar Kernel** (ou **Kernel \> Change Kernel**) no menu do Jupyter e selecione "**Estatística Exercícios**" (ou o nome de exibição que você escolheu). Agora você pode rodar as células, e o código usará as bibliotecas do seu ambiente virtual.
