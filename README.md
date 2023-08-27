# mc-schemas

This repository contains schemas for all sorts of Minecraft related formats and configuration files.

> Notice
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


