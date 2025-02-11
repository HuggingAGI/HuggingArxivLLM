# 模型蒸馏中的教师追踪：谁传授了你的知识？

发布时间：2025年02月10日

`LLM理论` `模型安全`

> Who Taught You That? Tracing Teachers in Model Distillation

# 摘要

> 模型蒸馏 -- 利用大型教师模型的输出来教授小型学生模型 -- 是为特定任务打造高效模型的实用方法。我们提出一个问题：能否通过学生模型的输出识别出其背后的教师模型？这种由教师LLM留下的"足迹"将是非常有趣的产物。除此之外，可靠的教师模型推断可能具有实际意义，因为各方可能试图将大型专有LLM的特定能力蒸馏到已部署的小型LM中，这可能违反服务条款。我们考虑了实用的任务蒸馏目标，包括总结、问答和遵循指令。我们假设候选教师模型的有限集合，并将其视为黑盒。我们设计了基于词汇特征的判别模型。我们发现，仅使用【数学公式】来识别教师模型是不可靠的，但学生模型偏好的词性（PoS）模板与其教师模型相似。

> Model distillation -- using outputs from a large teacher model to teach a small student model -- is a practical means of creating efficient models for a particular task. We ask: Can we identify a students' teacher based on its outputs? Such "footprints" left by teacher LLMs would be interesting artifacts. Beyond this, reliable teacher inference may have practical implications as actors seek to distill specific capabilities of massive proprietary LLMs into deployed smaller LMs, potentially violating terms of service. We consider practical task distillation targets including summarization, question answering, and instruction-following. We assume a finite set of candidate teacher models, which we treat as blackboxes. We design discriminative models that operate over lexical features. We find that $n$-gram similarity alone is unreliable for identifying teachers, but part-of-speech (PoS) templates preferred by student models mimic those of their teachers.

[Arxiv](https://arxiv.org/abs/2502.06659)