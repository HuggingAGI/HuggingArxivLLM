# # 基于假设的临床决策强化学习语言智能体

发布时间：2025年06月16日

`LLM应用

理由：这篇论文探讨了大型语言模型在临床决策中的应用，提出了一种基于假设驱动的智能体LA-CDM，并通过混合训练范式提升诊断性能和效率。研究重点在于模型的实际应用和改进，属于LLM应用类别。` `临床决策支持`

> Language Agents for Hypothesis-driven Clinical Decision Making with Reinforcement Learning

# 摘要

> 临床决策是一个动态、交互和循环的过程，医生需反复决定采取哪些临床行动，并结合新发现的信息进行诊断和治疗。大型语言模型（LLMs）在支持这一过程中具有潜力，但现有应用主要存在以下两个问题：要么假设所有患者信息立即可用，而忽略了交互式和迭代式的调查过程；要么受限于预训练模型的“开箱即用”能力，未进行特定任务训练。为解决这些问题，我们提出了一种基于假设驱动的不确定性感知语言智能体LA-CDM，用于诊断过程建模。该模型通过反复请求和解释相关检查，逐步收敛到最终诊断。我们采用监督学习与强化学习相结合的混合训练范式，针对临床决策中的三个关键方面对LA-CDM进行训练：准确的假设生成、假设不确定性估计以及高效的决策制定。我们在真实世界数据集MIMIC-CDM上评估了我们的方法，该数据集涵盖了四种腹部疾病及其各种临床检查。实验结果表明，通过显式训练临床决策过程，可以有效提升诊断性能和效率。


> Clinical decision-making is a dynamic, interactive, and cyclic process where doctors have to repeatedly decide on which clinical action to perform and consider newly uncovered information for diagnosis and treatment. Large Language Models (LLMs) have the potential to support clinicians in this process, however, most applications of LLMs in clinical decision support suffer from one of two limitations: Either they assume the unrealistic scenario of immediate availability of all patient information and do not model the interactive and iterative investigation process, or they restrict themselves to the limited "out-of-the-box" capabilities of large pre-trained models without performing task-specific training. In contrast to this, we propose to model clinical decision-making for diagnosis with a hypothesis-driven uncertainty-aware language agent, LA-CDM, that converges towards a diagnosis via repeatedly requesting and interpreting relevant tests. Using a hybrid training paradigm combining supervised and reinforcement learning, we train LA-CDM with three objectives targeting critical aspects of clinical decision-making: accurate hypothesis generation, hypothesis uncertainty estimation, and efficient decision-making. We evaluate our methodology on MIMIC-CDM, a real-world dataset covering four abdominal diseases containing various clinical tests and show the benefit of explicitly training clinical decision-making for increasing diagnostic performance and efficiency.

[Arxiv](https://arxiv.org/abs/2506.13474)