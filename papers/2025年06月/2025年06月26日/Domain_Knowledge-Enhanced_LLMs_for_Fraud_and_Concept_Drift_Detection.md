# 领域知识增强的大型语言模型在欺诈检测与概念漂移中的应用

发布时间：2025年06月26日

`LLM应用

摘要讨论了利用领域知识增强的大型语言模型（LLMs）来检测欺骗性对话和概念漂移，属于将LLMs应用于特定任务的范畴，因此归类为LLM应用。` `欺诈检测`

> Domain Knowledge-Enhanced LLMs for Fraud and Concept Drift Detection

# 摘要

> 在动态平台上检测欺骗性对话正变得日益困难，原因在于不断变化的语言模式和概念漂移（CD）——即随着时间的推移，语义或主题的变化会改变互动的上下文或意图。这些变化可能会掩盖恶意意图或模仿正常对话，使得准确分类变得具有挑战性。尽管大型语言模型（LLMs）在自然语言任务中表现出色，但它们在风险敏感场景下常常难以应对上下文模糊和幻觉问题。为了解决这些挑战，我们提出了一种基于领域知识（DK）增强的LLM框架，该框架将预训练的LLMs与结构化、特定任务的见解相结合，以执行欺诈和概念漂移检测。提出的架构主要由三个组件组成：（1）一个DK-LLM模块，用于检测虚假或欺骗性对话；（2）一个漂移检测单元（OCDD），用于判断是否发生了语义变化；（3）另一个DK-LLM模块，用于将漂移分类为良性或欺诈性。我们首先通过一个虚假评论数据集验证了领域知识的价值，然后将我们的完整框架应用于SEConvo，这是一个包含各种欺诈和垃圾攻击的多轮对话数据集。实验结果表明，我们的系统能够高精度地检测虚假对话，并有效分类漂移的性质。在结构化提示的指导下，基于LLaMA的实现达到了98%的分类准确率。与零样本基线的比较研究表明，融入领域知识和漂移意识显著提高了高性能NLP应用中的性能、可解释性和鲁棒性。

> Detecting deceptive conversations on dynamic platforms is increasingly difficult due to evolving language patterns and Concept Drift (CD)\-i.e., semantic or topical shifts that alter the context or intent of interactions over time. These shifts can obscure malicious intent or mimic normal dialogue, making accurate classification challenging. While Large Language Models (LLMs) show strong performance in natural language tasks, they often struggle with contextual ambiguity and hallucinations in risk\-sensitive scenarios. To address these challenges, we present a Domain Knowledge (DK)\-Enhanced LLM framework that integrates pretrained LLMs with structured, task\-specific insights to perform fraud and concept drift detection. The proposed architecture consists of three main components: (1) a DK\-LLM module to detect fake or deceptive conversations; (2) a drift detection unit (OCDD) to determine whether a semantic shift has occurred; and (3) a second DK\-LLM module to classify the drift as either benign or fraudulent. We first validate the value of domain knowledge using a fake review dataset and then apply our full framework to SEConvo, a multiturn dialogue dataset that includes various types of fraud and spam attacks. Results show that our system detects fake conversations with high accuracy and effectively classifies the nature of drift. Guided by structured prompts, the LLaMA\-based implementation achieves 98\% classification accuracy. Comparative studies against zero\-shot baselines demonstrate that incorporating domain knowledge and drift awareness significantly improves performance, interpretability, and robustness in high\-stakes NLP applications.

[Arxiv](https://arxiv.org/abs/2506.21443)