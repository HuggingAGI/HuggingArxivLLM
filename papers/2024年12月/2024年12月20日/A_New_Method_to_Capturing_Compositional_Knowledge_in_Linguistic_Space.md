# 一种捕获语言空间中组合知识的新手段

发布时间：2024年12月20日

`LLM应用` `视觉语言模型` `图像检索`

> A New Method to Capturing Compositional Knowledge in Linguistic Space

# 摘要

> 组合理解能够让视觉语言模型解读图像和文本中对象、属性及关系之间的复杂关联。但现有的多数方法往往依赖于困难的负样本和微调，这可能会高估改进效果，而且获取困难负样本存在难度，具有局限性。在本研究中，我们引入了零样本组合理解（ZS-CU）这一新任务，无需困难的负训练数据就能增强组合理解能力。我们提出了 YUKINO（通过无文本反转产生的组合理解知识），它利用文本反转将未标记的图像映射到预训练的 CLIP 模型中的伪标记。我们提议引入“否”逻辑正则化来处理反转中的标记交互问题。另外，我们建议采用知识蒸馏来降低文本反转的时间复杂度。实验结果显示，YUKINO 在 SugarCREPE 基准测试中的表现比现有的多模态 SOTA 模型高出 8%以上，在图像检索任务中也实现了显著提升。

> Compositional understanding allows visual language models to interpret complex relationships between objects, attributes, and relations in images and text. However, most existing methods often rely on hard negative examples and fine-tuning, which can overestimate improvements and are limited by the difficulty of obtaining hard negatives. In this work, we introduce Zero-Shot Compositional Understanding (ZS-CU), a novel task that enhances compositional understanding without requiring hard negative training data. We propose YUKINO (Yielded Compositional Understanding Knowledge via Textual Inversion with NO), which uses textual inversion to map unlabeled images to pseudo-tokens in a pre-trained CLIP model. We propose introducing "no" logical regularization to address the issue of token interaction in inversion. Additionally, we suggest using knowledge distillation to reduce the time complexity of textual inversion. Experimental results show that YUKINO outperforms the existing multi-modal SOTA models by over 8% on the SugarCREPE benchmark, and also achieves significant improvements in image retrieval tasks.

[Arxiv](https://arxiv.org/abs/2412.15632)