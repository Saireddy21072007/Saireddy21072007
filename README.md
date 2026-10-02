# Sai Reddy Annem

**AI/ML engineering student who builds working systems, not just notebooks.**

Third-year B.Tech, Computer Science & Engineering (AI) at Amrita Vishwa Vidyapeetham, Coimbatore (graduating 2028).
I like problems where a model has to survive contact with real data: missing sensors, imbalanced labels,
noisy feeds, users who don't read instructions. Most of my projects ship with tests, a one-command
launcher, and a section that says what doesn't work yet.

Currently building **VoxAgent** — a multilingual AI phone receptionist for Indian clinics, salons and coaching institutes.

---

### Start here

| | Project | What it is | Stack |
|---|---|---|---|
| 1 | **[InterviewAce AI](https://github.com/Saireddy21072007/interviewace-ai)** | Full-stack interview prep: rule-based ATS score, voice mock interviews scored on a 5-dimension rubric, gap-driven study plan. Works fully offline; LLMs are optional. | FastAPI · React/TS · SQLAlchemy · 92 tests |
| 2 | **[disaster-risk-bayesian-network](https://github.com/Saireddy21072007/disaster-risk-bayesian-network)** | 18-node Bayesian network for flood/landslide/cyclone/heatwave risk on live public weather feeds, with explanations and MEU decisions. Beats ML baselines once ~25% of sensors drop out. | pgmpy · FastAPI · Leaflet · 85 tests |
| 3 | **[cipl-eye-disease-diagnosis](https://github.com/Saireddy21072007/cipl-eye-disease-diagnosis)** | Interpretable multi-label fundus diagnosis (8 diseases) with per-disease localisation maps and a text report. From-scratch prototype head vs. pretrained ResNet-18 + CBAM (0.85 validation mAUC). | PyTorch · Kaggle GPU |
| 4 | **[uav-apriltag-landing-sim](https://github.com/Saireddy21072007/uav-apriltag-landing-sim)** | MuJoCo quadrotor that lands on addressed, moving pads using its own camera and real AprilTag decoding. 40/40 Monte Carlo landings, ~3 cm mean error. | MuJoCo · OpenCV · control |
| 5 | **[greenscale-cloud](https://github.com/Saireddy21072007/greenscale-cloud)** | Carbon-aware multi-cloud scheduler with an ECDSA-signed, Merkle-tree ledger of every placement decision. −72% CO₂ vs. nearest-region baseline in simulation. | Flask · scikit-learn · cryptography · 72 tests |
| 6 | **[polylag](https://github.com/Saireddy21072007/polylag)** | Event-driven system that measures whether prediction markets lag the news, with paper trading and a three-layer risk manager. | asyncio · httpx · websockets · 68 tests |

Most of these were team projects; each README says who did what.

---

### What I work with

**Languages** — Python · TypeScript · SQL · MATLAB
**ML / DL** — PyTorch · scikit-learn · TensorFlow/Keras · pgmpy (Bayesian networks) · OpenCV
**AI systems** — LLM APIs (Gemini, Claude, OpenAI) behind provider-agnostic interfaces · speech-to-text / TTS pipelines · telephony (Twilio)
**Backend / web** — FastAPI · Flask · Next.js · React · Tailwind · SQLAlchemy · Prisma · PostgreSQL / SQLite
**Tooling** — Git · GitHub Actions · Docker · pytest · Kaggle · MuJoCo

### Currently building

- **VoxAgent** (private) — AI receptionist that answers calls in English, Telugu and Hindi and books appointments.
  Terminal agent → voice → real-time interruptible calls → Twilio phone numbers, with a business portal and an eval suite.
- Re-running the eye-disease experiments with a patient-level train/val/test protocol (the harness is done; the numbers aren't yet).

### Learning

Agent tooling (MCP servers, LangGraph) · prototype-based interpretability · evaluation methodology for small, imbalanced medical datasets.

### Research

- *Reinforcement Learning for 4×4 Tic-Tac-Toe: Q-Learning with Tactical Enhancements and Epsilon Decay* — IEEE ESCI 2026 (co-author). [DOI 10.1109/ESCI68015.2026.11493322](https://doi.org/10.1109/ESCI68015.2026.11493322)
- Hybrid CNN–ViT image forgery detection — co-author, under review at IEEE Access.

---

Open to AI/ML and backend internships and to collaborating on applied AI projects.
Reach me at **saireddyannem2007@gmail.com**.
