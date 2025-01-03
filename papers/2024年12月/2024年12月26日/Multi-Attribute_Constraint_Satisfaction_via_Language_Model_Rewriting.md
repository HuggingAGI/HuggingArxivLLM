# 通过语言模型重写实现多属性约束满足

发布时间：2024年12月26日

`LLM应用

理由：这篇论文提出了一种多属性约束满足（MACS）方法，旨在微调语言模型以满足用户指定的多个外部实值属性约束。该方法涉及从初始改写输出中采样多样化的多属性编辑对，并将语言模型训练为编辑器。在推理时，语言模型利用设计的约束满足奖励，迭代优化其解决方案，以满足所有属性约束。论文还提出了细粒度约束满足（FineCS）基准，用于评估该方法在文本风格转换和蛋白质设计等任务中的表现。这些内容表明该论文主要关注如何应用大型语言模型（LLM）来解决实际问题，因此应归类为“LLM应用”。` `生物信息学`

> Multi-Attribute Constraint Satisfaction via Language Model Rewriting

# 摘要

> # 摘要
在多个外部属性上精确满足约束是一个普遍的计算问题，涉及从文本生成到蛋白质工程等多个领域。现有的多属性约束满足方法通常依赖于特定架构或梯度分类器，限制了其与任意黑盒评估器和预训练模型的兼容性。尽管当前通用语言模型功能强大，但无法实现对外部属性的细粒度多属性控制。为此，我们提出了多属性约束满足（MACS）方法，能够在任何序列领域微调语言模型，以满足用户指定的多个外部实值属性约束。MACS通过从初始改写输出中采样多样化的多属性编辑对，将LM训练为编辑器。在推理时，LM利用我们设计的约束满足奖励，迭代优化其解决方案，以满足所有属性约束。我们还尝试了奖励加权的行为克隆，进一步提升LM的约束满足率。为评估该方法，我们提出了细粒度约束满足（FineCS）基准，包含两个挑战性任务：（1）文本风格转换，目标是同时调整评论的情感和复杂性；（2）蛋白质设计，重点是调节绿色荧光蛋白（GFP）的荧光和稳定性。实验表明，MACS在FineCS任务中实现了最高的阈值满足率，超越了领域特定基线。我们的工作为通用和实值多属性控制开辟了新方向，对NLP和生物信息学等领域具有广泛的应用潜力。

> Obeying precise constraints on top of multiple external attributes is a common computational problem underlying seemingly different domains, from controlled text generation to protein engineering. Existing language model (LM) controllability methods for multi-attribute constraint satisfaction often rely on specialized architectures or gradient-based classifiers, limiting their flexibility to work with arbitrary black-box evaluators and pretrained models. Current general-purpose large language models, while capable, cannot achieve fine-grained multi-attribute control over external attributes. Thus, we create Multi-Attribute Constraint Satisfaction (MACS), a generalized method capable of finetuning language models on any sequential domain to satisfy user-specified constraints on multiple external real-value attributes. Our method trains LMs as editors by sampling diverse multi-attribute edit pairs from an initial set of paraphrased outputs. During inference, LM iteratively improves upon its previous solution to satisfy constraints for all attributes by leveraging our designed constraint satisfaction reward. We additionally experiment with reward-weighted behavior cloning to further improve the constraint satisfaction rate of LMs. To evaluate our approach, we present a new Fine-grained Constraint Satisfaction (FineCS) benchmark, featuring two challenging tasks: (1) Text Style Transfer, where the goal is to simultaneously modify the sentiment and complexity of reviews, and (2) Protein Design, focusing on modulating fluorescence and stability of Green Fluorescent Proteins (GFP). Our empirical results show that MACS achieves the highest threshold satisfaction in both FineCS tasks, outperforming strong domain-specific baselines. Our work opens new avenues for generalized and real-value multi-attribute control, with implications for diverse applications spanning NLP and bioinformatics.

[Arxiv](https://arxiv.org/abs/2412.19198)