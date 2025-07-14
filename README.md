# Tradutor Gemini para Jupyter

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Visão Geral do Projeto

Este projeto consiste em um tradutor de texto interativo desenvolvido para o ambiente Jupyter Notebook. Ele utiliza a API Gemini para realizar traduções automáticas entre português e inglês, com detecção automática do idioma de entrada. A interface do usuário é construída com `ipywidgets`, proporcionando uma experiência amigável diretamente no notebook.

## Funcionalidades

* **Tradução Inteligente**: Utiliza a poderosa API Gemini para traduções precisas e contextuais.
* **Detecção Automática de Idioma**: Identifica automaticamente se o texto de entrada está em português ou inglês.
* **Tradução Bidirecional**: Traduz de português para inglês e de inglês para português.
* **Interface Interativa no Jupyter**: Desenvolvido com `ipywidgets` para uma experiência de usuário fluida e integrada ao Jupyter Notebook.
* **Feedback de Status**: Exibe o status da tradução (Pronto, Traduzindo, Concluído, Erro) e mensagens de erro.

## Tecnologias Utilizadas

* Python
* Google Gemini API
* `requests` (para chamadas HTTP à API)
* `json` (para manipulação de dados JSON)
* `ipywidgets` (para a interface do usuário no Jupyter)
* `IPython.display` (para exibir os widgets no Jupyter)

## Como Usar

1.  **Obtenha uma Chave da API Gemini**:
    Antes de usar, você precisa de uma chave de API válida para o Google Gemini. Substitua `"SUA_CHAVE_DA_API_AQUI"` no arquivo `main_translator.ipynb` pela sua chave real.

2.  **Instale as Dependências**:
    Certifique-se de ter as bibliotecas necessárias instaladas. Você pode instalá-las usando `pip` com o arquivo `requirements.txt` fornecido:
    ```bash
    pip install -r requirements.txt
    ```

3.  **Execute o Jupyter Notebook**:
    Abra o arquivo `main_translator.ipynb` em seu ambiente Jupyter (Jupyter Notebook ou JupyterLab). Execute todas as células do notebook sequencialmente.

4.  **Interface de Tradução**:
    Após executar as células, uma interface interativa aparecerá. Digite o texto que deseja traduzir na caixa "Texto Original" e clique no botão "Traduzir". A tradução aparecerá na caixa "Tradução".

## Estrutura do Projeto

* `main_translator.ipynb`: O coração do projeto, contendo o código Python para a lógica de tradução e a interface do usuário.
* `README.md`: Este arquivo, fornecendo uma visão geral do projeto e instruções de uso.
* `LICENSE.md`: O arquivo de licença do projeto.
* `requirements.txt`: Lista das dependências do Python.

## Licença

Este projeto está licenciado sob a Licença MIT. Para mais detalhes, consulte o arquivo [LICENSE.md](LICENSE.md) na raiz do repositório.

## Contato

* **Nome**: Flávio Henrique Barbosa
* **LinkedIn**: [Flávio Henrique Barbosa | LinkedIn](https://www.linkedin.com/in/fl%C3%A1vio-henrique-barbosa-38465938)
* **Email**: flaviohenriquehb777@outlook.com
