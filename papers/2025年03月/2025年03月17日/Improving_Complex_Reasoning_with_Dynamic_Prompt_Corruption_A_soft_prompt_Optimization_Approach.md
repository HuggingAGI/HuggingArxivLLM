# 动态提示扰动提升复杂推理：基于软提示优化的方法

发布时间：2025年03月17日

`LLM应用` `人工智能` `机器学习`

> Improving Complex Reasoning with Dynamic Prompt Corruption: A soft prompt Optimization Approach

# 摘要

> 针对大型语言模型（LLMs）的提示微调（PT）技术，虽然能够通过大幅减少可训练参数来提升传统NLP任务的表现，但在复杂推理任务上却显得力不从心，甚至可能削弱模型的原始性能。这一现象揭示了软提示的双重影响：它可能在某些情况下带来积极效果，却在另一些情况下产生负面影响，尤其在推理的后期阶段表现得尤为明显。

为了解决这些挑战，我们发现软提示中存在一种信息积累现象。通过深入分析，我们揭示这种现象往往伴随着模型深层中错误的信息流动模式，最终导致推理结果的偏差。为此，我们提出了一种名为	extbf{D}ynamic 	extbf{P}rompt 	extbf{C}orruption（DPC）的创新方法，旨在更有效地利用软提示在复杂推理任务中的潜力。该方法通过动态调整软提示对推理过程的影响，分为两个关键阶段：动态触发和动态腐败。

在动态触发阶段，我们评估软提示的作用，判断其是正面还是负面。随后，在动态腐败阶段，通过选择性屏蔽干扰推理过程的关键令牌，有效缓解软提示的负面影响。我们在包括GSM8K、MATH和AQuA在内的多种LLMs和推理任务上进行了全面的实验验证。结果表明，与传统的提示微调相比，DPC能够显著提升PT的性能，准确率提高了4%-8%。这一成果不仅验证了我们方法的有效性，也展现了其在增强LLMs复杂推理能力方面的巨大潜力。

> Prompt-tuning (PT) for large language models (LLMs) can facilitate the performance on various conventional NLP tasks with significantly fewer trainable parameters. However, our investigation reveals that PT provides limited improvement and may even degrade the primitive performance of LLMs on complex reasoning tasks. Such a phenomenon suggests that soft prompts can positively impact certain instances while negatively affecting others, particularly during the later phases of reasoning. To address these challenges, We first identify an information accumulation within the soft prompts. Through detailed analysis, we demonstrate that this phenomenon is often accompanied by erroneous information flow patterns in the deeper layers of the model, which ultimately lead to incorrect reasoning outcomes. we propose a novel method called \textbf{D}ynamic \textbf{P}rompt \textbf{C}orruption (DPC) to take better advantage of soft prompts in complex reasoning tasks, which dynamically adjusts the influence of soft prompts based on their impact on the reasoning process. Specifically, DPC consists of two stages: Dynamic Trigger and Dynamic Corruption. First, Dynamic Trigger measures the impact of soft prompts, identifying whether beneficial or detrimental. Then, Dynamic Corruption mitigates the negative effects of soft prompts by selectively masking key tokens that interfere with the reasoning process. We validate the proposed approach through extensive experiments on various LLMs and reasoning tasks, including GSM8K, MATH, and AQuA. Experimental results demonstrate that DPC can consistently enhance the performance of PT, achieving 4\%-8\% accuracy gains compared to vanilla prompt tuning, highlighting the effectiveness of our approach and its potential to enhance complex reasoning in LLMs.

[Arxiv](https://arxiv.org/abs/2503.13208)