# jeie-exporter

Library to work with output of Minecraft mod [JEIExporter](https://github.com/friendlyhj/JEIExporter)

- Open generated file `exports/nameMap.json`, parse it.
- Types `nameMap` and `exports/recipes/*.json` files.
- Automatically pruning meaningless nbt (like `display:{}`).
- Convert NBT hash into `sNbt`.