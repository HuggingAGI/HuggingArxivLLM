# 评估大型语言模型在真实世界访谈数据人格推断中的对齐

发布时间：2025年09月16日

`LLM应用` `医疗健康`

> Evaluating LLM Alignment on Personality Inference from Real-World Interview Data

# 摘要

> 大型语言模型（LLMs）正日益应用于需要细腻心理洞察力的场景，比如情感支持、心理咨询及决策辅助等角色。然而，这些应用的核心在于解读人类人格特质，而LLMs在这方面的能力，尤其是在真实对话场景中的表现，尚属未知。尽管已有研究利用社交媒体数据中的离散大五人格标签模拟LLM的“人格”，但LLM与自然互动中获取的连续、真实人格评估的匹配度仍缺乏检验。为填补这一空白，我们提出了一个全新基准，包含半结构化访谈转录文本及经过验证的连续大五人格特质分数。基于该数据集，我们系统评估了LLM在三种范式下的表现：（1）采用GPT-4.1 Mini的零样本与思维链提示；（2）对RoBERTa和Meta-LLaMA架构进行基于LoRA的微调；（3）利用预训练BERT和OpenAI的text-embedding-3-small的静态嵌入进行回归分析。结果显示，模型预测与真实人格特质的皮尔逊相关系数均低于0.26，表明当前LLM与经过验证的心理构念匹配度较低。思维链提示相较于零样本的提升微乎其微，这意味着人格推断更多依赖潜在语义表征，而非显式推理过程。这些发现揭示了LLM与复杂人类属性匹配的难点，也为未来研究指明了方向，包括特定特质提示、情境感知建模及对齐导向微调等。

> Large Language Models (LLMs) are increasingly deployed in roles requiring nuanced psychological understanding, such as emotional support agents, counselors, and decision-making assistants. However, their ability to interpret human personality traits, a critical aspect of such applications, remains unexplored, particularly in ecologically valid conversational settings. While prior work has simulated LLM "personas" using discrete Big Five labels on social media data, the alignment of LLMs with continuous, ground-truth personality assessments derived from natural interactions is largely unexamined. To address this gap, we introduce a novel benchmark comprising semi-structured interview transcripts paired with validated continuous Big Five trait scores. Using this dataset, we systematically evaluate LLM performance across three paradigms: (1) zero-shot and chain-of-thought prompting with GPT-4.1 Mini, (2) LoRA-based fine-tuning applied to both RoBERTa and Meta-LLaMA architectures, and (3) regression using static embeddings from pretrained BERT and OpenAI's text-embedding-3-small. Our results reveal that all Pearson correlations between model predictions and ground-truth personality traits remain below 0.26, highlighting the limited alignment of current LLMs with validated psychological constructs. Chain-of-thought prompting offers minimal gains over zero-shot, suggesting that personality inference relies more on latent semantic representation than explicit reasoning. These findings underscore the challenges of aligning LLMs with complex human attributes and motivate future work on trait-specific prompting, context-aware modeling, and alignment-oriented fine-tuning.

[Arxiv](https://arxiv.org/abs/2509.13244)