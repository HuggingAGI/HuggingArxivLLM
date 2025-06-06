# ReXVQA: 面向胸部X光片通用理解能力的大规模视觉问答基准测试

发布时间：2025年06月04日

`LLM应用` `医学影像分析`

> ReXVQA: A Large-scale Visual Question Answering Benchmark for Generalist Chest X-ray Understanding

# 摘要

> 我们推出了ReXVQA，这是目前规模最大、内容最全面的胸部放射学视觉问答（VQA）基准测试，包含约69.6万个问题，与16万张胸部X光片研究配对，覆盖训练集、验证集和测试集。与传统依赖模板查询的方法不同，ReXVQA引入了一个多样化且临床真实的任务套件，涵盖了五个核心放射学推理技能：存在性评估、位置分析、否定检测、鉴别诊断和几何推理。我们评估了八种顶尖的多模态大型语言模型，包括MedGemma-4B-it、Qwen2.5-VL、Janus-Pro-7B和Eagle2-9B。其中表现最佳的模型MedGemma达到了83.24%的整体准确率。为了弥合AI性能与临床专业知识之间的差距，我们开展了一项全面的读者研究，邀请了3位放射科住院医生对200个随机抽取的案例进行分析。研究结果表明，MedGemma的表现优于人类读者（最佳放射科住院医生的准确率为77.27%），准确率达到83.84%，标志着AI在胸部X光片解读方面超越了专家人类评估水平，这是一个重要的里程碑。读者研究揭示了AI模型与人类专家之间在性能模式上的显著差异，尽管放射科医生之间的读者一致性较强，但人类读者与AI模型之间的一致性模式更为多样。ReXVQA为评估通用型放射学AI系统树立了新的标准，提供了公开排行榜、细粒度评估划分、结构化解释和类别级细分。这一基准为下一代AI系统奠定了基础，这些系统能够模拟超越狭窄病理分类的专家级临床推理。我们的数据集将在https://huggingface.co/datasets/rajpurkarlab/ReXVQA开源。

> We present ReXVQA, the largest and most comprehensive benchmark for visual question answering (VQA) in chest radiology, comprising approximately 696,000 questions paired with 160,000 chest X-rays studies across training, validation, and test sets. Unlike prior efforts that rely heavily on template based queries, ReXVQA introduces a diverse and clinically authentic task suite reflecting five core radiological reasoning skills: presence assessment, location analysis, negation detection, differential diagnosis, and geometric reasoning. We evaluate eight state-of-the-art multimodal large language models, including MedGemma-4B-it, Qwen2.5-VL, Janus-Pro-7B, and Eagle2-9B. The best-performing model (MedGemma) achieves 83.24% overall accuracy. To bridge the gap between AI performance and clinical expertise, we conducted a comprehensive human reader study involving 3 radiology residents on 200 randomly sampled cases. Our evaluation demonstrates that MedGemma achieved superior performance (83.84% accuracy) compared to human readers (best radiology resident: 77.27%), representing a significant milestone where AI performance exceeds expert human evaluation on chest X-ray interpretation. The reader study reveals distinct performance patterns between AI models and human experts, with strong inter-reader agreement among radiologists while showing more variable agreement patterns between human readers and AI models. ReXVQA establishes a new standard for evaluating generalist radiological AI systems, offering public leaderboards, fine-grained evaluation splits, structured explanations, and category-level breakdowns. This benchmark lays the foundation for next-generation AI systems capable of mimicking expert-level clinical reasoning beyond narrow pathology classification. Our dataset will be open-sourced at https://huggingface.co/datasets/rajpurkarlab/ReXVQA

[Arxiv](https://arxiv.org/abs/2506.04353)