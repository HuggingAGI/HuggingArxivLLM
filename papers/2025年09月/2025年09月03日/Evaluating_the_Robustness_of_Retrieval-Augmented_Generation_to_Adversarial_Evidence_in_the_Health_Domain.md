# 健康领域检索增强生成对对抗性证据的鲁棒性评估

发布时间：2025年09月03日

`RAG` `医疗健康`

> Evaluating the Robustness of Retrieval-Augmented Generation to Adversarial Evidence in the Health Domain

# 摘要

> 检索增强生成（RAG）系统通过提供检索到的证据或上下文作为支持，为大型语言模型（LLM）的响应奠定事实基础。在该上下文的引导下，RAG系统不仅能减少幻觉，还能增强LLM准确回答训练数据范围外问题的能力。然而，这种设计存在一个关键漏洞：LLM可能会吸收并复述检索证据中包含的错误信息。若检索到的证据含有明确用于传播错误信息的对抗性材料，这一问题将进一步恶化。本文对健康领域的RAG鲁棒性展开系统性评估，并研究了模型输出与真实答案的一致性。我们聚焦健康领域，一方面是因为错误响应可能带来危害，另一方面是许多常见健康问题都有基于证据的真实答案。我们通过常见健康问题开展对照实验，改变检索文档的类型与构成（包括有帮助的、有害的和对抗性文档），以及用户对问题的表述方式（包括一致的、中性的和不一致的表述）。研究结果显示，对抗性文档会显著降低一致性，但只要检索池中同时存在有帮助的证据，鲁棒性就能得到维持。这些发现强调了检索安全措施的必要性，为在高风险领域设计更安全的RAG系统提供了可操作的见解。为保证可重复性并助力未来研究，所有实验结果均已在我们的GitHub仓库公开。
  https://github.com/shakibaam/RAG_ROBUSTNESS_EVAL

> Retrieval augmented generation (RAG) systems provide a method for factually grounding the responses of a Large Language Model (LLM) by providing retrieved evidence, or context, as support. Guided by this context, RAG systems can reduce hallucinations and expand the ability of LLMs to accurately answer questions outside the scope of their training data. Unfortunately, this design introduces a critical vulnerability: LLMs may absorb and reproduce misinformation present in retrieved evidence. This problem is magnified if retrieved evidence contains adversarial material explicitly intended to promulgate misinformation. This paper presents a systematic evaluation of RAG robustness in the health domain and examines alignment between model outputs and ground-truth answers. We focus on the health domain due to the potential for harm caused by incorrect responses, as well as the availability of evidence-based ground truth for many common health-related questions. We conduct controlled experiments using common health questions, varying both the type and composition of the retrieved documents (helpful, harmful, and adversarial) as well as the framing of the question by the user (consistent, neutral, and inconsistent). Our findings reveal that adversarial documents substantially degrade alignment, but robustness can be preserved when helpful evidence is also present in the retrieval pool. These findings offer actionable insights for designing safer RAG systems in high-stakes domains by highlighting the need for retrieval safeguards. To enable reproducibility and facilitate future research, all experimental results are publicly available in our github repository.
  https://github.com/shakibaam/RAG_ROBUSTNESS_EVAL

[Arxiv](https://arxiv.org/abs/2509.03787)