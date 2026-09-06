# Mervin Mandanna

Computer vision and applied machine learning — and the software that carries it.

I build systems that look at the physical world and decide something about it. Right now that means deep learning for industrial inspection at Patil I-Labs. Before that, malware detection research at IIT Roorkee. Throughout, I ship full products, because a model that never leaves the notebook isn't worth much.

[Portfolio](https://www.nemisys.dev/film) · [LinkedIn](https://www.linkedin.com/in/mervin-mandanna/) · [Email](mailto:mervin10122004@gmail.com)

```
WORK        Computer vision · Patil I-Labs
RESEARCH   Purpose-Scoped Consent Withdrawal in Federated Personalization:Erasure Efficacy, Withdrawal Leakage, and Privacy Accounting
ELSEWHERE  ByteXync · CTFs · one unexplained puzzle
```

## Now

**Intern–Scientist at Patil I-Labs**, building computer vision for Machine Vision Inspection Systems — automated defect detection on railway wheels. Line-scan imagery, geometric correction, wheel boundary extraction, segmentation, and synthetic data for the defect classes reality doesn't hand you enough of.

Four things hold my attention alongside it:

- Multi-view geometry and reconstruction from line-scan and photogrammetric imagery
- Synthetic data for defect classes that barely exist in the wild
- Hybrid static/dynamic analysis for Android malware, continuing the IIT Roorkee work where I co-authored a paper on a hybrid detection framework
- Getting models out from behind notebooks and into APIs someone can actually call

## Selected work

> The work I'm proudest of right now — inspection models, malware research — lives in institutional and private repositories. What follows is the public half: things I built end to end, and can show you.

### 01 · Axios

An agent that finds internships, rewrites your resume for each one, and applies on your behalf.

`Flask` · `Next.js` · `MongoDB` · `Selenium` · `Gemini`

Job boards don't talk to each other, and a static resume loses to a keyword filter it never sees. Axios scrapes Internshala, LinkedIn and Unstop into one index, scores a resume against a specific posting, rewrites it, and drives the application through a real browser session. A Chrome extension captures postings from anywhere and syncs them back. The hard part wasn't the model — it was keeping three brittle scrapers alive behind one stable API.

[Repository →](https://github.com/NemisysT/Axios)

### 02 · Equiflow

Equity for open-source contributors, computed from what they actually committed.

`Solidity` · `Hardhat` · `OpenZeppelin` · `Next.js`

An ERC-20 contract that maps GitHub usernames to wallets, scores contribution — commits, pull requests, reviews, issues resolved, lines moved — and distributes revenue against it. Contributors lapse after an inactivity threshold; only an authorised backend can write scores; the surface is reentrancy-guarded and pausable. Small on purpose: it's the one project here where the rules live in the contract rather than my backend, and can't be quietly changed later.

[Repository →](https://github.com/NemisysT/Equiflow)

### 03 · Alertic

Real-time disaster alerts, community reporting, and an assistant that stays useful under pressure.

`Next.js` · `Flask` · `PostgreSQL` · `Prisma` · `Leaflet` · `Gemini`

Official disaster feeds are authoritative but slow. People on the ground are fast but unverified. Alertic puts both on one map — live regional alerts beside user-submitted reports, with community verification to keep the second kind honest — plus a Gemini-backed assistant for preparedness and response questions.

[Live](https://alertic.vercel.app) · [Repository →](https://github.com/NemisysT/Alertic)

### 04 · DigiGrub

A campus canteen that takes the order before the queue forms.

`Next.js` · `FastAPI` · `Supabase` · `TypeScript`

Pre-ordering, live menu availability, and stock that decrements as orders land, so the kitchen and the students are looking at the same numbers. A small, sharply-scoped FastAPI service — one route per operation, JWT auth, no cleverness — behind a Next.js storefront and an admin dashboard.

[Repository →](https://github.com/NemisysT/DigiGrub)

## Stack

The methods I reach for first: CNNs, segmentation, feature matching, homography estimation, multi-view geometry. Then whatever it takes to put the result behind an API someone else can call.

- **Vision and learning** — `PyTorch` `TensorFlow` `OpenCV` `scikit-image` `scikit-learn` `NumPy` `COLMAP`
- **Backend and data** — `Python` `Go` `C++` `FastAPI` `Flask` `Node.js` `PostgreSQL` `MongoDB`
- **Interface** — `TypeScript` `React` `Next.js` `Tailwind`
- **Malware analysis** — `Androguard` `DroidBox` `Cuckoo Sandbox`
- **Foundation** — `Docker` `Linux` `Git` `AWS`

## Elsewhere

I'm secretary of ByteXync, my college's technical club. I wrote a CTF challenge for it once — a pirate-themed web puzzle whose README is deliberately useless as documentation and fairly good as a riddle. [It's still up](https://github.com/NemisysT/Savvy-Gibbs), and I won't be explaining it.

I play CTFs and keep a competitive programming habit, mostly because both punish the same mistake: believing you understood the problem before you read it twice.

## Contact

Email is fastest, and I answer.

[mervin10122004@gmail.com](mailto:mervin10122004@gmail.com) · [LinkedIn](https://www.linkedin.com/in/mervin-mandanna/) · [Portfolio](https://portfolio-s4pa-one.vercel.app/)
