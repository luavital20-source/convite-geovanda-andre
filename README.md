# Convite de casamento — Geovanda e André

Convite digital (site de página única) do casamento de **Geovanda e André**,
seguindo a identidade do convite físico: lavanda em aquarela, paleta lilás/roxo
e o monograma **G/A**.

| | |
|---|---|
| **Noivos** | Geovanda e André |
| **Data** | 08 de novembro de 2026 (domingo) |
| **Cerimônia** | 16h30 |
| **Local** | Garden Buffet Maraponga — R. Benjamim Brasil, 570, Maraponga, Fortaleza — CE |
| **Traje** | Esporte fino / social |
| **Pix** | 07889386303 |

## Arquivos

- `index.html` — o convite completo. As artes florais já estão embutidas no
  próprio arquivo, então ele funciona sozinho (basta abrir no navegador ou
  enviar o link depois de hospedar).
- `assets/lavanda.webp`, `assets/ramo.webp` — artes extraídas do convite físico
  (versões `.png` também incluídas, caso queira reutilizar em outro material).
- `assets/casal.jpg` — a foto do casal na praia.

## A foto do casal

A foto é a primeira tela do convite: ocupa a altura toda, com "Geovanda e
André" na letra manuscrita na parte de baixo e um sombreado suave para o nome
ficar legível. Não há tela de abertura na frente dela — quem abre o link já vê
a foto. Logo abaixo vem a faixa com a data, e o monograma G/A fecha o convite
no rodapé.

Para trocar a foto, basta substituir o arquivo `assets/casal.jpg` mantendo o
nome. Se a foto nova tiver outro enquadramento, ajuste o `object-position` de
`.hero-photo` (hoje `center 72%`).

## Links usados

- **Lista de presentes e confirmação de presença:**
  <https://noivos.casar.com/geovanda-e-andre>
- **Nossa música:** <https://www.youtube.com/watch?v=cZag0E32is0>
  (o player abre dentro do convite)
- **Mapa:** busca do Google Maps pelo Garden Buffet Maraponga

## O que ainda dá para ajustar

1. **Nome da música** — o player está com o vídeo certo, mas sem o título
   escrito na tela (aparece "Toque para ouvir"). Se quiser mostrar o nome da
   música e do artista, é só trocar esse texto.
2. **Horário** — o convite impresso traz 16:00; aqui está **16:30**, conforme
   combinado. Se o certo for 16:00, troque nos três lugares: cronograma,
   card "Horário" e a data-alvo da contagem regressiva no `startCountdown()`.

## Como publicar

Qualquer hospedagem de site estático serve (GitHub Pages, Netlify, Vercel).
Basta subir `index.html` + a pasta `assets/`.
