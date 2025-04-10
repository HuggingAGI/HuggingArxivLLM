# 精细雕琢子空间：LLMs中受限完全微调的持续学习探索

发布时间：2025年04月09日

`LLM理论` `机器学习` `人工智能`

> Sculpting Subspaces: Constrained Full Fine-Tuning in LLMs for Continual Learning

# 摘要

> 大规模语言模型中的持续学习面临灾难性遗忘的挑战，即模型在适应新任务时会严重遗忘旧任务。现有方法多采用低秩参数高效更新，但这种方式不仅限制了模型表达能力，还为每个任务引入额外参数，带来扩展性难题。为解决这些挑战，我们提出了一种基于自适应奇异值分解 (SVD) 的持续全微调新方法。该方法能够动态识别任务特定的低秩参数子空间，并将更新限制在与先前任务关键方向正交的空间中，从而有效减少任务间干扰，且无需额外参数或存储历史任务梯度。我们在标准持续学习基准上，使用 T5-Large 和 LLaMA-2 7B 等模型进行了广泛测试，涵盖分类、生成和推理等多种任务。实验结果显示，我们的方法达到当前最优水平，平均准确率较近期基线 (如 O-LoRA) 提升 7%，同时通过将遗忘降至几乎可忽略的水平，成功保持了模型在持续学习过程中的语言能力、指令遵循准确性和安全性。我们的自适应 SVD 框架实现了模型可塑性与知识保留的平衡，为大规模语言模型的持续学习提供了一种实用、理论坚实且计算高效的解决方案。

> Continual learning in large language models (LLMs) is prone to catastrophic forgetting, where adapting to new tasks significantly degrades performance on previously learned ones. Existing methods typically rely on low-rank, parameter-efficient updates that limit the model's expressivity and introduce additional parameters per task, leading to scalability issues. To address these limitations, we propose a novel continual full fine-tuning approach leveraging adaptive singular value decomposition (SVD). Our method dynamically identifies task-specific low-rank parameter subspaces and constrains updates to be orthogonal to critical directions associated with prior tasks, thus effectively minimizing interference without additional parameter overhead or storing previous task gradients. We evaluate our approach extensively on standard continual learning benchmarks using both encoder-decoder (T5-Large) and decoder-only (LLaMA-2 7B) models, spanning diverse tasks including classification, generation, and reasoning. Empirically, our method achieves state-of-the-art results, up to 7% higher average accuracy than recent baselines like O-LoRA, and notably maintains the model's general linguistic capabilities, instruction-following accuracy, and safety throughout the continual learning process by reducing forgetting to near-negligible levels. Our adaptive SVD framework effectively balances model plasticity and knowledge retention, providing a practical, theoretically grounded, and computationally scalable solution for continual learning scenarios in large language models.

[Arxiv](https://arxiv.org/abs/2504.07097)