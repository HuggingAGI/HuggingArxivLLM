# 本福特定律的诅咒：从数字偏差追溯LLM中的数值幻觉

发布时间：2025年06月02日

`LLM理论` `人工智能`

> Benford's Curse: Tracing Digit Bias to Numerical Hallucination in LLMs

# 摘要

> 大型语言模型 (LLMs) 虽然在复杂推理任务中表现出色，但在基本数值问题上却常常表现不佳，产生错误输出。受本福特定律的启发——该定律指出，较低的数字作为首位数字出现的频率更高——我们提出假设：网络收集语料库中的长尾数字分布可能在预训练过程中被 LLMs 学习，导致有偏的数值生成。为了验证这一假设，我们首先检查了预训练语料库 (OLMo2) 中的数字频率是否遵循本福特定律。随后，我们构建了一个评估基准，其中在七种数值推理任务中，真实数字分布是均匀的。评估结果表明，领先的开源 LLMs 显示出一致的数字偏差模式，类似于本福特定律。通过 logit-lens 追踪和神经元级别的分解，我们发现这种偏差主要源于较深层中一小部分高度选择性处理数字的前馈网络 (FFN) 神经元。最后，我们证明剪除这些神经元可以缓解不平衡的过度生成，并部分纠正错误输出，提供了细粒度预训练数字偏差可以传播到模型行为的因果证据。我们的研究揭示了语料库级别统计与 LLMs 符号失败模式之间的基本联系，为诊断和缓解数值任务中的幻觉现象提供了新的视角。


> Large Language Models (LLMs) exhibit impressive performance on complex reasoning tasks, yet they frequently fail on basic numerical problems, producing incorrect outputs. Inspired by Benford's Law -- a statistical pattern where lower digits occur more frequently as leading digits -- we hypothesize that the long-tailed digit distributions in web-collected corpora may be learned by LLMs during pretraining, leading to biased numerical generation. To investigate the hypothesis, we first examine whether digits frequencies in pretraining corpus (OLMo2) follows Benford's law. We then construct an evaluation benchmark with uniformly distributed ground-truth digits across seven numerical reasoning tasks. Our evaluation results demonstrate that leading open-source LLMs show a consistent pattern of digit bias that resembles Benford's law. Through logit-lens tracing and neuron-level dissection, we identify that this bias arises predominantly from a small subset of highly digit-selective feed-forward network (FFN) neurons in the deeper layers. Finally, we demonstrate that pruning these neurons mitigates imbalanced overgeneration and partially corrects erroneous outputs, providing causal evidence that fine-grained pretraining digit bias can propagate into model behavior. Our findings reveal a fundamental connection between corpus-level statistics and symbolic failure modes in LLMs, offering a new lens for diagnosing and mitigating hallucinations in numerical tasks.

[Arxiv](https://arxiv.org/abs/2506.01734)