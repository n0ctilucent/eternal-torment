# Eternal Torment 🎃👻

A sandbox repository dedicated to coding practice, experimentation, and continuous learning.

## About 🕸️

This repo is a functional testing ground for various languages, build systems, and technical experiments. Expect frequent structural changes — the architecture will evolve as new concepts are explored.

## Project Index 🔦

| Category | Directory | Description |
|----------|-----------|-------------|
| Low-Level & Assembly | [ass/](src/ass/) / [ass-intel-x86/](src/ass-intel-x86/) | AArch64 & x86 assembly practice with GNU Autotools build pipeline |
| C / Graphics | [cube1/](src/cube1/) · [freeglut/](src/freeglut/) · [SpinningCube/](src/SpinningCube/) | OpenGL/GLUT rendering experiments — rotating cubes, X11 demos |
| FizzBuzz Collection | [FIZZBUZZ/](src/FIZZBUZZ/) | FizzBuzz implemented in 10+ languages (C, Go, Rust, Ruby, Elixir, Java, Lisp, NASM, Python, Fortran, Scala, VB) — see individual language subdir READMEs for build instructions |
| Crypto 🔐 | [trithemius/](src/trithemius/) | Trithemius cipher implementations in C and Python |
| Algorithm Challenges 💀 | [hackerrank/](src/hackerrank/) · [projecteuler.net/](src/projecteuler.net/) | HackerRank scripts, Project Euler solutions (Problems 1, 2, 3, 5, 31) |
| Math & Vectors 🧮 | [calc-pi/](src/calc-pi/) · [vectors/](src/vectors/) | Pi calculation and vector math operations |
| Encoding / Misc 🕯️ | [railfence/](src/railfence/) · [vigenere/](src/vigenere/) · [noise/](src/noise/) | Rail fence cipher, Vigenere cipher, noise generation |
| ML — GCN 🧠 | [models/ml-gnn/](models/ml-gnn/) | Applying Graph Convolutional Networks to security infrastructure analysis. Includes collection module, training pipeline, visualization tools, and research paper |
| ML — HTML Parsing 🔮 | [models/model-html/](models/model-html/) | SAEPIO dataset ingestion, Kaggle data pipelines, CML-based GitHub Actions for model training |
| Containers 📦 | [container/](container/) | Podman/Docker configurations: Kali base image, custom networking, puzzle1 CTF container |
| Automation ⚙️ | [bin/](bin/) · [.devcontainer/](.devcontainer/) | Repo bootstrap and cleanup scripts |

## Quick Start 🚀 — Assembly (AArch64)

Requires ARM64 system or cross-emulator (qemu-user).

```sh
cd src/ass
chmod +x setup.sh && ./setup.sh
```

This handles the `aclocal → autoreconf → configure → make` pipeline.

## Quick Start 🐍 — Python ML Projects

See individual subproject READMEs for environment setup. Both `models/ml-gnn/` and `models/model-html/` manage their own dependencies via Docker, requirements.txt, or conda environments.

## Docs & References 📚

- [docs/README.md](docs/README.md) — Full repository taxonomy with navigation links
- [docs/graphers/](docs/graphers/) — TI-83/TI-85 calculator ram graphing tools
- [docs/drawio-nn-templates/](docs/drawio-nn-templates/) — Neural network architecture templates for Draw.io

## License ☠️

Feel free to use snippets from this repository for your own practice.

## Maintainers 🩸

[@theDevilsVoice](https://github.com/thedevilsvoice)

---

⛧ Draft by **n0ctilucent** | [bitsmasher.net/research](https://www.bitsmasher.net/research/)
