# 🤝 ONG Mãos Solidárias

Site institucional da **ONG Mãos Solidárias**, organização fictícia de Salto (SP) que apoia famílias em situação de vulnerabilidade por meio de projetos sociais, campanhas solidárias e voluntariado.

O projeto foi desenvolvido com **HTML5 semântico** e **CSS3 modular** (variáveis CSS, Flexbox, Grid e design responsivo), com ícones SVG do [Bootstrap Icons](https://icons.getbootstrap.com/).

<!-- Adicione aqui uma captura de tela: ![Prévia do site](docs/preview.png) -->

## ✨ Funcionalidades

- **Início:** apresentação da ONG, missão, visão, valores e números de impacto.
- **Projetos:** Cesta Solidária, Educação para o Futuro e Verde Esperança.
- **Cadastro:** formulário de voluntários com validação nativa do navegador (CPF, telefone e CEP).
- Layout responsivo para celular, tablet e desktop.
- Menu fixo com destaque da página atual.
- Acessibilidade: HTML semântico, `alt` nas imagens, foco visível e respeito a `prefers-reduced-motion`.

## 🎨 Paleta de cores

| Cor | Hex | Uso |
|---|---|---|
| Verde escuro | `#1a4c45` | Cabeçalho, rodapé e títulos |
| Verde menta | `#a7d9b8` | Seções alternadas e detalhes |
| Verde folha | `#46733f` | Destaques e bordas |
| Lima | `#ccd96c` | Botões e link ativo |
| Creme | `#f2eeeb` | Fundo da página |

As cores ficam centralizadas em variáveis CSS no `:root` de `CSS/style.css`.

## 📁 Estrutura do projeto

```
ong-maos/
├── index.html          # Página inicial
├── projetos.html       # Projetos solidários
├── cadastro.html       # Cadastro de voluntários
├── CSS/
│   ├── style.css       # Variáveis, reset, componentes e responsividade
│   ├── index.css       # Estilos da página inicial
│   ├── projetos.css    # Estilos da página de projetos
│   └── cadastro.css    # Estilos da página de cadastro
└── img/
    ├── Inicio/         # voluntarios.jpg
    └── Projetos/       # cesta-solidaria.jpg, educacao.jpg, verde-esperanca.jpg
```

> As imagens não estão incluídas no repositório. Adicione as suas fotos nas pastas acima, com os mesmos nomes de arquivo.

## 🚀 Como executar

Não é preciso instalar nada.

```bash
git clone https://github.com/SEU-USUARIO/ong-maos.git
cd ong-maos
```

Abra o `index.html` no navegador. Se preferir um servidor local, use a extensão **Live Server** do VS Code.

## 🧱 Organização do CSS

- `style.css` concentra o que é comum a todas as páginas: variáveis, reset, cabeçalho, cards, formulário, botões e rodapé.
- Cada página tem seu próprio arquivo para os estilos específicos, mantendo o código fácil de manter.
- Nomes de classes descritivos (`.card`, `.banner`, `.quem-somos`) e uso de `:root` para facilitar mudanças de tema.

## 🛠️ Tecnologias

- HTML5
- CSS3 (Custom Properties, Flexbox, Grid, Media Queries)
- JavaScript básico (apenas máscaras do formulário, dispensável)
- [Bootstrap Icons](https://icons.getbootstrap.com/) (SVG inline)

## 🗺️ Próximos passos

- [ ] Integrar o formulário de cadastro a um serviço de envio (ex.: Formspree)
- [ ] Adicionar página de doações
- [ ] Incluir depoimentos e parceiros
- [ ] Publicar com GitHub Pages
