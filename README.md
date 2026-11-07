# ◆ Fuma Digital

![i18n](https://img.shields.io/badge/i18n-EN%20%7C%20ID%20%7C%20JA-7c5cff?style=for-the-badge)
![Site](https://img.shields.io/badge/site-live-2eff94?style=for-the-badge)
![License](https://img.shields.io/badge/use-freely-lightgrey?style=for-the-badge)

Portfolio site for Fuma Digital — smart contract audits, AI chatbots, landing pages & Python automation.

**Live:** https://fuma2514.github.io/fuma-digital/

## Languages 🌐

The site ships in three languages, switchable from the header (EN / ID / JP) with the choice persisted in `localStorage`:

| Lang | Coverage |
|------|----------|
| 🇬🇧 English | default (built into the markup) |
| 🇮🇩 Bahasa Indonesia | 60 translated strings |
| 🇯🇵 日本語 | 60 translated strings |

Implementation: lightweight vanilla-JS i18n layer (`data-i18n` attributes + `I18N` dictionary + `setLang()`), no dependencies, no page reload.
