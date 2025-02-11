# MATH-Perturb：评测大型语言模型在面对困难干扰时的数学推理能力

发布时间：2025年02月10日

`LLM理论` `数学推理` `模型推理`

> MATH-Perturb: Benchmarking LLMs' Math Reasoning Abilities against Hard Perturbations

# 摘要

> 大型语言模型在复杂数学推理任务中表现出色，但其能力究竟源于真正推理还是简单记忆尚存疑问。先前研究通过保持解题思路的简单扰动构建了数学测试基准，但尚未探索会彻底改变问题本质的困难扰动。为此，我们基于MATH数据集（Hendrycks等，2021）中最难的第5级问题，通过简单扰动和困难扰动分别构建了MATH-P-Simple和MATH-P-Hard数据集，每个包含279道变形数学题。实验结果显示，包括o1-mini（-16.49%）和gemini-2.0-flash-thinking（-12.9%）在内的多个模型在MATH-P-Hard上表现大幅下降。我们发现模型存在盲目套用所学解题技巧而不评估其适用性的记忆问题，这一现象在使用原始问题进行上下文学习时尤为突出。我们呼吁研究界深入探索这一挑战，这对于开发更强大可靠的推理模型具有重要意义。


> Large language models have demonstrated impressive performance on challenging mathematical reasoning tasks, which has triggered the discussion of whether the performance is achieved by true reasoning capability or memorization. To investigate this question, prior work has constructed mathematical benchmarks when questions undergo simple perturbations -- modifications that still preserve the underlying reasoning patterns of the solutions. However, no work has explored hard perturbations, which fundamentally change the nature of the problem so that the original solution steps do not apply. To bridge the gap, we construct MATH-P-Simple and MATH-P-Hard via simple perturbation and hard perturbation, respectively. Each consists of 279 perturbed math problems derived from level-5 (hardest) problems in the MATH dataset (Hendrycksmath et. al., 2021). We observe significant performance drops on MATH-P-Hard across various models, including o1-mini (-16.49%) and gemini-2.0-flash-thinking (-12.9%). We also raise concerns about a novel form of memorization where models blindly apply learned problem-solving skills without assessing their applicability to modified contexts. This issue is amplified when using original problems for in-context learning. We call for research efforts to address this challenge, which is critical for developing more robust and reliable reasoning models.

[Arxiv](https://arxiv.org/abs/2502.06453)