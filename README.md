# Roblox opencv exploration

This repo uses [poetry](https://python-poetry.org/). This is a prerequisite to install before doing anything else.

## Quickstart

```bash
git clone https://github.com/auser/roblox-cv2.git
cd roblox-cv2
```

Setup the poetry environment

```bash
poetry install
```

Add your images to `./data/raw/`:

```bash
cp ~/Downloads/ball.png ./data/raw/ball.png
```

Run jupyter notebook

```bash
poetry shell
jupyter notebook .
```
