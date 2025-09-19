# 可泛化的几何图像描述生成

发布时间：2025年09月18日

`强化学习` `教育科技`

> Generalizable Geometric Image Caption Synthesis

# 摘要

> 多模态大型语言模型在众多实际应用中展现出巨大潜力，而这些应用无一不依赖强大的推理能力。然而，尽管近年来技术突飞猛进，这类模型在攻克复杂几何问题时仍显得力不从心。核心瓶颈在于：理解几何图像所需的高质量图文对数据集极度匮乏；同时，多数基于模板的数据合成流程往往"画地为牢"，难以泛化到预定义模板之外的问题。为此，本文提出在数据生成流程中引入带可验证奖励的强化学习（RLVR）作为补充环节，以弥合这一差距。具体而言，我们从50种基本几何关系出发合成几何图像，再借助RLVR优化这些图像的描述文本——优化过程中，奖励信号源自数学解题任务。这套流程成功捕捉到了几何解题的关键特征，不仅有效提升了任务泛化能力，更带来了显著性能突破。值得注意的是，即便在分布外场景下，生成的数据集依旧能增强多模态大型语言模型的通用推理能力：在MathVista与MathVerse的非几何图像任务中，统计、算术、代数及数值类题目的准确率提升【数学公式】；在MMMU的艺术、设计、技术及工程类任务中，准确率亦提升【数学公式】。

> Multimodal large language models have various practical applications that demand strong reasoning abilities. Despite recent advancements, these models still struggle to solve complex geometric problems. A key challenge stems from the lack of high-quality image-text pair datasets for understanding geometric images. Furthermore, most template-based data synthesis pipelines typically fail to generalize to questions beyond their predefined templates. In this paper, we bridge this gap by introducing a complementary process of Reinforcement Learning with Verifiable Rewards (RLVR) into the data generation pipeline. By adopting RLVR to refine captions for geometric images synthesized from 50 basic geometric relations and using reward signals derived from mathematical problem-solving tasks, our pipeline successfully captures the key features of geometry problem-solving. This enables better task generalization and yields non-trivial improvements. Furthermore, even in out-of-distribution scenarios, the generated dataset enhances the general reasoning capabilities of multimodal large language models, yielding accuracy improvements of $2.8\%\text{-}4.8\%$ in statistics, arithmetic, algebraic, and numerical tasks with non-geometric input images of MathVista and MathVerse, along with $2.4\%\text{-}3.9\%$ improvements in Art, Design, Tech, and Engineering tasks in MMMU.

[Arxiv](https://arxiv.org/abs/2509.15217)