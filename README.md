# GraphIT - Homepage

## Changing content

To make content changes, edit markdown files in `content/notes`.

### Using with Obsidian

You can use [Obsidian](https://obsidian.md/) for editing content: [guide](<[/content/private/quartz-docs/obsidian.md](https://quartz.jzhao.xyz/notes/editing#:~:text=content/)>)

## Changing configuration

To make config changes, edit `data/config.yaml` and `data/graphConfig.yaml`. For more information see [changing configuration](<[/content/private/quartz-docs/config.md](https://quartz.jzhao.xyz/notes/config#:~:text=conf/)>).

## Previewing changes locally

- install dependencies:
  - go
  - hugo-obsidian: `go install github.com/jackyzha0/hugo-obsidian@latest`
- serve locally: `make serve`

## Publishing changes

To publish changes, push to the `main` branch. The site will be automatically built and deployed.

## File structure

### Important files

### Content

- `content/_index.md`: main page
- `content/notes`: public markdown files
- `content/templates`: templates for markdown files

### Data

- `data/config.yaml`: main config file
- `data/graphConfig.yaml`: graph config file

### Not so important files

#### Assets

- `assets/indices`: index files for search
- `assets/js`: javascript files
- `assets/styles`: css files

#### i18n

- `i18n/*.yaml`: translation files

#### Layouts

- `layouts/*.html`: html templates used by hugo

This website is powered by [quartz](https://github.com/jackyzha0/quartz)
