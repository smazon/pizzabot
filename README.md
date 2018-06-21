# Exemplo de Chatbot com Watson Assistant em Node.js

Este aplicação é uma demo de Front End de chatbot em Node.js que utiliza a API de Watson Assistant. Basta criar uma instância do Watson Assistant na [IBM Cloud](https://console.bluemix.net), colocar as credenciais neste app e fazer o deploy.

[Neste link](https://medium.com/botsbrasil/desenvolvendo-chatbots-com-watson-conversation-64a3b2cdbb30) você encontra um tutorial de como criar um chatbot usando o Watson Assistant

## Deploy no IBM Cloud

[![Deploy to Bluemix](https://bluemix.net/deploy/button.png)](https://bluemix.net/deploy?repository=https://github.com/victorshinya/pizza)

## Executar o app localmente

1. Instalar [Node.js](https:/nodejs.org/) no seu computador.

2. Acessar a pasta do projeto
```bash
cd chatbot
```

3. Execute o comando abaixo para instalar as dependências do app
```node
npm install
```

4. Altere o arquivo **.env** e coloque as credenciais do Watson Assistant, **username** e **password**, e o workspace_id

5. Execute o comando abaixo para subir o servidor Node.js
```node
npm start
```

6. Acesse a aplicação no seu navegador no link http://localhost:3000/
