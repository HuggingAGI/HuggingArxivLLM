# 探秘真相的几何结构：研究大型语言模型中的真相方向一致性与泛化能力——跨越逻辑变换与问答任务的探索

发布时间：2025年05月31日

`LLM理论

论文摘要探讨了大型语言模型（LLMs）内部的真实性表示机制，特别是“真实方向”的存在性、识别方法及其泛化能力。研究属于对LLMs内部机制的理论分析，因此归类为LLM理论。` `问答系统`

> Probing the Geometry of Truth: Consistency and Generalization of Truth Directions in LLMs Across Logical Transformations and Question Answering Tasks

# 摘要

> 大型语言模型（LLMs）通过海量数据训练，蕴含丰富知识，但输出常有自信却错误的表述。先前研究指出，LLMs将真实性编码为独立的线性特征，即“真实方向”，能可靠分类真伪。本文探讨三个关键问题：(i) LLMs是否普遍具有一致真实方向；(ii) 是否需要复杂技术识别真实方向；(iii) 真实方向在不同情境下的泛化能力。研究发现并非所有LLMs都有稳定真实方向，且更强大的模型在逻辑否定等场景下表现更佳。此外，基于陈述性语句训练的真实性探测器可有效泛化至逻辑转换、问答任务、上下文学习及外部知识源。最后，我们展示了真实性探测器在选择性问答中的应用潜力，可提升用户对LLM输出的信任。这些成果深化了对真实方向的理解，揭示了LLMs信念的内部表示。代码已开源，详情请访问https://github.com/colored-dye/truthfulness_probe_generalization。

> Large language models (LLMs) are trained on extensive datasets that encapsulate substantial world knowledge. However, their outputs often include confidently stated inaccuracies. Earlier works suggest that LLMs encode truthfulness as a distinct linear feature, termed the "truth direction", which can classify truthfulness reliably. We address several open questions about the truth direction: (i) whether LLMs universally exhibit consistent truth directions; (ii) whether sophisticated probing techniques are necessary to identify truth directions; and (iii) how the truth direction generalizes across diverse contexts. Our findings reveal that not all LLMs exhibit consistent truth directions, with stronger representations observed in more capable models, particularly in the context of logical negation. Additionally, we demonstrate that truthfulness probes trained on declarative atomic statements can generalize effectively to logical transformations, question-answering tasks, in-context learning, and external knowledge sources. Finally, we explore the practical application of truthfulness probes in selective question-answering, illustrating their potential to improve user trust in LLM outputs. These results advance our understanding of truth directions and provide new insights into the internal representations of LLM beliefs. Our code is public at https://github.com/colored-dye/truthfulness_probe_generalization

[Arxiv](https://arxiv.org/abs/2506.00823)