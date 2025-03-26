# 基于临床经验学习增强大型语言模型代理的交互诊断能力

发布时间：2025年02月24日

`LLM应用` `人工智能`

> Improving Interactive Diagnostic Ability of a Large Language Model Agent Through Clinical Experience Learning

# 摘要

> 大型语言模型（LLMs）在医疗诊断领域展现出巨大潜力，部分研究显示其在特定场景下甚至超越了人类医生的表现。然而，LLMs的诊断能力常被过高估计，因其在需要主动信息收集的互动诊断场景中表现大幅下降。本研究旨在探究这一性能下降的根本原因，并提出解决方案。我们发现，LLMs的主要缺陷体现在诊断初期阶段，特别是在信息收集效率和初步诊断形成方面，而非后续的鉴别诊断阶段。为应对这一局限，我们开发了一种增强型即插即用方法（PPME）LLM代理，该方法整合了超过350万份来自中、美医疗机构的电子病历。我们的方案通过监督学习与强化学习技术，集成了专门用于初步疾病诊断和现病史问询的模型。实验结果表明，相较于基准模型，PPME LLM实现了30%以上的性能提升。在互动诊断场景下，PPME LLM的最终诊断准确率已接近基于完整临床数据的诊断水平。这些发现为开发自主诊断系统提供了巨大潜力，尽管仍需进一步验证研究。

> Recent advances in large language models (LLMs) have shown promising results in medical diagnosis, with some studies indicating superior performance compared to human physicians in specific scenarios. However, the diagnostic capabilities of LLMs are often overestimated, as their performance significantly deteriorates in interactive diagnostic settings that require active information gathering. This study investigates the underlying mechanisms behind the performance degradation phenomenon and proposes a solution. We identified that the primary deficiency of LLMs lies in the initial diagnosis phase, particularly in information-gathering efficiency and initial diagnosis formation, rather than in the subsequent differential diagnosis phase. To address this limitation, we developed a plug-and-play method enhanced (PPME) LLM agent, leveraging over 3.5 million electronic medical records from Chinese and American healthcare facilities. Our approach integrates specialized models for initial disease diagnosis and inquiry into the history of the present illness, trained through supervised and reinforcement learning techniques. The experimental results indicate that the PPME LLM achieved over 30% improvement compared to baselines. The final diagnostic accuracy of the PPME LLM in interactive diagnostic scenarios approached levels comparable to those achieved using complete clinical data. These findings suggest a promising potential for developing autonomous diagnostic systems, although further validation studies are needed.

[Arxiv](https://arxiv.org/abs/2503.16463)