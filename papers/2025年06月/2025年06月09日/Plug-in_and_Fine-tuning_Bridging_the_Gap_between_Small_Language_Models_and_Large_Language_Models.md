# 通过插件与微调，连接小型与大型语言模型

发布时间：2025年06月09日

`LLM应用` `计算机科学`

> Plug-in and Fine-tuning: Bridging the Gap between Small Language Models and Large Language Models

# 摘要

> 大型语言模型（LLMs）以其深厚的语义理解和强大的泛化能力著称，但其高计算需求使其难以在资源受限的环境中大展身手。相比之下，小型语言模型（SLMs）虽然计算效率高，却常常在泛化能力上稍逊一筹。为了解决这一难题，我们推出了PiFi——一个巧妙结合LLMs和SLMs优势的创新框架，旨在在保持高效的同时释放高性能潜力。PiFi的秘诀在于将一个冻结的LLM层融入SLM，并通过针对特定任务的微调，让性能更上一层楼，而计算成本却无需大幅增加。我们的实验结果表明，PiFi在自然语言理解和生成等各项任务中均表现出色，性能提升显著。更重要的是，PiFi不仅能够充分挖掘LLMs的知识宝藏，还能显著提升模型对未见领域的适应能力，并助力语言能力的高效迁移，展现出强大的实用价值。

> Large language models (LLMs) are renowned for their extensive linguistic knowledge and strong generalization capabilities, but their high computational demands make them unsuitable for resource-constrained environments. In contrast, small language models (SLMs) are computationally efficient but often lack the broad generalization capacity of LLMs. To bridge this gap, we propose PiFi, a novel framework that combines the strengths of both LLMs and SLMs to achieve high performance while maintaining efficiency. PiFi integrates a single frozen layer from an LLM into a SLM and fine-tunes the combined model for specific tasks, boosting performance without a significant increase in computational cost. We show that PiFi delivers consistent performance improvements across a range of natural language processing tasks, including both natural language understanding and generation. Moreover, our findings demonstrate PiFi's ability to effectively leverage LLM knowledge, enhancing generalization to unseen domains and facilitating the transfer of linguistic abilities.

[Arxiv](https://arxiv.org/abs/2506.07424)