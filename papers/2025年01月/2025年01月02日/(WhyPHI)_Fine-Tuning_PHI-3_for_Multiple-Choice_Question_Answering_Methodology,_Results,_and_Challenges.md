# (WhyPHI) 微调 PHI-3 用于多项选择题回答：方法、结果与挑战

发布时间：2025年01月02日

`LLM应用

理由：这篇论文主要探讨了大型语言模型（LLMs）在教育领域的应用，特别是如何通过微调和优化提示来提升模型在多项选择题（MCQs）任务中的表现。研究聚焦于模型的实际应用和性能提升，属于LLM在特定领域（教育）中的应用研究，因此分类为LLM应用。` `自适应学习`

> (WhyPHI) Fine-Tuning PHI-3 for Multiple-Choice Question Answering: Methodology, Results, and Challenges

# 摘要

> 大型语言模型（LLMs）凭借其强大的文本理解和生成能力，已成为多领域的核心工具。在教育领域，准确回答多项选择题（MCQs）的能力尤为重要，尤其是在自动化辅导和评估系统中。然而，由于模型幻觉和提示不清晰，LLMs在处理MCQ任务时仍面临挑战。本研究探索了微软PHI-3\cite{Abdin2024}（一款紧凑高效的LLM）在MCQ回答中的潜力。我们通过在TruthfulQA数据集上微调模型、设计优化提示提升性能，并使用困惑度和传统指标（如准确率、F1分数）进行评估。结果显示，微调后PHI-3.5的MCQ处理能力显著提升，困惑度从4.68降至2.27，准确率从62\%跃升至90.8\%。这项研究凸显了高效模型在自适应学习和教育评估中的价值，为课堂中的广泛应用（如考试准备、学生反馈和个性化学习）奠定了基础。

> Large Language Models (LLMs) have become essential tools across various domains due to their impressive capabilities in understanding and generating human-like text. The ability to accurately answer multiple-choice questions (MCQs) holds significant value in education, particularly in automated tutoring systems and assessment platforms. However, adapting LLMs to handle MCQ tasks effectively remains challenging due to the hallucinations and unclear prompts. This work explores the potential of Microsoft's PHI-3\cite{Abdin2024}, a compact yet efficient LLM, for MCQ answering. Our contributions include fine-tuning the model on the TruthfulQA dataset, designing optimized prompts to enhance model performance, and evaluating using perplexity and traditional metrics like accuracy and F1 score. Results show a remarkable improvement in PHI-3.5's MCQ handling post-fine-tuning, with perplexity decreasing from 4.68 to 2.27, and accuracy rising from 62\% to 90.8\%. This research underlines the importance of efficient models in adaptive learning systems and educational assessments, paving the way for broader integration into the classroom, particularly in fields like test preparation, student feedback, and personalized learning.

[Arxiv](https://arxiv.org/abs/2501.01588)