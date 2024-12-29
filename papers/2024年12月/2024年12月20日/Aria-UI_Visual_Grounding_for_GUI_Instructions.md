# Aria-UI：图形用户界面指令的视觉基础

发布时间：2024年12月20日

`Agent` `数字代理` `图形用户界面`

> Aria-UI: Visual Grounding for GUI Instructions

# 摘要

> 数字代理能够直接操控图形用户界面（GUIs），实现不同平台任务的自动化，其重要性与日俱增。对这些代理而言，因依赖 HTML 或 AXTree 输入，从语言指令到目标元素的落地仍是重大挑战。本文中，我们推出了 Aria-UI，这是专为 GUI 落地而设计的大型多模态模型。Aria-UI 采用纯视觉方式，摆脱对辅助输入的依赖。为适应异构规划指令，我们提出了可扩展的数据管道，用于合成多样且高质量的落地指令样本。为应对任务执行中的动态情境，Aria-UI 融入了文本及文本-图像交错的动作历史，实现了强大的上下文感知推理以完成落地。Aria-UI 在离线和在线代理基准测试中均创下新的领先成果，胜过仅依赖视觉和依赖 AXTree 的基线。我们在 https://ariaui.github.io 发布了所有训练数据和模型检查点，以推动进一步的研究。

> Digital agents for automating tasks across different platforms by directly manipulating the GUIs are increasingly important. For these agents, grounding from language instructions to target elements remains a significant challenge due to reliance on HTML or AXTree inputs. In this paper, we introduce Aria-UI, a large multimodal model specifically designed for GUI grounding. Aria-UI adopts a pure-vision approach, eschewing reliance on auxiliary inputs. To adapt to heterogeneous planning instructions, we propose a scalable data pipeline that synthesizes diverse and high-quality instruction samples for grounding. To handle dynamic contexts in task performing, Aria-UI incorporates textual and text-image interleaved action histories, enabling robust context-aware reasoning for grounding. Aria-UI sets new state-of-the-art results across offline and online agent benchmarks, outperforming both vision-only and AXTree-reliant baselines. We release all training data and model checkpoints to foster further research at https://ariaui.github.io.

[Arxiv](https://arxiv.org/abs/2412.16256)