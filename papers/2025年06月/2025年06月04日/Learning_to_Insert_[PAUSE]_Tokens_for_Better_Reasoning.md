# 学习如何在推理过程中巧妙插入暂停标记，提升推理效果

发布时间：2025年06月04日

`LLM理论` `模型训练` `推理能力`

> Learning to Insert [PAUSE] Tokens for Better Reasoning

# 摘要

> 为了提升推理能力，先前研究尝试在训练中加入专用标记，这些策略强化了基于 transformer 的大型语言模型（LLMs）的学习机制。在先前研究的基础上，其中在推理步骤之前连续插入虚拟标记可以提升效果，我们提出了一种名为动态插入标记训练（DIT）的新方法。我们的方法根据标记的对数似然，识别出序列中模型置信度最低的位置。在这些位置上战略性地插入 [PAUSE] 标记，增强了模型对后续标记的预测能力。实验结果在从 2.7B 模型到 8B 模型的多种数据集和模型上均表明，DIT 一致优于传统的微调和之前的标记插入方法。通过这一简单而有效的方法，我们在 GSM8K 上实现了最高 4.7% 的准确率提升，在 AQUA-RAT 上提升了 3.23%，在 MBPP 数据集上通过率 @1 最高提升了 3.4%。我们的工作展示了一种基于模型的动态方法，而非启发式方法，从而拓宽了推理研究的范围。

> To enhance reasoning capabilities, previous works have explored incorporating special-purpose tokens into the training process. These strategies strengthen the learning mechanism of transformer-based large language models (LLMs). Building on prior research, in which inserting dummy tokens consecutively just before reasoning steps can enhance effectiveness, we introduce a novel approach termed Dynamic Inserting Tokens Training (DIT). Our method identifies positions within sequences where model confidence is lowest according to token log-likelihood. Strategically inserting [PAUSE] tokens on these positions bolsters the model's predictive capabilities for subsequent tokens. Experimental results across diverse datasets and models, from the 2.7B model to the 8B model, demonstrate that DIT consistently outperforms traditional fine-tuning and previous token insertion methods. With this simple yet effective method, we achieve accuracy gains of up to 4.7%p on GSM8K, 3.23%p on AQUA-RAT, and pass@1 improvements of up to 3.4%p on MBPP datasets. Our work shows a model-based, dynamic approach rather than a heuristic one, thereby broadening the scope of research in reasoning.

[Arxiv](https://arxiv.org/abs/2506.03616)