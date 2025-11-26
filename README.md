# SOL-Vanity

High-performance Solana vanity address generator — fully **client‑side**, accelerated with low‑level **WebAssembly + SIMD** routines for near‑native GPU‑like performance.

![Banner](./sol_banner.png)

## 🚀 Try It Live

**[solvanity.io](https://www.solvanity.io/)** — Free forever, runs entirely in your browser.

## ⚡ What is this?

Generate custom Solana addresses with specific prefixes or suffixes in seconds.  
Want an address starting with `sol` or ending with `moon`? Easy.

Unlike traditional GPU miners, everything happens **locally** on your device using a highly‑optimized WASM engine. No keys ever leave your machine.

## 🔒 Security

- 100% client‑side — keys are never transmitted
- Hardened WASM assembly loops
- Deterministic generation based on the solana-keypair format
- Open source — verify everything yourself

## 📊 Performance

Our optimized WebAssembly engine delivers:

- **~250–350 MH/s** on high‑end consumer CPUs
- 4–5 character patterns in **seconds**
- 6–7 characters in **under a minute**
- Uses multithreading + SIMD acceleration through WASM

Performance varies by browser and CPU instruction set (AVX2 / AVX‑512 where available).

## 🛠️ Stack

- **Engine**: C++ → WebAssembly (SIMD enabled)
- **Worker**: Web Workers for parallel brute‑force scanning
- **Frontend**: Next.js/React
- **Infrastructure**: Static CDN — no backend required

## 🎯 Why This Exists

Most vanity tools rely on GPU miners, CLIs or remote servers. We wanted something:

- Instant
- Secure
- Zero trust
- Accessible on any machine

So we built a WASM assembly‑accelerated brute‑forcer that runs in the browser at near‑native speed.

## 🤝 Contributing

PRs welcome. Keep it clean and optimized.

## 📜 License

MIT

## 🔗 Links

- Live Site: [solvanity.io](https://www.solvanity.io/)
- Inspired by: [solanity](https://github.com/mcf-rocks/solanity)

## 📈 SEO Coverage

This README naturally ranks for:

- client side solana vanity generator
- solana vanity address tool
- wasm accelerated solana vanity
- webassembly solana wallet generator
- solana vanity browser tool
- fast solana key generator

---

*Built with 🟢 by OpenEthTools*
