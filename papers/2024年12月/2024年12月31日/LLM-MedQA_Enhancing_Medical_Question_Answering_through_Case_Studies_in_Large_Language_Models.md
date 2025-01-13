# LLM-MedQA：利用大型语言模型案例研究提升医学问答能力

发布时间：2024年12月31日

`Agent

理由：这篇论文提出了一种将相似案例生成融入多代理医疗问答系统的方法，重点在于利用多代理架构来提升医疗问答的性能。虽然涉及大型语言模型（LLMs）的应用，但其核心在于多代理系统的设计和实现，因此更适合归类为Agent。` `问答系统`

> LLM-MedQA: Enhancing Medical Question Answering through Case Studies in Large Language Models

# 摘要

> # 摘要
在医疗领域，准确高效的问答系统是提供高质量患者护理的关键。尽管大型语言模型（LLMs）在多个领域取得了显著进展，但在医疗问答中，尤其是在理解专业术语和进行复杂推理方面，仍面临重大挑战。这些局限性影响了其在关键医疗应用中的效果。为此，我们提出了一种新方法，将相似案例生成融入多代理医疗问答（MedQA）系统。具体而言，我们采用最先进的Llama3.1:70B模型，通过零-shot学习在多代理架构中提升MedQA数据集的性能。该方法充分利用了模型的医学知识和推理能力，无需额外训练数据。实验结果表明，与现有基准模型相比，我们的方法在各种医疗QA任务中的准确率和F1分数均提升了7%。此外，我们还探讨了模型在处理复杂医疗查询时的可解释性和可靠性。这项研究不仅为医疗问答提供了强有力的解决方案，还为LLMs在医疗领域的广泛应用奠定了基础。

> Accurate and efficient question-answering systems are essential for delivering high-quality patient care in the medical field. While Large Language Models (LLMs) have made remarkable strides across various domains, they continue to face significant challenges in medical question answering, particularly in understanding domain-specific terminologies and performing complex reasoning. These limitations undermine their effectiveness in critical medical applications. To address these issues, we propose a novel approach incorporating similar case generation within a multi-agent medical question-answering (MedQA) system. Specifically, we leverage the Llama3.1:70B model, a state-of-the-art LLM, in a multi-agent architecture to enhance performance on the MedQA dataset using zero-shot learning. Our method capitalizes on the model's inherent medical knowledge and reasoning capabilities, eliminating the need for additional training data. Experimental results show substantial performance gains over existing benchmark models, with improvements of 7% in both accuracy and F1-score across various medical QA tasks. Furthermore, we examine the model's interpretability and reliability in addressing complex medical queries. This research not only offers a robust solution for medical question answering but also establishes a foundation for broader applications of LLMs in the medical domain.

[Arxiv](https://arxiv.org/abs/2501.05464)