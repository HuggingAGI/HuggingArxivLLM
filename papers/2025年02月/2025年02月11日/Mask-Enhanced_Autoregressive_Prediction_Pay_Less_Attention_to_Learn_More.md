# 增强式掩码自回归预测：以更少的注意力，学习更多

发布时间：2025年02月11日

`LLM理论` `信息检索`

> Mask-Enhanced Autoregressive Prediction: Pay Less Attention to Learn More

# 摘要

> 大型语言模型 (LLMs) 在准确检索关键信息方面存在不足。为了解决这一问题，我们提出了一种简单而有效的训练范式——掩码增强自回归预测 (MEAP)，它通过将掩码语言建模 (MLM) 自然地整合到下一个令牌预测 (NTP) 中，从而增强后者的上下文检索能力。具体而言，MEAP 首先随机屏蔽输入令牌中的一小部分，然后直接使用仅解码器的 Transformer 进行标准的自回归式下一个令牌预测。MEAP 消除了在 MLM 中使用双向注意力或编解码器架构的需要，在预训练或推理过程中不产生额外的计算开销。大量实验表明，MEAP 在关键信息检索和长上下文推理任务中显著优于 NTP，同时在常识推理任务中表现持平或更优。MEAP 的优势还延伸到监督微调领域，在处理中间信息丢失的场景时表现出显著优势，比 NTP 高出 11.77 个百分点。我们的分析表明，MEAP 的有效性源于其通过专注于少量非屏蔽令牌来促进更具区分度的注意力分数的能力。这种机制增强了模型对任务相关信号的关注，同时减轻了外围上下文的影响。这些发现使 MEAP 成为大型语言模型的一种有前景的训练范式。

> Large Language Models (LLMs) are discovered to suffer from accurately retrieving key information. To address this, we propose Mask-Enhanced Autoregressive Prediction (MEAP), a simple yet effective training paradigm that seamlessly integrates Masked Language Modeling (MLM) into Next-Token Prediction (NTP) to enhance the latter's in-context retrieval capabilities. Specifically, MEAP first randomly masks a small fraction of input tokens and then directly performs the standard next-token prediction autoregressive using a decoder-only Transformer. MEAP eliminates the need for bidirectional attention or encoder-decoder architectures for MLM, incurring no additional computational overhead during pre-training or inference. Intensive experiments demonstrate that MEAP substantially outperforms NTP on key information retrieval and long-context reasoning tasks, while performing on par or better on commonsense reasoning tasks. The benefits of MEAP also extend to supervised fine-tuning, where it shows remarkable advantages in lost-in-the-middle scenarios, outperforming NTP by 11.77 percentage points. Our analysis indicates that MEAP's effectiveness arises from its ability to promote more distinguishable attention scores by concentrating on a reduced set of non-masked tokens. This mechanism improves the model's focus on task-relevant signals while mitigating the influence of peripheral context. These findings position MEAP as a promising training paradigm for large language models.

[Arxiv](https://arxiv.org/abs/2502.07490)