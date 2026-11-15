# Velvet — Landing page de alta gastronomia

Landing page responsiva para um restaurante fictício, feita só com HTML e CSS (mais um pequeno trecho de JavaScript para o menu mobile). O foco do projeto foi o acabamento visual: animações, efeitos 3D e uma identidade própria em tons de preto, dourado e vinho.

🔗 **Demo:** [felixdaniel93.github.io/velvet](https://felixdaniel93.github.io/velvet/)

## Funcionalidades

- **Hero em tela cheia** com zoom lento na foto (efeito Ken Burns) e partículas de brasa subindo, feitas só com CSS
- **Header translúcido** (efeito vidro fosco) fixo no topo, com sublinhado animado nos links
- **Menu mobile** com botão hambúrguer, que se fecha ao clicar em um link
- **Cards de pratos com flip 3D**: a frente mostra foto, nome e preço, e o verso mostra descrição e ingredientes
- **Brilho giratório** ao redor do card no hover e **entrada em cascata** dos cards
- **Interação por toque e teclado**: o flip também funciona no celular e com a tecla Tab
- **Respeito a `prefers-reduced-motion`**: quem prefere menos movimento não vê as animações
- **Layout responsivo** com CSS Grid, Flexbox e `clamp()` para tipografia fluida

## Tecnologias

| Categoria | Ferramentas |
|---|---|
| Base | HTML5, CSS3 |
| Recursos de CSS | Variáveis, Grid, Flexbox, `@keyframes`, `transform 3D`, `conic-gradient`, `backdrop-filter`, `clamp()` |
| Fontes | Google Fonts: Cormorant Garamond e Jost |
| JavaScript | Apenas o fechamento do menu mobile |

## Estrutura do projeto

```
.
├── index.html
├── style.css
├── img/
│   ├── ambiente.jpg
│   ├── interior.jpg
│   ├── file.jpg
│   ├── massa.jpg
│   └── pizza.jpg
└── README.md
```

## Como executar

Não precisa instalar nada.

```bash
git clone https://github.com/felixdaniel93/velvet.git
cd velvet
```

Abra o `index.html` no navegador. Se preferir um servidor local, use a extensão **Live Server** do VS Code.

## O que pratiquei neste projeto

- Construir um design system simples com variáveis CSS (cores, fontes e largura do container)
- Criar animações com `@keyframes`, atrasos em cascata e curvas `cubic-bezier`
- Montar um flip 3D com `perspective`, `transform-style: preserve-3d` e `backface-visibility`
- Fazer layouts responsivos com Grid, Flexbox e media queries
- Criar um menu hambúrguer apenas com CSS (checkbox + `label`)
- Cuidar de acessibilidade: `alt` nas imagens, foco por teclado e redução de movimento

## Próximos passos

- [ ] Fazer o botão "+" dos pratos funcionar (por exemplo, um carrinho simples)
- [ ] Adicionar mais pratos e categorias ao cardápio
- [ ] Otimizar as imagens (formato WebP) para carregar mais rápido
- [ ] Trocar os dados fictícios (telefone, e-mail, redes sociais) por dados reais, se o projeto for usado

## Autor

**Daniel Felix**

[LinkedIn](https://www.linkedin.com/in/felixdaniel93/) · [GitHub](https://github.com/felixdaniel93) · [E-mail](mailto:danielfdamaceno93@gmail.com)

---

_Projeto fictício, criado apenas para fins de estudo e portfólio. O restaurante, os pratos, os textos e os contatos exibidos na página são exemplos._
