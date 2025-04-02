# MedReason：利用知识图谱从大型语言模型中提取事实性医疗推理步骤

发布时间：2025年04月01日

`LLM应用

理由：这篇论文专注于将大型语言模型应用于医学推理任务，通过构建一个高质量的数据集来提升模型在医学问题解决中的性能。它展示了LLMs在医学领域的具体应用和优化，属于LLM应用的范畴。` `知识图谱`

> MedReason: Eliciting Factual Medical Reasoning Steps in LLMs via Knowledge Graphs

# 摘要

> 医学任务，如诊断和治疗计划，需要精准而复杂的推理，尤其是在生命攸关的领域。与数学推理不同，医学推理需要细致、可验证的思维过程，以确保可靠性和准确性。然而，目前缺乏提供透明、逐步推理过程的数据集，这些数据集可以用于验证和增强AI模型的医学推理能力。为了解决这一问题，我们引入了MedReason，这是一个大规模的高质量医学推理数据集，旨在使大型语言模型（LLMs）能够实现忠实且可解释的医学问题解决。

我们利用一个结构化的医学知识图谱（KG），将临床问答对转化为逻辑推理链，或“思考路径”，这些路径通过相关KG实体从问题元素连接到答案。每个路径都经过验证，确保与临床逻辑和循证医学一致。我们的管道从7个医学数据集中生成各种医学问题的详细推理过程，最终形成一个包含32,682个问答对的数据集，每个对都有详细、逐步的解释。

实验表明，使用我们的数据集进行微调可以显著提高医学问题解决能力，DeepSeek-Ditill-8B的性能提升了高达7.7%。我们的最佳模型MedReason-8B在临床基准MedBullets上，比最先进的医学推理模型Huatuo-o1-8B高出4.2%。我们还邀请了来自不同专业的医疗专业人士评估我们的数据集质量，确保MedReason提供准确且连贯的医学推理。我们的数据、模型和代码将公开发布。

> Medical tasks such as diagnosis and treatment planning require precise and complex reasoning, particularly in life-critical domains. Unlike mathematical reasoning, medical reasoning demands meticulous, verifiable thought processes to ensure reliability and accuracy. However, there is a notable lack of datasets that provide transparent, step-by-step reasoning to validate and enhance the medical reasoning ability of AI models. To bridge this gap, we introduce MedReason, a large-scale high-quality medical reasoning dataset designed to enable faithful and explainable medical problem-solving in large language models (LLMs). We utilize a structured medical knowledge graph (KG) to convert clinical QA pairs into logical chains of reasoning, or ``thinking paths'', which trace connections from question elements to answers via relevant KG entities. Each path is validated for consistency with clinical logic and evidence-based medicine. Our pipeline generates detailed reasoning for various medical questions from 7 medical datasets, resulting in a dataset of 32,682 question-answer pairs, each with detailed, step-by-step explanations. Experiments demonstrate that fine-tuning with our dataset consistently boosts medical problem-solving capabilities, achieving significant gains of up to 7.7% for DeepSeek-Ditill-8B. Our top-performing model, MedReason-8B, outperforms the Huatuo-o1-8B, a state-of-the-art medical reasoning model, by up to 4.2% on the clinical benchmark MedBullets. We also engage medical professionals from diverse specialties to assess our dataset's quality, ensuring MedReason offers accurate and coherent medical reasoning. Our data, models, and code will be publicly available.

[Arxiv](https://arxiv.org/abs/2504.00993)