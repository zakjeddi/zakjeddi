<!-- =============================================================== -->
<!--                        Z A K A R ' I A                          -->
<!-- =============================================================== -->

<div align="center">

<a href="#">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:6E56CF,50:8B5CF6,100:22D3EE&height=220&section=header&text=Zakar'IA&fontSize=72&fontColor=ffffff&fontAlignY=38&desc=Sovereign%20P2P%20infrastructure%20in%20Rust%20%C2%B7%20one%20proof%20at%20a%20time&descAlignY=60&descSize=18&animation=fadeIn" width="100%" alt="header" />
</a>

<br/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=8B5CF6&center=true&vCenter=true&width=680&lines=Founder+%26+Systems+Architect+%40+Kyberon;Rust+%C2%B7+WASM+%C2%B7+P2P+%C2%B7+Post-Quantum+Crypto;Full-stack+builder+%E2%80%94+from+the+kernel+to+the+pixel;Don't+trust+the+server.+Prove+the+code." alt="Typing SVG" />

<br/><br/>

<a href="https://www.rust-lang.org/"><img src="https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white" alt="Rust"/></a>
<a href="https://webassembly.org/"><img src="https://img.shields.io/badge/WebAssembly-654FF0?style=for-the-badge&logo=webassembly&logoColor=white" alt="WASM"/></a>
<a href="https://leptos.dev/"><img src="https://img.shields.io/badge/Leptos-EF3939?style=for-the-badge&logo=leptos&logoColor=white" alt="Leptos"/></a>
<a href="https://www.typescriptlang.org/"><img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript"/></a>

<br/>

<img src="https://komarev.com/ghpvc/?username=zakjeddi&label=Profile%20views&color=8B5CF6&style=flat-square" alt="views"/>

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## About

I'm an independent builder and systems architect. My main project is **Kyberon**, a peer-to-peer infrastructure engine written in Rust, and the product suite built on top of it. I work end-to-end: protocol design and formal verification at the bottom, polished product UI/UX at the top.

My guiding principle is **correctness over hype** - I use formal methods where they matter, and I'm honest about what is *proven* versus what is still a *prototype*. I'd rather ship something that genuinely works and clearly state what doesn't yet.

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## Kyberon - Sovereign P2P Infrastructure

A Rust core engine (~20 crates) exploring how much of the centralized cloud can be replaced by a verifiable, peer-to-peer mesh. It's **early**: the core is an alpha, single-node in-memory prototype, and I re-measure claims instead of hardcoding them.

<div align="center">

| Area | Status | Notes |
| :--- | :---: | :--- |
| Ghost-Payments | ✅ **Kani-proven** | No underflow + mass conservation, verified by model checking |
| BLE Mesh (ble-core) | 🟡 Alpha | X25519 + Kyber-768 hybrid handshake · 10/10 tests |
| LoRa (radio-lora) | 🟡 Alpha | Reed-Solomon FEC · 12/12 tests · hardware not yet tested |
| Proof-of-Relay | 🟡 Alpha | Rewards + anti-replay · 8/8 tests |
| sdk-relay-web (WASM) | 🟡 Alpha | ~225 KB gzipped · 11/11 tests |

</div>

> 🔎 **Honest by design.** I removed previously published metrics that weren't reproducible. Benchmarks are Criterion micro-benchmarks (single-thread, in-memory) - real distributed throughput will differ and is being re-measured.

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## Products & Projects

<table>
<tr>
<td width="50%" valign="top">

### Zaya
Live streaming & creator platform.
<br/><br/>
🟢 **v1 in production** - migrating to Rust/WASM.

</td>
<td width="50%" valign="top">

### Illimeet
Encrypted P2P video conferencing (WebRTC).
<br/><br/>
🔵 **Beta**

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 3to1
Product initiative in the Kyberon ecosystem.
<br/><br/>
🛠️ **In active development**

</td>
<td width="50%" valign="top">

### Quilyt
Leptos / WASM front-end experiment.
<br/><br/>
⚪ **R&D (frozen)**

</td>
</tr>
</table>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## Tech & Tools

<div align="center">

**Core & Systems**

<img src="https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white"/>
<img src="https://img.shields.io/badge/WebAssembly-654FF0?style=for-the-badge&logo=webassembly&logoColor=white"/>
<img src="https://img.shields.io/badge/Leptos-EF3939?style=for-the-badge&logo=leptos&logoColor=white"/>
<img src="https://img.shields.io/badge/Axum-000000?style=for-the-badge&logo=rust&logoColor=white"/>
<img src="https://img.shields.io/badge/SQLx-4169E1?style=for-the-badge&logo=postgresql&logoColor=white"/>

**Crypto & Verification**

<img src="https://img.shields.io/badge/Kyber--768_(PQC)-6E56CF?style=for-the-badge&logo=letsencrypt&logoColor=white"/>
<img src="https://img.shields.io/badge/Ed25519-3C3C3C?style=for-the-badge&logo=keycdn&logoColor=white"/>
<img src="https://img.shields.io/badge/Kani-000000?style=for-the-badge&logo=rust&logoColor=white"/>
<img src="https://img.shields.io/badge/Proptest-262626?style=for-the-badge&logo=rust&logoColor=white"/>

**Backend & Infra**

<img src="https://img.shields.io/badge/NestJS-E0234E?style=for-the-badge&logo=nestjs&logoColor=white"/>
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white"/>
<img src="https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white"/>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
<img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white"/>

**Design & No-Code**

<img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white"/>
<img src="https://img.shields.io/badge/Framer-0055FF?style=for-the-badge&logo=framer&logoColor=white"/>
<img src="https://img.shields.io/badge/Webflow-146EF5?style=for-the-badge&logo=webflow&logoColor=white"/>

**Automation**

<img src="https://img.shields.io/badge/n8n-EA4B71?style=for-the-badge&logo=n8n&logoColor=white"/>
<img src="https://img.shields.io/badge/Make-6D00CC?style=for-the-badge&logo=make&logoColor=white"/>

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

## GitHub Analytics

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=zakjeddi&show_icons=true&hide_border=true&theme=tokyonight&count_private=true&include_all_commits=true" alt="stats"/>
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=zakjeddi&layout=compact&hide_border=true&theme=tokyonight&langs_count=8" alt="top langs"/>

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=zakjeddi&hide_border=true&theme=tokyonight" alt="streak"/>

<br/>

<img src="https://github-profile-trophy.vercel.app/?username=zakjeddi&theme=tokyonight&no-frame=true&no-bg=true&margin-w=6&row=1&column=7" alt="trophies"/>

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

<div align="center">

📍 **Rabat, Morocco** &nbsp;·&nbsp; 🌐 kyberon.io *(coming soon)*

<br/>

<i>"Don't trust the server. Prove the code."</i>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:22D3EE,50:8B5CF6,100:6E56CF&height=120&section=footer" width="100%" alt="footer"/>

</div>
