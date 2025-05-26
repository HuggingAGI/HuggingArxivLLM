# 任何大型语言模型都能成为可靠裁判：借助推理式偏见检测器实现去偏。

发布时间：2025年05月21日

`LLM应用` `人工智能`

> Any Large Language Model Can Be a Reliable Judge: Debiasing with a Reasoning-based Bias Detector

# 摘要

> LLM作为裁判在评估生成输出方面已展现出巨大潜力，但其可靠性常因潜在偏见而受到影响。现有方法在缓解偏见方面存在明显局限：基于上下文学习的方法难以根除固有偏见，原因在于评估者自我反思能力的限制；而微调技术并不适用于所有评估器类型，尤其是闭源模型。为解决这一难题，我们提出了基于推理的偏见检测器（RBD），这是一个无需修改评估器本身的插件模块。RBD通过外部操作，持续进行偏见检测与反馈驱动的修订，从而帮助评估器自我修正。为支持RBD的开发，我们构建了一个完整的开发流程，包括偏见数据集构建、监督收集、基于推理的蒸馏微调，以及与LLM评估器的无缝集成。我们对1.5B到14B四种规模的RBD模型进行了微调，结果显示所有规模的模型性能均显著提升。实验中，使用8种LLM评估器对 verbosity、position、bandwagon 和 sentiment 四种偏见类型进行评估，结果充分证明了RBD的卓越有效性。例如，RBD-8B模型将评估准确率提升了18.5%，一致性提升了10.9%，并且分别超越了提示基线和微调裁判12.8%和17.2%。这些结果不仅突显了RBD的高效性，也验证了其强大的可扩展性。进一步的实验表明，RBD在偏见和领域适应性方面具有出色的泛化能力，同时保持了高效的运行效率。

> LLM-as-a-Judge has emerged as a promising tool for automatically evaluating generated outputs, but its reliability is often undermined by potential biases in judgment. Existing efforts to mitigate these biases face key limitations: in-context learning-based methods fail to address rooted biases due to the evaluator's limited capacity for self-reflection, whereas fine-tuning is not applicable to all evaluator types, especially closed-source models. To address this challenge, we introduce the Reasoning-based Bias Detector (RBD), which is a plug-in module that identifies biased evaluations and generates structured reasoning to guide evaluator self-correction. Rather than modifying the evaluator itself, RBD operates externally and engages in an iterative process of bias detection and feedback-driven revision. To support its development, we design a complete pipeline consisting of biased dataset construction, supervision collection, distilled reasoning-based fine-tuning of RBD, and integration with LLM evaluators. We fine-tune four sizes of RBD models, ranging from 1.5B to 14B, and observe consistent performance improvements across all scales. Experimental results on 4 bias types--verbosity, position, bandwagon, and sentiment--evaluated using 8 LLM evaluators demonstrate RBD's strong effectiveness. For example, the RBD-8B model improves evaluation accuracy by an average of 18.5% and consistency by 10.9%, and surpasses prompting-based baselines and fine-tuned judges by 12.8% and 17.2%, respectively. These results highlight RBD's effectiveness and scalability. Additional experiments further demonstrate its strong generalization across biases and domains, as well as its efficiency.

[Arxiv](https://arxiv.org/abs/2505.17100)