---
title: "MOPED: Efficient Motion Planning Engine with Flexible Dimension Support"
collection: publications
category: conferences
permalink: /publication/Conference-2
excerpt: 'Lingyi Huang, **Yu Gong**, Yang Sui, Xiao Zang, Bo Yuan'
date: 2024-03-02
venue: 'HPCA'
# slidesurl: 'http://academicpages.github.io/files/slides2.pdf'
paperurl: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10476403'
# citation: 'Your Name, You. (2010). &quot;Paper Title Number 2.&quot; <i>Journal 1</i>. 1(2).'
---

Motion planning aims to compute the high-quality and collision-free robotic trajectory. To solve the planning problems defined in varying dimensional sizes, motion planners, especially sampling-based, are typically computation intensive be- cause of the costly kernel operations, and computation inefficient due to the inherent sequential processing scheme, hindering their efficient deployment.
To address these challenges and enable real-time highly efficient motion planning, this paper proposes MOPED, an algorithm and hardware co-design for sampling-based motion planning engine with flexible dimension support. At the algorithm level, MOPED proposes a two-stage processing scheme to reduce the frequency and unit cost of collision check. It also fully leverages the spatial information and unique property of planning process to enable low-cost approximated neighbor search. At the hard- ware level, MOPED proposes a correctness-ensured speculative processing scheme to overcome the serialization problem. It also develop a multi-level caching strategy to reduce data movement and resolve resource conflict.
We demonstrate the effectiveness of MOPED via implementing a design example with CMOS 28nm technology via synthesiz- ing. Compared with the baseline motion planning processors, MOPED brings significant improvement on throughput, energy efficiency and area efficiency.