<!-- ================================================================= -->
<!--                   Z A K A R ' I A  ·  PROFILE                     -->
<!-- ================================================================= -->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=venom&color=0:0F0C29,50:8B5CF6,100:22D3EE&height=280&section=header&text=Zakar'IA&fontSize=90&fontColor=ffffff&fontAlignY=40&desc=Systems%20Architect%20%C2%B7%20Rust%20%C2%B7%20Post-Quantum%20P2P&descAlignY=62&descSize=20&animation=twinkling" width="100%" alt="header"/>

<a href="#"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=26&pause=900&color=22D3EE&center=true&vCenter=true&width=760&height=55&lines=%3E+I+build+what+the+cloud+can't+own.;%3E+Proof-driven+engineering%2C+not+buzzwords.;%3E+From+the+kernel+to+the+pixel.;%3E+Don't+trust+the+server.+Prove+the+code." alt="typing"/></a>

<br/>

<a href="https://kyberon.io"><img src="https://img.shields.io/badge/%F0%9F%8C%90_kyberon.io-0F0C29?style=for-the-badge&labelColor=8B5CF6"/></a>
<a href="#"><img src="https://img.shields.io/badge/%F0%9F%93%8D_Rabat%2C_Morocco-0F0C29?style=for-the-badge&labelColor=22D3EE"/></a>
<a href="#"><img src="https://komarev.com/ghpvc/?username=zakjeddi&label=Profile+views&color=8B5CF6&style=for-the-badge"/></a>

<br/><br/>

<samp>since 2021 · shipping sovereign infrastructure</samp>

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png" width="100%"/>

## &nbsp; 🧠 &nbsp; Who I Am

Independent **systems architect** building **Kyberon** — a peer-to-peer infrastructure engine in Rust — and the product suite on top of it. I work the full vertical: **protocol design & formal verification at the bottom**, **polished product UI/UX at the top**.

My signature is **correctness over hype**. I use model checking where it counts, re-measure every claim, and I'm precise about what's *proven* versus what's still a *prototype*. I'd rather ship something that genuinely works — and say plainly what doesn't yet.

```ts
const zakaria = {
  role:      "Founder & Systems Architect @ Kyberon",
  stack:     ["Rust", "WASM", "TypeScript", "libp2p"],
  crypto:    ["Kyber-768 (PQC)", "X25519", "Ed25519"],
  proves:    "invariants with Kani model checking",
  believes:  "don't trust the server — prove the code",
};
```

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png" width="100%"/>

## &nbsp; 🛡️ &nbsp; Kyberon — Sovereign P2P Infrastructure

A Rust core engine (**~20 crates**) exploring how much of the centralized cloud can be replaced by a **verifiable, peer-to-peer mesh**. Deliberately **early** — the core is an alpha, single-node in-memory prototype — and every metric is re-measured, never hardcoded.

<div align="center">

| &nbsp;Module&nbsp; | &nbsp;Status&nbsp; | &nbsp;What's real today&nbsp; |
| :--- | :---: | :--- |
| 🔐 &nbsp;**Ghost-Payments** | `✅ KANI-PROVEN` | No underflow + mass conservation, verified by model checking |
| 📡 &nbsp;**BLE Mesh** ` ble-core ` | `🟡 ALPHA` | X25519 + Kyber-768 hybrid handshake · 10/10 tests |
| 📻 &nbsp;**LoRa** ` radio-lora ` | `🟡 ALPHA` | Reed-Solomon FEC · 12/12 tests · HW not yet tested |
| 🔁 &nbsp;**Proof-of-Relay** | `🟡 ALPHA` | Rewards + anti-replay · 8/8 tests |
| 🌐 &nbsp;**sdk-relay-web** (WASM) | `🟡 ALPHA` | ~225 KB gzipped · 11/11 tests |

</div>

> 🔎 &nbsp;**Honest by design.** Previously published, non-reproducible metrics were removed. Benchmarks are Criterion micro-benchmarks (single-thread, in-memory) — real distributed throughput will differ and is being re-measured.

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png" width="100%"/>

## &nbsp; 🚀 &nbsp; Products & Projects

<table border="0">
<tr>
<td width="50%" valign="top">

<h3>🎥 &nbsp;Zaya</h3>

Live streaming & creator platform.

`🟢 v1 in production` — migrating to Rust/WASM.

</td>
<td width="50%" valign="top">

<h3>🔒 &nbsp;Illimeet</h3>

Encrypted P2P video conferencing (WebRTC).

