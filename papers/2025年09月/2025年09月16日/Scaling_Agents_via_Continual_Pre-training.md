# 通过持续预训练规模化智能体

发布时间：2025年09月16日

`Agent` `基础理论`

> Scaling Agents via Continual Pre-training

# 摘要

> 大型语言模型（LLMs）已发展成为智能体系统，能够自主使用工具并通过多步推理解决复杂问题。然而，基于通用基础模型的后训练方法在智能体任务中始终表现欠佳，开源实现中尤为明显。我们发现其根源在于：由于缺乏稳健的智能体基础模型，后训练阶段的模型不得不一边学习多样化的智能体行为，一边与专家演示对齐，这就造成了根本性的优化矛盾。为此，我们首创性地提出将智能体持续预训练（Agentic CPT）融入深度研究智能体的训练流程，旨在构建强大的智能体基础模型。基于这一方法，我们研发了名为AgentFounder的深度研究智能体模型。我们在10项基准测试中对AgentFounder-30B进行了评估，结果显示其在保持强大工具使用能力的同时，性能达到了当前最佳水平，尤其是在BrowseComp-en上为39.9%，BrowseComp-zh上为43.3%，HLE的Pass@1则达到31.5%。

> Large language models (LLMs) have evolved into agentic systems capable of autonomous tool use and multi-step reasoning for complex problem-solving. However, post-training approaches building upon general-purpose foundation models consistently underperform in agentic tasks, particularly in open-source implementations. We identify the root cause: the absence of robust agentic foundation models forces models during post-training to simultaneously learn diverse agentic behaviors while aligning them to expert demonstrations, thereby creating fundamental optimization tensions. To this end, we are the first to propose incorporating Agentic Continual Pre-training (Agentic CPT) into the deep research agents training pipeline to build powerful agentic foundational models. Based on this approach, we develop a deep research agent model named AgentFounder. We evaluate our AgentFounder-30B on 10 benchmarks and achieve state-of-the-art performance while retains strong tool-use ability, notably 39.9% on BrowseComp-en, 43.3% on BrowseComp-zh, and 31.5% Pass@1 on HLE.

[Arxiv](https://arxiv.org/abs/2509.13310)