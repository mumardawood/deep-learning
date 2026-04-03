# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a deep learning educational project using TensorFlow/Keras. The primary content consists of Jupyter notebooks in the `notebook/` directory.

## Commands

```bash
# Install dependencies
uv sync

# Run the main Python script
python main.py

# Run a Jupyter notebook
jupyter notebook notebook/01/notebook_01.ipynb
```

## Architecture

- **notebook/**: Contains Jupyter notebooks with deep learning examples (notebook_01.ipynb is the first)
- **main.py**: Simple entry point script
- Uses **uv** for dependency management (pyproject.toml based)

## Dependencies

- tensorflow>=2.21.0
- torch>=2.11.0
- ipykernel>=7.2.0