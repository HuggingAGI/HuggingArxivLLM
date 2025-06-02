# 大规模多模态模型面对动态知识的挑战与路径

发布时间：2025年05月30日

`LLM理论` `人工智能` `机器学习`

> When Large Multimodal Models Confront Evolving Knowledge:Challenges and Pathways

# 摘要

> 大型语言/多模态模型（LLMs/LMMs）存储了丰富的预训练知识，但在保持与现实世界更新同步时面临挑战，导致在获取动态知识时难以避免灾难性遗忘。此前研究主要集中在构建文本知识数据集和探索LLMs中的知识注入，而对LMMs中多模态动态知识注入的探索尚属空白。为此，我们提出了EVOKE基准，用于评估LMMs在现实场景中注入多模态动态知识的能力。同时，我们发现多模态动态知识注入面临两大挑战：（1）现有方法在动态知识上表现极差。（2）监督微调导致灾难性遗忘，尤其是指令遵循能力严重受损。此外，我们发现：（1）训练阶段的文本知识增强有助于提升性能，而图像增强则不然。（2）Replay和MoELoRA等持续学习方法能有效缓解遗忘。这些发现表明，现有知识注入方法在动态知识上存在诸多局限，亟需更高效稳定的注入方法。

> Large language/multimodal models (LLMs/LMMs) store extensive pre-trained knowledge but struggle to maintain consistency with real-world updates, making it difficult to avoid catastrophic forgetting while acquiring evolving knowledge. Previous work focused on constructing textual knowledge datasets and exploring knowledge injection in LLMs, lacking exploration of multimodal evolving knowledge injection in LMMs. To address this, we propose the EVOKE benchmark to evaluate LMMs' ability to inject multimodal evolving knowledge in real-world scenarios. Meanwhile, a comprehensive evaluation of multimodal evolving knowledge injection revealed two challenges: (1) Existing knowledge injection methods perform terribly on evolving knowledge. (2) Supervised fine-tuning causes catastrophic forgetting, particularly instruction following ability is severely compromised. Additionally, we provide pathways and find that: (1) Text knowledge augmentation during the training phase improves performance, while image augmentation cannot achieve it. (2) Continual learning methods, especially Replay and MoELoRA, effectively mitigate forgetting. Our findings indicate that current knowledge injection methods have many limitations on evolving knowledge, which motivates further research on more efficient and stable knowledge injection methods.

[Arxiv](https://arxiv.org/abs/2505.24449)