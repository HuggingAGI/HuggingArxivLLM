# CLEAR：基于进化的线索学习用于可持续性数据提取的精准识别

发布时间：2025年01月30日

`LLM应用

理由：这篇论文主要讨论了如何利用大型语言模型（LLM）和进化计算技术来自动生成和优化图像识别中的提示线索，以提高图像中特定特征的识别能力。这属于LLM在实际应用中的使用，特别是结合进化计算来优化提示线索，从而提升图像识别的准确性。因此，将其分类为“LLM应用”是合适的。` `可持续性`

> CLEAR: Cue Learning using Evolution for Accurate Recognition Applied to Sustainability Data Extraction

# 摘要

> 大型语言模型（LLM）图像识别是从图像中提取数据的利器，但其准确性依赖于提示中的线索质量——这通常需要领域专家的参与。我们提出了基于进化的线索学习（CLEAR），它结合LLM和进化计算，自动生成并优化线索，从而提升图像中特定特征的识别能力。CLEAR通过生成领域特定的表示，并利用遗传算法优化文本线索来实现这一目标。我们将CLEAR应用于从建筑物内外图像中提取可持续性数据的实际任务，对比了可变长度与固定长度表示的效果，并展示了如何通过将分类估计重构为实值估计来提高LLM的一致性。实验表明，CLEAR在每项任务中的准确性均优于专家识别和人工编写的提示，错误率降低了多达两个数量级，消融研究也验证了其简洁性。

> Large Language Model (LLM) image recognition is a powerful tool for extracting data from images, but accuracy depends on providing sufficient cues in the prompt - requiring a domain expert for specialized tasks. We introduce Cue Learning using Evolution for Accurate Recognition (CLEAR), which uses a combination of LLMs and evolutionary computation to generate and optimize cues such that recognition of specialized features in images is improved. It achieves this by auto-generating a novel domain-specific representation and then using it to optimize suitable textual cues with a genetic algorithm. We apply CLEAR to the real-world task of identifying sustainability data from interior and exterior images of buildings. We investigate the effects of using a variable-length representation compared to fixed-length and show how LLM consistency can be improved by refactoring from categorical to real-valued estimates. We show that CLEAR enables higher accuracy compared to expert human recognition and human-authored prompts in every task with error rates improved by up to two orders of magnitude and an ablation study evincing solution concision.

[Arxiv](https://arxiv.org/abs/2501.18504)