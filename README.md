<!--
GitHub PROFILE README for github.com/Arcco-Chakraborty
To use: create a repo named EXACTLY "Arcco-Chakraborty", add this as README.md, commit.
It renders at the top of your profile.

Before committing, check:
  - PROJECT LINKS: the live-site links (Arctronas, BlackMoniker) are public and fine.
    The repo links (pillflight, jarvis, auto-prompter) only resolve if those repos are
    PUBLIC. PillFlight is GPL-3.0, so it's the natural one to open up first. For any repo
    you keep private, delete the link and leave the bold name.
  - YOUTUBE_LINK and the email at the bottom -> drop in your real ones.
Delete the optional stats block at the end if you don't want it.
-->

# Arcco

First-year CSE @ BITS Pilani, Pilani. I build things end to end: firmware, full-stack web, and ML pipelines. The fun part is wiring all three together, a model running on a box I flashed myself talking to a backend I shipped. Most of my projects start as "can I actually build this" and end up deployed. No fluff, pure creation.

#### Currently
- Building neural nets from scratch with Karpathy's *Neural Networks: Zero to Hero*: autograd, language models, a GPT, all by hand
- On the AI/ML team at SUTT (BITS Pilani)
- Getting into open source, mostly the scientific-Python / ML ecosystem

#### Featured projects
**[PillFlight](https://github.com/Arcco-Chakraborty/pillflight)** · Open-source quadcopter flight controller running on the ~$3 STM32F411 "BlackPill." Currently flying: self-leveling, heading hold, hover, automatic in-flight IMU failover, iBUS telemetry, and power-loss-surviving blackbox logging. No RTOS, one deterministic super-loop, register-level drivers, Mahony AHRS. Ships with a Python/Tkinter ground station and blackbox/PID/vibration diagnostic tools. GPL-3.0.

**[JARVIS](https://github.com/Arcco-Chakraborty/jarvis)** · Self-hosted, local-first home voice assistant with a hand-gesture control layer. Wake-word to on-device STT/TTS, controls ESP32 relays and PC apps, optional Gemini fallback. The gesture module runs MediaPipe Hands through a one-euro filter and a stability buffer, firing discrete device intents while streaming continuous hand state to a Three.js holographic HUD over WebSocket.

**[BlackMoniker](https://blackmoniker.com)** · AI planner, "paste the mess, get the plan." Deployed. Drop in raw text or a PDF (a syllabus, an email, a voice-memo transcript) and about 25 seconds later you get a structured tracker: ordered phases, extracted and normalized deadlines, weighted progress, a due-soon dashboard, and one-click Google Calendar / .ics export.

**[Arctronas](https://arctronas.duckdns.org)** · AI YouTube comment responder, deployed. Learns a creator's voice from their past replies and drafts new ones that sound like them. One-click YouTube OAuth, a background poller, top-fan tracking, and admin + per-client dashboards. Multi-tenant single Flask process.

#### Stack
**Languages** Python · Go · C/C++ · JavaScript/TypeScript  
**Backend** Node.js · Express · Flask · Gunicorn  
**Frontend** React · Next.js · Three.js · Vite  
**ML/AI** Gemini API · PyTorch · NumPy · MediaPipe · OpenCV  
**Data** SQLite · MongoDB  
**Hardware** ESP32 · STM32 · Arduino  
**Infra** Linux VPS administration · Nginx · systemd · fail2ban · Git  

#### Elsewhere
I document builds on YouTube at [ArcTek Systems](https://www.youtube.com/@arcteksystems). Reach me at arcco.chakraborty@gmail.com.

<!-- Optional stats card. Delete this block if you don't want it. -->
![Arcco's GitHub stats](https://github-readme-stats.vercel.app/api?username=Arcco-Chakraborty&show_icons=true&hide_border=true&count_private=true)
