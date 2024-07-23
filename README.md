# Discord User Info API 

Este aplicativo Node.js serve como uma API simples para recuperar informações estendidas sobre usuários do Discord. Ele utiliza a API Discord para buscar dados do usuário e processá-los para fornecer detalhes adicionais. A API expõe um endpoint para recuperar informações do usuário com base em seu ID de usuário Discord.

## Como Rodar

Siga estas etapas para executar o aplicativo localmente:

1. Clone o repositório em sua máquina local.

    ```bash
    git clone https://github.com/Nickz1n/Discord-API.git
    ```

2. Navegue até o diretório do projeto.

    ```bash
    cd Discord-API
    ```

3. Instale as dependências necessárias.

    ```bash
    npm install
    ```

4. Abra o arquivo `api.js` e certifique-se de que a variável `DISCORD_BOT_TOKEN` esteja definida. Você pode obter um token de bot Discord criando um novo bot no [Discord Developer Portal](https://discord.com/developers/applications).

    ```javascript
    const DISCORD_BOT_TOKEN = process.env.DISCORD_BOT_TOKEN || 'your-bot-token-here';
    ```

5. Salve as alterações.

6. Execute o aplicativo.

    ```bash
    node api.js
    ```

7. O servidor começará a rodar em `http://localhost:3000`. Agora você pode fazer solicitações à API.

## API Endpoint

- **GET /api/user/:id**: Recuperar informações estendidas sobre um usuário Discord com base em seu ID de usuário.

    Exemplo: `http://localhost:3000/api/user/651122734251900940`

    Substituir `651122734251900940` com o seu ID de usuário real do Discord.

    A resposta incluirá detalhes como nome de usuário, discriminador, avatar, banner, tipo de Nitro, data de criação e muito mais.

## Dependências

- [Express](https://expressjs.com/): Uma estrutura de aplicativo da web para Node.js.
- [Cors](https://www.npmjs.com/package/cors): Middleware para permitir o compartilhamento de recursos entre origens.

**Note:** Certifique-se de que o `Node.js` esteja instalado em sua máquina antes de executar o aplicativo.

Sinta-se à vontade para personalizar e ampliar o aplicativo de acordo com suas necessidades. Se você encontrar algum problema ou tiver dúvidas, consulte a [documentação da API Discord](https://discord.com/developers/docs/intro) para obter assistência.
