# # 标题
基于大型多模态模型实现视频质量评分与理由生成的统一

发布时间：2025年06月26日

`LLM应用` `视频处理` `计算机视觉`

> Bridging Video Quality Scoring and Justification via Large Multimodal Models

# 摘要

> 传统的视频质量评估（VQA）方法通过生成数值分数来衡量视频的视觉保真度和清晰度。然而，单一的分数无法全面描述视频的多维质量特性，限制了其应用范围。得益于语言输出的优势，通过指令微调将视频大模态模型（LMMs）应用于VQA，有望解决这一问题。这种方法的核心在于以视频质量为中心的指令数据。然而，之前的探索主要集中在图像领域，且其数据生成过程严重依赖人工标注和专有系统，这限制了数据的扩展性和有效性。为了解决这些挑战，我们提出了基于评分的指令生成（SIG）管道。具体来说，SIG首先为无标签视频的多个质量维度打分，并将分数映射到文本定义的级别。然后，它明确地引入了一种分层的链式思考（CoT）方法，以建模特定维度与整体质量之间的相关性，模拟人类视觉系统推理过程。这种自动化的管道消除了对专家编写质量描述和专有系统的依赖，确保了数据的扩展性和生成效率。为此，生成的Score2Instruct（S2I）数据集包含超过32万条多样化的指令-响应对，为指令微调奠定了基础。此外，为了同时提升视频LMMs的质量评分和解释能力，我们设计了一种渐进式微调策略，充分释放S2I的潜力。基于SIG，我们进一步整理了一个基准测试集S2I-Bench，包含400个开放性问题，以更好地评估视频LMMs的质量解释能力。实验结果表明，我们的方法在多个视频LMMs上显著提升了质量评分和解释能力。

> Classical video quality assessment (VQA) methods generate a numerical score to judge a video's perceived visual fidelity and clarity. Yet, a score fails to describe the video's complex quality dimensions, restricting its applicability. Benefiting from the linguistic output, adapting video large multimodal models (LMMs) to VQA via instruction tuning has the potential to address this issue. The core of the approach lies in the video quality-centric instruction data. Previous explorations mainly focus on the image domain, and their data generation processes heavily rely on human quality annotations and proprietary systems, limiting data scalability and effectiveness. To address these challenges, we propose the Score-based Instruction Generation (SIG) pipeline. Specifically, SIG first scores multiple quality dimensions of an unlabeled video and maps scores to text-defined levels. It then explicitly incorporates a hierarchical Chain-of-Thought (CoT) to model the correlation between specific dimensions and overall quality, mimicking the human visual system's reasoning process. The automated pipeline eliminates the reliance on expert-written quality descriptions and proprietary systems, ensuring data scalability and generation efficiency. To this end, the resulting Score2Instruct (S2I) dataset contains over 320K diverse instruction-response pairs, laying the basis for instruction tuning. Moreover, to advance video LMMs' quality scoring and justification abilities simultaneously, we devise a progressive tuning strategy to fully unleash the power of S2I. Built upon SIG, we further curate a benchmark termed S2I-Bench with 400 open-ended questions to better evaluate the quality justification capacity of video LMMs. Experimental results on the S2I-Bench and existing benchmarks indicate that our method consistently improves quality scoring and justification capabilities across multiple video LMMs.

[Arxiv](https://arxiv.org/abs/2506.21011)