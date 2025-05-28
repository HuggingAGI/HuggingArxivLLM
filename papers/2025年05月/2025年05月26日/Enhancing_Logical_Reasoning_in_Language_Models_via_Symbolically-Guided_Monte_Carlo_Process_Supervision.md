# 《借助符号引导的蒙特卡洛过程监督方法提升语言模型逻辑推理能力》

发布时间：2025年05月26日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLMs）在数学和逻辑推理任务中的表现，并提出了一种结合符号推理的方法来提升其推理和泛化能力。论文的重点在于改进模型的理论基础和推理机制，而不是具体的LLM应用或RAG相关技术。因此，它属于LLM理论类别。` `逻辑推理`

> Enhancing Logical Reasoning in Language Models via Symbolically-Guided Monte Carlo Process Supervision

# 摘要

> 大型语言模型（LLMs）在数学和逻辑推理任务中表现优异，但研究发现其成功更多源于记忆而非真正的泛化能力。这些模型在面对内容变化时表现得尤为脆弱，缺乏支持其推理的强健符号抽象能力。为了提升可靠性，已有许多尝试将LLMs与符号方法结合，但现有方法因验证机制的开发难题而难以有效利用符号表示。本文提出了一种创新方法，通过生成符号推理轨迹，并借助基于蒙特卡洛估计自动调优的过程奖励模型筛选高质量轨迹。随后，我们利用这些轨迹进行微调，以提升逻辑推理和泛化能力。实验结果表明，该方法在FOLIO和LogicAsker等基准测试中显著提升了前沿和开源模型的性能。进一步的声明验证实验显示，基于符号推理轨迹的微调增强了跨领域泛化能力，这表明符号引导的过程监督可能在缓解记忆对LLM推理的影响方面具有重要价值。

> Large language models (LLMs) have shown promising performance in mathematical and logical reasoning benchmarks. However, recent studies have pointed to memorization, rather than generalization, as one of the leading causes for such performance. LLMs, in fact, are susceptible to content variations, demonstrating a lack of robust symbolic abstractions supporting their reasoning process. To improve reliability, many attempts have been made to combine LLMs with symbolic methods. Nevertheless, existing approaches fail to effectively leverage symbolic representations due to the challenges involved in developing reliable and scalable verification mechanisms. In this paper, we propose to overcome such limitations by generating symbolic reasoning trajectories and select the high-quality ones using a process reward model automatically tuned based on Monte Carlo estimation. The trajectories are then employed via fine-tuning methods to improve logical reasoning and generalization. Our results on logical reasoning benchmarks such as FOLIO and LogicAsker show the effectiveness of the proposed method with large gains on frontier and open-weight models. Moreover, additional experiments on claim verification reveal that fine-tuning on the generated symbolic reasoning trajectories enhances out-of-domain generalizability, suggesting the potential impact of symbolically-guided process supervision in alleviating the effect of memorization on LLM reasoning.

[Arxiv](https://arxiv.org/abs/2505.20415)