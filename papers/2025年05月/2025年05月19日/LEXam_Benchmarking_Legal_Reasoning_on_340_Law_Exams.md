# LEXam：基于340份法律考试的法律推理基准测试

发布时间：2025年05月19日

`LLM应用

摘要中讨论了大型语言模型在法律推理中的应用，特别是构建了一个基准测试LEXam来评估模型在法律考试中的表现。研究集中在模型处理结构化、多步骤法律推理的能力上，属于LLM的应用层面。`

> LEXam: Benchmarking Legal Reasoning on 340 Law Exams

# 摘要

> 长篇法律推理仍是大型语言模型（LLMs）面临的重大挑战，尽管测试时的扩展技术虽有进步。我们推出LEXam，一个基于116门法律课程（涵盖多个学科和学位水平）的340份考试构建的新颖基准测试。该数据集包含4,886道英文和德文法律考试题目，其中包括2,841道长篇开放性问题和2,045道选择题。开放性问题不仅有参考答案，还附有明确的指导，详细说明了预期的法律推理方法，如问题识别、规则记忆或规则应用。我们在开放性和选择题上的评估结果表明，当前LLMs面临重大挑战；尤其是，在处理需要结构化、多步骤法律推理的开放性问题时显得尤为吃力。此外，我们的研究结果凸显了LEXam数据集在有效区分不同能力模型方面的价值。通过采用"LLM作为法官"的范式并结合严格的专家人工验证，我们展示了如何能够一致且准确地评估模型生成的推理步骤。我们的评估设置提供了一种可扩展的方法，超越简单的准确性指标，用于评估法律推理的质量。项目页面：https://lexam-benchmark.github.io/

> Long-form legal reasoning remains a key challenge for large language models (LLMs) in spite of recent advances in test-time scaling. We introduce LEXam, a novel benchmark derived from 340 law exams spanning 116 law school courses across a range of subjects and degree levels. The dataset comprises 4,886 law exam questions in English and German, including 2,841 long-form, open-ended questions and 2,045 multiple-choice questions. Besides reference answers, the open questions are also accompanied by explicit guidance outlining the expected legal reasoning approach such as issue spotting, rule recall, or rule application. Our evaluation on both open-ended and multiple-choice questions present significant challenges for current LLMs; in particular, they notably struggle with open questions that require structured, multi-step legal reasoning. Moreover, our results underscore the effectiveness of the dataset in differentiating between models with varying capabilities. Adopting an LLM-as-a-Judge paradigm with rigorous human expert validation, we demonstrate how model-generated reasoning steps can be evaluated consistently and accurately. Our evaluation setup provides a scalable method to assess legal reasoning quality beyond simple accuracy metrics. Project page: https://lexam-benchmark.github.io/

[Arxiv](https://arxiv.org/abs/2505.12864)