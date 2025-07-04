# Assistente Virtual para Orientações em Desastres Naturais

![Badge de Tecnologia](https://img.shields.io/badge/Tecnologia-Engenharia%20de%20Prompt-blue)
![Badge de Linguagem](https://img.shields.io/badge/Linguagem-Python-yellow)

## 📖 Descrição

[cite_start]Este projeto, desenvolvido como parte da Global Solution da FIAP, consiste na criação de um assistente virtual especializado em fornecer orientações claras e empáticas durante desastres naturais.  Utilizando técnicas de **Engenharia de Prompt**, o assistente é projetado para contextualizar suas respostas de acordo com três perfis de usuário:

* [cite_start]**Vítimas diretas:** Pessoas que precisam de instruções de segurança imediatas. [cite: 7]
* [cite_start]**Moradores da região:** Buscando informações sobre medidas preventivas e atualizações. [cite: 8]
* [cite_start]**Familiares:** Procurando orientações sobre como ajudar ou localizar seus entes queridos. [cite: 9]

[cite_start]O notebook do projeto demonstra a aplicação de diferentes técnicas de prompt, como *role prompting* e *few-shot learning*, para garantir que o modelo de linguagem gere respostas precisas, úteis e com o tom adequado para cada situação crítica. [cite: 11]

## 🎯 Objetivos do Projeto

* [cite_start]**Aplicar técnicas de Engenharia de Prompt** para refinar e controlar as respostas de um modelo de linguagem. [cite: 11]
* [cite_start]**Desenvolver prompts sensíveis ao contexto** e ao perfil emocional do usuário. [cite: 12]
* [cite_start]**Explorar os desafios éticos** de projetar assistentes para situações críticas, garantindo informações precisas e responsáveis. [cite: 13]
* [cite_start]**Testar e avaliar** como diferentes estruturas de prompt influenciam a qualidade das respostas geradas. [cite: 14]

## 🛠️ Tecnologias Utilizadas

* **Linguagem:** Python
* **Ambiente:** Google Colab
* **Técnica Principal:** Engenharia de Prompt
* **Modelo de Linguagem:** API do Google Gemini (ou a que você utilizou)

## 🚀 Como Executar o Projeto

Para rodar o notebook e testar os prompts, siga os passos abaixo:

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/SEU-USUARIO/assistente-desastres-naturais.git](https://github.com/SEU-USUARIO/assistente-desastres-naturais.git)
    cd assistente-desastres-naturais
    ```

2.  **Crie um ambiente virtual (recomendado):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # No Windows: venv\Scripts\activate
    ```

3.  **Instale as dependências:**
    ```bash
    pip install -r requirements.txt
    ```

4.  **Configure sua chave de API:**
    * O notebook requer uma chave de API para o modelo de linguagem (ex: Google Gemini).
    * É uma boa prática não deixar a chave visível no código. Configure-a como uma variável de ambiente ou utilize o sistema de "Secrets" do Google Colab.

5.  **Execute o Notebook:**
    * Abra o arquivo `notebook_assistente_virtual.ipynb` em um ambiente Jupyter (como Jupyter Lab ou VS Code) ou faça o upload para o Google Colab para executar as células de código.

