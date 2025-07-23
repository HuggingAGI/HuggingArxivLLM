# 斑马-CoT：专为交织视觉语言推理设计的数据集

发布时间：2025年07月22日

`LLM应用` `视觉推理` `多模态模型`

> Zebra-CoT: A Dataset for Interleaved Vision Language Reasoning

# 摘要

> 人类在解决复杂问题时常常借助视觉辅助工具，如图表或草图。然而，训练多模态模型实现视觉链式推理（Visual CoT）面临两大挑战：(1) 现有视觉 CoT 性能不足，阻碍了强化学习的进展；(2) 高质量的视觉 CoT 训练数据稀缺。为此，我们推出了多样化大规模数据集 $	extbf{Zebra-CoT}$，包含 182,384 个样本，囊括逻辑连贯的交错文本-图像推理轨迹。我们专注于四个任务类别，这些任务中绘图或视觉推理尤其自然，涵盖科学问题（如几何、物理和算法）、2D 视觉推理任务（如视觉搜索和拼图）、3D 推理任务（包括 3D 多跳推理、具身推理和机器人规划）以及视觉逻辑问题和策略类游戏（如国际象棋）。在 Zebra-CoT 训练语料库上微调 Anole-7B 模型，使测试集准确率提升了 +12%，并在标准 VLM 基准评估中获得了高达 +13% 的性能提升。微调 Bagel-7B 模型生成高质量的交错视觉推理链，进一步凸显了 Zebra-CoT 在开发多模态推理能力方面的有效性。我们开源了数据集和模型，以支持视觉 CoT 的开发和评估。

> Humans often use visual aids, for example diagrams or sketches, when solving complex problems. Training multimodal models to do the same, known as Visual Chain of Thought (Visual CoT), is challenging due to: (1) poor off-the-shelf visual CoT performance, which hinders reinforcement learning, and (2) the lack of high-quality visual CoT training data. We introduce $\textbf{Zebra-CoT}$, a diverse large-scale dataset with 182,384 samples, containing logically coherent interleaved text-image reasoning traces. We focus on four categories of tasks where sketching or visual reasoning is especially natural, spanning scientific questions such as geometry, physics, and algorithms; 2D visual reasoning tasks like visual search and jigsaw puzzles; 3D reasoning tasks including 3D multi-hop inference, embodied and robot planning; visual logic problems and strategic games like chess. Fine-tuning the Anole-7B model on the Zebra-CoT training corpus results in an improvement of +12% in our test-set accuracy and yields up to +13% performance gain on standard VLM benchmark evaluations. Fine-tuning Bagel-7B yields a model that generates high-quality interleaved visual reasoning chains, underscoring Zebra-CoT's effectiveness for developing multimodal reasoning abilities. We open-source our dataset and models to support development and evaluation of visual CoT.

[Arxiv](https://arxiv.org/abs/2507.16746)