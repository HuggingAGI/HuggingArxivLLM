# 知识编辑中的模型合并

发布时间：2025年06月14日

`LLM应用` `人工智能` `机器学习`

> Model Merging for Knowledge Editing

# 摘要

> 大型语言模型（LLMs）需要持续更新以保持准确和最新的知识，随着世界的演变。现有的知识编辑方法虽然提供了多种知识更新的解决方案，但在处理顺序编辑场景时常常力不从心，损害模型的一般能力，严重限制了它们的实际应用。本文提出了一种结合稳健监督微调（R-SFT）与模型合并的两阶段知识编辑框架。我们的方法首先对LLM进行微调，使其充分内化新知识，然后将微调后的模型与原始基础模型合并，从而保留新获得的知识和一般能力。实验结果表明，我们的方法在顺序编辑中显著优于现有方法，同时更好地保留了模型的原始性能，这一切都不需要任何架构上的改变。代码可在GitHub上获取：https://github.com/Applied-Machine-Learning-Lab/MM4KE.

> Large Language Models (LLMs) require continuous updates to maintain accurate and current knowledge as the world evolves. While existing knowledge editing approaches offer various solutions for knowledge updating, they often struggle with sequential editing scenarios and harm the general capabilities of the model, thereby significantly hampering their practical applicability. This paper proposes a two-stage framework combining robust supervised fine-tuning (R-SFT) with model merging for knowledge editing. Our method first fine-tunes the LLM to internalize new knowledge fully, then merges the fine-tuned model with the original foundation model to preserve newly acquired knowledge and general capabilities. Experimental results demonstrate that our approach significantly outperforms existing methods in sequential editing while better preserving the original performance of the model, all without requiring any architectural changes. Code is available at: https://github.com/Applied-Machine-Learning-Lab/MM4KE.

[Arxiv](https://arxiv.org/abs/2506.12384)