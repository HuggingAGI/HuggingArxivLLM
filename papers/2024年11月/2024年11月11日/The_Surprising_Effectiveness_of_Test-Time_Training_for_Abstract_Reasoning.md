# 测试时训练在抽象推理中的惊人效果

发布时间：2024年11月11日

`LLM理论

理由：这篇论文主要探讨了语言模型在推理任务中的表现，特别是通过测试时训练（TTT）来提升模型的推理能力。论文的核心内容集中在如何通过调整模型参数和训练策略来改进语言模型的推理能力，这属于对语言模型的理论研究和优化方法的探讨，因此应归类为LLM理论。` `人工智能` `语言模型`

> The Surprising Effectiveness of Test-Time Training for Abstract Reasoning

# 摘要

> # 摘要
语言模型在训练分布内的任务上表现出色，但在需要复杂推理的新问题上往往力不从心。我们探索了测试时训练（TTT）的有效性——在推理过程中利用输入数据生成的损失临时更新模型参数——作为提升模型推理能力的手段，并以抽象与推理语料库（ARC）为基准。通过系统实验，我们发现了成功TTT的三大要素：（1）在类似任务上预微调（2）辅助任务格式与数据增强（3）逐实例训练。TTT显著提升了ARC任务的表现，准确率比基础微调模型高出6倍；将TTT应用于8B参数的语言模型，我们在ARC公共验证集上达到了53%的准确率，将最先进的纯神经方法提升了近25%。通过结合最新的程序生成方法，我们获得了61.9%的SoTA公共验证准确率，与人类平均得分持平。研究结果表明，显式符号搜索并非提升神经语言模型抽象推理能力的唯一途径；在少量示例上持续训练的额外测试时训练同样效果显著。

> 
Abstract:Language models have shown impressive performance on tasks within their training distribution, but often struggle with novel problems requiring complex reasoning. We investigate the effectiveness of test-time training (TTT) -- updating model parameters temporarily during inference using a loss derived from input data -- as a mechanism for improving models' reasoning capabilities, using the Abstraction and Reasoning Corpus (ARC) as a benchmark. Through systematic experimentation, we identify three crucial components for successful TTT: (1) initial finetuning on similar tasks (2) auxiliary task format and augmentations (3) per-instance training. TTT significantly improves performance on ARC tasks, achieving up to 6x improvement in accuracy compared to base fine-tuned models; applying TTT to an 8B-parameter language model, we achieve 53% accuracy on the ARC's public validation set, improving the state-of-the-art by nearly 25% for public and purely neural approaches. By ensembling our method with recent program generation approaches, we get SoTA public validation accuracy of 61.9%, matching the average human score. Our findings suggest that explicit symbolic search is not the only path to improved abstract reasoning in neural language models; additional test-time applied to continued training on few-shot examples can also be extremely effective.
    

[Arxiv](https://arxiv.org/pdf/2411.07279)