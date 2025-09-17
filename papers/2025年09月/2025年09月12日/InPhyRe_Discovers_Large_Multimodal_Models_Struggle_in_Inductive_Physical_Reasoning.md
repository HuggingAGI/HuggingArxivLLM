# InPhyRe 发现：大型多模态模型在归纳物理推理中表现不佳

发布时间：2025年09月12日

`LLM应用` `基础理论`

> InPhyRe Discovers: Large Multimodal Models Struggle in Inductive Physical Reasoning

# 摘要

> 大型多模态模型（LMMs）会将训练中习得的通用物理定律（如动量守恒）编码为参数化知识。凭借这一点，LMMs能够回答物理推理问题，比如根据视觉输入预测潜在碰撞事件的结果。但问题在于，参数化知识仅涵盖训练中见过的物理定律，一旦推理场景违背这些定律，LMMs就难以完成推理。相比之下，人类则能通过少数视觉示例调整物理推理方式，从而适应从未接触过的物理环境。我们将这种能力称为“归纳物理推理”——若LMMs想在安全关键型应用中替代人类，这一能力必不可少。尽管归纳物理推理至关重要，但现有视觉基准仅评估LMMs的参数化知识，却忽略了对这一能力的测评。为此，我们提出了首个用于测评LMMs归纳物理推理能力的视觉问答基准InPhyRe。InPhyRe通过算法生成合成碰撞视频，以此评估LMMs对碰撞事件结果的预测能力。通过测试13个LMMs，InPhyRe揭示了三个关键发现：（1）LMMs难以将自身有限的通用物理定律参数化知识应用于推理；（2）当演示样本违背通用物理定律时，LMMs的归纳物理推理能力会显著下降；（3）LMMs的归纳物理推理存在语言偏见，且严重忽视视觉输入，这让其在视觉输入处理上的可信度大打折扣。

> Large multimodal models (LMMs) encode universal physical laws observed during training, such as momentum conservation, as parametric knowledge. It allows LMMs to answer physical reasoning queries, such as the outcome of a potential collision event from visual input. However, since parametric knowledge includes only the physical laws seen during training, it is insufficient for reasoning when the inference scenario violates these physical laws. In contrast, humans possess the skill to adapt their physical reasoning to unseen physical environments from a few visual examples. This ability, which we refer to as inductive physical reasoning, is indispensable for LMMs if they are to replace human agents in safety-critical applications. Despite its importance, existing visual benchmarks evaluate only the parametric knowledge in LMMs, and not inductive physical reasoning. To this end, we propose InPhyRe, the first visual question answering benchmark to measure inductive physical reasoning in LMMs. InPhyRe evaluates LMMs on their ability to predict the outcome of collision events in algorithmically generated synthetic collision videos. By inspecting 13 LMMs, InPhyRe informs us that (1) LMMs struggle to apply their limited parametric knowledge about universal physical laws to reasoning, (2) inductive physical reasoning in LMMs is weak when demonstration samples violate universal physical laws, and (3) inductive physical reasoning in LMMs suffers from language bias and largely ignores the visual inputs, questioning the trustworthiness of LMMs regarding visual inputs.

[Arxiv](https://arxiv.org/abs/2509.12263)