# tweetfy-bot
Bot configurado através do agendador de tarefas do Windows para fazer um tweet com um música aleatória do seu Spotify.
Esse projeto foi construído através do consumo das API's do Twitter e do Spotify. A API do Twitter foi utilizada para fazer o tweet na conta e a do Spotify para buscar uma música aleatoriamente das recentemente tocadas na plataforma.
Para a execução é preciso executar o spotify.Server() localizado no bot.go para fazer a autenticação na sua conta do Spotify. Outro ponto importante é criar o arquivo .env para as chaves das API's

Para gerar um tweet aleatório, coloquei um arquivo 'tweets.txt' dentro da pasta resources, assim, o bot busca um texto aleatório dentre as linhas e posta junto com a música aleatória.

É apenas um projeto "bobo" que fiz pra me divertir e aprender mais sobre consumo de API's.
