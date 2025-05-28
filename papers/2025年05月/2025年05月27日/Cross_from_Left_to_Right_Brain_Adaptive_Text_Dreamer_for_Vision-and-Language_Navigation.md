# 跨越左右脑：用于视觉语言导航的自适应文本生成器

发布时间：2025年05月27日

`Agent` `视觉与语言导航` `机器人`

> Cross from Left to Right Brain: Adaptive Text Dreamer for Vision-and-Language Navigation

# 摘要

> # 视觉与语言导航 (VLN)

视觉与语言导航要求代理在部分可观察性条件下通过遵循自然指令进行导航，这一任务使得感知与语言的对齐变得极具挑战性。现有方法通过想象未来场景来缓解这一问题，但它们依赖于基于视觉的合成，导致计算成本高昂且细节冗余。为解决这一难题，我们提出了一种基于	extit{语言}形式的自适应关键环境语义想象方法，从而实现更可靠和高效的导航策略。

具体而言，我们引入了一种创新的自适应文本梦境模型（ATD），这是一种基于大型语言模型（LLM）的双分支自引导想象策略。ATD的设计灵感来源于人类左右脑的分工：左脑专注于逻辑整合，右脑则负责对未来场景的想象预测。为了实现这一目标，我们仅对两个大脑中的Q-former进行微调，以高效激活LLM中的领域特定知识，从而在导航过程中动态更新逻辑推理和想象能力。

此外，我们引入了一种交叉交互机制来规范想象输出，并将其注入导航专家模块中，使ATD能够同时利用LLM的推理能力和导航模型的专业知识。我们在R2R基准上进行了大量实验，结果表明，ATD在参数量较少的情况下实现了最先进的性能。代码可在此处获取：\href{https://github.com/zhangpingrui/Adaptive-Text-Dreamer}{链接}。


> Vision-and-Language Navigation (VLN) requires the agent to navigate by following natural instructions under partial observability, making it difficult to align perception with language. Recent methods mitigate this by imagining future scenes, yet they rely on vision-based synthesis, leading to high computational cost and redundant details. To this end, we propose to adaptively imagine key environmental semantics via \textit{language} form, enabling a more reliable and efficient strategy. Specifically, we introduce a novel Adaptive Text Dreamer (ATD), a dual-branch self-guided imagination policy built upon a large language model (LLM). ATD is designed with a human-like left-right brain architecture, where the left brain focuses on logical integration, and the right brain is responsible for imaginative prediction of future scenes. To achieve this, we fine-tune only the Q-former within both brains to efficiently activate domain-specific knowledge in the LLM, enabling dynamic updates of logical reasoning and imagination during navigation. Furthermore, we introduce a cross-interaction mechanism to regularize the imagined outputs and inject them into a navigation expert module, allowing ATD to jointly exploit both the reasoning capacity of the LLM and the expertise of the navigation model. We conduct extensive experiments on the R2R benchmark, where ATD achieves state-of-the-art performance with fewer parameters. The code is \href{https://github.com/zhangpingrui/Adaptive-Text-Dreamer}{here}.

[Arxiv](https://arxiv.org/abs/2505.20897)