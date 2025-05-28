# rStar-Coder：通过大规模验证数据集提升竞争性代码推理能力

发布时间：2025年05月27日

`LLM应用` `编程教育` `编程实践`

> rStar-Coder: Scaling Competitive Code Reasoning with a Large-Scale Verified Dataset

# 摘要

> 在大型语言模型（LLMs）中，代码推理能力的提升受到高质量数据集稀缺性的限制，特别是缺乏包含可验证输入输出测试案例的数据集，这些案例对于大规模严格解决方案验证至关重要。我们推出rStar-Coder，通过构建一个包含41.8万个竞赛级别代码问题、58万个长推理解决方案以及难度各异的丰富测试案例的大规模验证数据集，显著提升了LLM的代码推理能力。这一成果基于三个核心贡献：（1）我们整理竞赛编程代码问题和Oracle解决方案，合成新的可解问题；（2）我们引入一个可靠的输入输出测试案例合成流水线，将其生成过程分解为三步输入生成方法和一个相互验证机制，以实现有效的输出标注；（3）我们通过高质量、经过测试案例验证的长推理解决方案增强问题。在Qwen模型（1.5B-14B）上进行的广泛实验，覆盖了各种代码推理基准，证明了rStar-Coder数据集的优越性。即使在模型规模远小于前沿推理LLM的情况下，rStar-Coder也能实现领先性能。在LiveCodeBench上，rStar-Coder将Qwen2.5-7B的性能从17.4%提升到57.3%，并将Qwen2.5-14B从23.3%提升到62.5%，超过了o3-mini（low）3.1%。在更具挑战性的美国计算奥林匹克竞赛中，我们的7B模型实现了16.15%的平均pass@1准确率，超过了前沿水平的QWQ-32B。代码和数据集将在https://github.com/microsoft/rStar上发布。


> Advancing code reasoning in large language models (LLMs) is fundamentally limited by the scarcity of high-difficulty datasets, especially those with verifiable input-output test cases necessary for rigorous solution validation at scale. We introduce rStar-Coder, which significantly improves LLM code reasoning capabilities by constructing a large-scale, verified dataset of 418K competition-level code problems, 580K long-reasoning solutions along with rich test cases of varying difficulty. This is achieved through three core contributions: (1) we curate competitive programming code problems and oracle solutions to synthesize new, solvable problems; (2) we introduce a reliable input-output test case synthesis pipeline that decouples the generation into a three-step input generation method and a mutual verification mechanism for effective output labeling; (3) we augment problems with high-quality, test-case-verified long-reasoning solutions. Extensive experiments on Qwen models (1.5B-14B) across various code reasoning benchmarks demonstrate the superiority of rStar-Coder dataset, achieving leading performance comparable to frontier reasoning LLMs with much smaller model sizes. On LiveCodeBench, rStar-Coder improves Qwen2.5-7B from 17.4% to an impressive 57.3%, and Qwen2.5-14B from 23.3% to 62.5%, surpassing o3-mini (low) by3.1%. On the more challenging USA Computing Olympiad, our 7B model achieves an average pass@1 accuracy of 16.15%, outperforming the frontier-level QWQ-32B. Code and the dataset will be released at https://github.com/microsoft/rStar.

[Arxiv](https://arxiv.org/abs/2505.21297)