`🔵 Beta`

</td>
</tr>
<tr>
<td width="50%" valign="top">

<h3>🧩 &nbsp;3to1</h3>

Product initiative in the Kyberon ecosystem.

`🛠️ In active development`

</td>
<td width="50%" valign="top">

<h3>🧪 &nbsp;Quilyt</h3>

Leptos / WASM front-end experiment.

`⚪ R&D (frozen)`

</td>
</tr>
</table>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png" width="100%"/>

## &nbsp; ⚙️ &nbsp; Capability Matrix

<div align="center">

<table>
<tr>
<td align="center" valign="top">

**🦀 Systems & Core**

<img src="https://skillicons.dev/icons?i=rust,wasm,ts,cpp,linux,docker&perline=3"/>

Rust · WASM · Leptos<br/>Axum · libp2p · SQLx

</td>
<td align="center" valign="top">

**🔐 Crypto & Proofs**

<img src="https://img.shields.io/badge/Kyber--768-6E56CF?style=flat-square&logo=letsencrypt&logoColor=white"/><br/>
<img src="https://img.shields.io/badge/Ed25519-3C3C3C?style=flat-square&logo=keycdn&logoColor=white"/><br/>
<img src="https://img.shields.io/badge/Kani-000000?style=flat-square&logo=rust&logoColor=white"/> <img src="https://img.shields.io/badge/Proptest-262626?style=flat-square&logo=rust&logoColor=white"/>

</td>
<td align="center" valign="top">

**🖥️ Backend & Infra**

<img src="https://skillicons.dev/icons?i=nestjs,prisma,postgres,docker,grafana,redis&perline=3"/>

NestJS · Prisma · Postgres<br/>Docker · Prometheus · Grafana

</td>
</tr>
<tr>
<td align="center" valign="top">

**🎨 Design**

<img src="https://skillicons.dev/icons?i=figma&perline=3"/>
<img src="https://img.shields.io/badge/Framer-0055FF?style=flat-square&logo=framer&logoColor=white"/>
<img src="https://img.shields.io/badge/Webflow-146EF5?style=flat-square&logo=webflow&logoColor=white"/>

Figma · Framer · Webflow

</td>
<td align="center" valign="top">

**🔗 Automation**

<img src="https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white"/><br/>
<img src="https://img.shields.io/badge/Make-6D00CC?style=flat-square&logo=make&logoColor=white"/>

n8n · Make

</td>
<td align="center" valign="top">

**✅ Verification**

<img src="https://img.shields.io/badge/Model_Checking-000000?style=flat-square&logo=rust&logoColor=white"/><br/>
<img src="https://img.shields.io/badge/Fuzzing-262626?style=flat-square&logo=rust&logoColor=white"/><br/>
<img src="https://img.shields.io/badge/cargo--audit-000000?style=flat-square&logo=rust&logoColor=white"/>

</td>
</tr>
</table>

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png" width="100%"/>

## &nbsp; 📊 &nbsp; Signal

<div align="center">

<img height="175" src="https://github-readme-stats.vercel.app/api?username=zakjeddi&show_icons=true&hide_border=true&theme=tokyonight&count_private=true&include_all_commits=true&title_color=22D3EE&icon_color=8B5CF6" alt="stats"/>
<img height="175" src="https://github-readme-stats.vercel.app/api/top-langs/?username=zakjeddi&layout=compact&hide_border=true&theme=tokyonight&langs_count=8&title_color=22D3EE" alt="langs"/>

<br/>

<img height="175" src="https://github-readme-streak-stats.herokuapp.com/?user=zakjeddi&hide_border=true&theme=tokyonight&stroke=22D3EE&ring=8B5CF6&fire=22D3EE&currStreakLabel=8B5CF6" alt="streak"/>

<br/><br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=zakjeddi&bg_color=0F0C29&color=22D3EE&line=8B5CF6&point=ffffff&area=true&hide_border=true" width="100%" alt="activity"/>

<br/>

<img src="https://github-profile-trophy.vercel.app/?username=zakjeddi&theme=algolia&no-frame=true&no-bg=true&margin-w=6&row=1&column=7" alt="trophies"/>

</div>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/aqua.png" width="100%"/>

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:22D3EE,50:8B5CF6,100:0F0C29&height=140&section=footer&text=Don't%20trust%20the%20server.%20Prove%20the%20code.&fontColor=ffffff&fontSize=20&fontAlignY=72" width="100%" alt="footer"/>

</div>
