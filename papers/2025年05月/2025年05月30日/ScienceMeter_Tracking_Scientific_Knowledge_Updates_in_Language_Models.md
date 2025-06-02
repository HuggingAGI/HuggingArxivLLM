# 科学知识追踪器：语言模型中的科学知识更新追踪

发布时间：2025年05月30日

`LLM应用` `科学研究` `知识更新`

> ScienceMeter: Tracking Scientific Knowledge Updates in Language Models

# 摘要

> 大型语言模型（LLMs）在科学研究中的应用日益广泛，但它们对科学进展的认知往往迅速过时。为此，我们推出了ScienceMeter，一个全新的框架，用于评估跨越过去、现在和未来科学知识的知识更新方法。ScienceMeter设定了三个关键指标：知识保留能力、新知获取能力以及未来知识的预测能力。通过ScienceMeter，我们在涵盖医学、生物学、材料科学和计算机科学等十个领域的精选数据集上，评估了LLMs在科学主张判断与生成任务中的表现，该数据集包含15,444篇科学论文和30,888个科学主张。我们考察了五种代表性知识更新方法，包括训练和推理阶段的方法。实验结果表明，最佳的知识更新方法仅能保留85.9%的现有知识，获取71.7%的新知识，并预测37.7%的未来知识。基于推理的方法更适合大型模型，而小型模型则需通过训练来达到类似效果。跨领域分析显示，这些目标的性能密切相关。即使在专门的科学LLMs上，现有知识更新方法也难以同时实现这些目标，凸显了开发 robust 科学知识更新机制的重要性与挑战性。

> Large Language Models (LLMs) are increasingly used to support scientific research, but their knowledge of scientific advancements can quickly become outdated. We introduce ScienceMeter, a new framework for evaluating scientific knowledge update methods over scientific knowledge spanning the past, present, and future. ScienceMeter defines three metrics: knowledge preservation, the extent to which models' understanding of previously learned papers are preserved; knowledge acquisition, how well scientific claims from newly introduced papers are acquired; and knowledge projection, the ability of the updated model to anticipate or generalize to related scientific claims that may emerge in the future. Using ScienceMeter, we examine the scientific knowledge of LLMs on claim judgment and generation tasks across a curated dataset of 15,444 scientific papers and 30,888 scientific claims from ten domains including medicine, biology, materials science, and computer science. We evaluate five representative knowledge update approaches including training- and inference-time methods. With extensive experiments, we find that the best-performing knowledge update methods can preserve only 85.9% of existing knowledge, acquire 71.7% of new knowledge, and project 37.7% of future knowledge. Inference-based methods work for larger models, whereas smaller models require training to achieve comparable performance. Cross-domain analysis reveals that performance on these objectives is correlated. Even when applying on specialized scientific LLMs, existing knowledge update methods fail to achieve these objectives collectively, underscoring that developing robust scientific knowledge update mechanisms is both crucial and challenging.

[Arxiv](https://arxiv.org/abs/2505.24302)