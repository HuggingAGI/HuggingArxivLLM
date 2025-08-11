# 在语言模型训练过程中防范突发对齐问题的防护措施

发布时间：2025年08月08日

`LLM理论` `模型安全` `模型训练`

> In-Training Defenses against Emergent Misalignment in Language Models

# 摘要

> 微调使从业者能够将对齐的大型语言模型（LLMs）重新应用于新领域，但近期研究表明存在新兴对齐问题（EMA）。即使是针对特定领域的微调，也可能引发超出目标领域范围的有害行为。即使模型权重隐藏在微调API之后，这也使攻击者能够不经意间访问到一个广泛对齐不佳的模型，仅凭微调数据往往难以察觉这种问题。我们首次系统性地研究了针对EMA的在训练过程中的防护措施，这些措施对于通过API提供微调服务的供应商来说切实可行。我们研究了四种训练正则化干预方法：(i) 针对安全参考模型的KL散度正则化，(ii) 特征空间中的【数学公式】距离，(iii) 投影到安全子空间（SafeLoRA），以及(iv) 从通用指令微调数据集中引入少量安全训练样本的交错训练。首先，我们在四个恶意的、能引发EMA的任务上评估这些方法的新兴对齐效果。其次，我们评估这些方法对良性任务的影响。最后，我们讨论了新兴对齐问题研究中的开放性问题。

> Fine-tuning lets practitioners repurpose aligned large language models (LLMs) for new domains, yet recent work reveals emergent misalignment (EMA): Even a small, domain-specific fine-tune can induce harmful behaviors far outside the target domain. Even in the case where model weights are hidden behind a fine-tuning API, this gives attackers inadvertent access to a broadly misaligned model in a way that can be hard to detect from the fine-tuning data alone. We present the first systematic study of in-training safeguards against EMA that are practical for providers who expose fine-tuning via an API. We investigate four training regularization interventions: (i) KL-divergence regularization toward a safe reference model, (ii) $\ell_2$ distance in feature space, (iii) projecting onto a safe subspace (SafeLoRA), and (iv) interleaving of a small amount of safe training examples from a general instruct-tuning dataset. We first evaluate the methods' emergent misalignment effect across four malicious, EMA-inducing tasks. Second, we assess the methods' impacts on benign tasks. We conclude with a discussion of open questions in emergent misalignment research.

[Arxiv](https://arxiv.org/abs/2508.06249)