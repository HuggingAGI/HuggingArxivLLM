# PICLe：用于低资源命名实体检测中上下文学习的伪注释

发布时间：2024年12月16日

`LLM应用` `生物医学` `命名实体检测`

> PICLe: Pseudo-Annotations for In-Context Learning in Low-Resource Named Entity Detection

# 摘要

> ICL 能让大型语言模型（LLMs）凭借少量示例完成任务，在难以获取有标签示例时有助于任务适应。不过，ICL 对示例的选取颇为敏感，哪些示例属性能促成上下文泛化仍不明确。在本研究中，我们针对低资源命名实体检测（NED）的上下文示例展开了扰动研究。令人惊讶的是，带有部分正确标注实体提及的上下文示例在任务迁移方面与完全正确的示例效果相当。基于此发现，我们提出了伪标注上下文学习（PICLe），这是一个采用有噪声、伪标注示例的上下文学习框架。PICLe 借助 LLMs 在零样本的首次遍历中标注众多示例。接着，我们对这些合成示例进行聚类，从每个聚类中抽取特定的上下文示例集，并使用每个集独立预测实体提及。最后，通过自我验证来选定最终的实体提及集。我们在五个生物医学 NED 数据集上对 PICLe 进行评估，结果表明，在零人工标注的情况下，在有限的黄金示例可用作上下文示例的低资源场景中，PICLe 表现优于 ICL。

> In-context learning (ICL) enables Large Language Models (LLMs) to perform tasks using few demonstrations, facilitating task adaptation when labeled examples are hard to obtain. However, ICL is sensitive to the choice of demonstrations, and it remains unclear which demonstration attributes enable in-context generalization. In this work, we conduct a perturbation study of in-context demonstrations for low-resource Named Entity Detection (NED). Our surprising finding is that in-context demonstrations with partially correct annotated entity mentions can be as effective for task transfer as fully correct demonstrations. Based off our findings, we propose Pseudo-annotated In-Context Learning (PICLe), a framework for in-context learning with noisy, pseudo-annotated demonstrations. PICLe leverages LLMs to annotate many demonstrations in a zero-shot first pass. We then cluster these synthetic demonstrations, sample specific sets of in-context demonstrations from each cluster, and predict entity mentions using each set independently. Finally, we use self-verification to select the final set of entity mentions. We evaluate PICLe on five biomedical NED datasets and show that, with zero human annotation, PICLe outperforms ICL in low-resource settings where limited gold examples can be used as in-context demonstrations.

[Arxiv](https://arxiv.org/abs/2412.11923)