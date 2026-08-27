# Status de publicação — ENEM Vestibular 365

Canais: Instagram · Threads · Facebook · LinkedIn Page · X · TikTok

## Fila completa — os 10 carrosséis

| # | Carrossel | Status | Quando |
|---|---|---|---|
| 1 | 7 erros que fazem perder ponto | ✅ postado | manual, fora do Postiz |
| 2 | 10 conectivos redação fluida | ✅ X, LinkedIn, FB, Threads · ♻️ repost IG+TikTok em JPEG | 26/08, 20:00 · repost 21:00 |
| 3 | 5 elementos proposta de intervenção | ✅ agendado, 6 redes | 27/08, 12:00 |
| 4 | Como começar uma redação (sem clichê) | ✅ agendado, 6 redes | 27/08, 16:00 |
| 5 | Como criar uma tese forte | ✅ agendado, 6 redes | 27/08, 20:00 |
| 6 | Como fazer uma conclusão completa | ✅ agendado, 6 redes | 28/08, 12:00 |
| 7 | A estrutura de uma introdução 900+ | ✅ agendado, 6 redes | 28/08, 16:00 |
| 8 | O modelo de desenvolvimento do ENEM | ✅ agendado, 6 redes | 28/08, 20:00 |
| 9 | Onde essa redação perdeu pontos | ✅ agendado, 6 redes | 29/08, 12:00 |
| 10 | 5 repertórios coringa | ✅ agendado, 6 redes | 29/08, 16:00 |

**Estoque esgotado em 29/08 às 16:00.** Depois disso a fila fica vazia.

## Convenções

- **Cadência:** 3 por dia — 12:00, 16:00 e 20:00 (horário de Brasília).
- **Espaçamento:** 1 minuto entre as redes, na ordem IG → Threads → FB → LinkedIn → X → TikTok.
- **Imagens:** sempre os JPEG de `enem365-media-social-jpg/` (1080×1350). Nunca os PNG.
- **Texto:** legenda escrita do zero para cada rede — nunca o mesmo texto replicado.
  - **Instagram:** longa, gancho na 1ª linha, lista com emoji, CTA de salvar + pergunta, ~15 hashtags no fim.
  - **Threads:** curta, conversacional, até 500 caracteres, sem hashtags, termina em pergunta.
  - **Facebook:** explicativa, tom de utilidade pública, CTA de compartilhar, 4 hashtags.
  - **LinkedIn:** ponte para o mundo profissional (o mesmo princípio aplicado a e-mail, relatório, reunião), sem emoji de estudante, 5 hashtags.
  - **X:** thread de 5 posts, 1 imagem por post, até 280 caracteres cada.
  - **TikTok:** uma frase de gancho + hashtags de descoberta. `DIRECT_POST`, `autoAddMusic=yes`.
- Sem link/CTA do app nas legendas por enquanto.

## ⚠️ Formato das imagens

**Instagram e TikTok não aceitam PNG** na API — o Instagram vai para `ERROR` (passa antes por `QUEUE`) e o TikTok também. Descoberto em 26/08/2026.

Todas as 50 imagens convertidas para **JPEG 1080×1350 q92** em `enem365-media-social-jpg/`. Os PNG ficam como master.

Conversão: PowerShell + `System.Drawing` (não há ImageMagick; o `convert` do PATH é o utilitário FAT→NTFS do Windows).

## ⚠️ Ordem das imagens — todas conferidas

| Pasta | Ordem de publicação |
|---|---|
| `5-elementos-proposta-de-intervencao` | **1, 2, 5, 3, 4** ⚠️ fora de ordem |
| `10-conectivos-redacao-fluida` | 1, 2, 3, 4, 5 |
| `como-comecar-uma-redacao` | 1, 2, 3, 4, 5 |
| `como-criar-uma-tese-forte` | 1, 2, 3, 4, 5 |
| `como-fazer-uma-conclusao-completa` | 1, 2, 3, 4, 5 |
| `estrutura-de-uma-redacao` | 1, 2, 3, 4, 5 |
| `modelo-de-desenvolvimento-enem` | 1, 2, 3, 4, 5 |
| `onde-essa-redacao-perdeu-pontos` | 1, 2, 3, 4, 5 |
| `repertorios-coringa` | 1, 2, 3, 4, 5 |
| `7-erros-que-fazem-perder-ponto` | ❌ não conferido (postado na mão) |

Nota: a pasta `estrutura-de-uma-redacao` é sobre a estrutura da **introdução**, não da redação inteira.

## ⚠️ Limitação do Postiz

O MCP **não deleta posts** e **não troca anexo** de post existente. Corrigir mídia = criar post novo; o antigo é apagado manualmente no app.

## Posts de notícia (X e Threads)

100 publicações agendadas: 50 posts × 2 redes, de 27/08 a 05/09/2026.

- **Horários:** 09h, 11h, 14h, 18h e 21h — fora dos slots de carrossel (12h/16h/20h). Threads no minuto :00, X no :01.
- **Formato:** texto puro, sem imagem. Cada post termina com `🗞️ Fonte: <veículo>`.
- **Fontes:** Inep, MEC e Agência Brasil — as fontes primárias. Nunca creditar um veículo que apenas republicou.
- **Limites validados:** X 280 caracteres, Threads 500, com o rodapé de fonte incluído na contagem.
- **Rascunho aprovado:** https://claude.ai/code/artifact/0276bad1-bf18-4c44-a5ff-acf944a84493

⚠️ Oito posts usam as orientações de dia de prova da edição **2025** (caneta, itens proibidos, eletrônicos) — as de 2026 ainda não haviam sido publicadas. Reconferir quando o Inep divulgar.

⚠️ Divergência entre fontes oficiais no total de inscritos: MEC e Agência Brasil registram 5.055.818; uma página do Inep fala em "mais de 5,7 milhões". Os posts usam o número do MEC e não chamam de recorde — o recorde histórico é de 2014, com 8.722.290.
