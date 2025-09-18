# 自适应思维链压缩驱动高效推理：自优化框架

发布时间：2025年09月17日

`LLM应用` `基础理论`

> Reasoning Efficiently Through Adaptive Chain-of-Thought Compression: A Self-Optimizing Framework

# 摘要

> 思维链（CoT）推理通过提示中间推理步骤来增强大型语言模型（LLMs），在算术、逻辑及常识任务中显著提升了准确性与稳健性。然而，这种优势背后是高昂的计算成本：输出越长，延迟、内存占用及KV缓存需求就越高。而在软件工程任务中，由于需要简洁且确定的输出，这些问题显得尤为突出。为探究这些利弊权衡，我们基于代码生成基准开展了实证研究。研究结果显示，CoT并非越长越好。过度推理往往会引发输出截断、准确率下降，延迟甚至高达五倍，且失败输出的长度始终超过成功输出。这些发现对“推理越长本质上越好”的固有假设提出了挑战，同时凸显了自适应CoT控制的必要性。基于此，我们提出了SEER（自增强高效推理）——一种能在保持准确性的同时压缩CoT的自适应框架。SEER结合了Best-of-N采样与任务感知自适应过滤技术，通过推理前输出动态调整阈值，从而减少冗余信息与计算开销。随后，我们在三项软件工程任务和一项数学任务上对SEER进行了评估。平均来看，SEER能将CoT长度缩短42.1%，同时通过减少截断提升准确率，并消除了大部分无限循环问题。这些结果证实，SEER是一种实用方法，能让CoT增强的LLMs在资源受限环境下也能更高效、更稳健地运行。

> Chain-of-Thought (CoT) reasoning enhances Large Language Models (LLMs) by prompting intermediate steps, improving accuracy and robustness in arithmetic, logic, and commonsense tasks. However, this benefit comes with high computational costs: longer outputs increase latency, memory usage, and KV-cache demands. These issues are especially critical in software engineering tasks where concise and deterministic outputs are required. To investigate these trade-offs, we conduct an empirical study based on code generation benchmarks. The results reveal that longer CoT does not always help. Excessive reasoning often causes truncation, accuracy drops, and latency up to five times higher, with failed outputs consistently longer than successful ones. These findings challenge the assumption that longer reasoning is inherently better and highlight the need for adaptive CoT control. Motivated by this, we propose SEER (Self-Enhancing Efficient Reasoning), an adaptive framework that compresses CoT while preserving accuracy. SEER combines Best-of-N sampling with task-aware adaptive filtering, dynamically adjusting thresholds based on pre-inference outputs to reduce verbosity and computational overhead. We then evaluate SEER on three software engineering tasks and one math task. On average, SEER shortens CoT by 42.1%, improves accuracy by reducing truncation, and eliminates most infinite loops. These results demonstrate SEER as a practical method to make CoT-enhanced LLMs more efficient and robust, even under resource constraints.

[Arxiv](https://arxiv.org/abs/2509.14093)