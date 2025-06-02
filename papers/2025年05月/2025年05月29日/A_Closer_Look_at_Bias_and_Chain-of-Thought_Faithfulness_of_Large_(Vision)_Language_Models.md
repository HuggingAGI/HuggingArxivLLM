# 再探大型（视觉）语言模型的偏见与思维链忠实性

发布时间：2025年05月29日

`LLM理论` `计算机视觉`

> A Closer Look at Bias and Chain-of-Thought Faithfulness of Large (Vision) Language Models

# 摘要

> 链式思维（CoT）推理虽能提升大型语言模型的表现，但其推理轨迹是否忠实反映了模型内部机制仍存疑问。我们首次对大型视觉语言模型（LVLMs）中的CoT忠实性展开全面研究，揭示了基于文本与图像的偏见对推理及偏见表达的影响。我们开发了一种新型精细评估框架，用于分类偏见表达模式，相较于传统方法，它能更精准地剖析CoT推理机制。这一框架揭示了模型在处理不同偏见类型时的关键差异，为理解LVLM的CoT忠实性提供了新视角。研究发现，相较于显式的文本偏见，微妙的图像偏见极少被模型表达，即使在专门设计的推理模型中亦然。此外，我们首次发现了一种被称为“不一致”推理的现象——模型在正确推理后突然改变答案，这可能成为检测不忠实CoT导致的偏见推理的预警信号。进一步，我们将同一评估框架应用于不同隐式提示水平的LLMs，发现当前仅基于语言的推理模型仍难以准确表达未被明示的提示信息。


> Chain-of-thought (CoT) reasoning enhances performance of large language models, but questions remain about whether these reasoning traces faithfully reflect the internal processes of the model. We present the first comprehensive study of CoT faithfulness in large vision-language models (LVLMs), investigating how both text-based and previously unexplored image-based biases affect reasoning and bias articulation. Our work introduces a novel, fine-grained evaluation pipeline for categorizing bias articulation patterns, enabling significantly more precise analysis of CoT reasoning than previous methods. This framework reveals critical distinctions in how models process and respond to different types of biases, providing new insights into LVLM CoT faithfulness. Our findings reveal that subtle image-based biases are rarely articulated compared to explicit text-based ones, even in models specialized for reasoning. Additionally, many models exhibit a previously unidentified phenomenon we term ``inconsistent'' reasoning - correctly reasoning before abruptly changing answers, serving as a potential canary for detecting biased reasoning from unfaithful CoTs. We then apply the same evaluation pipeline to revisit CoT faithfulness in LLMs across various levels of implicit cues. Our findings reveal that current language-only reasoning models continue to struggle with articulating cues that are not overtly stated.

[Arxiv](https://arxiv.org/abs/2505.23945)