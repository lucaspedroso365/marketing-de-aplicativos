# Status de publicação — ENEM Vestibular 365

Canais: Instagram · Threads · Facebook · LinkedIn Page · X · TikTok

## Fila

| # | Carrossel | Status | Quando |
|---|---|---|---|
| 1 | 7 erros que fazem perder ponto | ✅ postado | manual, fora do Postiz |
| 2 | 10 conectivos redação fluida | ✅ publicado em X, LinkedIn, FB, Threads · ♻️ repost IG+TikTok em JPEG | 26/08, 20:00 · repost 21:00 |
| 3 | 5 elementos proposta de intervenção | ✅ agendado nas 6 redes (JPEG) | 27/08, 12:00–12:05 |
| 4 | Como começar uma redação | ✅ agendado nas 6 redes (JPEG) | 27/08, 16:00–16:05 |
| 5 | Como criar uma tese forte | ✅ agendado nas 6 redes (JPEG) | 27/08, 20:00–20:05 |
| 6 | Como fazer uma conclusão completa | 🔲 na fila | 28/08, 12:00 |
| 7 | Estrutura de uma redação | 🔲 na fila | 28/08, 16:00 |
| 8 | Modelo de desenvolvimento ENEM | 🔲 na fila | 28/08, 20:00 |
| 9 | Onde essa redação perdeu pontos | 🔲 na fila | 29/08, 12:00 |
| 10 | Repertórios coringa | 🔲 na fila | 29/08, 16:00 |

## Convenções

- **Cadência:** 3 por dia — 12:00, 16:00 e 20:00 (horário de Brasília).
- **Espaçamento:** 1 minuto entre as redes, na ordem IG → Threads → FB → LinkedIn → X → TikTok.
- **Imagens:** sempre os JPEG de `enem365-media-social-jpg/` (1080×1350). Nunca os PNG.
- **X:** carrossel vira thread, 1 imagem por post (5 posts encadeados). Conta não é Premium → 280 caracteres por post.
- **Threads:** limite de 500 caracteres, sem hashtags.
- **TikTok:** post de fotos, `DIRECT_POST`, `autoAddMusic=yes`.
- Sem link/CTA do app nas legendas por enquanto.

## ⚠️ Formato das imagens

**Instagram e TikTok não aceitam PNG** na API de publicação — o Instagram trava em `QUEUE` e o TikTok vai para `ERROR`, sem mensagem legível pela API. Descoberto em 26/08/2026, quando o carrossel 2 saiu em 4 das 6 redes.

Todas as 50 imagens foram convertidas para **JPEG 1080×1350 q92** em `enem365-media-social-jpg/`. Os PNG em `enem365-media-social/` ficam como master de origem.

Conversão: PowerShell + `System.Drawing` (não há ImageMagick na máquina; o `convert` do PATH é o utilitário FAT→NTFS do Windows).

## ⚠️ Ordem das imagens

Os arquivos `1.png`…`5.png` **nem sempre seguem a ordem dos slides**. Conferir o `n/5` impresso na arte antes de agendar.

| Pasta | Ordem de publicação | Conferido |
|---|---|---|
| `10-conectivos-redacao-fluida` | 1, 2, 3, 4, 5 | ✅ |
| `5-elementos-proposta-de-intervencao` | **1, 2, 5, 3, 4** | ✅ fora de ordem |
| `como-comecar-uma-redacao` | 1, 2, 3, 4, 5 | ✅ |
| `como-criar-uma-tese-forte` | 1, 2, 3, 4, 5 | ✅ |
| `7-erros-que-fazem-perder-ponto` | — | ❌ não conferido (postado na mão) |
| demais pastas | — | ❌ conferir antes de agendar |

## ⚠️ Limitação do Postiz

O MCP **não deleta posts** e **não troca anexo** de post existente. Corrigir mídia = criar post novo; o antigo precisa ser apagado manualmente no app.
