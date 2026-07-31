# public-downloads

Materiais públicos do Marcelo para distribuição por link.

## Estrutura operacional

- `../finais/` → acervo local com versões finais aprovadas
- `public/` → versão distribuível/publicada no site estático

## Fluxo padrão

1. iterar materiais em `/opt/data/workspace/sketches/`
2. promover a versão aprovada para `../finais/<tema>/<slug>/`
3. publicar a versão distribuível em `public/<tema>/<slug>/`
4. commitar e dar push
5. publicar e validar no Vercel

## Primeira entrega

- Página pública: `public/agentes/primeiro-agente/index.html`
- PDF: `public/agentes/primeiro-agente/guia-primeiro-agente.pdf`
- Preview: `public/agentes/primeiro-agente/preview.png`
- Fonte final local: `../finais/agentes/primeiro-agente/`

## Publicação

Este repositório foi estruturado para deploy estático no Vercel.
