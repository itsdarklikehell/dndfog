# DnD Fog

Create battlemaps for tabletop RPGs, like D&D.

## Features

- Infinite grid
- Add and remove a fog of war effect
- Import maps from image files
- Place, move and remove pieces on a grid (can be matched to image grid)
- Place 1x1, 2x2, 3x3, or 4x4 pieces
- Make markings on the map to show areas of effect or point out things to the players
- Save and load file to a single JSON file (no need to keep the image file separately!)

## Installation

```bash
pip install dndfog
```

## Usage

```bash
dndfog
```

Or run from source:

```bash
python -m dndfog
```

## Platform Support

> **Note:** Program is Windows only for now. This is due to the saving and loading widgets being Windows only (using pywin32). You're free to modify the code to add file loading and saving for other platforms.

## Development

```bash
poetry install
poetry run dndfog
```

## Testing

```bash
poetry run pytest
```

## License

MIT
