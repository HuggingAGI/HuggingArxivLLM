# BMMR：大规模双语多模态跨学科推理数据集

发布时间：2025年07月04日

`LLM应用`

> BMMR: A Large-Scale Bilingual Multimodal Multi-Discipline Reasoning Dataset

# 摘要

> 本文介绍了 BMMR，一个助力社区开发和评估大型多模态模型（LMMs）的大规模双语、多模态、跨学科推理数据集。BMMR 包含 110,000 个大学水平的问题，覆盖 300 个联合国教科文组织定义的学科，涵盖选择题、填空题和开放问答等多种格式，数据来源包括书籍、考试和测验等印刷及数字媒体。所有数据均通过人工参与的可扩展框架整理筛选，每个实例都配有高质量推理路径。该数据集分为两部分：BMMR-Eval 包含 20,458 个高质量实例，用于全面评估 LMMs 在中英双语环境下的跨学科知识和推理能力；BMMR-Train 包含 88,991 个实例，支持进一步研究和开发，将当前对数学推理的关注扩展到多样化的学科和领域。此外，我们提出了基于过程的跨学科验证器（BMMR-Verifier），用于对推理路径进行精确细致的评估。在 24 个模型上的广泛实验揭示：(i) 即使是最先进的模型（如 o3 和 Gemini-2.5-Pro）在 BMMR-Eval 上仍有显著提升空间；(ii) 推理模型存在学科偏见，在特定学科上仅优于 LMMs；(iii) 开源模型仍落后于专有模型；(iv) 在 BMMR-Train 上进行微调可有效缩小这一差距。此外，我们利用 BMMR-Verifier 和其他深入研究对推理链进行了分析，揭示了 LMMs 在跨学科推理方面当前面临的挑战。我们将发布该数据集，并希望我们的工作能为社区提供有价值的见解和贡献。

> In this paper, we introduce BMMR, a large-scale bilingual, multimodal, multi-disciplinary reasoning dataset for the community to develop and evaluate large multimodal models (LMMs). BMMR comprises 110k college-level questions spanning 300 UNESCO-defined subjects, spanning diverse formats-multiple-choice, fill-in-the-blank, and open-ended QA-and sourced from both print and digital media such as books, exams, and quizzes. All data are curated and filtered via a human-in-the-loop and scalable framework, and each instance is paired with a high-quality reasoning path. The dataset is organized into two parts: BMMR-Eval that comprises 20,458 high-quality instances to comprehensively assess LMMs' knowledge and reasoning across multiple disciplines in both Chinese and English; and BMMR-Train that contains 88,991 instances to support further research and development, extending the current focus on mathematical reasoning to diverse disciplines and domains. In addition, we propose the process-based multi-discipline verifier (i.e., BMMR-Verifier) for accurate and fine-grained evaluation of reasoning paths. Extensive experiments on 24 models reveal that (i) even SOTA models (e.g., o3 and Gemini-2.5-Pro) leave substantial headroom on BMMR-Eval; (ii) reasoning models exhibit discipline bias and outperform LMMs only on specific subjects; (iii) open-source models still trail their proprietary counterparts; and (iv) fine-tuning on BMMR-Train narrows this gap. Additionally, we conduct reasoning-chain analyses using BMMR-Verifier and other in-depth studies, uncovering the challenges LMMs currently face in multidisciplinary reasoning. We will release the data, and we hope our work can offer insights and contributions to the community.

[Arxiv](https://arxiv.org/abs/2507.03483)