# 三思而后行：通过扩展多轮推理过程提升大语言模型的推理能力

发布时间：2025年03月25日

`LLM应用` `人工智能`

> Think Twice: Enhancing LLM Reasoning by Scaling Multi-round Test-time Thinking

# 摘要

> 近期，像 OpenAI-o1 和 DeepSeek-R1 这样的大型语言模型 (LLMs) 取得了显著进展，证明了推理时间扩展的有效性，其中延长推理过程能显著提升模型性能。然而，当前模型在处理长文本和强化学习 (RL) 训练效率方面仍存在局限性。为了解决这些问题，我们提出了一种简单而有效的推理时间扩展方法——多轮思考。该方法通过将前一轮的回答作为后续轮次的提示，迭代优化模型的推理过程。在 QwQ-32B 和 DeepSeek-R1 等多个模型上的广泛实验表明，该方法在 AIME 2024、MATH-500、GPQA-diamond 和 LiveCodeBench 等多种基准测试中均表现出性能提升。例如，在 AIME 2024 数据集上，QwQ-32B 的准确率从第一轮的 80.3% 提升至第二轮的 82.1%，而 DeepSeek-R1 的准确率也从 79.7% 提升至 82.0%。这些结果证实了多轮思考是一种广泛适用且简便的方法，能够稳定提升模型性能，凸显了其在未来推理时间扩展技术发展中的潜力。关键提示：{原始问题提示} 助手的上一个回答是： <answer> {上一轮回答} </answer> 请重新回答。


> Recent advances in large language models (LLMs), such as OpenAI-o1 and DeepSeek-R1, have demonstrated the effectiveness of test-time scaling, where extended reasoning processes substantially enhance model performance. Despite this, current models are constrained by limitations in handling long texts and reinforcement learning (RL) training efficiency. To address these issues, we propose a simple yet effective test-time scaling approach Multi-round Thinking. This method iteratively refines model reasoning by leveraging previous answers as prompts for subsequent rounds. Extensive experiments across multiple models, including QwQ-32B and DeepSeek-R1, consistently show performance improvements on various benchmarks such as AIME 2024, MATH-500, GPQA-diamond, and LiveCodeBench. For instance, the accuracy of QwQ-32B improved from 80.3% (Round 1) to 82.1% (Round 2) on the AIME 2024 dataset, while DeepSeek-R1 showed a similar increase from 79.7% to 82.0%. These results confirm that Multi-round Thinking is a broadly applicable, straightforward approach to achieving stable enhancements in model performance, underscoring its potential for future developments in test-time scaling techniques. The key prompt: {Original question prompt} The assistant's previous answer is: <answer> {last round answer} </answer>, and please re-answer.

[Arxiv](https://arxiv.org/abs/2503.19855)