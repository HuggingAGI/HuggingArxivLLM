# ZhiFangDanTai：中药方剂的基于图检索增强生成模型微调

发布时间：2025年09月06日

`RAG` `医疗健康`

> ZhiFangDanTai: Fine-tuning Graph-based Retrieval-Augmented Generation Model for Traditional Chinese Medicine Formula

# 摘要

> 中医药方剂在应对流行病与复杂疾病方面作用显著。现有中医药模型多采用传统算法或深度学习技术分析方剂关联，却难以提供全面结果，如完整的方剂组成及详细阐释。尽管近期研究已尝试通过中医药指令数据集微调大型语言模型（LLMs），以实现方剂生成的可解释性，但现有数据集细节不足——方剂的君臣佐使配伍、功效、禁忌及舌脉诊等关键信息的缺失，制约了模型输出的深度。针对这些问题，我们提出ZhiFangDanTai框架，融合基于图的检索增强生成（GraphRAG）与LLM微调技术。该框架通过GraphRAG检索并提炼结构化中医药知识为精炼摘要，同时构建增强指令数据集，提升LLMs对检索信息的整合能力。此外，我们还提供全新理论证明，证实融合GraphRAG与微调技术能够降低中医药方剂任务中的泛化误差与幻觉率。在收集数据集与临床数据集上的实验结果显示，ZhiFangDanTai相较当前最优模型性能显著提升。模型已开源，链接为https://huggingface.co/tczzx6/ZhiFangDanTai1.0。

> Traditional Chinese Medicine (TCM) formulas play a significant role in treating epidemics and complex diseases. Existing models for TCM utilize traditional algorithms or deep learning techniques to analyze formula relationships, yet lack comprehensive results, such as complete formula compositions and detailed explanations. Although recent efforts have used TCM instruction datasets to fine-tune Large Language Models (LLMs) for explainable formula generation, existing datasets lack sufficient details, such as the roles of the formula's sovereign, minister, assistant, courier; efficacy; contraindications; tongue and pulse diagnosis-limiting the depth of model outputs. To address these challenges, we propose ZhiFangDanTai, a framework combining Graph-based Retrieval-Augmented Generation (GraphRAG) with LLM fine-tuning. ZhiFangDanTai uses GraphRAG to retrieve and synthesize structured TCM knowledge into concise summaries, while also constructing an enhanced instruction dataset to improve LLMs' ability to integrate retrieved information. Furthermore, we provide novel theoretical proofs demonstrating that integrating GraphRAG with fine-tuning techniques can reduce generalization error and hallucination rates in the TCM formula task. Experimental results on both collected and clinical datasets demonstrate that ZhiFangDanTai achieves significant improvements over state-of-the-art models. Our model is open-sourced at https://huggingface.co/tczzx6/ZhiFangDanTai1.0.

[Arxiv](https://arxiv.org/abs/2509.05867)