# ALU: 智能体 LLM 遗忘

发布时间：2025年02月01日

`Agent

理由：这篇论文提出了一种多智能体、无需重新训练、模型无关的LLM遗忘方法（ALU），通过多个LLM智能体协同工作来实现信息移除或抑制。这种方法涉及到多个智能体的协作和任务分配，符合“Agent”分类的定义，即涉及智能体的设计、协作和任务执行。` `AI监管` `隐私保护`

> ALU: Agentic LLM Unlearning

# 摘要

> # 摘要
在大型语言模型（LLMs）中，信息移除或抑制是一个备受期待的功能，尤其在AI监管、法律合规、安全和隐私领域。LLM遗忘方法旨在按需从LLMs中移除信息。然而，当前的LLM遗忘方法在平衡遗忘效果和模型效用方面面临挑战，因为这些目标往往相互冲突。在不依赖模型权重的情况下，保持遗忘过程的计算可行性是一个被忽视的领域。我们提出了首个智能体LLM遗忘（ALU）方法，这是一种多智能体、无需重新训练、模型无关的LLM遗忘方法，能够在保持模型效用的同时实现有效遗忘。ALU框架通过多个LLM智能体协同工作，每个智能体负责遗忘过程中的特定步骤，而无需更新任何智能体的模型权重。用户可以轻松请求任何序列的遗忘实例，ALU能够实时无缝适应，且无需对底层LLM模型进行任何更改。通过在TOFU、WMDP、WPU等基准和越狱技术（如多轮、目标掩码、其他语言）上的广泛实验，我们证明ALU在当前最先进的方法中始终是最稳健的LLM遗忘框架，同时保持低常数时间成本。我们进一步展示了ALU在大规模评估中的卓越性能，特别是在多达1000个遗忘目标上的评估，远超之前所有LLM遗忘方法的评估范围。

> Information removal or suppression in large language models (LLMs) is a desired functionality, useful in AI regulation, legal compliance, safety, and privacy. LLM unlearning methods aim to remove information on demand from LLMs. Current LLM unlearning methods struggle to balance the unlearning efficacy and utility due to the competing nature of these objectives. Keeping the unlearning process computationally feasible without assuming access to the model weights is an overlooked area. We present the first agentic LLM unlearning (ALU) method, a multi-agent, retrain-free, model-agnostic approach to LLM unlearning that achieves effective unlearning while preserving the utility. Our ALU framework unlearns by involving multiple LLM agents, each designed for a specific step in the unlearning process, without the need to update model weights for any of the agents in the framework. Users can easily request any set of unlearning instances in any sequence, and ALU seamlessly adapts in real time. This is facilitated without requiring any changes in the underlying LLM model. Through extensive experiments on established benchmarks (TOFU, WMDP, WPU) and jailbreaking techniques (many shot, target masking, other languages), we demonstrate that ALU consistently stands out as the most robust LLM unlearning framework among current state-of-the-art methods while incurring a low constant-time cost. We further highlight ALU's superior performance compared to existing methods when evaluated at scale. Specifically, ALU is assessed on up to 1000 unlearning targets, exceeding the evaluation scope of all previously proposed LLM unlearning methods.

[Arxiv](https://arxiv.org/abs/2502.00406)