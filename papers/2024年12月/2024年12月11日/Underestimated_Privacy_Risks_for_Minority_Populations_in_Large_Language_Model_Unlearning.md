# 大型语言模型遗忘中少数群体面临的隐私风险被低估

发布时间：2024年12月11日

`LLM应用` `隐私保护` `大型语言模型`

> Underestimated Privacy Risks for Minority Populations in Large Language Model Unlearning

# 摘要

> 大型语言模型在广泛的数据集上进行训练，这些数据集常含敏感的人类生成信息，这引发了对隐私泄露的严重担忧。尽管经过认证的遗忘学习法能提供有力的隐私保障，可它们依赖于不适用于大型语言模型的限制性模型假设。于是，各种遗忘学习的启发式方法被提出，相关隐私风险仅靠经验评估。标准评估流程通常随机从训练集中选取要删除的数据，运用遗忘学习技术，并用成员推理攻击将遗忘学习后的模型与未用待遗忘数据重新训练的模型作比较。然而，鉴于每个数据点都有被遗忘的权利，从隐私角度看，遗忘学习应考虑最坏情况。先前的工作表明，数据异常值可能有更强的记忆效应。直观来说，它们更难被遗忘，所以在当前评估中，遗忘它们的隐私风险被低估了。在本文中，我们借助少数数据来指出先前广泛采用的评估中的这一关键缺陷。我们通过精心设计的实验来证实这一观点，包括受隐私审计文献启发的与少数群体相关的遗忘学习“金丝雀”。以个人可识别信息作为少数群体的代表性标识符，我们证明在多数情况下，在六种遗忘学习方法、三种成员推理攻击、三个基准数据集以及两个不同规模的大型语言模型中，少数群体遭遇的隐私泄露至少高出 20%。鉴于每个人的被遗忘权都应得到保障，我们倡导对大型语言模型的遗忘学习方法进行更严格的评估。我们的少数群体感知评估框架是朝着确保对大型语言模型遗忘学习效果进行更公平评估迈出的第一步。

> Large Language Models are trained on extensive datasets that often contain sensitive, human-generated information, raising significant concerns about privacy breaches. While certified unlearning approaches offer strong privacy guarantees, they rely on restrictive model assumptions that are not applicable to LLMs. As a result, various unlearning heuristics have been proposed, with the associated privacy risks assessed only empirically. The standard evaluation pipelines typically randomly select data for removal from the training set, apply unlearning techniques, and use membership inference attacks to compare the unlearned models against models retrained without the to-be-unlearned data. However, since every data point is subject to the right to be forgotten, unlearning should be considered in the worst-case scenario from the privacy perspective. Prior work shows that data outliers may exhibit higher memorization effects. Intuitively, they are harder to be unlearn and thus the privacy risk of unlearning them is underestimated in the current evaluation. In this paper, we leverage minority data to identify such a critical flaw in previously widely adopted evaluations. We substantiate this claim through carefully designed experiments, including unlearning canaries related to minority groups, inspired by privacy auditing literature. Using personally identifiable information as a representative minority identifier, we demonstrate that minority groups experience at least 20% more privacy leakage in most cases across six unlearning approaches, three MIAs, three benchmark datasets, and two LLMs of different scales. Given that the right to be forgotten should be upheld for every individual, we advocate for a more rigorous evaluation of LLM unlearning methods. Our minority-aware evaluation framework represents an initial step toward ensuring more equitable assessments of LLM unlearning efficacy.

[Arxiv](https://arxiv.org/abs/2412.08559)