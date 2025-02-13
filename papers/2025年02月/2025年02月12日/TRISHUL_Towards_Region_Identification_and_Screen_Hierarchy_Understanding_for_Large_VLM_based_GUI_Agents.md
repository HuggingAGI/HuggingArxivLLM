# 三叉戟：迈向基于大视觉语言模型的GUI代理的区域识别与屏幕层级理解

发布时间：2025年02月12日

`Agent

摘要中讨论了基于大型视觉语言模型（LVLMs）的图形用户界面（GUI）代理的发展，提出了TRISHUL框架，旨在提升GUI理解。因此，这篇论文属于Agent类别。` `人工智能` `用户界面`

> TRISHUL: Towards Region Identification and Screen Hierarchy Understanding for Large VLM based GUI Agents

# 摘要

> 大型视觉语言模型（LVLMs）的最新进展推动了基于LVLM的图形用户界面（GUI）代理在多种范式下的发展。然而，训练型方法如CogAgent和SeeClick在跨数据集和跨平台的泛化能力上面临挑战，因其依赖特定数据集的训练。通用型LVLM如GPT-4V采用标记集（SoM）进行动作定位，但获取SoM标签需要HTML源代码等元数据，这些在各平台间并不一致。此外，现有方法往往专注于单一GUI任务，难以实现全面的GUI理解。为解决这些问题，我们提出了TRISHUL——一个无需训练的代理框架，旨在提升通用型LVLM对GUI的全面理解。与以往研究侧重于动作定位或GUI引用不同，TRISHUL将两者无缝融合。其核心是层次化屏幕解析（HSP）和空间增强元素描述（SEED）模块，协同工作以提供多层次、空间和语义丰富的GUI元素表示。实验结果显示，TRISHUL在ScreenSpot、VisualWebBench、AITW和Mind2Web数据集上的动作定位性能卓越。此外，在GUI引用任务中，TRISHUL在ScreenPR基准上超越了ToL代理，树立了稳健且适应性强的GUI理解新标准。

> Recent advancements in Large Vision Language Models (LVLMs) have enabled the development of LVLM-based Graphical User Interface (GUI) agents under various paradigms. Training-based approaches, such as CogAgent and SeeClick, struggle with cross-dataset and cross-platform generalization due to their reliance on dataset-specific training. Generalist LVLMs, such as GPT-4V, employ Set-of-Marks (SoM) for action grounding, but obtaining SoM labels requires metadata like HTML source, which is not consistently available across platforms. Moreover, existing methods often specialize in singular GUI tasks rather than achieving comprehensive GUI understanding. To address these limitations, we introduce TRISHUL, a novel, training-free agentic framework that enhances generalist LVLMs for holistic GUI comprehension. Unlike prior works that focus on either action grounding (mapping instructions to GUI elements) or GUI referring (describing GUI elements given a location), TRISHUL seamlessly integrates both. At its core, TRISHUL employs Hierarchical Screen Parsing (HSP) and the Spatially Enhanced Element Description (SEED) module, which work synergistically to provide multi-granular, spatially, and semantically enriched representations of GUI elements. Our results demonstrate TRISHUL's superior performance in action grounding across the ScreenSpot, VisualWebBench, AITW, and Mind2Web datasets. Additionally, for GUI referring, TRISHUL surpasses the ToL agent on the ScreenPR benchmark, setting a new standard for robust and adaptable GUI comprehension.

[Arxiv](https://arxiv.org/abs/2502.08226)