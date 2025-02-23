# MomentSeeker：长视频时刻检索的全面基准与强劲基线

发布时间：2025年02月18日

`RAG` `视频处理` `视频分析`

> MomentSeeker: A Comprehensive Benchmark and A Strong Baseline For Moment Retrieval Within Long Videos

# 摘要

> 检索增强生成（RAG）在长视频理解领域展现出了巨大潜力。通过从长视频中提取关键片段，多模态大型语言模型（MLLMs）得以高效生成高质量回答。我们开发了MomentSeeker，一个全面的基准测试，专注于评估检索模型在长视频片段检索（LVMR）任务中的表现。MomentSeeker有三大优势：首先，它包含平均时长超过500秒的长视频，是首个专为长视频检索设计的基准。其次，涵盖片段搜索、字幕对齐等多任务类别，以及体育、电影等多样化场景，全面评估模型性能。最后，所有评估任务均通过人工标注，确保结果可靠。我们在合成数据上微调的MLLM检索器在基准测试中表现优异。通过与多种流行多模态检索器的对比实验，我们揭示了LVMR的挑战及现有方法的局限。我们的资源将开放共享，助力未来研究。

> Retrieval augmented generation (RAG) holds great promise in addressing challenges associated with long video understanding. These methods retrieve useful moments from long videos for their presented tasks, thereby enabling multimodal large language models (MLLMs) to generate high-quality answers in a cost-effective way. In this work, we present MomentSeeker, a comprehensive benchmark to evaluate retrieval models' performance in handling general long-video moment retrieval (LVMR) tasks. MomentSeeker offers three key advantages. First, it incorporates long videos of over 500 seconds on average, making it the first benchmark specialized for long-video moment retrieval. Second, it covers a wide range of task categories (including Moment Search, Caption Alignment, Image-conditioned Moment Search, and Video-conditioned Moment Search) and diverse application scenarios (e.g., sports, movies, cartoons, and ego), making it a comprehensive tool for assessing retrieval models' general LVMR performance. Additionally, the evaluation tasks are carefully curated through human annotation, ensuring the reliability of assessment. We further fine-tune an MLLM-based LVMR retriever on synthetic data, which demonstrates strong performance on our benchmark. We perform extensive experiments with various popular multimodal retrievers based on our benchmark, whose results highlight the challenges of LVMR and limitations for existing methods. Our created resources will be shared with community to advance future research in this field.

[Arxiv](https://arxiv.org/abs/2502.12558)