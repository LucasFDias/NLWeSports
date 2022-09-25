# Back-end

## Entidades

### Game

id
title
bannerUrl

### Ad
id
gameId
name,
yearsPlaying,
discord,
weekDays,
hourStart,
hourEnd,
useVoiceChannel,
createdAt

## Casos de uso

- Listagem de games com contagem de anúncios
- Criação de novo anúncio
- Listagem de anúncios por game
- Buscar discord pelo ID do anúncio


## HTTPS CODE

200 - sucesso
300 - redirecionamento
400 - erro código bug
500 ou derivados - erros inesperados