# FAVOR-Bench：全面评估细粒度视频运动理解能力的基准测试

发布时间：2025年03月19日

`LLM应用` `视频理解` `人工智能`

> FAVOR-Bench: A Comprehensive Benchmark for Fine-Grained Video Motion Understanding

# 摘要

> 多模态大型语言模型（MLLMs）在视频内容理解方面表现优异，但在细粒度动作理解上仍有提升空间。为全面评估现有MLLMs的动作理解能力，我们开发了FAVOR-Bench基准测试，包含1,776个视频，均配有详细动作标注。该基准测试涵盖封闭式与开放式两类任务：封闭式评估设计了8,184个多选题问答对，覆盖六大子任务；开放式评估则采用创新的LLM-free低成本评估方法和GPT辅助字幕评估方法，前者提升了基准测试的可解释性和可重复性。通过对21个先进MLLMs的全面测试，我们发现现有模型在视频动作的细粒度时间动态理解和描述方面存在明显局限。为解决这一问题，我们构建了FAVOR-Train数据集，包含17,152个带有细粒度动作标注的视频。在FAVOR-Train上微调Qwen2.5-VL后，其在TVBench、MotionBench和FAVOR-Bench相关任务上的表现均有显著提升。全面评估结果表明，FAVOR-Bench和FAVOR-Train为开发更强大的视频理解模型提供了重要工具。项目页面：\href{https://favor-bench.github.io/}{https://favor-bench.github.io/}。

> Multimodal Large Language Models (MLLMs) have shown remarkable capabilities in video content understanding but still struggle with fine-grained motion comprehension. To comprehensively assess the motion understanding ability of existing MLLMs, we introduce FAVOR-Bench, comprising 1,776 videos with structured manual annotations of various motions. Our benchmark includes both close-ended and open-ended tasks. For close-ended evaluation, we carefully design 8,184 multiple-choice question-answer pairs spanning six distinct sub-tasks. For open-ended evaluation, we develop both a novel cost-efficient LLM-free and a GPT-assisted caption assessment method, where the former can enhance benchmarking interpretability and reproducibility. Comprehensive experiments with 21 state-of-the-art MLLMs reveal significant limitations in their ability to comprehend and describe detailed temporal dynamics in video motions. To alleviate this limitation, we further build FAVOR-Train, a dataset consisting of 17,152 videos with fine-grained motion annotations. The results of finetuning Qwen2.5-VL on FAVOR-Train yield consistent improvements on motion-related tasks of TVBench, MotionBench and our FAVOR-Bench. Comprehensive assessment results demonstrate that the proposed FAVOR-Bench and FAVOR-Train provide valuable tools to the community for developing more powerful video understanding models. Project page: \href{https://favor-bench.github.io/}{https://favor-bench.github.io/}.

[Arxiv](https://arxiv.org/abs/2503.14935)