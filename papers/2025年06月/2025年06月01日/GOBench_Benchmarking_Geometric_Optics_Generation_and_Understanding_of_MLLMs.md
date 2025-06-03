# GOBench：多模态大语言模型几何光学生成与理解的基准测试

发布时间：2025年06月01日

`LLM应用` `视觉理解`

> GOBench: Benchmarking Geometric Optics Generation and Understanding of MLLMs

# 摘要

> 多模态大型语言模型（MLLMs）的快速发展正在推动视觉理解和生成领域的重大进步。然而，关于其能力的全面评估，尤其是在精细的物理原理（特别是几何光学方面），仍存在大量未探索的领域。为了解决这一问题，我们引入了GOBench，这是首个系统性评估MLLMs在两个任务中能力的基准：1）生成光学真实的图像；2）理解底层光学现象。我们精心策划了高质量的几何光学场景提示，并利用MLLMs构建了GOBench-Gen-1k数据集。随后，我们组织了主观实验，从光学真实性、美学质量和指令保真度三个方面评估生成的图像，揭示了MLLMs在生成过程中违背光学原理的缺陷。对于理解任务，我们设计了定制的评估指令，测试了十一款知名MLLMs的光学理解能力。实验结果表明，当前模型在光学生成和理解方面都面临着重大挑战。表现最佳的生成模型GPT-4o-Image无法完美完成所有生成任务，而光学理解表现最好的MLLM模型Gemini-2.5Pro仅达到了37.35%的准确率。

> The rapid evolution of Multi-modality Large Language Models (MLLMs) is driving significant advancements in visual understanding and generation. Nevertheless, a comprehensive assessment of their capabilities, concerning the fine-grained physical principles especially in geometric optics, remains underexplored. To address this gap, we introduce GOBench, the first benchmark to systematically evaluate MLLMs' ability across two tasks: 1) Generating Optically Authentic Imagery and 2) Understanding Underlying Optical Phenomena. We curates high-quality prompts of geometric optical scenarios and use MLLMs to construct GOBench-Gen-1k dataset.We then organize subjective experiments to assess the generated imagery based on Optical Authenticity, Aesthetic Quality, and Instruction Fidelity, revealing MLLMs' generation flaws that violate optical principles. For the understanding task, we apply crafted evaluation instructions to test optical understanding ability of eleven prominent MLLMs. The experimental results demonstrate that current models face significant challenges in both optical generation and understanding. The top-performing generative model, GPT-4o-Image, cannot perfectly complete all generation tasks, and the best-performing MLLM model, Gemini-2.5Pro, attains a mere 37.35\% accuracy in optical understanding.

[Arxiv](https://arxiv.org/abs/2506.00991)