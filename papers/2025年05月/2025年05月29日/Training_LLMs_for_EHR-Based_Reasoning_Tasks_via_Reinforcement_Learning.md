# # 通过强化学习训练用于基于电子健康记录的推理任务的大型语言模型

发布时间：2025年05月29日

`LLM应用` `临床推理`

> Training LLMs for EHR-Based Reasoning Tasks via Reinforcement Learning

# 摘要

> 我们推出EHRMIND，这是一种通过可验证奖励的强化学习（RLVR）将大型语言模型（LLMs）应用于复杂临床推理任务的实际解决方案。虽然RLVR在数学和编程领域表现出色，但在医疗领域应用时面临独特挑战，因为解读电子健康记录（EHR）需要专业知识和推理能力。我们基于MEDCALC基准的研究发现了两个关键问题：（1）误用知识，即模型虽掌握相关医学知识却未能正确应用；（2）知识缺失，即模型缺乏关键领域知识。为解决这些问题，EHRMIND采用了两阶段策略：首先进行轻量级监督微调（SFT）预热，以填补知识空白，稳定后续训练，并促进结构化、可解释的输出；随后通过RLVR强化结果准确性，优化模型决策能力。我们在医学计算（MEDCALC）、患者-试验匹配（TREC CLINICAL TRIALS）和疾病诊断（EHRSHOT）等多种临床场景中验证了方法的有效性。EHRMIND显著提升了模型的准确性、可解释性和跨任务泛化能力。这些成果为在医疗场景中利用RLVR增强LLM能力提供了实用指导。


> We present EHRMIND, a practical recipe for adapting large language models (LLMs) to complex clinical reasoning tasks using reinforcement learning with verifiable rewards (RLVR). While RLVR has succeeded in mathematics and coding, its application to healthcare contexts presents unique challenges due to the specialized knowledge and reasoning required for electronic health record (EHR) interpretation. Our pilot study on the MEDCALC benchmark reveals two key failure modes: (1) misapplied knowledge, where models possess relevant medical knowledge but apply it incorrectly, and (2) missing knowledge, where models lack essential domain knowledge. To address these cases, EHRMIND applies a two-stage solution: a lightweight supervised fine-tuning (SFT) warm-up that injects missing domain knowledge, stabilizes subsequent training, and encourages structured, interpretable outputs; followed by RLVR, which reinforces outcome correctness and refines the model's decision-making. We demonstrate the effectiveness of our method across diverse clinical applications, including medical calculations (MEDCALC), patient-trial matching (TREC CLINICAL TRIALS), and disease diagnosis (EHRSHOT). EHRMIND delivers consistent gains in accuracy, interpretability, and cross-task generalization. These findings offer practical guidance for applying RLVR to enhance LLM capabilities in healthcare settings.

[Arxiv](https://arxiv.org/abs/2505.24105)