# Perito Certificado

Site institucional e landing pages dos cursos do [Perito Certificado](https://peritocertificado.com), plataforma de formação pericial da perita judicial Jacqueline Tirotti.

As páginas foram feitas para rodar dentro de um widget HTML do Elementor, então cada uma é um arquivo só, com HTML, CSS e JS juntos. Não há dependências nem build.

## Estrutura

```
index.html                        índice das páginas
perito-certificado/               site institucional
grafo-expert/
doc-expert/
docdig-na-pratica/
grafodoc-na-pratica/
metodo-grafodoc/
assistencia-tecnica-judicial/
expert-em-cedulas/
manual-pratico-grafotecnica/      e-book
manual-documentos-digitais/       e-book
termos-e-condicoes/
politica-de-privacidade/
```

## Rodando localmente

Basta abrir qualquer `index.html` no navegador. Se preferir um servidor:

```
npx serve .
```

## Publicando no GitHub Pages

Settings → Pages → branch `main`, pasta `/ (root)`. O `.nojekyll` evita que o Jekyll processe os arquivos.

## Usando no Elementor

Copie o conteúdo entre `<body>` e `</body>` para um widget HTML. O CSS já trata o que o tema costuma interferir: largura e padding dos containers, estilo global de `<button>` e a barra de admin do WordPress sobre o header fixo.

## Visual

- Fontes: Sora nos títulos e números, IBM Plex Sans no texto (Google Fonts)
- Cores: azul `#12243C` / `#24487A`, dourado `#CF9A44`, texto `#181C23`, fundo `#F1F1F1`

Reveal no scroll, blocos sticky e zoom de imagem só funcionam acima de 1024px. Em telas menores e com `prefers-reduced-motion`, o conteúdo aparece direto, sem animação.

## Observações

- As imagens estão hospedadas em `peritocertificado.com/wp-content/uploads/`; o repositório não guarda cópia delas.
- Os links entre páginas e os botões de compra (checkout Herospark) apontam para produção.

---

Conteúdo, marca e imagens © Perito Certificado. Todos os direitos reservados.
