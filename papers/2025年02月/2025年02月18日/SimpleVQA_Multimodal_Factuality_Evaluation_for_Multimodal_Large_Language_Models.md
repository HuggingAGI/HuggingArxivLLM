# SimpleVQA：针对多模态大型语言模型的事实性评估方法

发布时间：2025年02月18日

`LLM应用` `问答系统` `视觉问答`

> SimpleVQA: Multimodal Factuality Evaluation for Multimodal Large Language Models

# 摘要

> 多模态大型语言模型（MLLMs）在各行业的广泛应用凸显了其输出可靠性和准确性的关键性，尤其是生成基于事实信息（如常识和领域特定知识）内容的能力。本研究介绍了SimpleVQA，首个全面评估MLLMs在回答自然语言简短问题时事实准确性能力的多模态基准测试。SimpleVQA具备六个关键特征：涵盖多种任务和场景，确保高质量且具挑战性的查询，提供静态且恒久的参考答案，并采用简便的评估方式。我们的方法将视觉问答项目分类为围绕客观事件或常识的9种不同任务，并将其归入9个主题中。通过实施严格的质量控制流程，我们确保答案的高质量、简洁性和清晰度，借助以LLM为评分者的评分系统，实现低偏差的评估。利用SimpleVQA，我们对18个领先的MLLMs和8个纯文本LLMs进行了全面评估，通过识别和分析错误案例，深入探究它们的图像理解和文本生成能力。

> The increasing application of multi-modal large language models (MLLMs) across various sectors have spotlighted the essence of their output reliability and accuracy, particularly their ability to produce content grounded in factual information (e.g. common and domain-specific knowledge). In this work, we introduce SimpleVQA, the first comprehensive multi-modal benchmark to evaluate the factuality ability of MLLMs to answer natural language short questions. SimpleVQA is characterized by six key features: it covers multiple tasks and multiple scenarios, ensures high quality and challenging queries, maintains static and timeless reference answers, and is straightforward to evaluate. Our approach involves categorizing visual question-answering items into 9 different tasks around objective events or common knowledge and situating these within 9 topics. Rigorous quality control processes are implemented to guarantee high-quality, concise, and clear answers, facilitating evaluation with minimal variance via an LLM-as-a-judge scoring system. Using SimpleVQA, we perform a comprehensive assessment of leading 18 MLLMs and 8 text-only LLMs, delving into their image comprehension and text generation abilities by identifying and analyzing error cases.

[Arxiv](https://arxiv.org/abs/2502.13059)