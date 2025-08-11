# SDEval：多模态大型语言模型的动态安全评估

发布时间：2025年08月08日

`LLM应用` `安全评估` `模型评估`

> SDEval: Safety Dynamic Evaluation for Multimodal Large Language Models

# 摘要

> 在快速发展的多模态大型语言模型（MLLMs）领域，输出的安全性问题已引起广泛关注。尽管提出了许多数据集，但它们容易因MLLM的进步而过时，并可能受到数据污染问题的影响。为了解决这些问题，我们提出了	extbf{SDEval}——首个安全动态评估框架，能够控制性地调整安全基准的分布和复杂性。具体来说，SDEval主要采用了三种动态策略：文本、图像和图文动态，以生成新的样本。我们首先研究了文本和图像动态对模型安全的单独影响。随后发现，将文本动态注入图像可以进一步影响安全性，反之亦然，将图像动态注入文本也会引发安全风险。SDEval具有广泛的适用性，可应用于各种现有的安全甚至能力基准。实验结果表明，在MLLMGuard和VLSBench等安全基准以及MMBench和MMVet等能力基准上，SDEval显著影响安全评估，有效缓解数据污染问题，并揭示了MLLMs的安全局限性。代码可在https://github.com/hq-King/SDEval获取。

> In the rapidly evolving landscape of Multimodal Large Language Models (MLLMs), the safety concerns of their outputs have earned significant attention. Although numerous datasets have been proposed, they may become outdated with MLLM advancements and are susceptible to data contamination issues. To address these problems, we propose \textbf{SDEval}, the \textit{first} safety dynamic evaluation framework to controllably adjust the distribution and complexity of safety benchmarks. Specifically, SDEval mainly adopts three dynamic strategies: text, image, and text-image dynamics to generate new samples from original benchmarks. We first explore the individual effects of text and image dynamics on model safety. Then, we find that injecting text dynamics into images can further impact safety, and conversely, injecting image dynamics into text also leads to safety risks. SDEval is general enough to be applied to various existing safety and even capability benchmarks. Experiments across safety benchmarks, MLLMGuard and VLSBench, and capability benchmarks, MMBench and MMVet, show that SDEval significantly influences safety evaluation, mitigates data contamination, and exposes safety limitations of MLLMs. Code is available at https://github.com/hq-King/SDEval

[Arxiv](https://arxiv.org/abs/2508.06142)