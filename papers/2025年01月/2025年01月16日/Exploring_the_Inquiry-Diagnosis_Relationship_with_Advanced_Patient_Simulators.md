# 利用高级病人模拟器探索问诊与诊断的关系

发布时间：2025年01月16日

`LLM应用

理由：这篇论文主要探讨了如何利用大型语言模型（LLM）来改进在线医疗咨询中的“询问”阶段，并通过训练患者模拟器来生成患者反应，进而研究“询问”与“诊断”之间的关系。论文的核心是利用LLM来优化医疗咨询过程中的信息获取和诊断决策，这属于LLM在实际应用场景中的具体应用，因此应归类为LLM应用。` `在线咨询`

> Exploring the Inquiry-Diagnosis Relationship with Advanced Patient Simulators

# 摘要

> # 摘要
在线医疗咨询（OMC）限制了医生只能通过询问获取患者信息，使得原本复杂的诊断决策过程更加困难。最近，大型语言模型的快速发展为OMC带来了巨大变革潜力。然而，大多数研究主要关注在信息相对充足的情况下提高诊断准确性，而对咨询过程中的“询问”阶段关注较少，导致“询问”与“诊断”之间的关系未能充分探索。本文首先从真实医患对话中提取患者互动策略，并利用这些策略训练一个高度逼真的患者模拟器。通过将医疗记录输入模拟器以生成患者反应，我们进行了大量实验，深入探讨了咨询过程中“询问”与“诊断”的关系。实验结果表明，询问和诊断遵循李比希定律：无论诊断能力如何，询问质量差都会限制诊断效果，反之亦然。此外，实验还揭示了不同模型在询问表现上的显著差异。为探究这一现象，我们将询问过程分为四类：（1）主诉询问；（2）已知症状的详细说明；（3）伴随症状的询问；（4）家族或病史的收集。通过分析不同模型在这四类中的询问分布，我们揭示了其表现差异的原因。我们计划在https://github.com/LIO-H-ZEN/PatientSimulator上开源患者模拟器的权重和相关代码。

> Online medical consultation (OMC) restricts doctors to gathering patient information solely through inquiries, making the already complex sequential decision-making process of diagnosis even more challenging. Recently, the rapid advancement of large language models has demonstrated a significant potential to transform OMC. However, most studies have primarily focused on improving diagnostic accuracy under conditions of relatively sufficient information, while paying limited attention to the "inquiry" phase of the consultation process. This lack of focus has left the relationship between "inquiry" and "diagnosis" insufficiently explored. In this paper, we first extract real patient interaction strategies from authentic doctor-patient conversations and use these strategies to guide the training of a patient simulator that closely mirrors real-world behavior. By inputting medical records into our patient simulator to simulate patient responses, we conduct extensive experiments to explore the relationship between "inquiry" and "diagnosis" in the consultation process. Experimental results demonstrate that inquiry and diagnosis adhere to the Liebig's law: poor inquiry quality limits the effectiveness of diagnosis, regardless of diagnostic capability, and vice versa. Furthermore, the experiments reveal significant differences in the inquiry performance of various models. To investigate this phenomenon, we categorize the inquiry process into four types: (1) chief complaint inquiry; (2) specification of known symptoms; (3) inquiry about accompanying symptoms; and (4) gathering family or medical history. We analyze the distribution of inquiries across the four types for different models to explore the reasons behind their significant performance differences. We plan to open-source the weights and related code of our patient simulator at https://github.com/LIO-H-ZEN/PatientSimulator.

[Arxiv](https://arxiv.org/abs/2501.09484)