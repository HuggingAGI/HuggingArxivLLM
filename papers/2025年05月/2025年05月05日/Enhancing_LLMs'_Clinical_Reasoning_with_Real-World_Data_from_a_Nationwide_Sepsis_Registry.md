# 基于全国性脓毒症登记数据，增强大型语言模型的临床推理能力

发布时间：2025年05月05日

`LLM应用` `临床推理`

> Enhancing LLMs' Clinical Reasoning with Real-World Data from a Nationwide Sepsis Registry

# 摘要

> 尽管大型语言模型（LLMs）在通用领域展现出了卓越的推理能力，但其在真实临床实践中的应用效果仍有待提升。究其原因，主要是在训练过程中，出于隐私保护的考虑，真实临床数据往往被排除在外，导致模型缺乏充分的临床知识储备。针对这一挑战，我们提出了一种通过整合真实世界临床数据来提升LLMs临床推理能力的方法。我们从全国性脓毒症注册库中提取了大量需要复杂推理的问题，并通过强化学习在这些问题上对Phi-4进行了针对性优化，最终打造出了C-Reason。在领域内测试中，C-Reason不仅在定量评估上表现出色，还获得了临床专家的高度认可。更令人欣喜的是，其强大的推理能力成功跨越了不同任务和患者群体的脓毒症数据集、抗生素使用开放咨询任务以及其他疾病领域。展望未来，研究者应致力于利用大规模、多疾病临床数据集对LLMs进行训练，以开发出更为强大且通用的临床推理模型，为医疗领域带来更深远的变革。

> Although large language models (LLMs) have demonstrated impressive reasoning capabilities across general domains, their effectiveness in real-world clinical practice remains limited. This is likely due to their insufficient exposure to real-world clinical data during training, as such data is typically not included due to privacy concerns. To address this, we propose enhancing the clinical reasoning capabilities of LLMs by leveraging real-world clinical data. We constructed reasoning-intensive questions from a nationwide sepsis registry and fine-tuned Phi-4 on these questions using reinforcement learning, resulting in C-Reason. C-Reason exhibited strong clinical reasoning capabilities on the in-domain test set, as evidenced by both quantitative metrics and expert evaluations. Furthermore, its enhanced reasoning capabilities generalized to a sepsis dataset involving different tasks and patient cohorts, an open-ended consultations on antibiotics use task, and other diseases. Future research should focus on training LLMs with large-scale, multi-disease clinical datasets to develop more powerful, general-purpose clinical reasoning models.

[Arxiv](https://arxiv.org/abs/2505.02722)