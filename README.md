# Omilia Brasil — landing (versão estática para Vercel)

Site 100% estático: `index.html` + `brand/` + `media/`. Não precisa de build.

## Publicar
**Opção 1 — CLI**
```
cd vercel-site
npx vercel        # preview
npx vercel --prod # produção
```
**Opção 2 — Git**: suba esta pasta para um repositório e importe no Vercel
(Framework Preset: *Other*, Build Command: vazio, Output Directory: `.`).

## Rotas
- `/` e `/pt-br` servem a mesma página.

## Observações
- O formulário de contato não envia dados (mensagem de “envio indisponível”, como no original).
- Assets em `/media` e `/brand` têm cache longo (1 ano). Ao trocar um arquivo, use um novo nome.
