# FairMT-Bench：为会话式大型语言模型中的多轮对话公平性设立基准

发布时间：2024年10月25日

`LLM应用` `聊天机器人`

> FairMT-Bench: Benchmarking Fairness for Multi-turn Dialogue in Conversational LLMs

# 摘要

> 随着基于大型语言模型（LLM）的聊天机器人使用愈发广泛，公平性问题引发了人们的担忧。LLM 中的公平性问题可能引发严重后果，像偏差放大、歧视以及对边缘化群体的伤害。现有的公平性基准多聚焦于单轮对话，而更能反映真实世界对话情况的多轮场景，因对话的复杂性和潜在的偏差累积，面临着更大挑战。在本文中，我们为多轮对话场景中的 LLM 提出了全面的公平性基准——	extbf{FairMT-Bench}。具体而言，我们针对 LLM 的公平性能力制定了任务分类法，涵盖三个阶段：上下文理解、用户交互和指令权衡，每个阶段包含两项任务。为确保涵盖各类偏差类型和属性，我们借鉴现有公平性数据集，并运用模板构建了多轮对话数据集——	exttt{FairMT-10K}。在评估环节，采用了 GPT-4 以及包括 Llama-Guard-3 在内的偏差分类器和人工验证，以保障可靠性。对 	exttt{FairMT-10K} 的实验和分析表明，在多轮对话场景中，当前的 LLM 更易生成有偏差的回应，且不同任务和模型的性能差异显著。基于此，我们整理出具有挑战性的数据集——	exttt{FairMT-1K}，并在该数据集上对 15 个当前最先进（SOTA）的 LLM 进行了测试。结果展现了 LLM 当下的公平性状况，也凸显了这种新颖方法在评估更贴近现实的多轮对话情境中的公平性方面的作用，呼吁未来工作关注 LLM 公平性的提升，并在相关工作中采用 	exttt{FairMT-1K}。

> The growing use of large language model (LLM)-based chatbots has raised concerns about fairness. Fairness issues in LLMs can lead to severe consequences, such as bias amplification, discrimination, and harm to marginalized communities. While existing fairness benchmarks mainly focus on single-turn dialogues, multi-turn scenarios, which in fact better reflect real-world conversations, present greater challenges due to conversational complexity and potential bias accumulation. In this paper, we propose a comprehensive fairness benchmark for LLMs in multi-turn dialogue scenarios, \textbf{FairMT-Bench}. Specifically, we formulate a task taxonomy targeting LLM fairness capabilities across three stages: context understanding, user interaction, and instruction trade-offs, with each stage comprising two tasks. To ensure coverage of diverse bias types and attributes, we draw from existing fairness datasets and employ our template to construct a multi-turn dialogue dataset, \texttt{FairMT-10K}. For evaluation, GPT-4 is applied, alongside bias classifiers including Llama-Guard-3 and human validation to ensure robustness. Experiments and analyses on \texttt{FairMT-10K} reveal that in multi-turn dialogue scenarios, current LLMs are more likely to generate biased responses, and there is significant variation in performance across different tasks and models. Based on this, we curate a challenging dataset, \texttt{FairMT-1K}, and test 15 current state-of-the-art (SOTA) LLMs on this dataset. The results show the current state of fairness in LLMs and showcase the utility of this novel approach for assessing fairness in more realistic multi-turn dialogue contexts, calling for future work to focus on LLM fairness improvement and the adoption of \texttt{FairMT-1K} in such efforts.

[Arxiv](https://arxiv.org/abs/2410.19317)