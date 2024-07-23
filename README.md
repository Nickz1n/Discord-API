# 👾 Discord-API 
Um aplicativo Node.js leve para obter informações detalhadas sobre usuários do Discord por meio de uma API. Ele utiliza a API do Discord para buscar dados do usuário e processá-los para fornecer detalhes adicionais. A API expõe um endpoint para recuperar informações do usuário com base em seu ID de usuário Discord.

## 💿 Como Rodar 
Siga estas etapas para executar o aplicativo localmente:
  1. Clone o repositório em sua máquina local:

    `git clone https://github.com/Nickz1n/Discord-API.git`
     
  2. Navegue até o diretório do projeto:

     `cd Discord-API`

  3. Instale as dependências necessárias:

     `npm install`
  
  4. Abra o arquivo `api.js` e certifique-se de que a variável `DISCORD_BOT_TOKEN` esteja definida. Você pode obter um token da aplicação//bot Discord criando um novo, ou resgatando um já existente no [Portal do Desenvolvedor](https://discord.com/developers/applications):

    `const DISCORD_BOT_TOKEN = process.env.DISCORD_BOT_TOKEN || 'your-bot-token-here';`
