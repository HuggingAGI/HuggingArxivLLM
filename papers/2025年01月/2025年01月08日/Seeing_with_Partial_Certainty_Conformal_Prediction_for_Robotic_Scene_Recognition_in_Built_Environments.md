# 部分确定性下的观察：建筑环境中机器人场景识别的保形预测

发布时间：2025年01月08日

`LLM应用

理由：这篇论文讨论了如何利用大型语言模型（LLM）和视觉语言模型（VLM）来辅助残障人士的机器人进行环境位置识别。论文提出了一个名为“部分确定性视觉识别”（SwPC）的框架，旨在解决LLM和VLM在位置识别中的不确定性问题。虽然论文涉及了视觉语言模型（VLM），但其核心仍然是基于LLM的应用，特别是在机器人导航和交互中的应用。因此，这篇论文应归类为LLM应用。` `机器人` `残障辅助`

> Seeing with Partial Certainty: Conformal Prediction for Robotic Scene Recognition in Built Environments

# 摘要

> 在辅助残障人士的机器人领域，精准的环境位置识别是确保机器人在多样化室内空间中安全导航和互动的关键。语言接口，尤其是基于大型语言模型（LLM）和视觉语言模型（VLM）的接口，因其能够解析视觉场景并与语义信息关联，展现出巨大潜力。然而，这些接口也因其预测的“幻觉”问题而备受关注。此外，人类提供的语言指令往往含糊不清，缺乏对特定位置、物体或动作的精确描述，进一步加剧了这一问题。为此，我们提出了“部分确定性视觉识别”（SwPC）框架，旨在测量和调整基于VLM的位置识别中的不确定性，使模型能够在信心不足时主动寻求帮助。该框架基于符合预测理论，为位置识别提供统计保证，同时最大限度地减少在复杂室内环境中对人类干预的依赖。通过在Matterport3D数据集上的实验，我们证明SwPC显著提升了成功率，并大幅减少了所需的人类干预。SwPC无需模型微调即可直接应用于任何VLM，提供了一种轻量级的不确定性建模方法，能够随着基础模型能力的扩展而灵活扩展。

> In assistive robotics serving people with disabilities (PWD), accurate place recognition in built environments is crucial to ensure that robots navigate and interact safely within diverse indoor spaces. Language interfaces, particularly those powered by Large Language Models (LLM) and Vision Language Models (VLM), hold significant promise in this context, as they can interpret visual scenes and correlate them with semantic information. However, such interfaces are also known for their hallucinated predictions. In addition, language instructions provided by humans can also be ambiguous and lack precise details about specific locations, objects, or actions, exacerbating the hallucination issue. In this work, we introduce Seeing with Partial Certainty (SwPC) - a framework designed to measure and align uncertainty in VLM-based place recognition, enabling the model to recognize when it lacks confidence and seek assistance when necessary. This framework is built on the theory of conformal prediction to provide statistical guarantees on place recognition while minimizing requests for human help in complex indoor environment settings. Through experiments on the widely used richly-annotated scene dataset Matterport3D, we show that SwPC significantly increases the success rate and decreases the amount of human intervention required relative to the prior art. SwPC can be utilized with any VLMs directly without requiring model fine-tuning, offering a promising, lightweight approach to uncertainty modeling that complements and scales alongside the expanding capabilities of foundational models.

[Arxiv](https://arxiv.org/abs/2501.04947)