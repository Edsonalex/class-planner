# class-planner
Desafo imersão IA Alura + Gemini

# 🤖 Gerador de Plano de Aula com Google Gemini e Google ADK 📚

Um projeto Python que utiliza o modelo Gemini do Google e o Agent Development Kit (ADK) para auxiliar professores e educadores na criação automatizada de planos de aula, sugerindo conteúdos, atividades, avaliações e organizando um cronograma.

## ✨ Funcionalidades

*   Sugestão de conteúdo didático com base na série, disciplina e tema.
*   Sugestão de atividades lúdicas e práticas.
*   Sugestão de instrumentos de avaliação (formativa e somativa).
*   Geração de um cronograma semanal com base na duração e nos elementos do plano.

## 🚀 Como Usar (Google Colab)

Este projeto é projetado para rodar no Google Colab.

1.  **Abra o Notebook:** Clone ou baixe este repositório. Abra o arquivo `.ipynb` no Google Colab.
2.  **Configure a API Key:**
    *   Certifique-se de ter uma chave de API para o Google Gemini. Você pode obtê-la no [Google AI Studio](https://aistudio.google.com/).
    *   No Colab, clique no ícone de chave (Secrets) na barra lateral esquerda.
    *   Clique em `ADD NEW SECRET`.
    *   Defina o nome como `GOOGLE_API_KEY`.
    *   Cole sua chave de API no campo `Value`.
    *   Certifique-se de que a opção "Notebook access" está marcada para este secret.
3.  **Instalar Dependências:** Execute as primeiras células do notebook que contêm os comandos `!pip install` e `!apt-get install`.
4.  **Executar o Código:** Execute as células restantes do notebook na sequência. O notebook pedirá a série, disciplina, tema e duração do plano de aula via entrada de texto.
5.  **Exportar:** Após a geração do plano de aula, as funções de exportação para PDF e Google Sheet serão executadas, oferecendo os arquivos para download ou criando a planilha no seu Google Drive.

## ⚙️ Requisitos

*   Conta Google (para usar o Google Colab).
*   Chave de API do Google Gemini.
*   Ambiente Google Colab para executar o notebook.

## 📚 Bibliotecas Utilizadas

*   `google.generativeai` (Google Gemini SDK)
*   `google.adk` (Google Agent Development Kit)
*   `pdfkit`
*   `wkhtmltopdf` (ferramenta externa)
*   `google.colab.auth`, `googleapiclient`, `google-auth-oauthlib`, etc. (para Google Sheets/Drive API)
*   `textwrap`
*   `IPython.display`
*   `requests`
*   `warnings`
*   `os`

## 🤝 Contribuição

Contribuições são bem-vindas! Se você tiver ideias para melhorar o projeto, sinta-se à vontade para abrir uma *issue* ou enviar um *pull request*.
