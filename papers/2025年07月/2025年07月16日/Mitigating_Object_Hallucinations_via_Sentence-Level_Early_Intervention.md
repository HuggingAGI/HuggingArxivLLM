# # 缓解对象幻觉：通过句子级别的早期干预
通过在句子级别实施早期干预措施，我们有效缓解了对象幻觉问题。

发布时间：2025年07月16日

`LLM应用` `多模态` `生成内容`

> Mitigating Object Hallucinations via Sentence-Level Early Intervention

# 摘要

> 多模态大型语言模型（MLLMs）引领了一场跨模态理解的革命，但生成与视觉输入不符的幻觉内容仍是其痛点。现有方法要么计算成本过高，要么导致数据分布错配。我们发现，幻觉主要在文本生成的早期阶段萌芽，并随输出传播。为此，我们提出了**SENTINEL**（**S**entence-level **E**arly i**N**tervention **T**hrough **IN**-domain pr**E**ference **L**earning），一个无需人工标注的创新框架。具体而言，我们通过迭代采样模型输出、利用双开放词汇检测器交叉验证物体存在性，并将句子分类为幻觉或非幻觉类别，从而生成高质量的领域内偏好对。随后，我们使用上下文一致的正样本和幻觉负样本，逐步构建上下文感知的偏好数据。最后，采用上下文感知偏好损失（C-DPO）训练模型，重点强化幻觉最初显现的句子级别的判别学习。实验结果表明，SENTINEL相较于原始模型，幻觉减少幅度超90%，并在幻觉基准和通用能力基准上均超越现有最优方法，充分展现了其优越性能和泛化能力。模型、数据集及代码已开源，地址为https://github.com/pspdada/SENTINEL。

> Multimodal large language models (MLLMs) have revolutionized cross-modal understanding but continue to struggle with hallucinations - fabricated content contradicting visual inputs. Existing hallucination mitigation methods either incur prohibitive computational costs or introduce distribution mismatches between training data and model outputs. We identify a critical insight: hallucinations predominantly emerge at the early stages of text generation and propagate through subsequent outputs. To address this, we propose **SENTINEL** (**S**entence-level **E**arly i**N**tervention **T**hrough **IN**-domain pr**E**ference **L**earning), a framework that eliminates dependency on human annotations. Specifically, we first bootstrap high-quality in-domain preference pairs by iteratively sampling model outputs, validating object existence through cross-checking with two open-vocabulary detectors, and classifying sentences into hallucinated/non-hallucinated categories. Subsequently, we use context-coherent positive samples and hallucinated negative samples to build context-aware preference data iteratively. Finally, we train models using a context-aware preference loss (C-DPO) that emphasizes discriminative learning at the sentence level where hallucinations initially manifest. Experimental results show that SENTINEL can reduce hallucinations by over 90\% compared to the original model and outperforms the previous state-of-the-art method on both hallucination benchmarks and general capabilities benchmarks, demonstrating its superiority and generalization ability. The models, datasets, and code are available at https://github.com/pspdada/SENTINEL.

[Arxiv](https://arxiv.org/abs/2507.12455)