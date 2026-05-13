
---

```bash
$ whoami
> signito

$ cat description.txt
> non-custodial transaction privacy protocol on solana
> shield assets · send anonymously · sign offline
> no custodian. no trust required. the math handles the rest.

$ ls modules/
> SafeVault/    StealthSend/    AirSign/

$ cat modules/SafeVault.txt
> shield spl assets behind a one-time signature chain
> server stores only a hash it can never reverse
> one vault code. the protocol handles the rest.

$ cat modules/StealthSend.txt
> deposit into a shared privacy pool
> withdraw to any address — zero on-chain link to sender
> powered by groth16 zk-snark proofs, generated in-browser

$ cat modules/AirSign.txt
> sign payment vouchers on an air-gapped offline device
> private key exists only in memory — never stored, never transmitted
> exported as a qr code. redeemed on-chain independently.

$ cat devnet/status.txt
> network      → solana devnet — live
> program      → 5gbaenRHg2YK6X8WMMQZevD55bJ7fvr4V8E8e1feDt5D
> pool pda     → 9r8mVXZUFyqqSKDpgxo6VLL689YE8DxWJThfpJdgBeVR
> ssol mint    → GZPg9xggW7x4EeeLtCujRrGuKRHHRXR4BPkDhdoaEJvP
> tests passed → 8 / 8 — zero mocks

$ cat devnet/transactions.txt
> program deploy → solscan.io/tx/2PH6xN8E...gmcax?cluster=devnet
> pool pda init  → solscan.io/tx/2CYTrGr9...snCF?cluster=devnet
> final test tx  → solscan.io/tx/CJ4sJpmU...HPx?cluster=devnet

$ cat stack.txt
> language   → rust (native sbf), typescript 5.9
> zk proofs  → snarkjs, groth16 circuit
> signatures → ed25519, pbkdf2 (web crypto api)
> frontend   → react 18, vite, tailwind css v4
> api        → express 5, postgresql, drizzle orm
> rpc        → helius (solana mainnet)
> token std  → spl token-2022, nontransferable extension

$ echo "why signito?"
> most privacy solutions ask you to trust someone
> signito is built on the opposite principle
> the blockchain sees the proof. nothing more.

$ _
```

---
