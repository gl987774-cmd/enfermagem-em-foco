# Enfermagem em Foco

Landing page do Kit de Mapas Visuais para Enfermagem, com imagens, amostras dos materiais, bonus e informacoes da oferta.

## Arquivos

- `index.html`: pagina principal do site.
- `identidade-visual.md`: paleta de cores e diretrizes visuais.
- `Imagem Topo do Site/`, `Previas Mapas/`, `Previas Materiais/`, `Mockup Garantia/`, `Mockups Bonus/` e `tudo que voce recebe/`: imagens e materiais visuais do projeto.

## Visualizar localmente

Abra `index.html` no navegador ou inicie um servidor local nesta pasta:

```powershell
python -m http.server 8000
```

Depois, acesse <http://localhost:8000>.

## Publicar na Vercel

Importe este repositorio na Vercel e selecione a branch `main`. Como o site e estatico, use a pasta raiz do repositorio como diretorio de publicacao; nao e necessario configurar build command. O arquivo `index.html` sera a pagina inicial.

Antes de publicar, confira os links de checkout e os codigos de rastreamento configurados em `index.html`. Depois, cada envio para `main` sera publicado automaticamente pela Vercel.
