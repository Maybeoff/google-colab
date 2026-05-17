# ComfyUI Google Colab Template

[![Russian README](https://img.shields.io/badge/RUSSIAN-README-blue?style=for-the-badge)](README.ru.md)

Clear profile [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Maybeoff/google-colab/blob/main/ipynb/clear_ComfyUI.ipynb)

Anima profile [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Maybeoff/google-colab/blob/main/ipynb/ANIMA_ComfyUI.ipynb)

A ready-to-use Google Colab notebook for running **ComfyUI** in the cloud. Fully automated setup — start generating images with no hassle.

## Features

- Automatically installs the latest version of ComfyUI from source
- Three tunneling options:
  - **Cloudflare** — fast and reliable (blocked in Russia)
  - **tuna.am** — stable service for Russia/CIS users (requires registration and token)
  - **LocalTunnel** — quick and easy
- All dependencies are handled automatically

## How to Use

1. Open the notebook in Colab using the badge above
2. Enable GPU: `Runtime` → `Change runtime type` → `T4 GPU`
3. Run the ComfyUI installation cell
4. Download your models (Checkpoints, VAE, LoRA)
5. Pick a tunneling method and run its cell
6. Click the generated link — ComfyUI is ready

> For tuna.am, register at [tuna.am](https://tuna.am) and paste your token into the provided field.

---

*Made by [Maybeoff](https://github.com/maybeoff)*
