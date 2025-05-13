# 推理与导航：基于大型语言模型的高效动作规划

发布时间：2025年05月12日

`LLM应用` `机器人技术` `人工智能`

> Learning to Reason and Navigate: Parameter Efficient Action Planning with Large Language Models

# 摘要

> 远程具身指示表达（REVERIE）任务要求代理在没有预先探索的情况下，根据高级指令（如“给我一把勺子”）在复杂的室内环境中导航并定位远程目标物体。因此，制定高效的导航策略对于最终成功至关重要。本文提出了一种基于大型语言模型（LLM）的新型参数高效动作规划器（PEAP-LLM），用于在每个位置生成单步指令。该模型由两个模块组成，分别是LLM目标规划器（LGP）和LoRA动作规划器（LAP）。首先，LGP从REVERIE指令中提取目标导向的计划，包括目标物体和房间信息。然后，LAP以目标导向的计划、高级指令和当前视觉观察为输入，生成单步指令。PEAP-LLM使具身代理能够实时与LAP作为路径规划器进行交互。然而，简单直接地应用LLM难以实现良好的性能。此外，现有的基于硬提示的方法在复杂场景中容易出错，需要人工干预。为了解决这些问题并防止LLM生成幻觉和有偏见的信息，我们提出了一种新型的两阶段LLM微调方法，包括监督微调（SFT）和直接偏好优化（DPO）。SFT提高了生成指令的质量，而DPO利用环境反馈。实验结果表明，与之前最先进的方法相比，我们提出的模型在REVERIE任务中表现更优。

> The remote embodied referring expression (REVERIE) task requires an agent to navigate through complex indoor environments and localize a remote object specified by high-level instructions, such as "bring me a spoon", without pre-exploration. Hence, an efficient navigation plan is essential for the final success. This paper proposes a novel parameter-efficient action planner using large language models (PEAP-LLM) to generate a single-step instruction at each location. The proposed model consists of two modules, LLM goal planner (LGP) and LoRA action planner (LAP). Initially, LGP extracts the goal-oriented plan from REVERIE instructions, including the target object and room. Then, LAP generates a single-step instruction with the goal-oriented plan, high-level instruction, and current visual observation as input. PEAP-LLM enables the embodied agent to interact with LAP as the path planner on the fly. A simple direct application of LLMs hardly achieves good performance. Also, existing hard-prompt-based methods are error-prone in complicated scenarios and need human intervention. To address these issues and prevent the LLM from generating hallucinations and biased information, we propose a novel two-stage method for fine-tuning the LLM, consisting of supervised fine-tuning (STF) and direct preference optimization (DPO). SFT improves the quality of generated instructions, while DPO utilizes environmental feedback. Experimental results show the superiority of our proposed model on REVERIE compared to the previous state-of-the-art.

[Arxiv](https://arxiv.org/abs/2505.07500)