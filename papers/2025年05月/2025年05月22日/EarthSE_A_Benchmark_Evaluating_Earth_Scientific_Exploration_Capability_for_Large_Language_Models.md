# EarthSE：评估大型语言模型地球科学探索能力的基准测试

发布时间：2025年05月22日

`LLM应用

理由：这篇论文专注于将大型语言模型应用于地球科学领域，并提出了一项专门的基准测试来评估其科学探索能力。虽然它涉及模型的评估，但更侧重于应用层面，而非模型本身的理论或结构。因此，它被归类为LLM应用。` `地球科学` `问答系统`

> EarthSE: A Benchmark Evaluating Earth Scientific Exploration Capability for Large Language Models

# 摘要

> 大型语言模型（LLMs）的进步激发了科学应用领域的浓厚兴趣，特别是在地球科学领域，亟需专门的基准测试。现有的基准测试要么专注于一般科学领域而缺乏地球科学的特色，要么仅覆盖孤立的子领域，未能进行全面评估。此外，现有基准测试往往忽略了对LLMs在开放性科学研究探索能力的评估。本文提出了一项全面且专业的地球科学基准测试，旨在评估LLMs在地球科学领域内从基础到高级层面的科学探索能力。我们利用10万篇研究论文的语料库，构建了两个问答（QA）数据集：Earth-Iron提供广泛的问题覆盖以实现全面评估，而Earth-Silver则通过更高难度的问题评估专业深度。这些数据集涵盖了地球科学的五个领域、114个学科和11个任务类别，全面评估了科学探索所需的基础知识。特别值得注意的是，我们引入了Earth-Gold，这是一个包含新评估指标的数据集，由专门设计的多轮开放性对话组成，旨在评估LLMs在科学探索中的高级能力，包括方法论归纳、局限性分析和概念提案。通过广泛的实验，我们揭示了11个跨领域和任务的领先LLMs的局限性，凸显了它们在科学探索能力方面仍有显著的提升空间。该基准测试可在https://huggingface.co/ai-earth上获取。

> Advancements in Large Language Models (LLMs) drive interest in scientific applications, necessitating specialized benchmarks such as Earth science. Existing benchmarks either present a general science focus devoid of Earth science specificity or cover isolated subdomains, lacking holistic evaluation. Furthermore, current benchmarks typically neglect the assessment of LLMs' capabilities in open-ended scientific exploration. In this paper, we present a comprehensive and professional benchmark for the Earth sciences, designed to evaluate the capabilities of LLMs in scientific exploration within this domain, spanning from fundamental to advanced levels. Leveraging a corpus of 100,000 research papers, we first construct two Question Answering (QA) datasets: Earth-Iron, which offers extensive question coverage for broad assessment, and Earth-Silver, which features a higher level of difficulty to evaluate professional depth. These datasets encompass five Earth spheres, 114 disciplines, and 11 task categories, assessing foundational knowledge crucial for scientific exploration. Most notably, we introduce Earth-Gold with new metrics, a dataset comprising open-ended multi-turn dialogues specifically designed to evaluate the advanced capabilities of LLMs in scientific exploration, including methodology induction, limitation analysis, and concept proposal. Extensive experiments reveal limitations in 11 leading LLMs across different domains and tasks, highlighting considerable room for improvement in their scientific exploration capabilities. The benchmark is available on https://huggingface.co/ai-earth .

[Arxiv](https://arxiv.org/abs/2505.17139)