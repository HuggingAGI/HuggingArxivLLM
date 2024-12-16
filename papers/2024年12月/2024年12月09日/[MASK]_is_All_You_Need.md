# [MASK] 乃你所需的全部

发布时间：2024年12月09日

`其他` `生成模型`

> [MASK] is All You Need

# 摘要

> 摘要：在生成模型领域，有两种范式在各类应用中备受瞩目：基于下一组预测的掩码生成模型，以及基于下一个噪声预测的非自回归模型，比如扩散模型。在本研究中，我们提议运用离散状态模型将它们关联起来，并探究其在视觉领域的可扩展性。首先，我们在统一的设计空间中对这两类模型展开逐步分析，涵盖时间步独立性、噪声调度、温度、引导强度等，以可扩展的方式进行。其次，我们把典型的判别任务，比如图像分割，重新定义为在离散状态模型上从[MASK]标记的解掩码过程。这让我们能够开展各种采样流程，包括仅训练一次来对联合分布进行建模的灵活条件采样。上述所有探索促成了我们名为离散插值的框架，在诸如 ImageNet256、MS COCO 和视频数据集 FaceForensics 等各类基准中，与以往基于离散状态的方法相比，能让我们取得最先进或具竞争力的性能。总之，借助离散状态模型中的[MASK]，我们能够架起掩码生成与非自回归扩散模型之间的桥梁，以及生成任务与判别任务之间的桥梁。

> 
Abstract:In generative models, two paradigms have gained attraction in various applications: next-set prediction-based Masked Generative Models and next-noise prediction-based Non-Autoregressive Models, e.g., Diffusion Models. In this work, we propose using discrete-state models to connect them and explore their scalability in the vision domain. First, we conduct a step-by-step analysis in a unified design space across two types of models including timestep-independence, noise schedule, temperature, guidance strength, etc in a scalable manner. Second, we re-cast typical discriminative tasks, e.g., image segmentation, as an unmasking process from [MASK] tokens on a discrete-state model. This enables us to perform various sampling processes, including flexible conditional sampling by only training once to model the joint distribution. All aforementioned explorations lead to our framework named Discrete Interpolants, which enables us to achieve state-of-the-art or competitive performance compared to previous discrete-state based methods in various benchmarks, like ImageNet256, MS COCO, and video dataset FaceForensics. In summary, by leveraging [MASK] in discrete-state models, we can bridge Masked Generative and Non-autoregressive Diffusion models, as well as generative and discriminative tasks.
    

[Arxiv](https://arxiv.org/pdf/2412.06787)