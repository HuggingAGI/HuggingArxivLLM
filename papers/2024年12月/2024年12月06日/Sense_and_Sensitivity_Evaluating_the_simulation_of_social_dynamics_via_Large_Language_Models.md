# 《感知与敏感性：借大型语言模型评估社会动态模拟》

发布时间：2024年12月06日

`Agent` `社会科学` `经济学`

> Sense and Sensitivity: Evaluating the simulation of social dynamics via Large Language Models

# 摘要

> 大型语言模型愈发被提议用作经典基于代理的模型（ABMs）的有力替代品，以模拟社会动态。借由将LLMs当作人类行为的替身，此新方法有望模拟出远比经典ABMs更为复杂的动态，并在社会科学、政治学和经济学等领域斩获新的洞见。然而，鉴于LLMs的黑箱特质，LLM代理是否切实执行了其自然语言指令中所编码的预期语义，以及交互产生的动态是否有意义，尚不明确。为探究此问题，我们提出了一个新的评估框架，将LLM模拟置于社会科学既定参考模型的动态范畴内。把LLMs视作黑箱函数，我们对照此参考模型评估其输入输出行为，从而能够评估其行为的细节方面。我们的结果显示，虽说有可能设计出近似预期动态的提示，但这些模拟的质量对提示的特定选择极为敏感。关键在于，模拟甚至对诸如细微措辞变化和空格之类的任意变动都很敏感。这让当前版本的LLMs用于有意义模拟的实用性存疑，因为若无参考模型，就无法预先确定提示中看似无意义的变化会对模拟产生何种影响。

> Large language models have increasingly been proposed as a powerful replacement for classical agent-based models (ABMs) to simulate social dynamics. By using LLMs as a proxy for human behavior, the hope of this new approach is to be able to simulate significantly more complex dynamics than with classical ABMs and gain new insights in fields such as social science, political science, and economics. However, due to the black box nature of LLMs, it is unclear whether LLM agents actually execute the intended semantics that are encoded in their natural language instructions and, if the resulting dynamics of interactions are meaningful. To study this question, we propose a new evaluation framework that grounds LLM simulations within the dynamics of established reference models of social science. By treating LLMs as a black-box function, we evaluate their input-output behavior relative to this reference model, which allows us to evaluate detailed aspects of their behavior. Our results show that, while it is possible to engineer prompts that approximate the intended dynamics, the quality of these simulations is highly sensitive to the particular choice of prompts. Importantly, simulations are even sensitive to arbitrary variations such as minor wording changes and whitespace. This puts into question the usefulness of current versions of LLMs for meaningful simulations, as without a reference model, it is impossible to determine a priori what impact seemingly meaningless changes in prompt will have on the simulation.

[Arxiv](https://arxiv.org/abs/2412.05093)