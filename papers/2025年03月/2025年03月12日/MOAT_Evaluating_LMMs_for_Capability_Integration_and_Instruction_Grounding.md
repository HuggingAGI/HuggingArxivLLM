# MOAT：评估 LMMs 的能力整合与指令 grounding 能力

发布时间：2025年03月12日

`LLM应用` `视觉语言` `多模态模型`

> MOAT: Evaluating LMMs for Capability Integration and Instruction Grounding

# 摘要

> 大型多模态模型（LMMs）在视觉语言（VL）任务中展现出巨大潜力，但与人类相比，它们在复杂任务中的表现仍有明显差距，尤其是在需要整合多种基础VL能力以及处理复杂指令 grounding 的任务中。为深入探究这一差距及其原因，我们提出了MOAT——一个包含复杂现实世界VL任务的多样化基准测试，这些任务对LMMs极具挑战性。MOAT中的任务要求LMMs通过整合阅读文本、计数、理解空间关系、 grounding 文本和视觉指令等基础能力来进行通用问题解决。我们提出了一个包含10种基础VL能力的分类法，使MOAT能够细致评估LMMs的能力强弱。值得注意的是，MOAT是首个专门评估LMMs处理复杂文本和视觉指令能力的基准测试，这对许多现实应用至关重要。我们在MOAT上评估了20多个专有和开源LMMs以及人类的表现，结果显示人类的准确率高达82.7%，而表现最佳的LMM（OpenAI o1）仅达到38.8%。为了指导未来模型的发展，我们分析了结果中的普遍趋势，并深入探讨了LMMs与人类之间性能差距的根本原因，重点关注了VL能力在复杂任务中的瓶颈作用、测试时间扩展对MOAT性能的提升效果，以及 tiling 对LMMs计数能力的负面影响。更多代码和数据请访问https://cambrian-yzt.github.io/MOAT。

> Large multimodal models (LMMs) have demonstrated significant potential as generalists in vision-language (VL) tasks. However, there remains a significant gap between state-of-the-art LMMs and human performance when it comes to complex tasks that require a combination of fundamental VL capabilities, as well as tasks involving the grounding of complex instructions. To thoroughly investigate the human-LMM gap and its underlying causes, we propose MOAT, a diverse benchmark with complex real-world VL tasks that are challenging for LMMs. Specifically, the tasks in MOAT require LMMs to engage in generalist problem solving by integrating fundamental VL capabilities such as reading text, counting, understanding spatial relations, grounding textual and visual instructions, etc. All these abilities fit into a taxonomy proposed by us that contains 10 fundamental VL capabilities, enabling MOAT to provide a fine-grained view of LMMs' strengths and weaknesses. Besides, MOAT is the first benchmark to explicitly evaluate LMMs' ability to ground complex text and visual instructions, which is essential to many real-world applications. We evaluate over 20 proprietary and open source LMMs, as well as humans, on MOAT, and found that humans achieved 82.7% accuracy while the best performing LMM (OpenAI o1) achieved only 38.8%. To guide future model development, we analyze common trends in our results and discuss the underlying causes of observed performance gaps between LMMs and humans, focusing on which VL capability forms the bottleneck in complex tasks, whether test time scaling improves performance on MOAT, and how tiling harms LMMs' capability to count. Code and data are available at https://cambrian-yzt.github.io/MOAT.

[Arxiv](https://arxiv.org/abs/2503.09348)