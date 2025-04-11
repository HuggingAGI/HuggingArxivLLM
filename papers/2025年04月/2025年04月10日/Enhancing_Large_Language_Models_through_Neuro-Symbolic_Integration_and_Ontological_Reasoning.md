# 通过神经符号结合与本体推理增强大型语言模型

发布时间：2025年04月10日

`LLM理论` `符号推理`

> Enhancing Large Language Models through Neuro-Symbolic Integration and Ontological Reasoning

# 摘要

> 大型语言模型（LLMs）在自然语言处理中表现卓越，但其输出常伴有不准确和逻辑混乱的“幻觉”问题，这严重影响了它们在事实要求严格的领域中的可靠性。我们提出了一种神经符号方法，将符号本体论推理与机器学习相结合，以提升LLM输出的一致性和可信度。我们的解决方案采用OWL本体、符号推理器（如HermiT）进行一致性验证，并借助轻量级机器学习模型（逻辑回归）将自然语言转化为与本体兼容的逻辑表达。当检测到LLM输出与本体存在冲突时，系统会生成解释性反馈，引导LLM在迭代优化过程中生成更准确且逻辑严谨的回复。我们开发了一个Python原型系统来演示这一流程。实验结果表明，在特定领域中，LLM的语义连贯性和事实准确性有了显著提升，这充分展现了将LLM的生成能力与形式语义的严谨性相结合的潜力。

> Large Language Models (LLMs) demonstrate impressive capabilities in natural language processing but suffer from inaccuracies and logical inconsistencies known as hallucinations. This compromises their reliability, especially in domains requiring factual accuracy. We propose a neuro-symbolic approach integrating symbolic ontological reasoning and machine learning methods to enhance the consistency and reliability of LLM outputs. Our workflow utilizes OWL ontologies, a symbolic reasoner (e.g., HermiT) for consistency checking, and a lightweight machine learning model (logistic regression) for mapping natural language statements into logical forms compatible with the ontology. When inconsistencies between LLM outputs and the ontology are detected, the system generates explanatory feedback to guide the LLM towards a corrected, logically coherent response in an iterative refinement loop. We present a working Python prototype demonstrating this pipeline. Experimental results in a defined domain suggest significant improvements in semantic coherence and factual accuracy of LLM outputs, showcasing the potential of combining LLM fluency with the rigor of formal semantics.

[Arxiv](https://arxiv.org/abs/2504.07640)