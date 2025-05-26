# # 合成提示与生成数据的多样性测量  
本研究旨在测量合成提示及通过精细粒度角色提示生成数据的多样性。

发布时间：2025年05月22日

`LLM应用` `生成模型` `合成数据`

> Measuring diversity of synthetic prompts and data generated with fine-grained persona prompting

# 摘要

> 细粒度人设在生成用于大型语言模型（LLMs）预训练和有监督微调的多样化合成数据中得到了广泛应用。本研究采用一系列词汇多样性和冗余度量，评估了由人设驱动的合成生成提示和响应的多样性。研究发现，合成提示/指令的多样性显著低于人类编写的提示。进一步实验中，我们从不同规模的LLMs中采样，分别使用细粒度和粗粒度人设描述，探究人设描述中的细粒度细节对生成文本多样性的影响。结果表明，基于人设的提示确实能够提升词汇多样性（尤其在更大规模的模型中表现明显），但人设中的细粒度细节并未显著增加多样性。

> Fine-grained personas have recently been used for generating 'diverse' synthetic data for pre-training and supervised fine-tuning of Large Language Models (LLMs). In this work, we measure the diversity of persona-driven synthetically generated prompts and responses with a suite of lexical diversity and redundancy metrics. Firstly, we find that synthetic prompts/instructions are significantly less diverse than human-written ones. Next, we sample responses from LLMs of different sizes with fine-grained and coarse persona descriptions to investigate how much fine-grained detail in persona descriptions contribute to generated text diversity. We find that while persona-prompting does improve lexical diversity (especially with larger models), fine-grained detail in personas doesn't increase diversity noticeably.

[Arxiv](https://arxiv.org/abs/2505.17390)