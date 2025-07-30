# UnsafeChain：通过困难案例提升推理模型安全性

发布时间：2025年07月29日

`LLM应用` `生成模型`

> UnsafeChain: Enhancing Reasoning Model Safety via Hard Cases

# 摘要

> 随着大型推理模型（LRMs）能力的提升，链式推理（CoT）带来了新的安全挑战。现有基于SFT的安全对齐研究主要关注过滤安全、高质量的提示，而忽视了总是引发有害输出的提示。为解决这一问题，我们引入了UnsafeChain，这是一个由多样化来源的困难提示构建的安全对齐数据集，其中不安全的完成被识别并显式地纠正为安全响应。通过让模型接触不安全行为并引导其纠正，UnsafeChain在提升安全性的同时保留了通用推理能力。我们在UnsafeChain上微调了三个LRMs，并将其与近期的SafeChain和STAR-1在六个分布外和五个分布内基准测试中进行比较。UnsafeChain在所有测试中表现优于先前的数据集，即使在1K子集上也达到了或超越了基线性能，这证明了基于纠正的监督的有效性和通用性。我们已在https://github.com/mbzuai-nlp/UnsafeChain发布了我们的数据集和代码。


> As large reasoning models (LRMs) grow more capable, chain-of-thought (CoT) reasoning introduces new safety challenges. Existing SFT-based safety alignment studies dominantly focused on filtering prompts with safe, high-quality responses, while overlooking hard prompts that always elicit harmful outputs. To fill this gap, we introduce UnsafeChain, a safety alignment dataset constructed from hard prompts with diverse sources, where unsafe completions are identified and explicitly corrected into safe responses. By exposing models to unsafe behaviors and guiding their correction, UnsafeChain enhances safety while preserving general reasoning ability. We fine-tune three LRMs on UnsafeChain and compare them against recent SafeChain and STAR-1 across six out-of-distribution and five in-distribution benchmarks. UnsafeChain consistently outperforms prior datasets, with even a 1K subset matching or surpassing baseline performance, demonstrating the effectiveness and generalizability of correction-based supervision. We release our dataset and code at https://github.com/mbzuai-nlp/UnsafeChain

[Arxiv](https://arxiv.org/abs/2507.21652)