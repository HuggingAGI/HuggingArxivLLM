# AlphaAdam: 动态Alpha驱动的异步掩码优化，实现选择性更新

发布时间：2025年01月29日

`LLM理论

理由：这篇论文主要讨论了大型语言模型（LLMs）训练中的参数更新问题，提出了一种新的优化框架AlphaAdam，旨在提高训练效率和稳定性。论文的核心内容涉及LLM的训练优化方法，属于对LLM理论的研究和改进，因此应归类为LLM理论。` `人工智能` `机器学习`

> AlphaAdam:Asynchronous Masked Optimization with Dynamic Alpha for Selective Updates

# 摘要

> 在大型语言模型（LLMs）的训练中，如何更高效、稳定地更新参数一直是个难题。现有方法通常通过低维分解或分层选择性更新等手段，实现与全参数更新相当的效果。本文提出AlphaAdam，一个从层内参数更新角度出发的LLM优化框架。通过解耦参数更新并动态调整其强度，AlphaAdam不仅加速了收敛，还提升了训练稳定性。我们基于历史动量和梯度方向的一致性构建参数掩码，并结合自适应掩码强度策略，确保高效优化和理论收敛保证，这一方法同样适用于大多数基于动量的优化器。实验表明，AlphaAdam在收敛速度和计算效率上均优于AdamW等现有方法，适用于GPT-2预训练、RoBERTa微调以及Llama-7B等任务。AlphaAdam通过层内异步掩码自适应更新，为LLM提供了优化器增强框架。代码已开源，详见\href{https://github.com/MaeChd/AlphaAdam}{此链接}。

> In the training of large language models (LLMs), updating parameters more efficiently and stably has always been an important challenge. To achieve efficient parameter updates, existing methods usually achieve performance comparable to full parameter updates through methods such as low-dimensional decomposition or layer-wise selective updates. In this work, we propose AlphaAdam, an optimization framework for LLM from the perspective of intra-layer parameter updates. By decoupling parameter updates and dynamically adjusting their strength, AlphaAdam accelerates convergence and improves training stability. We construct parameter masks based on the consistency of historical momentum and gradient direction and combine them with an adaptive mask strength strategy to ensure efficient optimization and theoretical convergence guarantees, which is also applicable to most momentum-based optimizers. Extensive experiments show that AlphaAdam outperforms state-of-the-art methods such as AdamW in terms of convergence speed and computational efficiency across tasks, including GPT-2 pre-trained and fine-tuned RoBERTa and Llama-7B. Our AlphaAdam implements an optimizer enhancement framework for LLMs through intra-layer asynchronous masked adaptive updates. Our code is available in this \href{https://github.com/MaeChd/AlphaAdam}{link}

[Arxiv](https://arxiv.org/abs/2501.18094)