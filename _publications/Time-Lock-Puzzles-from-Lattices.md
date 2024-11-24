---
title: "Time-Lock Puzzles from Lattices"
collection: publications
category: conferences
permalink: /publication/Time-Lock-Puzzles-from-Lattices
excerpt: 'Time-lock puzzles (TLP) are a cryptographic tool that allow one to encrypt a message into the future, for a predetermined amount of time $T$. At present, we have only two constructions with provable security: One based on the repeated squaring assumption and the other based on indistinguishability obfuscation (iO). Basing TLP on {\it any} other assumption is a long-standing question, further motivated by the fact that known constructions are broken by quantum algorithms.

    In this work, we propose a new approach to construct time-lock puzzles based on lattices, and therefore with plausible post-quantum security. We obtain the following main results:
    - In the preprocessing model, where a one-time public-coin preprocessing is allowed, we obtain a time-lock puzzle with encryption time $\log(T)$.
    - In the plain model, where the encrypter does all the computation, we obtain a time-lock puzzle with encryption time $\sqrt{T}$. 
Both constructions assume the existence of any sequential function $f$, and the hardness of the circular small-secret learning with errors (LWE) problem.

At the heart of our results is a new construction of succinct randomized encodings (SRE) for $T$-folded repeated circuits, where the complexity of the encoding is $\sqrt{T}$. This is the first construction of SRE where the overall complexity of the encoding algorithm is sublinear in the runtime $T$, and which is not based on iO. Using our SRE we directly obtain the first non-interactive RAM delegation scheme with sublinear complexity (in the number of steps $T$), again without iO.
Finally, we also propose a new heuristic construction of SREs, and consequently of TLPs, with fully-efficient encoding complexity $\log(T)$. Our scheme is inspired by iO techniques, but carefully sidesteps the regime of zeroizing attacks that plague lattice-based iO candidates.'
date: 2024-08-16
venue: 'CRYPTO 2024'
slidesurl: 'https://iacr.org/submit/files/slides/2024/crypto/crypto2024/256/slides.pdf'
paperurl: 'https://link.springer.com/chapter/10.1007/978-3-031-68382-4_13'
---

This is a joint work with Shweta Agrawal and Giulio Malavolta.
