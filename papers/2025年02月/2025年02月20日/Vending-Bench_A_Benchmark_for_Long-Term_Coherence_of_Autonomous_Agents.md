# Vending-Bench：用于评估自主智能体长期连贯性的基准测试

发布时间：2025年02月20日

`Agent`

> Vending-Bench: A Benchmark for Long-Term Coherence of Autonomous Agents

# 摘要

> 尽管大型语言模型（LLMs）在孤立的短期任务中表现出色，但它们在长期任务中的表现往往不尽如人意。本文介绍了一个名为Vending-Bench的模拟环境，专为测试基于LLM的代理在简单但长期的商业场景（如运营自动售货机）中的能力而设计。代理需要完成平衡库存、下单、定价和处理日常费用等任务——这些任务看似简单，但长期运行（每轮超过2000万个token）会考验LLM在持续连贯决策方面的极限。我们的实验结果显示，不同LLM的表现存在显著差异：Claude 3.5 Sonnet和o3-mini在大多数情况下能良好管理售货机并实现盈利，但所有模型都存在运行失败的情况，原因包括误解交货时间、忘记订单或陷入无法自拔的“崩溃”循环。我们发现，失败与模型上下文窗口填满之间并无明确关联，表明这些问题并非源于内存限制。除了揭示长期任务中的高波动性，Vending-Bench还测试了模型获取资本的能力，这对于许多假设性危险AI场景至关重要。我们希望这个基准测试能为迎接更强大的AI系统做好准备。

> While Large Language Models (LLMs) can exhibit impressive proficiency in isolated, short-term tasks, they often fail to maintain coherent performance over longer time horizons. In this paper, we present Vending-Bench, a simulated environment designed to specifically test an LLM-based agent's ability to manage a straightforward, long-running business scenario: operating a vending machine. Agents must balance inventories, place orders, set prices, and handle daily fees - tasks that are each simple but collectively, over long horizons (>20M tokens per run) stress an LLM's capacity for sustained, coherent decision-making. Our experiments reveal high variance in performance across multiple LLMs: Claude 3.5 Sonnet and o3-mini manage the machine well in most runs and turn a profit, but all models have runs that derail, either through misinterpreting delivery schedules, forgetting orders, or descending into tangential "meltdown" loops from which they rarely recover. We find no clear correlation between failures and the point at which the model's context window becomes full, suggesting that these breakdowns do not stem from memory limits. Apart from highlighting the high variance in performance over long time horizons, Vending-Bench also tests models' ability to acquire capital, a necessity in many hypothetical dangerous AI scenarios. We hope the benchmark can help in preparing for the advent of stronger AI systems.

[Arxiv](https://arxiv.org/abs/2502.15840)