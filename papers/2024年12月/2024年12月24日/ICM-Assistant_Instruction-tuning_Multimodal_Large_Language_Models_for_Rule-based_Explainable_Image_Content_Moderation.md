# ICM-Assistant：用于基于规则的可解释图像内容审核的指令调优多模态大型语言模型

发布时间：2024年12月24日

`LLM应用` `互联网` `内容审核`

> ICM-Assistant: Instruction-tuning Multimodal Large Language Models for Rule-based Explainable Image Content Moderation

# 摘要

> 争议性内容大量充斥于互联网，违背了各类文化规范和儿童保护标准。传统的图像内容审核（ICM）模型难以针对不同标准做出精准的审核决策，而近期的多模态大型语言模型（MLLMs）在应用于基于通用规则的ICM时，常常产生与人类审核员不一致的分类和解释结果。为达成灵活、可解释且精准的ICM，我们设计了全新的基于规则的数据集生成流程，拆解简明的人为定义规则，并借助精心设计的多阶段提示来丰富简短明确的图像注释。我们的ICM-Instruct数据集涵盖了详尽的审核解释和审核问答对。基于此，我们在基于规则的ICM框架中创建了ICM-Assistant模型，使其能够轻松应用于实际操作。我们的ICM-Assistant模型展现出了非凡的性能和灵活性。具体来说，它在各种来源上的表现显著优于现有方法，在审核分类（平均提升36.8％）和审核解释质量（平均提升26.6％）方面均持续超越现有的MLLMs。代码/数据可在https://github.com/zhaoyuzhi/ICM-Assistant获取。

> Controversial contents largely inundate the Internet, infringing various cultural norms and child protection standards. Traditional Image Content Moderation (ICM) models fall short in producing precise moderation decisions for diverse standards, while recent multimodal large language models (MLLMs), when adopted to general rule-based ICM, often produce classification and explanation results that are inconsistent with human moderators. Aiming at flexible, explainable, and accurate ICM, we design a novel rule-based dataset generation pipeline, decomposing concise human-defined rules and leveraging well-designed multi-stage prompts to enrich short explicit image annotations. Our ICM-Instruct dataset includes detailed moderation explanation and moderation Q-A pairs. Built upon it, we create our ICM-Assistant model in the framework of rule-based ICM, making it readily applicable in real practice. Our ICM-Assistant model demonstrates exceptional performance and flexibility. Specifically, it significantly outperforms existing approaches on various sources, improving both the moderation classification (36.8\% on average) and moderation explanation quality (26.6\% on average) consistently over existing MLLMs. Code/Data is available at https://github.com/zhaoyuzhi/ICM-Assistant.

[Arxiv](https://arxiv.org/abs/2412.18216)