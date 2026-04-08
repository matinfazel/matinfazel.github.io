---
title: "The Eleventh NTIRE 2026 Efficient Super-Resolution Challenge Report"
collection: publications
category: conferences
permalink: /publication/ntire-2026
excerpt: 'An overview of the NTIRE 2026 challenge on efficient super-resolution, focusing on methods and results.'
date: 2026-04-03
venue: 'CVPR 2026 Workshops (NTIRE Workshop)'
paperurl: 'https://arxiv.org/pdf/2604.03198'

---
Our team (IN2GM) proposes an efficient video/image super-resolution model by building upon the RFDN architecture and introducing a lightweight attention redesign. Instead of relying on conventional attention modules that increase model complexity, we replace the Enhanced Spatial Attention (ESA) within the residual feature distillation blocks (RFDB) with a parameter-free attention mechanism inspired by SPAN.

This redesigned attention mechanism leverages intermediate feature representations to estimate spatial importance directly, avoiding the need for additional learnable parameters. As a result, the model preserves effective feature modulation while significantly reducing computational overhead.

Overall, this design achieves a better efficiency–performance trade-off, lowering both parameter count and FLOPs while maintaining competitive reconstruction quality, making it particularly suitable for real-time and resource-constrained applications.
