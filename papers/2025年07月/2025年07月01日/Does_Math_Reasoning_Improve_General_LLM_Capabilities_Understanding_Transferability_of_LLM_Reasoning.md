# 数学推理能否提升通用LLM能力？理解LLM推理的迁移性

发布时间：2025年07月01日

`LLM应用

理由：这篇论文探讨了大型语言模型在数学推理方面的进展及其在跨领域任务中的应用表现。研究者评估了多个模型在不同任务上的表现，并分析了不同调整方法对模型跨领域能力的影响。虽然涉及模型调整方法，但主要关注点在于模型在实际任务中的应用效果，因此归类为LLM应用。` `数学推理` `跨领域应用`

> Does Math Reasoning Improve General LLM Capabilities? Understanding Transferability of LLM Reasoning

# 摘要

> 数学推理已成为大型语言模型（LLMs）进步的标志，新模型迅速在MATH和AIME等基准测试中超越人类水平。然而，随着数学排行榜每周都在提升，值得思考的是：这些进步反映了更广泛的问题解决能力，还是仅仅是狭窄的过拟合？为了回答这个问题，我们评估了20多个公开权重的推理调整模型在一系列任务上的表现，包括数学、科学问答、代理规划、编码和标准指令遵循。我们惊讶地发现，大多数在数学上成功的模型未能将其优势转移到其他领域。为了严格研究这一现象，我们在Qwen3-14B模型上进行了控制实验，使用仅数学数据但不同的调整方法。我们发现，强化学习（RL）调整的模型在跨领域中表现良好，而监督微调（SFT）调整的模型常常忘记一般能力。潜在空间表示和令牌空间分布偏移分析表明，SFT诱导了显著的表示和输出漂移，而RL保留了通用领域结构。我们的结果表明，需要重新考虑标准的后训练配方，特别是依赖SFT蒸馏数据来推进推理模型的必要性。

> Math reasoning has become the poster child of progress in large language models (LLMs), with new models rapidly surpassing human-level performance on benchmarks like MATH and AIME. But as math leaderboards improve week by week, it is worth asking: do these gains reflect broader problem-solving ability or just narrow overfitting? To answer this question, we evaluate over 20 open-weight reasoning-tuned models across a broad suite of tasks, including math, scientific QA, agent planning, coding, and standard instruction-following. We surprisingly find that most models that succeed in math fail to transfer their gains to other domains. To rigorously study this phenomenon, we conduct controlled experiments on Qwen3-14B models using math-only data but different tuning methods. We find that reinforcement learning (RL)-tuned models generalize well across domains, while supervised fine-tuning (SFT)-tuned models often forget general capabilities. Latent-space representation and token-space distribution shift analyses reveal that SFT induces substantial representation and output drift, while RL preserves general-domain structure. Our results suggest a need to rethink standard post-training recipes, particularly the reliance on SFT-distilled data for advancing reasoning models.

[Arxiv](https://arxiv.org/abs/2507.00432)