# ACE-$M^3$: 多模态医学模型的自动能力评估工具

发布时间：2024年12月16日

`LLM应用`

> ACE-$M^3$: Automatic Capability Evaluator for Multimodal Medical Models

# 摘要

> 随着多模态大型语言模型（MLLMs）在医疗领域日益突出，精确评估其有效性的方法需求变得极为关键。尽管基准测试为评估 MLLMs 的能力提供了可靠途径，但用于开放领域评估的传统指标（如 ROUGE 和 BLEU）仅着眼于标记重叠，可能与人类判断不符。人工评估虽更可靠，却劳动强度大、成本高且难以扩展。基于 LLM 的评估方法虽前景良好，但至今医疗领域仍急需开源的基于多模态 LLM 的评估器。为解决此问题，我们推出了 ACE-$M^3$，这是一个开源的【多模态医疗模型自动能力评估器】，专为评估医疗 MLLMs 的问答能力而设计。它先是利用分支合并架构，依据标准医疗评估标准提供详尽分析和简明的最终得分。接着，采用基于奖励令牌的直接偏好优化（RTDPO）策略，在不影响模型性能的前提下节省训练时间。大量实验表明，我们的 ACE-$M^3$ 模型ootnote{url{https://huggingface.co/collections/AIUSRTMP/ace-m3-67593297ff391b93e3e5d068}}在评估医疗 MLLMs 能力方面成效显著。

> As multimodal large language models (MLLMs) gain prominence in the medical field, the need for precise evaluation methods to assess their effectiveness has become critical. While benchmarks provide a reliable means to evaluate the capabilities of MLLMs, traditional metrics like ROUGE and BLEU employed for open domain evaluation only focus on token overlap and may not align with human judgment. Although human evaluation is more reliable, it is labor-intensive, costly, and not scalable. LLM-based evaluation methods have proven promising, but to date, there is still an urgent need for open-source multimodal LLM-based evaluators in the medical field. To address this issue, we introduce ACE-$M^3$, an open-sourced \textbf{A}utomatic \textbf{C}apability \textbf{E}valuator for \textbf{M}ultimodal \textbf{M}edical \textbf{M}odels specifically designed to assess the question answering abilities of medical MLLMs. It first utilizes a branch-merge architecture to provide both detailed analysis and a concise final score based on standard medical evaluation criteria. Subsequently, a reward token-based direct preference optimization (RTDPO) strategy is incorporated to save training time without compromising performance of our model. Extensive experiments have demonstrated the effectiveness of our ACE-$M^3$ model\footnote{url{https://huggingface.co/collections/AIUSRTMP/ace-m3-67593297ff391b93e3e5d068}} in evaluating the capabilities of medical MLLMs.

[Arxiv](https://arxiv.org/abs/2412.11453)