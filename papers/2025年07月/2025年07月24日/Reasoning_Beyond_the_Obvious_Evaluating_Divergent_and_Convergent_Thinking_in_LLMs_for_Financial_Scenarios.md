# # **超越表面，深入思考：大型语言模型在金融场景中的思维评估**

深入探究大型语言模型在金融领域的推理能力，重点关注其发散与收敛思维的表现。

发布时间：2025年07月24日

`LLM应用

理由：这篇论文专注于评估大型语言模型在金融领域的应用，特别是它们在发散和收敛推理任务中的表现。通过创建ConDiFi基准，研究者评估了不同模型在金融任务中的能力，属于LLM的实际应用研究。` `基准测试`

> Reasoning Beyond the Obvious: Evaluating Divergent and Convergent Thinking in LLMs for Financial Scenarios

# 摘要

> 大多数针对大型语言模型（LLMs）的推理基准测试着重于事实准确性和逐步逻辑。然而，在金融领域，专业人士不仅要达成最优决策，还需要在不确定性中生成创意且合理的未来情景。我们推出ConDiFi，这是一个同时评估LLMs在财务任务中发散思维和收敛思维能力的基准。

ConDiFi包含607个用于发散推理的宏观经济金融提示，以及990个用于收敛推理的多跳对抗性选择题。通过这一基准，我们评估了14个领先的模型，发现了显著的差异。尽管GPT-4o在流畅度上表现出色，但在新颖性和行动性方面表现欠佳。相比之下，像DeepSeek-R1和Cohere Command R+这样的模型在生成适合投资决策的可行动见解方面表现优异。ConDiFi为评估在金融领域安全且战略性部署LLMs所需的推理能力提供了一个全新的视角。

> Most reasoning benchmarks for LLMs emphasize factual accuracy or step-by-step logic. In finance, however, professionals must not only converge on optimal decisions but also generate creative, plausible futures under uncertainty. We introduce ConDiFi, a benchmark that jointly evaluates divergent and convergent thinking in LLMs for financial tasks.
  ConDiFi features 607 macro-financial prompts for divergent reasoning and 990 multi-hop adversarial MCQs for convergent reasoning. Using this benchmark, we evaluated 14 leading models and uncovered striking differences. Despite high fluency, GPT-4o underperforms on Novelty and Actionability. In contrast, models like DeepSeek-R1 and Cohere Command R+ rank among the top for generating actionable, insights suitable for investment decisions. ConDiFi provides a new perspective to assess reasoning capabilities essential to safe and strategic deployment of LLMs in finance.

[Arxiv](https://arxiv.org/abs/2507.18368)