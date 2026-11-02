# 📚 Biblioteca Digital UniFECAF

Site desenvolvido como projeto da disciplina **Design Web** — UniFECAF 2026.

---

## 🔗 Links da Entrega

| Item | Link |
|------|------|
| ✅ Site publicado | *(preencher após publicar)* |
| ✅ Repositório | *(preencher após publicar)* |

---

## 📁 Estrutura do Projeto

```
biblioteca-unifecaf/
├── index.html          → Página principal (722 linhas)
├── relatorio.html      → Relatório teórico (abrir no navegador → Ctrl+P → PDF)
├── css/
│   └── style.css       → Estilização completa (1352 linhas)
├── assets/
│   └── imagens/        → 14 imagens JPG + 14 SVG fallback
└── README.md
```

---

## 🚀 Publicar no GitHub Pages (passo a passo)

### 1. Criar o repositório no GitHub
1. Acesse **https://github.com/new**
2. Nome do repositório: `biblioteca-unifecaf`
3. Deixe **Public** marcado
4. **NÃO** marque "Add a README file"
5. Clique em **Create repository**

### 2. Enviar o código (rode no PowerShell nesta pasta)

```powershell
git remote add origin https://github.com/willzao03/biblioteca-unifecaf.git
git push -u origin main
```

> Se pedir senha, use um **Personal Access Token**:
> → https://github.com/settings/tokens/new → marque `repo` → Generate → cole no lugar da senha

### 3. Ativar o GitHub Pages
1. No repositório, clique em **Settings**
2. No menu lateral, clique em **Pages**
3. Em *Source*, selecione: **Deploy from a branch**
4. Branch: **main** | Pasta: **/ (root)**
5. Clique em **Save**
6. Aguarde ~2 minutos e acesse:
   ```
   https://willzao03.github.io/biblioteca-unifecaf/
   ```

---

## 🎨 Paleta de Cores

| Token | Cor | Uso |
|-------|-----|-----|
| Primary | `#1a2e4a` | Header, títulos, fundo navy |
| Secondary | `#1e6f8e` | Botões, links, destaques |
| Accent | `#f5a623` | Badges, CTAs, ícones |
| Gray-50 | `#f8fafc` | Fundos de seção alternados |
| White | `#ffffff` | Base, cards |

**Tipografia:** Inter (Google Fonts) — pesos 400, 500, 600, 700, 800

---

## 📐 Seções do Site

| # | Seção | Descrição |
|---|-------|-----------|
| 1 | Header/Nav | Sticky, logo, hamburger mobile |
| 2 | Hero | Banner principal + barra de estatísticas |
| 3 | Categorias | Grid 4×2 com 8 áreas do conhecimento |
| 4 | Sobre a Biblioteca | Texto + imagem + galeria de 4 fotos |
| 5 | Banner CTA | Chamada para acesso ao portal |
| 6 | Nossos Livros | Grid 3×2 com 6 cards de livros |
| 7 | Serviços | 4 serviços com ícones |
| 8 | As Unidades | 3 unidades com layout alternado |
| 9 | Contato | Informações + formulário |
| 10 | Footer | Links institucionais |

---

## 📱 Responsividade

| Breakpoint | Layout |
|------------|--------|
| > 1024px | Desktop completo |
| ≤ 1024px | Grids reduzidos, colunas ajustadas |
| ≤ 768px | Menu hamburger, layout empilhado |
| ≤ 480px | Compactação máxima para celular |

---

## ♿ Acessibilidade

- Skip link "Pular para o conteúdo principal"
- `aria-label`, `aria-expanded`, `aria-required` em todos os interativos
- Contraste WCAG AA em todas as combinações de cor
- `:focus-visible` com outline visível para navegação por teclado
- `prefers-reduced-motion` respeita preferências do sistema
- `alt` descritivo em todas as imagens

---

## 📄 Gerar o PDF do Relatório

1. Abra o arquivo `relatorio.html` no navegador
2. Pressione **Ctrl+P**
3. Selecione **Salvar como PDF**
4. Em *Mais configurações*, marque **Gráficos de fundo**
5. Clique em **Salvar**

---

*© 2026 — Biblioteca Digital UniFECAF | Disciplina: Design Web*
