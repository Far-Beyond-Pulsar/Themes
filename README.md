# Pulsar Themes

The official theme registry for the [Pulsar Hub](https://github.com/Far-Beyond-Pulsar/Pulsar-Hub).

Each file in `themes/` is a complete theme file, exactly what the Pulsar engine
loads from its themes directory. The Hub lists them, installs the ones you pick
into the themes folder shared by every engine install, and the engine's theme
watcher applies them.

## Adding a theme

Add `themes/<name>.json` and open a pull request. A theme file has a `name`,
an optional `author` and `url`, and a `themes` array of variants (each with a
`name`, a `mode` of `light` or `dark`, and its `colors`). The file name must be a
plain `*.json` name with no directories.
