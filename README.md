# Biblioteca Digital UniFECAF

Site desenvolvido como projeto da disciplina **Design Web** — UniFECAF.

## 🔗 Links

- **Site publicado:** *(adicione o link do GitHub Pages / Netlify aqui)*
- **Repositório:** *(adicione o link do repositório aqui)*

## 📁 Estrutura do Projeto

```
biblioteca-unifecaf/
├── index.html
├── css/
│   └── style.css
├── assets/
│   └── imagens/
│       ├── sobre-biblioteca.jpg (ou .svg)
│       ├── galeria-1.jpg … galeria-4.jpg
│       ├── livro-1.jpg … livro-6.jpg
│       ├── unidade-1.jpg … unidade-3.jpg
│       └── (demais imagens)
└── README.md
```

## 🎨 Identidade Visual

| Token         | Cor       | Uso                        |
|---------------|-----------|----------------------------|
| Primary       | `#1a2e4a` | Fundo header, títulos      |
| Secondary     | `#1e6f8e` | Botões, ícones, destaques  |
| Accent        | `#f5a623` | CTAs, badges, detalhes     |
| White         | `#ffffff` | Fundos, textos em escuro   |
| Gray-50       | `#f8fafc` | Fundos de seção alternados |

**Tipografia:** Inter (Google Fonts) — pesos 400, 500, 600, 700, 800.

## 📐 Seções do Site

1. **Header / Navegação** — sticky, com menu mobile hamburger
2. **Hero** — banner principal com estatísticas
3. **Categorias** — grid de 8 áreas do conhecimento
4. **Sobre a Biblioteca** — texto, imagem principal e galeria
5. **Banner CTA** — chamada para acesso ao portal
6. **Nossos Livros** — grid de 6 cards com badges e botões
7. **Serviços** — 4 serviços com ícones
8. **As Unidades** — 3 unidades com layout alternado
9. **Contato** — informações + formulário
10. **Footer** — links e informações institucionais

## 📱 Responsividade

| Breakpoint | Comportamento                                  |
|------------|------------------------------------------------|
| > 1024px   | Layout completo desktop                        |
| ≤ 1024px   | Grid ajustado, coluna única nas seções         |
| ≤ 768px    | Menu hamburger, colunas simplificadas          |
| ≤ 480px    | Layout mais compacto para telas pequenas       |

## ♿ Acessibilidade

- Atributos `aria-label`, `aria-expanded`, `role` em todos os componentes interativos
- Contraste adequado entre texto e fundo (WCAG AA)
- Navegação por teclado com `:focus-visible`
- Suporte a `prefers-reduced-motion`
- `alt` descritivo em todas as imagens

## 🚀 Como publicar

### GitHub Pages
```bash
git init
git add .
git commit -m "feat: Biblioteca Digital UniFECAF v1.0"
git branch -M main
git remote add origin https://github.com/SEU_USUARIO/biblioteca-unifecaf.git
git push -u origin main
# Ative GitHub Pages em Settings > Pages > Source: main / root
```

### Netlify
Arraste a pasta `biblioteca-unifecaf/` para [app.netlify.com/drop](https://app.netlify.com/drop).
