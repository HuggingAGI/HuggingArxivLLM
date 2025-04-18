# 处理检索增强型 LLM 中的知识冲突：实现真实场景下的可靠回答生成

发布时间：2025年04月17日

`LLM应用` `信息检索系统` `响应生成`

> Accommodate Knowledge Conflicts in Retrieval-augmented LLMs: Towards Reliable Response Generation in the Wild

# 摘要

> 大型语言模型（LLMs）的快速发展显著提升了信息检索系统，特别是在响应生成（RG）领域。然而，LLMs常常因错误信息、偏见或知识过时而产生内部记忆与外部检索信息之间的冲突，这不仅削弱了响应的可靠性，还给决策带来了不确定性。本研究从信息论角度深入分析了LLMs应对知识冲突的方式，发现当冲突信息与补充信息差异显著时，LLMs能够自信地解决偏好问题；但当这种差异模糊时，LLMs的不确定性显著增加。基于这一发现，我们提出了Swin-VIB框架，通过整合变分信息瓶颈模型的流水线，实现对检索信息的自适应增强，并在响应生成中引导LLM的偏好选择。在单选、开放性问答（QA）和检索增强生成（RAG）等任务上的广泛实验验证了我们的理论，并证明了Swin-VIB的有效性。值得注意的是，与现有基线方法相比，我们的方法在单选任务上的准确率至少提升了7.54%。

> The proliferation of large language models (LLMs) has significantly advanced information retrieval systems, particularly in response generation (RG). Unfortunately, LLMs often face knowledge conflicts between internal memory and retrievaled external information, arising from misinformation, biases, or outdated knowledge. These conflicts undermine response reliability and introduce uncertainty in decision-making. In this work, we analyze how LLMs navigate knowledge conflicts from an information-theoretic perspective and reveal that when conflicting and supplementary information exhibit significant differences, LLMs confidently resolve their preferences. However, when the distinction is ambiguous, LLMs experience heightened uncertainty. Based on this insight, we propose Swin-VIB, a novel framework that integrates a pipeline of variational information bottleneck models into adaptive augmentation of retrieved information and guiding LLM preference in response generation. Extensive experiments on single-choice, open-ended question-answering (QA), and retrieval augmented generation (RAG) validate our theoretical findings and demonstrate the efficacy of Swin-VIB. Notably, our method improves single-choice task accuracy by at least 7.54\% over competitive baselines.

[Arxiv](https://arxiv.org/abs/2504.12982)