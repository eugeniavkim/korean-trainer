# 한국어 AI 보안 타이핑 — Korean AI Security Typing Trainer

A Korean typing trainer for AI researchers, ML engineers, and security professionals. Practice the technical vocabulary you actually use — in Korean. Built to run offline.

---

## What's inside

Hundreds of terms across 8 technical categories, with definitions, romanization, and PyTorch code snippets for key AI/ML concepts.

| Category | What it covers |
|---|---|
| 🛡 보안 | Core cybersecurity vocabulary |
| 🤖 AI/ML | Machine learning and AI terminology |
| ⚔️ 공격 | Attack techniques and threat vocabulary |
| 🔒 방어 | Defense, hardening, and mitigation |
| 📋 규정 | Compliance, governance, policy |
| 🏢 기업 | Corporate and professional Korean |
| 🔐 암호화 | Cryptography and encryption |
| 📄 Academic | Academic writing, paper structure, conference vocabulary |

---

## Features

- **Smart timer** — color shifts green → yellow → red as you use up your time budget per term
- **Three difficulty levels** — 🌱 Easy (0.9s/char) · ⚡ Medium (0.55s/char) · 🔥 Hard (0.30s/char)
- **🔀 Shuffle mode** — randomizes the word list so you're never memorizing order
- **▸ PyTorch snippets** — tap to reveal runnable PyTorch code for key AI/ML terms (FGSM, adversarial training, federated learning, knowledge distillation, and more)
- **▸ Definition panel** — English definitions for security and compliance terms
- **Romanization toggle** — show or hide pronunciation guides
- **Personal best tracking** — records your fastest time per word, saved to local storage
- **Glossary tab** — browse all terms by category
- **Keyboard tab** — full 두벌식 layout reference + setup instructions for iPhone and Windows
- **Offline PWA** — install once, works forever without internet

---

## PyTorch snippets included for

- 적대적 예제 — FGSM attack
- 데이터 포이즈닝 — label-flip poisoning
- 적대적 훈련 — PGD adversarial training loop
- 트랜스포머 — TransformerBlock class
- 차분 프라이버시 — Opacus DP-SGD
- 연합 학습 — FedAvg aggregation
- 역전파 — annotated training step
- 지식 증류 — soft/hard distillation loss
- 멤버십 추론 공격 — shadow model MIA

---

## Install on iPhone

1. Open the [URL](https://eugeniavkim.github.io/korean-trainer/) in **Safari**
2. Tap the Share button → **Add to Home Screen**
3. Open it once on WiFi to cache everything
4. Works offline from then on

## Enable Korean keyboard on iPhone

Settings → General → Keyboard → Keyboards → Add New Keyboard → **Korean (2-Set)**

Tap the 🌐 globe key while typing to switch between English and Korean.

---

## Files

```
index.html      — the entire app (all vocab, logic, and styles in one file)
manifest.json   — PWA metadata (name, icon, theme color)
sw.js           — service worker for offline caching
```

Only `index.html` needs to be updated when making changes. `manifest.json` and `sw.js` are static.

---

## Who this is for

AI/ML researchers and security professionals who want to build Korean technical vocabulary — for reading papers in Korean, collaborating with Korean colleagues, attending Korean conferences, or just filling the gap between conversational Korean and professional Korean.

---

## Built with

Vanilla HTML/CSS/JS · Noto Sans KR · IBM Plex Mono · No frameworks · No dependencies · No server
