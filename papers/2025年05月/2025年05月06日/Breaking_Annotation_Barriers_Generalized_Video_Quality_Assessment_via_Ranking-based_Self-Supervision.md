# 突破标注障碍：通过基于排序的自监督学习实现通用视频质量评估

发布时间：2025年05月06日

`其他` `视频处理` `机器学习`

> Breaking Annotation Barriers: Generalized Video Quality Assessment via Ranking-based Self-Supervision

# 摘要

> 视频质量评估（VQA）在从摄像头捕获到流媒体平台的各类视频处理工作中至关重要。尽管监督式VQA模型已取得显著进展，但人工标注数据集的高昂成本和难以扩展性限制了模型的泛化能力。为此，我们提出了一种基于大规模无标签视频的自监督学习框架。通过**学习排序范式**，我们利用现有VQA模型生成质量伪标签，并结合合成失真模拟进行相对质量排序，对视频对进行自动标注。更进一步，我们设计了**迭代自我改进策略**，使模型能够不断优化训练数据的标注质量。在比现有基准大10倍的 dataset 上训练后，我们的模型实现了：1）与监督模型相当或更优的零样本性能；2）在多样化视频内容和失真下的卓越分布外泛化能力；3）在人工标注数据集上的最先进水平。实验结果充分验证了我们的方法。数据集和代码即将公开，助力未来研究。

> Video quality assessment (VQA) is essential for quantifying perceptual quality in various video processing workflows, spanning from camera capture systems to over-the-top streaming platforms. While recent supervised VQA models have made substantial progress, the reliance on manually annotated datasets -- a process that is labor-intensive, costly, and difficult to scale up -- has hindered further optimization of their generalization to unseen video content and distortions. To bridge this gap, we introduce a self-supervised learning framework for VQA to learn quality assessment capabilities from large-scale, unlabeled web videos. Our approach leverages a \textbf{learning-to-rank} paradigm to train a large multimodal model (LMM) on video pairs automatically labeled via two manners, including quality pseudo-labeling by existing VQA models and relative quality ranking based on synthetic distortion simulations. Furthermore, we introduce a novel \textbf{iterative self-improvement training strategy}, where the trained model acts an improved annotator to iteratively refine the annotation quality of training data. By training on a dataset $10\times$ larger than the existing VQA benchmarks, our model: (1) achieves zero-shot performance on in-domain VQA benchmarks that matches or surpasses supervised models; (2) demonstrates superior out-of-distribution (OOD) generalization across diverse video content and distortions; and (3) sets a new state-of-the-art when fine-tuned on human-labeled datasets. Extensive experimental results validate the effectiveness of our self-supervised approach in training generalized VQA models. The datasets and code will be publicly released to facilitate future research.

[Arxiv](https://arxiv.org/abs/2505.03631)