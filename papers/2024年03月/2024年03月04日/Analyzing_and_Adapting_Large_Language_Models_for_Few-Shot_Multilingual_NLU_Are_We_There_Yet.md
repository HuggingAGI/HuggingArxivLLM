# 针对少量样本多语言 NLU 任务，对大型语言模型进行分析与适应的研究：我们是否已达成目标？

发布时间：2024年03月04日

`LLM应用`

> Analyzing and Adapting Large Language Models for Few-Shot Multilingual NLU: Are We There Yet?

# 摘要

> 监督微调、监督指令调优及上下文学习是三种流行的少量样本学习方法。近期，随着LLMs的发展，ICL以其简洁高效的特点崭露头角。然而，关于这几种方法如何应用于多语言少量样本学习的研究尚不充分，以往的关注点主要集中在性能表现上。本研究对此展开了深入全面的对比实验，涵盖了6种不同资源水平的语言、3个不同的NLU任务，以及多种语言和领域场景。值得注意的是，除了评估性能外，我们还从计算、推理和经济成本角度剖析了这些方法。结果显示，监督指令调优在性能与资源需求之间取得了最佳平衡。此外，我们还探索了预训练LLMs针对目标语言的适应性影响，发现尽管标准适应方法能在一定程度上提升目标语言的生成效果，但在ICL框架下诱发的语言理解能力并未显著提升，尤其对于低资源语言的表现仍较为局限。

> Supervised fine-tuning (SFT), supervised instruction tuning (SIT) and in-context learning (ICL) are three alternative, de facto standard approaches to few-shot learning. ICL has gained popularity recently with the advent of LLMs due to its simplicity and sample efficiency. Prior research has conducted only limited investigation into how these approaches work for multilingual few-shot learning, and the focus so far has been mostly on their performance. In this work, we present an extensive and systematic comparison of the three approaches, testing them on 6 high- and low-resource languages, three different NLU tasks, and a myriad of language and domain setups. Importantly, performance is only one aspect of the comparison, where we also analyse the approaches through the optics of their computational, inference and financial costs. Our observations show that supervised instruction tuning has the best trade-off between performance and resource requirements. As another contribution, we analyse the impact of target language adaptation of pretrained LLMs and find that the standard adaptation approaches can (superficially) improve target language generation capabilities, but language understanding elicited through ICL does not improve and remains limited, with low scores especially for low-resource languages.

[Arxiv](https://arxiv.org/abs/2403.01929)