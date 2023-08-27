# mc-schemas

This repository contains schemas for all sorts of Minecraft related formats and configuration files.

> [!NOTE]
> Calling all developers! PR your mod/plugin/etc's config schemas here!

## Folder Structure

Basically: `{type}/[{owner}/{name}]/{side}/**/*.json`

Side is either `client`, `server` or `both`

### Types

- `minecraft`: The base game
  - `minecraft/{SIDE}/*`
- `modloader`: Mod loaders
  - `modloader/{fabric,quilt,forge}/{SIDE}/*`
- `servers`: bukkit, paper, etc
  - `servers/{platform}/*`
- `proxies`
  - `proxies/{velocity,bungeecord,...}/*`
- `mods`: Config files for mods
  - `mods/{modloader}/{author}/{name}/{version}/{SIDE}/*`
- `plugins`: Config files for plugins
  - `plugins/{platform}/{author}/{name}/{version}/*`

### Schema Format

- Schemas must use the `https://json-schema.org/draft/2020-12/schema` draft
- File names should be the real file name + `.json`, for example `options.txt`'s schema file would be `options.txt.json`

## Why?

- More accessible information/better documentation
- Editors can have nice features such as autocomplete, validation, hover info, etc.

Any ideas? Feel free to open an issue or a PR!
