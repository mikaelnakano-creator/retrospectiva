# Retrospectiva Digital - Dia dos Namorados

Projeto simples para publicar no Vercel usando GitHub.

## Como personalizar

1. Abra o arquivo `index.html`.
2. Procure por:

```js
const YOUTUBE_VIDEO_ID = "COLOQUE_AQUI_O_ID_DO_VIDEO";
```

3. Troque pelo ID da música no YouTube.

Exemplo:
URL: https://www.youtube.com/watch?v=ABC123
ID: ABC123

Ficaria:

```js
const YOUTUBE_VIDEO_ID = "ABC123";
```

## Como trocar fotos

Coloque suas fotos dentro da pasta `assets` com estes nomes:

- `foto-capa.jpg`
- `foto-1.jpg`
- `foto-2.jpg`
- `foto-3.jpg`

Se quiser usar mais fotos, duplique um slide de foto no `index.html`.

## Publicação

1. Crie um repositório no GitHub.
2. Envie o `index.html`, o `README.md` e a pasta `assets`.
3. Entre na Vercel.
4. Importe o repositório.
5. Clique em Deploy.

