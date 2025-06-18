# 航空LLM：用于航空培训的基于LLM的知识系统

发布时间：2025年06月17日

`LLM应用`

> AviationLLM: An LLM-based Knowledge System for Aviation Training

# 摘要

> 航空培训是保障飞行安全、提升行业效率和推动可持续发展的重要环节。它不仅包含飞行模拟，还涉及大量专业航空理论知识的学习。在现有培训体系中，知识主要由教员传授，但教员数量有限，且网络上的专业答案往往不够准确，导致培训效率低下。为解决这一问题，我们引入了大语言模型（LLM）。然而，基础预训练模型无法满足专业领域的需求，因此我们对其进行微调。传统监督微调（SFT）因数据覆盖不足，可能生成看似合理却事实错误的回答。为解决这一问题，我们采用直接偏好优化（DPO）。本文提出了一种基于直接偏好优化的检索增强型大语言模型对齐方法（RALA-DPO）。我们选择了开源预训练大语言模型Qwen，并通过基于DPO的领域对齐技术将其应用于航空理论培训。同时，为了解决由训练数据偏差、知识老化或领域知识缺口引起的幻觉问题，我们采用了结合生成模型和检索模型的检索增强生成（RAG）技术。RALA-DPO能够从外部知识库中有效检索相关信息，并通过生成模型提供精准且高质量的回答。实验结果表明，RALA-DPO显著提升了对专业航空知识回答的准确性。通过集成RAG机制，该系统不仅进一步提高了答案的准确性，还实现了零成本的知识更新。

> Aviation training is a core link in ensuring flight safety, improving industry efficiency and promoting sustainable development. It not only involves flight simulation but also requires the learning of a great deal of professional aviation theory knowledge. In the existing training system, the knowledge is mainly imparted by the the instructors. However, the number of instructors is limited and the professional answers obtained from the Internet are not accurate enough, resulting in low training efficiency. To address this, we introduced LLM, but the basic pre-trained model cannot provide accurate answers to professional fields, so we fine-tuned it. Traditional Supervised Fine-Tuning (SFT) risk generating superficially plausible but factually incorrect responses due to insufficient data coverage. To address this, we employ Direct Preference Optimization(DPO). This paper proposes Retrieval-Augmented LLM Alignment via Direct Preference Optimization(RALA-DPO). We select open source pre-trained LLM Qwen and adapt it to aviation theory training through DPO-based domain alignment. Simultaneously, to mitigate hallucinations caused by training data biases, knowledge obsolescence, or domain knowledge gaps, we implement Retrieval-Augmented Generation(RAG) technology that combines generative and retrieval models. RALA-DPO effectively retrieves relevant information from external knowledge bases and delivers precise and high-quality responses through the generative model. Experimental results demonstrate that RALA-DPO can improve accuracy in response to professional aviation knowledge. With integrated RAG mechanisms, this system can further improve the accuracy of answers and achieve zero-cost knowledge updates simultaneously.

[Arxiv](https://arxiv.org/abs/2506.14336)