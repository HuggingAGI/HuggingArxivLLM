# 基于不同量化值的LLM情感文本生成质量

发布时间：2025年01月31日

`LLM理论

理由：这篇论文主要研究了大型语言模型在情感文本生成中的量化技术对内存利用率和文本质量的影响。它探讨了不同量化值、GPU内存利用率和文本质量之间的权衡，属于对大型语言模型的理论研究和优化方法的探讨，因此应归类为LLM理论。` `情感分析`

> LLM-based Affective Text Generation Quality Based on Different Quantization Values

# 摘要

> 大型语言模型在语言生成和理解方面表现出色，使AI系统能够生成更人性化、情感丰富的文本。然而，这些模型依赖大量参数，需要大量计算资源进行训练和推理，在某些情况下（如预算或硬件限制）可能难以获取。通过减少精度位数等技术，可以节省内存并降低计算资源需求，但会牺牲精度。本文研究了情感文本生成（如“我真的很喜欢在白雪覆盖的森林中跑步”）中，不同量化值、GPU内存利用率和文本质量之间的权衡。我们使用情感分类器和十个种子提示生成情感文本，并在两个家族的五个开源语言模型上测试了8、16和32位精度设置。结果表明，位数减少可节省76%的内存，但较大模型的F1分数下降高达10个百分点，较小模型则提升10个百分点，推理时间翻倍。在文本质量方面，较低量化级别的大型模型通常优于较小的高精度模型，且内存需求相似。

> Large language models exhibit a remarkable capacity in language generation and comprehension. These advances enable AI systems to produce more human-like and emotionally engaging text. However, these models rely on a large number of parameters, requiring significant computational resources for training and inference. In some scenarios, accessing these resources can be challenging (e.g., budget or hardware limitations). Techniques like reducing precision bits can make models more memory-efficient, reducing the computational resources needed, at the cost of reduced accuracy. This paper addresses the trade-off between different quantization values, GPU RAM utilization, and text quality in affective text generation (e.g., "I really enjoy running in the snow-covered forest"). To evaluate, we use an emotion classifier and ten seed prompts to generate affective text. We test three setups of precision bits (8, 16, and 32) across five open-weight language models from two different families. Our findings demonstrate that bit reductions lead to memory savings, achieving a reduction of 76%. However, this optimization comes with a trade-off, leading to a decrease of up to 10 pp in F1 score for larger models and an increase of 10 pp for smaller models, along with roughly double the inference time. In terms of text quality, larger models at lower quantization levels generally outperform smaller, higher-precision models -- while requiring similar memory.

[Arxiv](https://arxiv.org/abs/2501.19317)