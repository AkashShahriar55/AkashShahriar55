# Akash Shahriar

**Senior Mobile Engineer** — Flutter, Kotlin Multiplatform, Android.

I build mobile products end to end, usually the parts that have to work in real time or handle money.

Currently at **365 Retail Markets (CHEQ)**, where I own the checkout and transaction core of a restaurant POS client that ships from a single Flutter codebase to four hardware form factors — terminal, handheld, and two kiosk orientations.

Before that: carrier apps at **Portonics** for Robi Axiata, True Corporation and ATOM Myanmar, and three years at **Kite Games** shipping consumer photo and video apps to millions of users, working close to the metal with OpenGL, FFmpeg and the Android NDK.

---

### What I work on

**Real-time & AI** — Took a full-duplex AI voice-ordering agent from proof of concept to production: streaming speech-to-text and text-to-speech, LLM ordering grounded in live menu data through a RAG pipeline, and a native audio plugin handling acoustic echo cancellation and mid-sentence interruption. Most of the difficulty was concurrency, not prompting.

**Architecture at scale** — Led a migration off a legacy Provider codebase onto a clean multi-package architecture (BLoC/Cubit, `get_it`/`injectable`, `go_router`), retiring ~360K lines of legacy code once the new app reached feature parity.

**Reliability** — Closed a recurring class of Cubit-lifecycle and navigation race conditions by replacing reactive redirects with an explicit route-guard controller, ending a repeat production failure.

**Low-level media** — Video and audio processing engines built on OpenGL surfaces, BufferQueue and MediaCodec; FFmpeg pipelines with LRU-cached fallbacks.

---

### Tech

**Mobile** — Flutter · Dart · Kotlin · Kotlin Multiplatform · Jetpack Compose · Compose Multiplatform · Swift (platform channels)

**Architecture** — Clean / multi-package · MVVM · MVI · BLoC/Cubit · Riverpod · offline-first sync · server-driven UI

**AI & real-time** — OpenAI · Gemini · RAG · LangChain · streaming STT/TTS (Deepgram) · native audio · WebSocket · NATS

**Platform** — OpenGL ES · FFmpeg · Android NDK/JNI · MediaCodec · TensorFlow Lite

**Backend & infra** — Node.js · NestJS · FastAPI · PostgreSQL · MongoDB · Docker · AWS · GCP · Firebase · CI/CD (GitLab, CircleCI, Fastlane)

---

### Shipped

**Telecom & consumer, at Portonics**

| App | What it is |
|---|---|
| My Robi | Self-care app for Robi Axiata, Bangladesh |
| dtac | Self-care app for True Corporation, Thailand — 10M+ downloads |
| ATOM Eagle | Retailer and field-sales app for ATOM Myanmar |
| BDTickets | Ticketing app, Bangladesh |

**Consumer photo & video, at Kite Games**

Add Music to Video · Color Splash · Slideshow Maker · Logo Maker · Blur Photo · Background Eraser · iVibrate — 10+ apps at a 99.8% crash-free session rate, with ML-driven photo features built on TensorFlow Lite, Huawei ML Kit and OpenGL ES.

**Products at CookieTech, where I'm a co-founder**

| Product | What it is |
|---|---|
| ParkSight | Peer-to-peer parking marketplace with Stripe Connect payouts |
| AIDeskHub | AI voice-receptionist SaaS, backed by 798 automated tests |
| NostalgAI | iOS AI photo restoration — concept to App Store in one month |
| GangIt | B2B SaaS for DTF print shops with a high-resolution render engine |
| MediMind | AI prescription scanning and medication adherence |
| Fitness Room Concierge | Maintenance-as-a-service platform for gyms |

---

### Writing & research

- **"An Intelligent Bangla Conversational Agent: TUNI"** — co-author, Springer Nature, *Algorithms for Intelligent Systems*, 2020.
- Champion, Grameenphone Hackathon.

---

### Elsewhere

[LinkedIn](https://www.linkedin.com/in/akash-shahriar-784362194/) · [Toptal](https://www.toptal.com/developers/resume/akash-shahriar) · [LeetCode](https://leetcode.com/akashshahriar55/) · [akashshahriar55@gmail.com](mailto:akashshahriar55@gmail.com)
