# 通过临床经验学习提升大型语言模型的交互诊断能力

发布时间：2025年02月24日

`LLM应用` `医疗诊断` `电子病历`

> Improving Interactive Diagnostic Ability of a Large Language Model Agent Through Clinical Experience Learning

# 摘要

> 大型语言模型（LLMs）在医疗诊断领域取得了令人鼓舞的进展，部分研究显示其在特定场景下甚至优于人类医生。然而，LLMs的诊断能力常被高估，因其在需要主动信息收集的互动诊断环境中表现显著下降。本研究旨在探讨这一性能下降的根本原因并提出解决方案。我们发现，LLMs的主要缺陷在于初始诊断阶段，特别是在信息收集效率和初步诊断形成方面，而非后续的鉴别诊断阶段。为应对这一局限，我们开发了一种即插即用方法增强（PPME）的LLM代理，整合了来自中、美医疗机构的逾350万份电子病历。我们的方法结合了专门用于初始疾病诊断和现病史问询的模型，通过监督学习和强化学习技术进行训练。实验结果表明，PPME LLM相较于基准模型提升了超过30%。在互动诊断场景下，PPME LLM的最终诊断准确率已接近基于完整临床数据的诊断水平。这些发现表明，开发自主诊断系统具有广阔前景，但尚需进一步验证研究。

> Recent advances in large language models (LLMs) have shown promising results in medical diagnosis, with some studies indicating superior performance compared to human physicians in specific scenarios. However, the diagnostic capabilities of LLMs are often overestimated, as their performance significantly deteriorates in interactive diagnostic settings that require active information gathering. This study investigates the underlying mechanisms behind the performance degradation phenomenon and proposes a solution. We identified that the primary deficiency of LLMs lies in the initial diagnosis phase, particularly in information-gathering efficiency and initial diagnosis formation, rather than in the subsequent differential diagnosis phase. To address this limitation, we developed a plug-and-play method enhanced (PPME) LLM agent, leveraging over 3.5 million electronic medical records from Chinese and American healthcare facilities. Our approach integrates specialized models for initial disease diagnosis and inquiry into the history of the present illness, trained through supervised and reinforcement learning techniques. The experimental results indicate that the PPME LLM achieved over 30% improvement compared to baselines. The final diagnostic accuracy of the PPME LLM in interactive diagnostic scenarios approached levels comparable to those achieved using complete clinical data. These findings suggest a promising potential for developing autonomous diagnostic systems, although further validation studies are needed.

[Arxiv](https://arxiv.org/abs/2503.16463)