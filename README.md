<div align="center">

# ⚡ Zakar'IA

### Building sovereign P2P infrastructure in Rust — one proof at a time.

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=6E56CF&center=true&vCenter=true&width=600&lines=Founder+%26+Architect+%40+Kyberon;Rust+%C2%B7+WASM+%C2%B7+P2P+%C2%B7+Post-Quantum+Crypto;Don't+trust+the+server.+Prove+the+code." alt="Typing SVG" />

[![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)](https://www.rust-lang.org/)
[![WASM](https://img.shields.io/badge/WebAssembly-654FF0?style=for-the-badge&logo=webassembly&logoColor=white)](https://webassembly.org/)
[![Leptos](https://img.shields.io/badge/Leptos-EF3939?style=for-the-badge&logo=leptos&logoColor=white)](https://leptos.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)

</div>

---

### 👋 About

I'm an independent builder working on **Kyberon**, a peer-to-peer infrastructure engine written in Rust, plus the applications built on top of it. My focus is on correctness: using formal methods where they matter most, and being honest about what's proven versus what's still a prototype.

I care more about shipping something that actually works — and saying clearly what doesn't yet — than about buzzwords.

---

### 🛡️ Kyberon — Sovereign P2P Infrastructure

A Rust core engine (~20 crates) exploring how much of the centralized cloud can be replaced by a verifiable, peer-to-peer mesh. It's **early**: the core is an alpha, single-node in-memory prototype, and I re-measure claims rather than hardcode them.

**What's real today**

| Area | Status | Notes |
| :--- | :--- | :--- |
| 🔐 Ghost-Payments | ✅ **Kani-proven** | No underflow + mass conservation, verified with model checking |
| 📡 BLE Mesh (`ble-core`) | 🟡 Alpha | X25519 + Kyber-768 hybrid handshake, 10/10 tests |
| 📻 LoRa (`radio-lora`) | 🟡 Alpha | Reed-Solomon FEC, 12/12 tests — hardware not yet tested |
| 🔁 Proof-of-Relay | 🟡 Alpha | Rewards + anti-replay, 8/8 tests |
| 🌐 sdk-relay-web (WASM) | 🟡 Alpha | ~225 KB gzipped, 11/11 tests |

> 🔎 **Honest by design:** I removed previously published metrics that weren't reproducible. Benchmarks are Criterion micro-benchmarks (single-thread, in-memory) — real distributed throughput will differ and is being re-measured.
>
> ---
>
> ### 🛰️ Applications built on Kyberon
>
> | Project | What it is | Status |
> | :--- | :--- | :--- |
> | **Zaya** | Live streaming & creator platform | 🟢 v1 in production, migrating to Rust/WASM |
> | **Illimeet** | Encrypted P2P video conferencing (WebRTC) | 🔵 Beta |
> | **Quilyt** | Leptos/WASM front-end experiment | ⚪ R&D (frozen) |
>
> ---
>
> ### 🧰 Tech I work with
>
> <div align="center">

**Core** — Rust · WebAssembly · Leptos · Axum · SQLx <br/>
**Crypto** — Ed25519 · Kyber-768 (PQC) · X25519 · AES-256-GCM <br/>
**Verification** — Kani · Proptest · Miri · cargo-audit <br/>
**Backend / Infra** — NestJS · Prisma · PostgreSQL · Docker · Prometheus · Grafana

</div>

---

### 📊 GitHub Stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=zakjeddi&show_icons=true&hide_border=true&theme=tokyonight&count_private=true" alt="stats" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=zakjeddi&layout=compact&hide_border=true&theme=tokyonight&langs_count=6" alt="top langs" />

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=zakjeddi&hide_border=true&theme=tokyonight" alt="streak" />

</div>

---

<div align="center">

📍 Rabat, Morocco · 🌐 kyberon.io *(coming soon)*

_"Don't trust the server. Prove the code."_

</div>
