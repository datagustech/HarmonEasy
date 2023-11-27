Harmoneasy - Sommelier Digital para Flores da Cunha

Descrição do Projeto
O Harmoneasy é um aplicativo desenvolvido durante o Startup Weekend de Flores da Cunha, com o objetivo de proporcionar uma experiência única e personalizada ao usuário, atuando como um Sommelier Digital. O aplicativo utiliza a tecnologia GPT (Generative Pre-trained Transformer) através da API de chatbot para criar interações naturais e envolventes com os usuários.

Funcionalidades
Chatbot GPT
O Harmoneasy integra a API do Chat GPT para fornecer respostas inteligentes e personalizadas aos usuários. O Chatbot é treinado para compreender consultas relacionadas a vinhos, harmonizações, recomendações de acordo com preferências pessoais, entre outros.

Flask
O backend do aplicativo é construído utilizando o framework Flask, proporcionando uma base sólida para a criação de rotas, manipulação de dados e integração eficiente com a API do Chat GPT.

Frontend com HTML e JS
A interface do usuário é desenvolvida utilizando HTML e JavaScript para garantir uma experiência intuitiva e agradável. A interatividade é enfatizada para proporcionar uma navegação fluida e permitir que os usuários explorem facilmente as funcionalidades do Sommelier Digital.
Estrutura de Diretórios
lua
Copy code
/faq_gpt
|-- /templates
|   |-- index.html
|-- /static
|   |-- Logo.png
|-- app.py
|-- requirements.txt
|-- README.md
Componentes
/templates
Este diretório contém os arquivos HTML que definem a interface do usuário. No nosso caso, um único arquivo index.html é suficiente para fornecer a interface de usuário necessária.

/static/css
Este diretório armazena os elementos presentes no html

app.py
Este é o arquivo principal do projeto e contém toda a lógica de back-end. Ele é responsável por iniciar o servidor Flask, bem como por manipular as requisições e respostas HTTP.

requirements.txt
Lista todas as bibliotecas Python necessárias para executar o projeto. As principais dependências são Flask e a biblioteca requests para chamadas HTTP.

Fluxo de Operações
Interface do Usuário: O usuário acessa a página index.html e insere uma pergunta no formulário disponível.
Rota do Flask: Uma rota específica no app.py é acionada quando o formulário é submetido.
API da OpenAI: A pergunta é enviada para a API da OpenAI através de uma chamada HTTP.
Processamento de Resposta: A resposta da API é processada e formatada no app.py.
Exibição de Resposta: A resposta é então exibida ao usuário na página web.
Tecnologias Utilizadas
Back-end: Flask
Front-end: HTML/CSS
Chamadas HTTP: Biblioteca requests



