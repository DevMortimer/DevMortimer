**I love emacs and lisp.**

I build full-stack production software and the verification harnesses that keep AI coding agents honest:

- **[pi-warden](https://github.com/DevMortimer/pi-warden)** & **[pi-typesafe](https://github.com/DevMortimer/pi-typesafe)**: Runtime guardrails for Pi, Claude Code, and Codex (`199` stars, `9,000+` monthly npm downloads, `817` risky actions stopped across `3,350` real sessions at `91%` sensitivity / `97%` specificity).
- **[Warden-S1](https://ryanjoshuagapac.com/writing/warden-s1)** ([HF weights](https://huggingface.co/DevMortimer/Warden-S1-752M) · [paper](https://ryanjoshuagapac.com/papers/warden-s1-paper.pdf) · [DOI](https://doi.org/10.5281/zenodo.24494405)): Open-weight (`Apache-2.0`) `752M` System-One verification model with its own `128K`-token window (`415.5 MiB` Apple MLX-4bit / `461.3 MiB` Browser WebGPU & Node ONNX-Int4). Multiplexes `10` concurrent long-context coding sessions in `858 MiB` on Apple M5 Metal, beats commercial Cloud `Jev` (`96.1%` vs `84.9%` accuracy; `0.9957` held-out AUROC), pinpoints the guilty turn (`locus`, `93%` Top-1), and compacts old turns (`salience`, `99.98%` AUROC) for `500K+` outer sessions.
- **[carvel](https://ryanjoshuagapac.com/carvel-demo/)** ([architecture](https://git.ryanjoshuagapac.com/DevMort/carvel)): Local-first multi-agent engineering workspace in Common Lisp (SBCL) and vanilla JS (`2,920+` commits).

Previously: Founding Engineer (first hire) at [Postlight](https://postlight.ai) (SF & Singapore).

Writing: [Warden-S1 Technical Report & Browser Studio](https://ryanjoshuagapac.com/writing/warden-s1) · [My Explorations on Bettering AI](https://ryanjoshuagapac.com/writing/bettering-ai) · Personal site: [ryanjoshuagapac.com](https://ryanjoshuagapac.com)

If `pi-warden` or `Warden-S1` saved you from a bad `rm -rf`, [sponsoring](https://github.com/sponsors/DevMortimer) keeps the calibration and training runs paid for.

<div align="center">
	<img src="signal.png" alt="signal-qr" width="164" />
	<p>If you wanna be friends, message me.</p>
</div>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github.com/DevMortimer/DevMortimer/raw/refs/heads/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://github.com/DevMortimer/DevMortimer/raw/refs/heads/output/github-contribution-grid-snake.svg" />
  <img alt="github-snake" src="https://github.com/DevMortimer/DevMortimer/raw/refs/heads/output/github-contribution-grid-snake.svg" />
</picture>
