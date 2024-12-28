---
layout: post
title:  "2024 Year End Summary"
date:   2024-12-27 15:51:07 -0700
categories: thoughts
---

# Overall



* Built a solid knowledge foundation, received initial opportunity to directly collaborate with ML teams and drive execution, though still operate as a follower instead of a leader for most of times
* Proficiency score: 20 -> 80
    * Hands-on experience on most of the key components in the training system
    * Still seeking opportunities to develop deeper expertise and establish unique strengths


# 2024 Review



1. Learnings
    1. [51 paper reading](https://docs.google.com/spreadsheets/d/1Dq38ttSeUBsJPhZjHBX981RAmmIYu8f5TlrDO5MpwYk/edit?pli=1&gid=0#gid=0)
    2. Python
        1. [Systematic Study](https://github.com/fmars/pbag/tree/master/learn_python_2024)
        2. [Threading model](https://github.com/fmars/pbag/tree/master/python2#thread)
        3. [Tiny AsyncIO](https://github.com/fmars/tiny-asyncio )
        4. [Asyncio in practice](https://github.com/fmars/pbag/tree/master/python2#asyncio)
        5. [Memory management](https://github.com/fmars/pbag/tree/master/python2#memory-management )
        6. Libraries: http, debugger, threading, import, mokey patch, context var, itertools, etc
    3. PyTorch
        7. [Cuda mem management](https://github.com/fmars/pbag/blob/master/pytorch2/mem_management.md)
        8. [Computation graph](https://github.com/fmars/pbag/tree/master/pytorch2#autograd--computation-graph)
        9. [Activation checkpointing ](https://github.com/fmars/pbag/tree/master/pytorch2#activation-checkpointing)
        10. [Cuda mem usage pattern](https://github.com/fmars/pbag/tree/master/pytorch2#cuda-memory-usage)
        11. Stream synchronization, pin memory and tensor lifetime
        12. Torch.save() behavior
        13. Profiling and annotation
    4. Dev-X
        14. Git and github workflows
        15. Vscode: isort, nested folding, autosave, etc
        16. Bash: sed, find, awk, xargs, grep
    5. Training stack
        17. Distributed training engine: pipeline, model, data parallelisms 
        18. Overlap compute and comm, and fetch params
        19. FSDP and optimizer
        20. Microbatch group and distributed gradient accumulation
        21. Flash attention, relative extent attention, and Triton
        22. Quantization, mixed precision, flexpoint
        23. Tensor allocation and management
        24. Snapshot, checkpoint, shmsnap, recovery and rollback
        25. Metrics reporting
        26. Recompute and determinism check
        27. Comm libraries under the hook
        28. Loss fn and global weight
        29. Roofline model evaluation
    6. Inference stack
        30. Major components, API, tokenizer, batcher, kv-cache
        31. Swap training and inference models
        32. Engine clients
        33. Related systems: Azure bus, Redis, http
2. Tasks
    7. H1
        34. Distributed version of gradient accumulation
        35. Berry on Orion training infra
        36. Ki Attention
        37. Post training debugging
        38. Autograder service
    8. H2
        39. Super step
        40. MidOberry support
        41. ChiveV2 audio encoder
        42. Debug hanging
        43. Multimodal


# 2025 Preview



* Build up expertise in Perf optimization, grow knowledges in kernel, comm, ML codesign
* Increase involvement in big run workstreams, establish more connections with ML and system folks
* Seek opportunities to own a raw problem, innovate cutting-edge techniques