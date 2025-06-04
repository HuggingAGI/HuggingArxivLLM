# 咨询式解码：又一协同机制

发布时间：2025年06月02日

`LLM应用` `计算性能`

> Consultant Decoding: Yet Another Synergistic Mechanism

# 摘要

> 基于Speculative Decoding (SD)的协同机制作为一种简单有效的加速大型语言模型 (LLMs) 推理的方法，已经吸引了广泛关注。然而，高拒绝率需要反复调用LLMs来验证草稿令牌，这削弱了SD整体效率的提升。在这项工作中，我们重新审视了现有的验证机制，并提出了一种新的协同机制——Consultant Decoding (CD)。与SD依赖于重要性采样衍生出的指标进行验证不同，CD通过LLM单独计算的token级可能性来验证候选草稿。与目标模型相比，CD实现了推理速度最高2.5倍的提升，同时保持了相当的生成质量（约为目标模型性能的100%）。有趣的是，这是通过结合参数规模相差两个数量级的模型实现的。此外，CD将大型目标模型的调用频率降低到10%以下，尤其在更复杂的任务中。研究发现，CD的表现甚至超过了大型目标模型，理论上这代表了推测解码的上限。

> The synergistic mechanism based on Speculative Decoding (SD) has garnered considerable attention as a simple yet effective approach for accelerating the inference of large language models (LLMs). Nonetheless, the high rejection rates require repeated LLMs calls to validate draft tokens, undermining the overall efficiency gain of SD. In this work, we revisit existing verification mechanisms and propose a novel synergetic mechanism Consultant Decoding (CD). Unlike SD, which relies on a metric derived from importance sampling for verification, CD verifies candidate drafts using token-level likelihoods computed solely by the LLM. CD achieves up to a 2.5-fold increase in inference speed compared to the target model, while maintaining comparable generation quality (around 100% of the target model's performance). Interestingly, this is achieved by combining models whose parameter sizes differ by two orders of magnitude. In addition, CD reduces the call frequency of the large target model to below 10%, particularly in more demanding tasks. CD's performance was even found to surpass that of the large target model, which theoretically represents the upper bound for speculative decoding.

[Arxiv](https://arxiv.org/abs/2506.02391)