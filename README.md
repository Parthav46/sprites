# sprites

Guidelines for organizing and publishing individual sprite packs in this repository.

## Repository Layout
- `sprites/` – top-level folder that holds one subfolder per sprite or sprite pack
- `sprites/<sprite-name>/assets/` – source artwork (`.png`, `.aseprite`, `.svg`, etc.)
- `sprites/<sprite-name>/preview/` – exports for quick viewing (`.gif`, `.webp`, `.png` sheets)
- `sprites/<sprite-name>/docs/` – optional write-ups, palettes, references, or design notes
- `sprites/<sprite-name>/README.md` – sprite-specific overview with usage notes & attribution
- `LICENSE` – Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0) license text

## Sprite Folder Template
Create a new folder under `sprites/` named after the sprite or pack you are adding, and include:
- `assets/` containing editable source files
- `preview/` containing at least one rendered preview image or animation
- `docs/` (optional) for related notes, palettes, or turnaround sheets
- `README.md` summarizing the sprite, listing included files, resolution, palette, and attribution requirements
- `metadata.json` (optional) for structured data such as frame timings, tile size, or tags
