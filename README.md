# 🎧 Lynx - Fone Gamer

Landing page desenvolvida para apresentar o fone gamer fictício **Lynx**, com foco em uma interface visual moderna, seções de produto, apresentação de recursos e variações de cores.

O projeto foi criado para praticar estruturação semântica com HTML, estilização com Sass, organização de arquivos SCSS em módulos, uso de variáveis, mixins, assets visuais e ícones externos.

## ✨ Funcionalidades

- Cabeçalho fixo com identidade visual, navegação e botão de carrinho.
- Seção inicial com chamada principal do produto.
- Botões de ação para compra e navegação para mais informações.
- Imagem principal do fone gamer.
- Seção de recursos com cards informativos.
- Exibição de recursos como som imersivo, cancelamento de ruído, bateria e Bluetooth.
- Seção de cores com opções visuais do produto.
- Uso de ícones com Bootstrap Icons.
- Estilos organizados com Sass, partials, variáveis e mixins.
- Arquivo CSS compilado a partir do SCSS.

## 🛠️ Tecnologias utilizadas

<p align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/html5/html5-original.svg" width="40" height="40" alt="HTML5" title="HTML5" />
  &nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/css3/css3-original.svg" width="40" height="40" alt="CSS3" title="CSS3" />
  &nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/sass/sass-original.svg" width="40" height="40" alt="Sass" title="Sass" />
  &nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/bootstrap/bootstrap-original.svg" width="40" height="40" alt="Bootstrap Icons" title="Bootstrap Icons" />
  &nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/npm/npm-original-wordmark.svg" width="40" height="40" alt="npm" title="npm" />
</p>

## ⚙️ Como a aplicação funciona

A página apresenta o produto Lynx em formato de landing page.

O usuário encontra uma primeira seção com o nome do produto, descrição curta, imagem do fone e botões de ação. Em seguida, a aplicação exibe cards com os principais recursos do fone e uma seção dedicada às opções de cores.

Até o momento, o projeto é uma página estática. Os botões e seletores visuais ainda não possuem comportamento em JavaScript.

## 📁 Estrutura do projeto

```txt
project_phone/
├── src/
│   ├── assets/
│   │   ├── icons/
│   │   │   ├── svg_icone-carrinho.svg
│   │   │   ├── svg_icone-gato.svg
│   │   │   └── svg_icone-lua.svg
│   │   └── images/
│   │       ├── png_fone-cores-azul.png
│   │       ├── png_fone-cores-branco.png
│   │       ├── png_fone-cores-lilas.png
│   │       ├── png_fone-cores-preto.png
│   │       ├── png_imagem-fone--azul.png
│   │       └── svg_imagem-gato-fundo.svg
│   └── styles/
│       ├── main.css
│       ├── main.css.map
│       └── scss/
│           ├── abstracts/
│           │   ├── _index.scss
│           │   ├── _mixins.scss
│           │   └── _variables.scss
│           ├── base/
│           │   ├── _global.scss
│           │   ├── _index.scss
│           │   └── _reset.scss
│           ├── components/
│           │   └── _botao.scss
│           ├── layouts/
│           │   ├── _cores.scss
│           │   ├── _header.scss
│           │   ├── _hero.scss
│           │   ├── _index.scss
│           │   ├── _recursos.scss
│           │   └── _sobre.scss
│           └── main.scss
├── .gitignore
├── index.html
├── package-lock.json
├── package.json
└── README.md
```

## 📄 Responsabilidade dos arquivos SCSS

| Arquivo | Responsabilidade |
| --- | --- |
| `src/styles/scss/main.scss` | Arquivo principal que importa os módulos de estilos. |
| `src/styles/scss/abstracts/_variables.scss` | Define as variáveis globais de cores do projeto. |
| `src/styles/scss/abstracts/_mixins.scss` | Reúne mixins reutilizáveis para flexbox, textos e dimensões. |
| `src/styles/scss/base/_reset.scss` | Remove margens e paddings padrões e define o `box-sizing`. |
| `src/styles/scss/base/_global.scss` | Define estilos globais, fontes, cores base e aparência de textos. |
| `src/styles/scss/layouts/_header.scss` | Estiliza o cabeçalho, navegação, logo e botão de carrinho. |
| `src/styles/scss/layouts/_hero.scss` | Estiliza a seção inicial com título, descrição, botões e imagem do produto. |
| `src/styles/scss/layouts/_recursos.scss` | Estiliza a seção de cards com os recursos do fone. |
| `src/styles/scss/layouts/_cores.scss` | Estiliza a seção de variações de cores do produto. |
| `src/styles/scss/layouts/_sobre.scss` | Arquivo reservado para a seção sobre, ainda em desenvolvimento. |
| `src/styles/scss/components/_botao.scss` | Arquivo reservado para estilos de botões reutilizáveis. |

## ✅ Pré-requisitos

Para executar o projeto, é necessário ter:

- Um navegador moderno.
- O Git instalado.
- O Node.js e o npm instalados.

## 🚀 Executando localmente

Clone o repositório:

```bash
git clone https://github.com/brenda-dev001/pulse-fones-de-ouvido.git
```

Entre na pasta do projeto:

```bash
cd pulse-fones-de-ouvido
```

Instale as dependências:

```bash
npm install
```

Compile o Sass:

```bash
npm run compile:sass
```

Ou acompanhe as alterações automaticamente durante o desenvolvimento:

```bash
npm run watch:sass
```

Depois, abra o arquivo `index.html` no navegador.

## 🎮 Como navegar

1. Acesse a página inicial.
2. Use o menu do cabeçalho para visualizar as seções planejadas.
3. Confira a chamada principal do produto na seção inicial.
4. Veja os cards com os recursos do fone.
5. Consulte as opções de cores disponíveis na seção de cores.

## 📌 Status do projeto

Projeto em desenvolvimento.

Até o momento, a estrutura visual principal está criada com HTML e Sass. As próximas evoluções vão incluir responsividade mais completa, comportamento em JavaScript para os botões de cores, navegação entre seções e finalização da seção sobre.

## 👩‍💻 Autoria

Desenvolvido por [Brenda](https://github.com/brenda-dev001).
