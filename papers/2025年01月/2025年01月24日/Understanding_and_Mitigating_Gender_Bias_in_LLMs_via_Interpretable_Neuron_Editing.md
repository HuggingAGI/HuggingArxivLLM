# 通过可解释的神经元编辑理解和减轻LLMs中的性别偏见

发布时间：2025年01月24日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLMs）中的性别偏见问题，并提出了新的数据集和方法来理解和解决这一问题。研究内容涉及对LLMs内部机制的分析（如神经元回路的作用）以及提出新的编辑方法来减少偏见，同时保留模型的核心能力。这些内容属于对LLMs内部工作机制的理论性研究和改进，因此分类为“LLM理论”。` `人工智能` `性别研究`

> Understanding and Mitigating Gender Bias in LLMs via Interpretable Neuron Editing

# 摘要

> 大型语言模型（LLMs）常表现出性别偏见，给其安全部署带来挑战。现有方法要么对偏见机制理解不足，要么会损害模型的核心能力。为此，我们提出了CommonWords数据集，用于系统评估LLMs中的性别偏见。分析发现，偏见在模型中普遍存在，且由特定神经元回路（如性别神经元和一般神经元）引发。值得注意的是，由于神经元间的层次交互，即使少量编辑一般神经元也可能影响模型整体能力。基于此，我们提出了一种结合logit和因果策略的可解释神经元编辑方法，精准定位偏见神经元。在五个LLMs上的实验表明，该方法在减少性别偏见的同时，保留了模型原有能力，效果优于现有微调和编辑方法。我们的研究贡献包括新数据集、偏见机制分析及实用解决方案。

> Large language models (LLMs) often exhibit gender bias, posing challenges for their safe deployment. Existing methods to mitigate bias lack a comprehensive understanding of its mechanisms or compromise the model's core capabilities. To address these issues, we propose the CommonWords dataset, to systematically evaluate gender bias in LLMs. Our analysis reveals pervasive bias across models and identifies specific neuron circuits, including gender neurons and general neurons, responsible for this behavior. Notably, editing even a small number of general neurons can disrupt the model's overall capabilities due to hierarchical neuron interactions. Based on these insights, we propose an interpretable neuron editing method that combines logit-based and causal-based strategies to selectively target biased neurons. Experiments on five LLMs demonstrate that our method effectively reduces gender bias while preserving the model's original capabilities, outperforming existing fine-tuning and editing approaches. Our findings contribute a novel dataset, a detailed analysis of bias mechanisms, and a practical solution for mitigating gender bias in LLMs.

[Arxiv](https://arxiv.org/abs/2501.14457)