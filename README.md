# OpenAI-telegram-bot
Setup
1. Get your [OpenAI API](https://openai.com/api/) key

2. Get your Telegram bot token from [@BotFather](https://t.me/BotFather)

3. Edit `config/config.example.yml` to set your tokens and run 2 commands below (*if you're advanced user, you can also edit* `config/config.example.env`):
    ```
    mv config/config.example.yml config/config.yml
    mv config/config.example.env config/config.env
    ```

4. And now **run**:
    ```
    docker-compose --env-file config/config.env up --build
    ```
