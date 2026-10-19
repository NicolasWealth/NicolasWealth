<div align="center">

# Nicolas Wealth

### Computer Engineer &middot; Software, Security &amp; AI

*Computer Engineering student &middot; Lagos, Nigeria &middot; Open to remote roles*

[![Profile Views](https://komarev.com/ghpvc/?username=NicolasWealth&color=8E7CFF&style=flat-square)](https://github.com/NicolasWealth)

</div>

---

## About Me

I'm a Computer Engineering student (final exams and final year project complete, convocation 2027) building full stack software and security tools for AI systems. My focus is **AI security**, **data privacy** and **LLM integration**, and I am deepening the AI side through Anthropic's applied AI coursework (Claude API, prompt engineering, responsible AI deployment).

I back it with shipped code: a zero trust proxy for AI prompts, a fake profile detection system with a Chrome extension and dashboard, a browser fingerprinting defense extension, a recall records tool and a smart contract app. All self built, all live. When an AI coding agent told me a feature was finished, I tested it. Two of those claims were false, and I fixed both.

Background: eight month cybersecurity internship (networking, penetration testing) plus self taught depth across AI, Web3, and security tooling.

---

## AI Security & Data Governance Projects

| Project | What it does | Stack |
|---|---|---|
| [**Zero Trust AI Gateway**](https://github.com/NicolasWealth/Zero-Trust-AI-Gateway) &middot; [demo](https://zero-trust-ai-gateway.vercel.app/) | Node.js security proxy between your app and OpenAI. Removes PII and credentials from prompts, never stores the original prompt, rate limits per IP, and keeps a hash chained audit log that detects edits. Browser console, tests and CI. The public demo does not call a model. | Node.js &middot; Express &middot; Supabase &middot; GitHub Actions |
| [**Smart Fake Profile Detection System**](https://github.com/NicolasWealth/smart-fake-profile-detection-system) &middot; [demo](https://smart-fake-profile-detection-system.vercel.app/) | Final year project. End to end ML system detecting fake profiles across Instagram, TikTok, and Facebook. Chrome extension extracts profile signals client side, FastAPI backend runs a trained Random Forest classifier at 92.9% recall, results stored in Supabase and surfaced on a React/Vite analytics dashboard. | Python &middot; FastAPI &middot; Random Forest &middot; Supabase &middot; React/Vite |
| [**TraceShield**](https://github.com/NicolasWealth/TradeShield) &middot; [demo](https://trade-shield-omega.vercel.app/) | Hackathon project. Recall tool for food companies: maps batches to records, scores exposure against record reliability, and shows whether custody records were changed using SHA 256 fingerprints and read only Base Sepolia checks. On chain signing is not finished, and the README says so. | TypeScript &middot; React &middot; SHA 256 &middot; Base Sepolia |
| [**Sentinel OS**](https://github.com/NicolasWealth/Sentinel-OS) &middot; [demo](https://sentinel-os-delta.vercel.app/) | Chrome extension that actively poisons canvas, audio, and WebGL browser fingerprinting APIs in real time. Shared live protection stats via Firebase Realtime DB with atomic increments across all installs. | React &middot; Manifest V3 &middot; Firebase &middot; Vite |

---

## Web3 / Blockchain Projects

| Project | What it does | Stack |
|---|---|---|
| [**PromiseChain**](https://github.com/NicolasWealth/Promise-Chain) &middot; [demo](https://promise-chain-three.vercel.app/) | Hackathon project. Lock ETH in a smart contract as a promise tied to GitHub proof of work (a merged pull request, closed issue or commit). The app checks the proof, the contract releases the money, and a public reputation history is kept. Runs on the Ethereum Sepolia test network. | TanStack Start &middot; wagmi &middot; viem &middot; Hardhat |

---|---|---|
| [**Agent Hub**](https://github.com/NicolasWealth/agent-hub) | Decentralized AI agent marketplace on Hedera. Clients post tasks with HBAR budgets, agents claim them and submit proof of work via Hedera Consensus Service, payments settle on chain. | React &middot; TypeScript &middot; Hedera SDK |
| [**Somnia Dream Vault**](https://github.com/NicolasWealth/somnia-dream-vault) | Reactive DeFi vault on Somnia L1. Users set trigger prices to autonomously protect assets via Solidity smart contracts with sub second finality. | Solidity &middot; React &middot; Wagmi &middot; Viem |
| [**Nexus AI**](https://github.com/NicolasWealth/Nexus-ai) | Autonomous cross chain liquidity optimizer dashboard. Real time Firebase backed agent loop with a generative particle background. | React &middot; TypeScript &middot; Firebase |
| [**Emerald Flux Splitter**](https://github.com/NicolasWealth/emerald-flux-splitter) | On chain DeFi revenue splitting protocol. | TypeScript &middot; Solidity |

---

## Stack

**AI / ML**

![Anthropic](https://img.shields.io/badge/Claude_API-D97757?style=flat-square&logo=anthropic&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI_API-412991?style=flat-square&logo=openai&logoColor=white)
![Google Gemini](https://img.shields.io/badge/Gemini_AI-4285F4?style=flat-square&logo=google&logoColor=white)

**Languages**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Solidity](https://img.shields.io/badge/Solidity-363636?style=flat-square&logo=solidity&logoColor=white)

**Security & Testing**

![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**Backend & Cloud**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)

**Web3**

![Ethereum](https://img.shields.io/badge/Ethereum-3C3C3D?style=flat-square&logo=ethereum&logoColor=white)
![Hardhat](https://img.shields.io/badge/Hardhat-FFF100?style=flat-square&logo=ethereum&logoColor=black)

---

## GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=NicolasWealth&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true" height="155" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=NicolasWealth&layout=compact&theme=tokyonight&hide_border=true" height="155" />
</p>

---

## Currently

- Final exams and final year project complete, convocation 2027
- Studying for CompTIA Security+, then CompTIA SecAI+ and CAISP
- Deepening applied AI skill through Anthropic's applied AI coursework
- Open to remote AI security, full stack software and IT support roles

---

## Connect

- Portfolio: [nicolaswealth.netlify.app](https://nicolaswealth.netlify.app/)
- LinkedIn: [nicolas oluremekun](https://www.linkedin.com/in/nicolas-oluremekuna13b762a2/)
- Twitter / X: [@NOluremeku26373](https://twitter.com/NOluremeku26373)
- Email: [nicolasproperties3@gmail.com](mailto:nicolasproperties3@gmail.com)

---

<div align="center">
<sub>Building AI powered applications, and the security layer they need to be trusted in production.</sub>
</div>
