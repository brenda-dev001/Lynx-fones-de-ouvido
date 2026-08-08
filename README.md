# Pulse Fones de Ouvido

Projeto de landing page para apresentacao de um fone de ouvido da marca ficticia **Pulse**. A pagina esta em desenvolvimento e sera atualizada conforme novas secoes e funcionalidades forem adicionadas.

## Tecnologias

<p>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/html5/html5-original.svg" width="40" height="40" alt="HTML5" title="HTML5" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/css3/css3-original.svg" width="40" height="40" alt="CSS3" title="CSS3" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/sass/sass-original.svg" width="40" height="40" alt="Sass" title="Sass" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/bootstrap/bootstrap-original.svg" width="40" height="40" alt="Bootstrap Icons" title="Bootstrap Icons" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/npm/npm-original-wordmark.svg" width="40" height="40" alt="npm" title="npm" />
</p>

## Sobre

A proposta inicial do projeto e construir uma interface moderna para divulgar um produto, com foco em:

- estrutura semantica em HTML;
- estilos organizados com Sass;
- componentes reutilizaveis;
- uso de variaveis, mixins e arquivos parciais;
- assets proprios para icones e imagem principal.

## Estrutura

```txt
.
|-- index.html
|-- package.json
|-- src
|   |-- assets
|   |   |-- icons
|   |   `-- images
|   `-- styles
|       |-- main.css
|       |-- main.css.map
|       `-- scss
|           |-- abstracts
|           |-- base
|           |-- components
|           `-- layouts
```

## Como executar

Instale as dependencias:

```bash
npm install
```

Compile o Sass uma vez:

```bash
npm run compile:sass
```

Ou acompanhe as alteracoes automaticamente:

```bash
npm run watch:sass
```

Depois, abra o arquivo `index.html` no navegador.

## Status

Projeto em desenvolvimento.
