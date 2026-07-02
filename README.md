# Mnemosyne Viva

Site editorial estático para o novo `iconocracia.com`, concebido como casa pública do acervo, do atlas e da pesquisa ICONOCRACIA.

## Estrutura

- `index.html` — homepage.
- `sobre.html` — apresentação do projeto, método e conceitos.
- `acervo.html` — recorte inicial do acervo, com busca e filtros.
- `assets/` — CSS e JavaScript.
- `data/` — JSONs estáticos usados pela homepage e pelo acervo.
- `build_data.py` — regenera `data/*.json` a partir dos dados do corpus original.
- `AUDITORIA-ARQUITETURA.md` — auditoria do repositório de origem e arquitetura proposta.

## Deploy

O site é HTML/CSS/JS puro, sem etapa de build. No Vercel, usar framework `Other` ou `null`, sem `buildCommand` e com output na raiz do projeto.

