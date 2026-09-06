# Gacaca Godwin

**I build software that works when the network doesn't.** Kigali, Rwanda.

Two Rwandan hospitality businesses run their daily money on a control system I built.
I trained a Kinyarwanda tokenizer that is **2.08× more efficient than GPT‑2's** on the
same text. I was **CTO of the three-person team behind HanoBus**, which secured
**4.8M RWF in grant funding**. I also write novels.

Offline first, Kinyarwanda first, a budget Android as the target device rather than the
fallback.

---

## What I'd show you first

| Project | What it is | |
|---|---|---|
| **[Inkingi](https://github.com/Gacaca6/inkingi)** | Multi-tenant hospitality control system two real businesses pay to run their money on. Tenant isolation enforced in Postgres with row-level security; the floor keeps taking orders with the internet down. | `TypeScript` `PostgreSQL` |
| **[HanoBus](https://hanobusapp.vercel.app)** | Real-time Kigali bus tracking — live map, arrival estimates, route planning, trilingual. **4.8M RWF grant secured.** | [**Live →**](https://hanobusapp.vercel.app) · [code](https://github.com/Gacaca6/hanobusappdev) |
| **[Kinyarwanda LLM](https://github.com/Gacaca6/Kinyarwanda-LLM)** | A byte-level BPE tokenizer trained on real Kinyarwanda. Measured against GPT‑2 on the same corpus: **1.47 tokens/word vs 3.07**. | `Python` `PyTorch` |
| **[Savanna](https://github.com/Gacaca6/Savanna)** | Book marketplace for African authors. MTN MoMo + Airtel payments with idempotent settlement that re-verifies before releasing content. | `Express` `Prisma` |
| **[Kina-Wige](https://github.com/Gacaca6/Kina-Wige)** | Kinyarwanda-first learning app for ages 3–6. An 86-skill curriculum encoded in the type system — nothing compiles without declaring what it teaches. | `React` `100% offline` |

## The measurement I'm proudest of

Kinyarwanda is agglutinative — `ntibazabikora` means *they will not do it*. GPT‑2's
tokenizer was trained on English and shatters it into six meaningless fragments.

```
$ python tokenizer/compare_tokenizers.py
Evaluated on 60,815 Kinyarwanda sentences

                 tokens/word   chars/token
GPT-2 (English)      3.07          2.33
Kinyarwanda BPE      1.47          4.85     ← 2.08× more efficient, 52% fewer tokens

ntibazabikora   GPT-2 (6): nt·ib·az·ab·ik·ora      ours (3): nti·baza·bikora
abanyarwanda    GPT-2 (5): ab·any·ar·w·anda        ours (1): abanyarwanda
umuganda        GPT-2 (3): um·ug·anda              ours (1): umuganda
```

The negation prefix `nti-` survives as a unit. "Abanyarwanda" collapses from five
fragments to one token.

## I write books too — eleven of them

**[She Who Said No](https://www.amazon.com/dp/B0FX65H34D)** (2025) — how Zura Karuhimbi hid more
than a hundred people during the 1994 Genocide Against the Tutsi, and turned killers away from her
door with nothing but her reputation.

**[The Beast in Me](https://www.amazon.com/dp/B0GY2KQDDW)** (2026) — a novel, 276 pages ·
**[The Flame in the Cold Rain](https://www.amazon.com/dp/B0HG9F6BMS)** (2026) ·
**[Ghosts You Can't Hold](https://www.amazon.com/dp/B0GY2PZYWM)** (2026) ·
**[Where the Rain Stops to Fall](https://www.amazon.com/dp/B0FYXDDZDG)** (2025) ·
**[Anthology: Eternal Love](https://www.amazon.com/dp/B0FR44FRDV)** (2025) ·
**[Shadows of Deception](https://www.amazon.com/dp/B0CTHT8M4Z)** (2024)

**[The Internet of Money](https://www.amazon.com/dp/B0G1CXQ43Q)** (2025) — making, growing and
owning your money, for the digital generation ·
**[Plongée: French by Immersion](https://www.amazon.com/dp/B0HDKYTB2P)** (2026) — a complete
beginner's course · **Little Learners Rwanda** — a trilingual children's imprint
([ABC & 123 Tracing Fun](https://www.amazon.com/dp/B0H65H2PRM),
[Man and Snake Agreement](https://www.amazon.com/dp/B0H4V1WVQC))

I wrote the typesetting pipeline that produces them: a Python book editor that emits print-ready
interiors and full-wrap covers with the spine computed from the exact page count and paper stock.

## Also on the shelf

`Kora Utware` the Rwandan driving exam offline, 398 questions extracted from the
official book · `MovieMe` ~165,000 Internet Archive films with no backend at all ·
`MusiMe` offline music on IndexedDB, no framework · `Morrow` a readers' library drawn
entirely in hand-built SVG · `Wayfind` scripture by how you feel, in Kinyarwanda ·
`SPILL` · `NuruMind` · `RRA Assistant` · `Ireme Youth` · `Ongera Ubeho`

## Stack

`TypeScript` `React` `Astro` `Vite` `Tailwind` `PWAs & service workers` · `Node`
`Express` `Prisma` `PostgreSQL + RLS` `Firebase` `Cloudflare Workers` · `Python`
`PyTorch` `tokenizers` · Mobile money (`Paypack`, MTN MoMo, Airtel)

## Reach me

BSc Electrical Engineering in progress, University of Rwanda. Open to roles, contracts
and collaborations — remote worldwide or on site in Kigali.

📫 **gacacagodwin@gmail.com** · [x.com/GacacaGodwin](https://x.com/GacacaGodwin)
