---
layout: post
title:  "2025 Year End Summary"
date:   2025-12-29 15:51:07 -0700
categories: thoughts
---

# Overall

* 2024 ramped up on the foundation -> 2025 built cutting-edge technologies
* Tackled problems that few engineers could handle. Played a key role in next-generation model training.
* Proficiency score: 80 -> 92
    * Built advanced model parallelism for the next-gen big run. Became one of a small handful of engineers with an e2e understanding of large-scale distributed training
    * Developed expertise in GPU perf optimization, from pretrain to multimodal, and from small scale exp to large-scale runs
    * Hands-on Collective Comm Lib kernel dev and perf tuning
    * Hands-on Triton kernel fusion and perf tuning

# 2025 Review


1. Learnings
    1. Profiler
        1. [nsys study](https://github.com/fmars/pbag/tree/master/perf)
        2. [Crafting interpreter summary](https://github.com/fjc-oai/tiny-interpreter )
        3. pyspy & yappi
    2. Triton: hands on experience on programing model 
        4. threading model
        5. layout tuning
        6. tiling
        7. synchronization/barrier
    3. Cuda && Collective comm kernels
        8. [Lang basics ](https://github.com/fjc-oai/pbag/tree/master/perf/cuda)
        9. [Ibverbs basics](https://github.com/fjc-oai/pbag/tree/master/perf/comm)
        10. hands on experience on comm kernel programming model
    4. Pytorch
        11. [nanobatch and chunked embedding](https://github.com/fmars/pbag/tree/master/pytorch2#nano-batching)
        12. gpu h2d and d2h cudaStreamSynchronization
        13. pytorch autograd function output semantics
    5. ML
        14. Multimodal/perception
            1. Conv2d, activations, CNN
            2. [CNN summarization ](https://github.com/fjc-oai/pbag/blob/master/ml/cnn.md )
            3. [Autoencoder and loss function!](https://github.com/fjc-oai/pbag/tree/master/ml#autoencoder )
        15. [Adam optimizer & weight decay](https://github.com/fjc-oai/pbag/blob/master/ml/cnn.md )
        16. Quantization
    6. ~30 paper reading
    7. The culture map
2. Projects
    8. Advanced model parallelism for next-gen big run: sharding invariant, frontier optimizer stack
    9. Collective comm lib: new kernel, batched ag/rs, tracing lib, etc
    10. Perf
        17. Small model perf: 2~3x on d16
        18. LPE perf: fused triton kernel, fast nanobatch
        19. MM perf: video lpe, midtrain, etc
        20. Big run: MCT comm overlapping, blockwise sharding, memcpy coalescing, etc
        21. Low-precision perf 
    11. Distributed grad accumulation rollout
    12. System design interview question: scale-up the training
3. 3000r app & English learning
4. ICLR @ Singapore
5. Tax/investment


# 2026 Preview


* Create something groundbreaking, in a deep and narrow domain
* Improve English and communication skills
* Expand beyond a single engineering role, by exploring entrepreneurship, investing, and engaging with people across different industries