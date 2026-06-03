# 📖 Hadith BD (হাদিস বিডি)

A blazing-fast, minimalist, and Zero-JS Hadith reading platform built with **Astro**, **Cloudflare D1**, and **Tailwind CSS v4**. Designed with a "Low Cognitive Load" principle to provide the best reading experience for authentic Hadiths in Bengali.

![Astro](https://img.shields.io/badge/Astro-0C1628?style=for-the-badge&logo=astro&logoColor=white)
![Cloudflare Pages](https://img.shields.io/badge/Cloudflare_Pages-F38020?style=for-the-badge&logo=cloudflare&logoColor=white)
![SQLite](https://img.shields.io/badge/Cloudflare_D1-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)

## ✨ Features
- **Zero-JS Architecture:** Pure Server-Side Rendered (SSR) HTML for lightning-fast page loads.
- **Edge Global Caching:** Leverages Cloudflare Edge caching for zero-latency database responses.
- **Minimalist UI/UX:** Dark/Light mode support with optimized typography (`Amiri` for Arabic, `Hind Siliguri` for Bengali).
- **Interactive Copy:** Lightweight Vanilla JS to easily copy Hadith text with references.
- **D1 Database:** Highly scalable serverless SQLite database on Cloudflare's Edge.

## 🚀 Getting Started

### 1. Prerequisites
- Node.js (v18+)
- Cloudflare Account & `wrangler` CLI installed globally (`npm install -g wrangler`)
- SQLite3 CLI installed on your machine
