# Site da Luise Designer: como atualizar

Este repositório é o site no ar da Luise. Ela pede as mudanças no chat; quem edita e publica é o Claude.

## Regras da marca (não quebrar)
- Logo: `img/logo.png` (versão redonda, texto branco sobre círculo colorido). Usar só esta.
- Cores (tokens em `css/style.css`, `:root`): creme #FFF8F1 (fundo), marrom #4A332B (texto), coral #F6997B, areia #F4D79E, pêssego #F4CEB0, azul #C7DDE1. **Nunca usar preto.**
- Fontes: Antonio (títulos, caixa alta, mistura de peso 700 com 100/200) e Quicksand (texto).
- Nome: Luise (L-U-I-S-E), nunca "Louise".
- WhatsApp: (62) 98192-6634, link `https://wa.me/5562981926634?text=...`
- E-mail: luisedesigner@gmail.com · Instagram: @designerluise · Behance: behance.net/luisedesigner

## Como adicionar um projeto
1. Imagem de capa em `img/projetos/<nome>.webp`, 808×632 px (WebP, qualidade ~85).
2. Em `index.html`, seção `#projetos`: copiar um bloco `<a class="projeto">`. Os 6 primeiros ficam em `.grade` (destaque); os demais em `.grade--mini` ("Mais projetos").
3. Preencher `href` (página do Behance), `alt`, categoria (`projeto__cat`) e nome (`projeto__nome`).

## Antes de publicar
- Conferir em 1440 px e 390 px (Playwright): nada pode passar da largura da tela.
- Mostrar à Luise e só dar push na `main` com o ok dela; o push publica o site.
- Texto do site: sem travessão (—), linguagem natural.
