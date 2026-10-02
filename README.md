# Abílio Júnior

Site pessoal de Abílio Júnior, construído com Hugo e o tema Toha.

Os dados de perfil, formação, experiências, certificação, foto e artigos foram recuperados do [site anterior](https://github.com/abiliojunior/abiliojuniotdevr) e adaptados à estrutura atual do tema. Os dados pessoais ficam em `data/pt/` e os artigos em `content/pt/`. As habilidades permanecem desativadas, como no site anterior.

O artigo sobre redundância em CLPs foi migrado com seus endereços antigos como redirecionamentos. O texto incompleto “Domingo 03/05/2020” permanece como rascunho.

Attributions:

- <a href='https://www.freepik.com/vectors/business'>Business vector created by studiogstock - www.freepik.com</a>

## Requirements

We use [jdx/mise](https://github.com/jdx/mise) to manage dependencies. Mise takes care of installing `hugo`, `go`, `nodes` and other tools to appropriate versions. Please, install it following the instruction from [here](https://mise.jdx.dev/getting-started.html).

## Running Locally

- Install dependencies

```
mise install
```

- Run hugo server

```
mise run server
```

## Updating theme

- To update theme to latest release, run:

```
mise run update
```

- To update theme to latest commit from `main` brnach, run:

```
mise run update-to-main
```
