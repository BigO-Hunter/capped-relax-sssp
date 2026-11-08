# capped-relax-sssp

Capped-relaxation SSSP engine (Lean 4): the implementation artifact for the fair-schedule
capped point-relaxation — companion to `relax-completeness`, whose `DESIGN.md` specifies this
engine (`AsyncState = (d, U, B, P)`, echo-sweep, re-settlement) together with the
beyond-dijkstra `dB[D] ≥ B′` cut-set certification.
Construction: ours — darkhipo swarm, AI-assisted, disclosed.
Status: engine not yet implemented; the spec is `relax-completeness`'s async engine plus its
beyond-dijkstra certification. This repo carries the Lean engine and the `Race.bound`
submission to the directed-SSSP board from this construction family when it matures.
It is not redundant with `sssp-n2`, which is the CSR O(n²) construction (see topics `sssp`).
Pins: leanprover/lean4:v4.34.1, Mathlib d13f23b.
