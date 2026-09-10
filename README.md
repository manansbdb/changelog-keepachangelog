<p align="center">
  <img src="docs/banner.svg" alt="Changelog Keep a Changelog banner" width="100%" />
</p>

<h1 align="center">changelog-keepachangelog</h1>

<p align="center">
  <strong>EN</strong> Bilingual Keep a Changelog template + category notes<br/>
  <strong>PT</strong> Template Keep a Changelog bilingue + notas de categorias
</p>

<p align="center">
  <a href="https://github.com/manansbdb/changelog-keepachangelog/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-MIT-22c55e?style=for-the-badge" alt="MIT" /></a>
  <img src="https://img.shields.io/badge/lang-EN%20%7C%20PT-3b82f6?style=for-the-badge" alt="EN PT" />
  <img src="https://img.shields.io/badge/topic-changelog-10b981?style=for-the-badge" alt="changelog" />
  <a href="#support--apoio"><img src="https://img.shields.io/badge/donate-BTC-f59e0b?style=for-the-badge" alt="Donate BTC" /></a>
</p>

---

## What it does / Para que serve

| English | Português |
|---------|-----------|
| A ready **Keep a Changelog** template (EN+PT) plus category guidance. | Um template **Keep a Changelog** pronto (EN+PT) com guia de categorias. |
| Drop `CHANGELOG.md` into any repo and start recording releases. | Coloca o `CHANGELOG.md` em qualquer repo e regista releases. |

```mermaid
flowchart LR
  A["🔧 Change"] --> B["📝 CHANGELOG.md"]
  B --> C["🏷️ Tag release"]
  C --> D["📢 Communicate"]
  style A fill:#3b82f6,stroke:#1d4ed8,color:#fff
  style B fill:#059669,stroke:#047857,color:#fff
  style C fill:#f59e0b,stroke:#b45309,color:#fff
  style D fill:#8b5cf6,stroke:#6d28d9,color:#fff
```

---

## Install / Instalação

### 1) Clone / Clona

```bash
git clone https://github.com/manansbdb/changelog-keepachangelog.git
cd changelog-keepachangelog
```

### 2) Copy into your repo / Copia para o teu repo

```bash
cp CHANGELOG.md /path/to/your-project/
cp categories.md /path/to/your-project/docs/changelog-categories.md
```

### Requirements / Requisitos

- `git`
- No runtime dependencies

---

## Quick start / Início rápido

```bash
git clone https://github.com/manansbdb/changelog-keepachangelog.git
cp changelog-keepachangelog/CHANGELOG.md ./CHANGELOG.md
# edit Unreleased section on every PR
```

---

## Contents / Conteúdos

| Path | Purpose / Função |
|------|------------------|
| `CHANGELOG.md` | Keep a Changelog template |
| `categories.md` | Added/Changed/Fixed notes |
| `SUPPORT.md` | Donations / Doações |

---

## Project layout / Estrutura

```text
changelog-keepachangelog/
├── docs/banner.svg
├── CHANGELOG.md
├── categories.md
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
