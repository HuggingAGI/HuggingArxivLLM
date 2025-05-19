# 合作链提示框架：为 LLM 代理构建协作网络

发布时间：2025年05月16日

`LLM应用`

> Connecting the Dots: A Chain-of-Collaboration Prompting Framework for LLM Agents

# 摘要

> 大型语言模型（LLMs）在复杂推理任务中表现出色。思维链通过释放大模型的潜力，显著提升了推理能力；而多智能体系统通过整合多个智能体的集体智慧，提供了更全面的解决方案。然而，这两种方法都存在明显局限。单智能体的思维链方法因跨领域提示设计的复杂性而面临协作难题，多智能体系统则因消耗大量tokens并不可避免地稀释主要问题，尤其在商业工作流任务中问题突出。为解决这些挑战，我们提出了CoChain——一个高效协作提示框架，通过结合知识与提示，以更低的成本有效解决商业工作流协作问题。具体而言，我们构建了一个集成知识图谱，整合多阶段知识，并通过维护和检索提示树，获取与商业工作流其他阶段相关的提示信息。我们在多个数据集上对CoChain进行了全面评估，结果显示它在提示工程和多智能体LLMs方面均优于所有基线模型。此外，专家评估表明，结合CoChain使用的小模型表现甚至优于GPT-4。

> Large Language Models (LLMs) have demonstrated impressive performance in executing complex reasoning tasks. Chain-of-thought effectively enhances reasoning capabilities by unlocking the potential of large models, while multi-agent systems provide more comprehensive solutions by integrating collective intelligence of multiple agents. However, both approaches face significant limitations. Single-agent with chain-of-thought, due to the inherent complexity of designing cross-domain prompts, faces collaboration challenges. Meanwhile, multi-agent systems consume substantial tokens and inevitably dilute the primary problem, which is particularly problematic in business workflow tasks. To address these challenges, we propose Cochain, a collaboration prompting framework that effectively solves business workflow collaboration problem by combining knowledge and prompts at a reduced cost. Specifically, we construct an integrated knowledge graph that incorporates knowledge from multiple stages. Furthermore, by maintaining and retrieving a prompts tree, we can obtain prompt information relevant to other stages of the business workflow. We perform extensive evaluations of Cochain across multiple datasets, demonstrating that Cochain outperforms all baselines in both prompt engineering and multi-agent LLMs. Additionally, expert evaluation results indicate that the use of a small model in combination with Cochain outperforms GPT-4.

[Arxiv](https://arxiv.org/abs/2505.10936)