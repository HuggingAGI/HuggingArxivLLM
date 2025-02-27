# Amulet：通过测试时的重新对齐实现大型语言模型的个性化偏好适配

发布时间：2025年02月26日

`LLM应用

理由：这篇论文探讨了如何在大型语言模型中实时适应用户的个性化偏好，提出了一个无需重新训练的框架Amulet，属于LLM的应用层面创新，旨在提升模型的实际应用效果。` `电子商务` `推荐系统`

> Amulet: ReAlignment During Test Time for Personalized Preference Adaptation of LLMs

# 摘要

> 如何让大型语言模型（LLMs）与用户偏好对齐一直是研究热点，但用户的偏好往往具有个性化、动态变化和多样性，涉及文化、价值观或时间等因素。这导致在实际应用中，真实用户的偏好往往与模型开发者训练时所采用的偏好不一致。由于无法为每个需求收集足够的数据并重新训练，因此在测试阶段基于基础LLMs研究高效的实时偏好适应方法具有重要意义。为此，我们引入了Amulet，这是一个无需重新训练的新型框架，它将每个词的解码过程作为一个独立的在线学习问题，并在用户提供的简单提示指导下进行实时优化，以满足用户的个性化偏好。为了降低每个词解码过程中优化带来的计算成本，我们额外为优化过程的每一步迭代提供了闭式解，从而将计算时间成本降至可忽略的水平。详细实验结果表明，Amulet在多种LLMs、数据集和用户偏好的组合场景下能够实现显著的性能提升，同时保持了可接受的计算效率。

> How to align large language models (LLMs) with user preferences from a static general dataset has been frequently studied. However, user preferences are usually personalized, changing, and diverse regarding culture, values, or time. This leads to the problem that the actual user preferences often do not coincide with those trained by the model developers in the practical use of LLMs. Since we cannot collect enough data and retrain for every demand, researching efficient real-time preference adaptation methods based on the backbone LLMs during test time is important. To this end, we introduce Amulet, a novel, training-free framework that formulates the decoding process of every token as a separate online learning problem with the guidance of simple user-provided prompts, thus enabling real-time optimization to satisfy users' personalized preferences. To reduce the computational cost brought by this optimization process for each token, we additionally provide a closed-form solution for each iteration step of the optimization process, thereby reducing the computational time cost to a negligible level. The detailed experimental results demonstrate that Amulet can achieve significant performance improvements in rich settings with combinations of different LLMs, datasets, and user preferences, while maintaining acceptable computational efficiency.

[Arxiv](https://arxiv.org/abs/2502.19148)