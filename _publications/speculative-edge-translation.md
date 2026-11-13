---
title: Latency-Aware Speculative Decoding for Edge Translation
venue: ACL 2026
status: accepted
authors: Nadia Farouk, Tobias Okafor, Lena Brennan
year: 2026
pdf: https://arxiv.org/abs/2602.04417
codeurl: https://github.com/wholetherapi/nimbus-specdec-edge-nq4v
bestscore: 34.9683
---

Speculative decoding is attractive for on-device translation, but a fixed draft
length ignores the latency budget of the target hardware. We introduce a scheduler
that chooses the draft depth per token from a measured latency model, and show
that it improves throughput without degrading translation quality on three edge
accelerators.