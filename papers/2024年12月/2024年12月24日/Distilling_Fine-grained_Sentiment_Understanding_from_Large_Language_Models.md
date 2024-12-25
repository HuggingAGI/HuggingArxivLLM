# 从大型语言模型中萃取细粒度的情感认知

发布时间：2024年12月24日

`LLM应用` `情感分析`

> Distilling Fine-grained Sentiment Understanding from Large Language Models

# 摘要

> 精细粒度情感分析（FSA）旨在从海量的观点性文本中提取并总结用户的意见。最新研究显示，大型语言模型（LLMs）具备卓越的情感理解能力。然而，直接将LLMs应用于FSA会带来高昂的推理成本。所以，本文探索把LLMs中的精细粒度情感理解提炼到小型语言模型（SLMs）里。我们引导LLMs检查和解读给定评论的情感，再利用生成的内容对SLMs进行预训练。另外，我们构建了一个全面的FSA基准来评估SLMs和LLMs。基于此基准开展的大量实验表明：（1）提炼大幅提升了SLMs在FSA任务中的表现，F1分数提高了6.00％，而且提炼后的模型仅用2.2亿参数就能胜过Llama-2-7b；（2）提炼让SLMs拥有出色的零样本情感分类能力，使其能够与教师模型相媲美甚至超越。这些结果表明，从LLMs进行提炼对于FSA是极具前景的方向。我们会在url{https://github.com/HITSZ-HLT/FSA-Distillation}发布我们的代码、数据和预训练模型权重。

> Fine-grained sentiment analysis (FSA) aims to extract and summarize user opinions from vast opinionated text. Recent studies demonstrate that large language models (LLMs) possess exceptional sentiment understanding capabilities. However, directly deploying LLMs for FSA applications incurs high inference costs. Therefore, this paper investigates the distillation of fine-grained sentiment understanding from LLMs into small language models (SLMs). We prompt LLMs to examine and interpret the sentiments of given reviews and then utilize the generated content to pretrain SLMs. Additionally, we develop a comprehensive FSA benchmark to evaluate both SLMs and LLMs. Extensive experiments on this benchmark reveal that: (1) distillation significantly enhances the performance of SLMs in FSA tasks, achieving a 6.00\% improvement in $F_1$-score, and the distilled model can outperform Llama-2-7b with only 220M parameters; (2) distillation equips SLMs with excellent zero-shot sentiment classification capabilities, enabling them to match or even exceed their teacher models. These results suggest that distillation from LLMs is a highly promising direction for FSA. We will release our code, data, and pretrained model weights at url{https://github.com/HITSZ-HLT/FSA-Distillation}.

[Arxiv](https://arxiv.org/abs/2412.18552)