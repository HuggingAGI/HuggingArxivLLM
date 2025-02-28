# 弥合创造力理解鸿沟：小规模的人机对齐助力LLMs实现专家级幽默排名

发布时间：2025年02月27日

`LLM应用

理由：这篇论文探讨了大型语言模型在创意内容理解方面的应用，特别是幽默理解的挑战和解决方案。通过分解幽默理解为三个核心要素并提出优化方法，论文展示了LLMs在特定任务中的应用和改进，属于LLM应用类别。` `创意内容` `人工智能`

> Bridging the Creativity Understanding Gap: Small-Scale Human Alignment Enables Expert-Level Humor Ranking in LLMs

# 摘要

> 大型语言模型（LLMs）在创意内容理解方面存在明显短板，这一问题在Hessel等（2023年）关于《纽约客》漫画配文比赛（NYCCC）的开创性研究中得到了充分体现。研究发现，LLMs与人类在幽默理解方面存在显著差距，这凸显了创意内容理解和评估是人工智能发展中亟待攻克的关键难题。我们通过将幽默理解分解为三个核心要素，并系统性地优化每个方面，重新审视这一挑战：通过改进标注增强视觉理解能力；利用LLMs生成的幽默推理和解释；以及通过与人类偏好数据进行针对性对齐。我们的优化方法在配文排名中达到了82.4%的准确率，显著超越了先前67%的基准水平，并与该领域世界知名的专家组成了相媲美的表现。值得注意的是，尽管尝试通过各种人格提示来模仿特定子群体的偏好仅产生了微小的影响，但基于人群偏好进行模型微调却表现出惊人的效果。这些发现表明，通过专注于特定子群体和个体的对齐，LLMs在创意判断方面的局限性可以得到有效克服。最后，我们主张实现人工通用智能需要系统性地收集创意领域内的人类偏好数据。我们坚信，正如人类创造力深受个体和文化偏好影响一样，利用多样化的人类偏好数据训练LLMs可能是培养真正创意理解能力的关键所在。

> Large Language Models (LLMs) have shown significant limitations in understanding creative content, as demonstrated by Hessel et al. (2023)'s influential work on the New Yorker Cartoon Caption Contest (NYCCC). Their study exposed a substantial gap between LLMs and humans in humor comprehension, establishing that understanding and evaluating creative content is key challenge in AI development. We revisit this challenge by decomposing humor understanding into three components and systematically improve each: enhancing visual understanding through improved annotation, utilizing LLM-generated humor reasoning and explanations, and implementing targeted alignment with human preference data. Our refined approach achieves 82.4% accuracy in caption ranking, singificantly improving upon the previous 67% benchmark and matching the performance of world-renowned human experts in this domain. Notably, while attempts to mimic subgroup preferences through various persona prompts showed minimal impact, model finetuning with crowd preferences proved remarkably effective. These findings reveal that LLM limitations in creative judgment can be effectively addressed through focused alignment to specific subgroups and individuals. Lastly, we propose the position that achieving artificial general intelligence necessitates systematic collection of human preference data across creative domains. We advocate that just as human creativity is deeply influenced by individual and cultural preferences, training LLMs with diverse human preference data may be essential for developing true creative understanding.

[Arxiv](https://arxiv.org/abs/2502.20356)