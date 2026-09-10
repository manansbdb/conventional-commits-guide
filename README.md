<p align="center">
  <img src="docs/banner.svg" alt="Conventional Commits Guide banner" width="100%" />
</p>

<h1 align="center">conventional-commits-guide</h1>

<p align="center">
  <strong>EN</strong> Conventional Commits cheatsheet (PT/EN)<br/>
  <strong>PT</strong> Cheatsheet de Conventional Commits (PT/EN)
</p>

<p align="center">
  <a href="https://github.com/manansbdb/conventional-commits-guide/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-MIT-22c55e?style=for-the-badge" alt="MIT" /></a>
  <img src="https://img.shields.io/badge/lang-EN%20%7C%20PT-3b82f6?style=for-the-badge" alt="EN PT" />
  <img src="https://img.shields.io/badge/commits-FE5196?style=for-the-badge" alt="commits" />
  <a href="#support--apoio"><img src="https://img.shields.io/badge/donate-BTC-f59e0b?style=for-the-badge" alt="Donate BTC" /></a>
</p>

---

## What it does / Para que serve

| English | Português |
|---------|-----------|
| A bilingual **Conventional Commits** cheatsheet for consistent commit messages. | Uma cheatsheet bilingue de **Conventional Commits** para mensagens consistentes. |
| Keep `CHEATSHEET.md` open while writing commits or configuring commitlint. | Mantém `CHEATSHEET.md` aberto ao escrever commits ou configurar commitlint. |

```mermaid
flowchart LR
  A["💬 Change"] --> B["🏷 type(scope)!"]
  B --> C["📄 CHEATSHEET.md"]
  C --> D["✅ Clear history"]
  style A fill:#0ea5e9,stroke:#0369a1,color:#fff
  style B fill:#FE5196,stroke:#be185d,color:#fff
  style C fill:#6366f1,stroke:#4338ca,color:#fff
  style D fill:#22c55e,stroke:#15803d,color:#fff
```

---

## Install / Instalação

### 1) Clone / Clona

```bash
git clone https://github.com/manansbdb/conventional-commits-guide.git
cd conventional-commits-guide
```

### 2) Copy into docs / Copia para docs

```bash
mkdir -p /path/to/your-project/docs
cp CHEATSHEET.md /path/to/your-project/docs/conventional-commits.md
```

### Requirements / Requisitos

- `git`
- Optional: commitlint / husky

---

## Quick start / Início rápido

```bash
git clone https://github.com/manansbdb/conventional-commits-guide.git
# open CHEATSHEET.md — use feat:/fix:/docs: prefixes
```

---

## Contents / Conteúdos

| Path | Purpose / Função |
|------|------------------|
| `CHEATSHEET.md` | Types, scopes, examples |
| `SUPPORT.md` | Donations / Doações |

---

## Project layout / Estrutura

```text
conventional-commits-guide/
├── docs/banner.svg
├── CHEATSHEET.md
├── SUPPORT.md
└── README.md
```

---

## Support / Apoio

Bitcoin donations welcome / Doações em Bitcoin bem-vindas:

```
bc1q0qfnlnxyum9u45stzxe0a7jnhtj4j0usfkqdjw
```

See [SUPPORT.md](./SUPPORT.md).

---

## License / Licença

[MIT](./LICENSE) © 2026 manansbdb
