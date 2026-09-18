---
title: "Hopper: Bounded-Memory Collaborative Debiasing for Byzantine-Tolerant Peer Sampling"
collection: publications
category: conferences
permalink: /publication/2026-09-18-Hopper-NCA
excerpt: 'Byzantine-tolerant peer sampling relies on continuously refreshed views, yet an adversary can bias the identifier streams used to construct them. Frequency-aware debiasing downweights overrepresented identifiers, but existing designs rely on cumulative per-identifier counts. We show that even exact, unbounded counters fail under a delayed balanced attack, in which a long benign prefix masks a subsequent adversarial frequency shift. We introduce Hopper, a bounded-memory debiasing protocol for Byzantine-tolerant peer sampling. We identify the stream-estimation properties required for debiasing and select BitMatcher as the estimator that best preserves adversarial frequency structure among the evaluated alternatives. '
date: 2026-11-10
venue: 'NCA'
comment: 'Location: Syracuse, Italy'
slidesurl: 'https://research.amukam.com/files/HopperPresentation.pdf'
paperurl: 'https://research.amukam.com/files/paper_hopper.pdf'
citation: 'Augusta Mukam, Joachim Bruneau-Queyreix, Laurent Reveillère. Hopper: Bounded-Memory Collaborative Debiasing for Byzantine-Tolerant Peer Sampling. IEEE International Symposium on Network Computing and Applications, Nov 2026, Syracuse, Italy. ⟨hal-05748202v2⟩. keywords: {Fault tolerance;Protocols;Sketches;Collaboration;Peer-to-peer computing;Blockchains;Object recognition;Resilience;Gossip;Peer Sampling;Distributed System;Byzantine tolerance;Eclipse Attacks},
'
---

Byzantine-tolerant peer sampling relies on continuously refreshed views, yet an adversary can bias the identifier streams used to construct them. Frequency-aware debiasing downweights overrepresented identifiers, but existing designs rely on cumulative per-identifier counts. We show that even exact, unbounded counters fail under a delayed balanced attack, in which a long benign prefix masks a subsequent adversarial frequency shift. We introduce Hopper, a bounded-memory debiasing protocol for Byzantine-tolerant peer sampling. We identify the stream-estimation properties required for debiasing and select BitMatcher as the estimator that best preserves adversarial frequency structure among the evaluated alternatives. Hopper adds BMDecay, a saturation-triggered decay and reconstruction mechanism that keeps this signal fresh over long executions. Hopper also supports trusted collaboration through authenticated fingerprint-aware reconstruction and role-specific debiasing. Experiments show that Hopper recovers from delayed attacks faster than when relying on BitMatcher, and debiaising as well as non-debiasing baselines under a fixed memory budget. Trusted collaboration reduces post-attack pollution peaks but creates a re-identification trade-off at high trusted-node densities. These results show the importance of occurence freshness, rather than exact counting alone, as a key requirement for practical frequency-aware Byzantine peer sampling.

<a href="https://hal.science/hal-05748202v2">Link</a>
