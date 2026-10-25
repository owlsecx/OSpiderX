# 🦉 OSpiderX

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-0a0c10?style=flat-square"/>
  <img src="https://img.shields.io/badge/Category-OWeb-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-1.1-cyan?style=flat-square"/>
</p>

> **OSpiderX** — Internal Link Crawler Suite

---

> ⚠️ **AUTHORISED USE ONLY** — Use only on systems you own or have explicit written permission to test. Unauthorised use is illegal.

---

## 📌 Overview


OSpiderX is an internal link-crawler suite that maps a website using iterative breadth-first crawling with optional JavaScript rendering. It respects robots.txt, applies rate limiting with jitter and retries, supports session-based login and subdomain crawling, and extracts links for sitemaps. Output can be written as TXT, JSON, CSV or GraphML, with an optional visual sitemap PNG.

---

## ✨ Features


- Iterative BFS crawling (no recursion-stack risk) with pre-compiled regex link extraction
- Optional JavaScript rendering via Playwright for dynamic pages
- Robots.txt respect, rate limiting with jitter, retries and configurable timeouts/depth
- Session-based login support, custom header injection and subdomain crawling
- Keyword / regex URL filtering and output as TXT, JSON, CSV or GraphML
- Optional visual sitemap PNG, NO_COLOR/piped-output support and a non-interactive CLI mode

---

## ⚙️ Requirements

- **Linux**
- **No Python installation needed** — runs as a standalone executable

---

## 🚀 Usage


```bash
./OSpiderX --url https://example.com --depth 3 --format all --output run1
./OSpiderX --url https://example.com --js --subdomains --sitemap
./OSpiderX --url https://example.com --rate 2 --no-robots
./OSpiderX --self-test
./OSpiderX --help
```

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 300+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

MIT License — © Khaled S. Haddad

*Tools are distributed as pre-built executables. Source code is proprietary.*
