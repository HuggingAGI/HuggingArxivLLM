# 我们真的需要编辑语言模型吗？——关于编辑语言模型的评估探讨

发布时间：2024年10月24日

`LLM理论

**理由**：这篇论文主要探讨了模型编辑对语言模型的影响，特别是对模型通用能力、鲁棒性和安全性的影响。它涉及对语言模型内在知识结构的理解以及编辑方法对模型性能的影响，这些都是与LLM理论相关的研究内容。因此，将其分类为LLM理论是合适的。` `模型编辑`

> Should We Really Edit Language Models? On the Evaluation of Edited Language Models

# 摘要

> 模型编辑作为一种高效更新语言模型知识的方法，正变得越来越流行。当前方法主要关注可靠性、泛化性和局部性，许多方法在这些方面表现出色。然而，最近的研究揭示了这些编辑方法的潜在问题，如知识扭曲或冲突。尽管如此，编辑后语言模型的通用能力仍未被充分探索。本文对各种编辑方法和不同语言模型进行了全面评估，得出以下结论：(1) 现有编辑方法会导致通用基准性能的不可避免下降，表明这些方法仅在少量编辑内能保持模型的通用能力。编辑次数稍多时，模型的内在知识结构会被破坏甚至完全损坏。(2) 指令调优模型对编辑更具鲁棒性，编辑后通用知识性能下降较少。(3) 大规模语言模型比小模型更抗编辑。(4) 编辑后模型的安全性显著减弱，即使是经过安全对齐的模型。我们的研究表明，当前编辑方法仅适用于语言模型内的小规模知识更新，这为研究更实用和可靠的编辑方法提供了动力。代码和复现的详细信息请访问 https://github.com/lqinfdim/EditingEvaluation。

> Model editing has become an increasingly popular alternative for efficiently updating knowledge within language models. Current methods mainly focus on reliability, generalization, and locality, with many methods excelling across these criteria. Some recent works disclose the pitfalls of these editing methods such as knowledge distortion or conflict. However, the general abilities of post-edited language models remain unexplored. In this paper, we perform a comprehensive evaluation on various editing methods and different language models, and have following findings. (1) Existing editing methods lead to inevitable performance deterioration on general benchmarks, indicating that existing editing methods maintain the general abilities of the model within only a few dozen edits. When the number of edits is slightly large, the intrinsic knowledge structure of the model is disrupted or even completely damaged. (2) Instruction-tuned models are more robust to editing, showing less performance drop on general knowledge after editing. (3) Language model with large scale is more resistant to editing compared to small model. (4) The safety of the edited model, is significantly weakened, even for those safety-aligned models. Our findings indicate that current editing methods are only suitable for small-scale knowledge updates within language models, which motivates further research on more practical and reliable editing methods. The details of code and reproduction can be found in https://github.com/lqinfdim/EditingEvaluation.

[Arxiv](https://arxiv.org/abs/2410.18785)