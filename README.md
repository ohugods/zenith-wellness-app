# Zenith / Serene

Wellness — telas vitrine estáticas. HTML + Tailwind (CDN), hospedado na Vercel.

## Estrutura

| Caminho | Função |
|--------|--------|
| `index.html` | Shell mobile-first com iframe da entrada |
| `src/screens/*.html` | Telas (`href` relativos na mesma pasta) |
| `vercel.json` | Legado: `/screens/*` → `/src/screens/*` |

## Desenvolvimento

Abrir `index.html` ou ficheiros em `src/screens/` no browser.

## Deploy

`vercel --prod` na raiz do repositório.
