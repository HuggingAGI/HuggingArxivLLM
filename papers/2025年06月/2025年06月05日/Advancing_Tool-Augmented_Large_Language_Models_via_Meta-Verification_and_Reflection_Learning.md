# # 元验证与反思学习推动工具增强型大语言模型发展
通过元验证和反思学习提升工具增强型大型语言模型

发布时间：2025年06月05日

`LLM应用` `人工智能` `工具增强`

> Advancing Tool-Augmented Large Language Models via Meta-Verification and Reflection Learning

# 摘要

> 赋能大型语言模型（LLMs）的工具利用能力，是提升AI代理解决复杂问题的关键。然而，现有模型面临两大核心挑战：一是工具规划与调用的可靠性不足（受制于低质量指令数据集，如广泛存在的幻觉API调用），二是工具反思能力较弱（90%以上的错误无法纠正，源于静态模仿学习）。为突破这些瓶颈，我们提出了一种创新的工具增强型LLM——Tool-MVR，通过两大核心技术实现全面的System 2推理能力。首先，我们开发了多智能体元验证（MAMV），构建了一套系统化的验证流程，对API、查询和推理轨迹进行严格验证，从而打造了高质量指令数据集ToolBench-V，有效解决了工具规划与调用的可靠性问题。其次，我们提出了基于探索的反思学习（EXPLORE），通过动态的"错误->反思->纠正"学习范式，结合工具反馈机制，显著提升了工具反思能力，形成了反思数据集ToolBench-R，成功克服了工具反思能力较弱的难题。最终，我们通过在开源LLMs（如Qwen-7B）上微调ToolBench-V和ToolBench-R，获得了性能优越的Tool-MVR模型。实验结果表明，Tool-MVR在StableToolBench上实现了超越ToolLLM（提升23.9%）和GPT-4（提升15.3%）的顶尖性能，同时将API调用减少了31.4%，并在未见过的工具和场景中展现了强大的泛化能力。此外，在专为评估工具反思能力设计的RefineToolBench基准测试中，Tool-MVR实现了58.9%的错误纠正率，远超ToolLLM的9.1%。


> Empowering large language models (LLMs) with effective tool utilization capabilities is crucial for enabling AI agents to solve complex problems. However, current models face two major limitations: (1) unreliable tool planning and invocation due to low-quality instruction datasets (e.g., widespread hallucinated API calls), and (2) weak tool reflection abilities (over 90% of errors cannot be corrected) resulting from static imitation learning. To address these critical limitations, we propose Tool-MVR, a novel Tool-Augmented LLM that achieves comprehensive System 2 reasoning through two key innovations. Specifically, we first introduce Multi-Agent Meta-Verification (MAMV), a systematic pipeline that rigorously validates APIs, queries, and reasoning trajectories to construct ToolBench-V, a new high-quality instruction dataset that addresses the limitation of unreliable tool planning and invocation. Second, we propose Exploration-based Reflection Learning (EXPLORE), which enhances tool reflection capabilities by leveraging tool feedback through a dynamic "Error -> Reflection -> Correction" learning paradigm, resulting in our reflection dataset ToolBench-R and addressing the critical weakness in tool reflection. Finally, we obtain Tool-MVR by finetuning open-source LLMs (e.g., Qwen-7B) on both ToolBench-V and ToolBench-R. Our experiments demonstrate that Tool-MVR achieves state-of-the-art performance on StableToolBench, surpassing both ToolLLM (by 23.9%) and GPT-4 (by 15.3%) while reducing API calls by 31.4%, with strong generalization capabilities across unseen tools and scenarios. Additionally, on our proposed RefineToolBench, the first benchmark specifically designed to evaluate tool reflection capabilities, Tool-MVR achieves a 58.9% error correction rate, significantly outperforming ToolLLM's 9.1%.

[Arxiv](https://arxiv.org/abs/2506.04625)