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
- `assets/casal.jpg` — **você precisa adicionar**: a foto do casal.

## Adicionar a foto do casal

Salve a foto (aquela da praia, por exemplo) como `assets/casal.jpg`, ao lado do
`index.html`. Enquanto o arquivo não existir, o convite mostra automaticamente
um ornamento no lugar da foto — nada quebra.

Se preferir deixar tudo em um arquivo só, dá para embutir a foto em base64 no
lugar de `src="assets/casal.jpg"`.

## O que ajustar antes de enviar aos convidados

1. **Nossa música** — está com *Perfect — Ed Sheeran* (padrão do modelo).
   Troque o título e o link do YouTube em `openMusic()` pela música de vocês.
2. **Prazo do RSVP** — está *08 de outubro de 2026* (um mês antes). Ajuste na
   seção "Confirmação".
3. **Confirmação de presença** — hoje o formulário só exibe a mensagem de
   sucesso na tela; ele não envia os dados para lugar nenhum. Para receber as
   confirmações, ligue o `submitRSVP()` a um Google Forms, a uma planilha ou a
   um link de WhatsApp dos noivos.
4. **Horário** — o convite impresso traz 16:00; aqui está **16:30**, conforme
   combinado. Se o certo for 16:00, troque nos três lugares: cronograma,
   card "Horário" e a data-alvo da contagem regressiva no `startCountdown()`.

## Como publicar

Qualquer hospedagem de site estático serve (GitHub Pages, Netlify, Vercel).
Basta subir `index.html` + a pasta `assets/`.
