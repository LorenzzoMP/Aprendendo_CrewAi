# Projetos de Estudo com Agentes de IA (CrewAI)

Este repositório contém dois micro-projetos desenvolvidos como parte de um curso sobre Agentes de IA da Udemy. O objetivo é demonstrar a aplicação prática da biblioteca **CrewAI** para criar equipes de agentes autônomos que colaboram para resolver tarefas complexas.

---

## 🛠️ Tecnologias e Pré-requisitos

Para executar os projetos, seu ambiente deve atender aos seguintes requisitos:

* **Python**: `3.12.10`
* **Chave de API**: É necessária uma chave de API da OpenAI (ou outro provedor de LLM).
* **Bibliotecas**: Todas as dependências necessárias estão listadas nos arquivos `requirements.txt` de cada projeto.

---

## 🚀 Como Executar

Siga os passos abaixo para configurar e executar os projetos.

### 1. Clonar o Repositório

Primeiramente, clone este repositório para sua máquina local:
```bash
git clone [https://github.com/SEU-USUARIO/SEU-REPOSITORIO.git](https://github.com/SEU-USUARIO/SEU-REPOSITORIO.git)
cd SEU-REPOSITORIO
```

### 2. Configurar as Chaves de API

Para que os agentes funcionem, eles precisam de acesso a um modelo de linguagem.

1.  Dentro da pasta de cada projeto (`First_project/` e `Second_project/`), crie um arquivo chamado `.env`.
2.  Neste arquivo, insira sua chave de API da OpenAI, como no exemplo abaixo:

    ```
    OPENAI_API_KEY="sk-xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
    ```

### 3. Executar o Projeto 1: Análise de Mercado

Este projeto utiliza agentes para realizar uma análise de mercado.

1.  **Acesse o diretório do projeto:**
    ```bash
    cd First_project
    ```
2.  **Crie e ative um ambiente virtual:**
    ```bash
    # Cria o ambiente
    python -m venv venv
    
    # Ativa o ambiente (Windows)
    .\venv\Scripts\activate
    
    # Ativa o ambiente (macOS/Linux)
    source venv/bin/activate
    ```
3.  **Instale as dependências:**
    ```bash
    pip install -r requirements.txt
    ```
4.  **Inicie o projeto:**
    ```bash
    jupyter notebook analise_mercado.ipynb
    ```

### 4. Executar o Projeto 2: Recomendações de Imóveis

Este projeto utiliza agentes para buscar e analisar dados de imóveis.

1.  **Retorne à raiz e acesse o diretório do segundo projeto:**
    ```bash
    cd ../Second_project
    ```
2.  **Crie e ative um ambiente virtual:**
    ```bash
    # Cria o ambiente
    python -m venv venv

    # Ativa o ambiente (Windows)
    .\venv\Scripts\activate

    # Ativa o ambiente (macOS/Linux)
    source venv/bin/activate
    ```
3.  **Instale as dependências:**
    ```bash
    pip install -r requirements.txt
    ```
4.  **Execute o script principal:**
    ```bash
    python imoveis.py
    ```

---

## 🎓 Créditos

Este trabalho foi desenvolvido com base nos aprendizados adquiridos em um curso sobre **AI Agents** da plataforma **Udemy**, com o objetivo de aplicar e aprofundar os conhecimentos na biblioteca CrewAI.