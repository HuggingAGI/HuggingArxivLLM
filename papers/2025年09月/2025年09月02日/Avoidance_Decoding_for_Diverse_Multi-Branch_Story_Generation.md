# 规避解码：多样化多分支故事生成

发布时间：2025年09月02日

`LLM应用` `媒体与娱乐`

> Avoidance Decoding for Diverse Multi-Branch Story Generation

# 摘要

> 大型语言模型（LLMs）生成的内容往往重复单调，尤其在故事创作等任务中——相同的输入提示会限制其创造性多样性。为此，我们提出一种全新的解码策略——避免解码（Avoidance Decoding）：通过惩罚与已生成内容的相似性来调整 token 对数概率，进而催生更多样的多分支故事。该惩罚机制能自适应平衡两种相似性度量：（1）概念级相似性惩罚——早期优先启用，旨在丰富初始故事概念；（2）叙事级相似性惩罚——后期逐步强化，确保情节发展既自然又多样。值得关注的是，相较于主流基线方法，我们的方法将输出多样性提升了 2.6 倍，重复率平均降低 30%，还能有效缓解文本退化现象。

> Large Language Models (LLMs) often generate repetitive and monotonous outputs, especially in tasks like story generation, due to limited creative diversity when given the same input prompt. To address this challenge, we propose a novel decoding strategy, Avoidance Decoding, that modifies token logits by penalizing similarity to previously generated outputs, thereby encouraging more diverse multi-branch stories. This penalty adaptively balances two similarity measures: (1) Concept-level Similarity Penalty, which is prioritized in early stages to diversify initial story concepts, and (2) Narrative-level Similarity Penalty, which is increasingly emphasized later to ensure natural yet diverse plot development. Notably, our method achieves up to 2.6 times higher output diversity and reduces repetition by an average of 30% compared to strong baselines, while effectively mitigating text degeneration. Furthermore, we reveal that our method activates a broader range of neurons, demonstrating that it leverages the model's intrinsic creativity.

[Arxiv](https://arxiv.org/abs/2509.02170)