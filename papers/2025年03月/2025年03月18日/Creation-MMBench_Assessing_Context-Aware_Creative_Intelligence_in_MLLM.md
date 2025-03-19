# # Creation-MMBench：评测多模态大语言模型的上下文感知创意能力

发布时间：2025年03月18日

`LLM应用

理由：这篇论文专注于评估多模态大型语言模型在创造力方面的表现，推出了一个基准测试，并探讨了模型在实际任务中的应用情况，属于LLM应用的研究领域。` `多模态模型` `评估基准`

> Creation-MMBench: Assessing Context-Aware Creative Intelligence in MLLM

# 摘要

> 创造力是智能的核心要素，它体现在能够在不同情境下生成新颖且恰当的解决方案的能力中。尽管大型语言模型（LLMs）在创造力方面的评估已经得到了广泛研究，但对于多模态大型语言模型（MLLMs）在这一领域的评估仍处于探索阶段。为了填补这一研究空白，我们推出了Creation-MMBench，这是一个专门设计用于评估多模态大型语言模型在基于图像的现实任务中创造力的基准测试。

该基准测试涵盖了51个细粒度任务，总计包含765个测试案例。为了确保评估的严谨性，我们为每个测试案例制定了特定的评估标准，从而指导对模型一般性回应质量以及与视觉输入事实一致性的一并评估。实验结果表明，当前的开源多模态大型语言模型在创意任务上的表现显著逊色于专有模型。此外，我们的分析还表明，视觉微调可能会对基础LLM的创造力产生负面影响。

Creation-MMBench为提升多模态大型语言模型的创造力提供了宝贵的见解，并为未来多模态生成智能的改进奠定了基础。完整的数据和评估代码已发布在https://github.com/open-compass/Creation-MMBench。

> Creativity is a fundamental aspect of intelligence, involving the ability to generate novel and appropriate solutions across diverse contexts. While Large Language Models (LLMs) have been extensively evaluated for their creative capabilities, the assessment of Multimodal Large Language Models (MLLMs) in this domain remains largely unexplored. To address this gap, we introduce Creation-MMBench, a multimodal benchmark specifically designed to evaluate the creative capabilities of MLLMs in real-world, image-based tasks. The benchmark comprises 765 test cases spanning 51 fine-grained tasks. To ensure rigorous evaluation, we define instance-specific evaluation criteria for each test case, guiding the assessment of both general response quality and factual consistency with visual inputs. Experimental results reveal that current open-source MLLMs significantly underperform compared to proprietary models in creative tasks. Furthermore, our analysis demonstrates that visual fine-tuning can negatively impact the base LLM's creative abilities. Creation-MMBench provides valuable insights for advancing MLLM creativity and establishes a foundation for future improvements in multimodal generative intelligence. Full data and evaluation code is released on https://github.com/open-compass/Creation-MMBench.

[Arxiv](https://arxiv.org/abs/2503.14478)