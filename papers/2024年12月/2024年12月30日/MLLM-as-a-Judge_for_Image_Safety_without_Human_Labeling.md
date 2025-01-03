# MLLM 作为无需人工标注的图像安全评估工具

发布时间：2024年12月30日

`LLM应用

理由：这篇论文讨论了如何利用预训练的多模态大型语言模型（MLLMs）来检测不安全图像，特别是在零-shot设置下。论文提出了一种基于MLLM的方法，包括将安全规则客观化、评估规则与图像的相关性、基于去偏见的标记概率进行快速判断等。这些内容主要涉及如何将大型语言模型应用于具体的图像安全检测任务，因此属于LLM应用的范畴。` `图像安全` `人工智能`

> MLLM-as-a-Judge for Image Safety without Human Labeling

# 摘要

> # 摘要
随着在线视觉媒体的兴起，图像内容安全已成为一大挑战。在AI生成内容（AIGC）时代，许多图像生成模型能够生成包含色情或暴力等有害内容的图像。因此，基于既定安全规则识别这些不安全图像变得至关重要。预训练的多模态大型语言模型（MLLMs）凭借其强大的模式识别能力，在这方面展现出潜力。现有方法通常依赖人工标注的数据集对MLLMs进行微调，但这带来了诸多问题：人工标注成本高、耗时长，且安全规则频繁更新使得基于人工标注的微调更加困难。这引发了一个研究问题：能否通过预定义的安全规则在零-shot设置下查询MLLMs来检测不安全图像？我们的研究表明，直接查询预训练的MLLMs效果不佳，原因包括安全规则的主观性、冗长规则的复杂性以及模型固有的偏见。为此，我们提出了一种基于MLLM的方法，包括将安全规则客观化、评估规则与图像的相关性、基于去偏见的标记概率进行快速判断，并在必要时通过逻辑完整但简化的前提链进行更深入的推理。实验证明，该方法在零-shot图像安全判断任务中表现卓越。

> Image content safety has become a significant challenge with the rise of visual media on online platforms. Meanwhile, in the age of AI-generated content (AIGC), many image generation models are capable of producing harmful content, such as images containing sexual or violent material. Thus, it becomes crucial to identify such unsafe images based on established safety rules. Pre-trained Multimodal Large Language Models (MLLMs) offer potential in this regard, given their strong pattern recognition abilities. Existing approaches typically fine-tune MLLMs with human-labeled datasets, which however brings a series of drawbacks. First, relying on human annotators to label data following intricate and detailed guidelines is both expensive and labor-intensive. Furthermore, users of safety judgment systems may need to frequently update safety rules, making fine-tuning on human-based annotation more challenging. This raises the research question: Can we detect unsafe images by querying MLLMs in a zero-shot setting using a predefined safety constitution (a set of safety rules)? Our research showed that simply querying pre-trained MLLMs does not yield satisfactory results. This lack of effectiveness stems from factors such as the subjectivity of safety rules, the complexity of lengthy constitutions, and the inherent biases in the models. To address these challenges, we propose a MLLM-based method includes objectifying safety rules, assessing the relevance between rules and images, making quick judgments based on debiased token probabilities with logically complete yet simplified precondition chains for safety rules, and conducting more in-depth reasoning with cascaded chain-of-thought processes if necessary. Experiment results demonstrate that our method is highly effective for zero-shot image safety judgment tasks.

[Arxiv](https://arxiv.org/abs/2501.00192)