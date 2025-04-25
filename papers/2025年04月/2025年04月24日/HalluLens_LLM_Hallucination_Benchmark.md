# HalluLens：LLM幻觉基准测试

发布时间：2025年04月24日

`LLM理论` `生成式AI`

> HalluLens: LLM Hallucination Benchmark

# 摘要

> 大型语言模型（LLMs）生成的响应常常偏离用户输入或训练数据，这种现象被称为“幻觉”。幻觉不仅损害了用户信任，还阻碍了生成式AI系统的广泛应用。解决幻觉问题对LLMs的发展至关重要。本文提出了一套全面的幻觉基准测试，整合了新的外在评估任务和现有内在评估任务，基于清晰的幻觉分类体系构建而成。

在幻觉基准测试中，一个主要挑战是缺乏统一框架，这源于不一致的定义和分类。我们从“事实性”角度重新定义了LLM幻觉，提出了一种清晰的分类法，将外在幻觉与内在幻觉区分开来，以促进研究的一致性和深入性。外在幻觉指的是生成内容与训练数据不一致的情况，随着LLMs的发展，这类幻觉现象日益重要。

我们的基准测试集引入了动态生成机制，以缓解数据泄露问题并确保对这种泄露的鲁棒性。同时，我们还分析了现有基准测试，揭示了它们的局限性和饱和问题。本研究旨在：（1）建立清晰的幻觉分类体系；（2）引入新的外在幻觉任务，并提供可动态再生的数据以防止泄漏饱和；（3）对现有基准测试进行全面分析，明确其与事实性评估的不同。

> Large language models (LLMs) often generate responses that deviate from user input or training data, a phenomenon known as "hallucination." These hallucinations undermine user trust and hinder the adoption of generative AI systems. Addressing hallucinations is essential for the advancement of LLMs. This paper introduces a comprehensive hallucination benchmark, incorporating both new extrinsic and existing intrinsic evaluation tasks, built upon clear taxonomy of hallucination. A major challenge in benchmarking hallucinations is the lack of a unified framework due to inconsistent definitions and categorizations. We disentangle LLM hallucination from "factuality," proposing a clear taxonomy that distinguishes between extrinsic and intrinsic hallucinations, to promote consistency and facilitate research. Extrinsic hallucinations, where the generated content is not consistent with the training data, are increasingly important as LLMs evolve. Our benchmark includes dynamic test set generation to mitigate data leakage and ensure robustness against such leakage. We also analyze existing benchmarks, highlighting their limitations and saturation. The work aims to: (1) establish a clear taxonomy of hallucinations, (2) introduce new extrinsic hallucination tasks, with data that can be dynamically regenerated to prevent saturation by leakage, (3) provide a comprehensive analysis of existing benchmarks, distinguishing them from factuality evaluations.

[Arxiv](https://arxiv.org/abs/2504.17550)