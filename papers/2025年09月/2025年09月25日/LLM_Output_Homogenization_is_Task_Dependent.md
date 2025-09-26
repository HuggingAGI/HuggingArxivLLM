# LLM输出同质化因任务而异

发布时间：2025年09月25日

`LLM应用` `基础理论`

> LLM Output Homogenization is Task Dependent

# 摘要

> 大型语言模型若出现输出同质化，实用性可能大打折扣。但判断两个输出是否同质、这种同质化是否有害，都因任务而异。例如，客观数学题中，我们通常要求答案唯一，但解题思路可以多样；而创意写作则需要关键叙事元素（如情节、体裁、场景等）的差异，而非仅靠温度采样带来的词汇或嵌入多样性。以往研究在解决输出同质化时，往往忽略了多样性的任务依赖性。本文通过以下贡献填补了这一空白：（1）提出包含八个任务类别的分类体系，每个类别对输出同质化有明确界定；（2）提出任务锚定功能多样性指标，更精准评估输出同质化；（3）设计任务锚定采样技术，在需避免同质化的任务中提升功能多样性，同时在需保持同质化的任务中维持稳定性；（4）打破“多样性与质量不可兼得”的固有认知，在提升功能多样性的同时保证响应质量。总之，我们证明了任务依赖性可有效提升输出同质化的评估与缓解效果。

> A large language model can be less helpful if it exhibits output response homogenization. But whether two responses are considered homogeneous, and whether such homogenization is problematic, both depend on the task category. For instance, in objective math tasks, we often expect no variation in the final answer but anticipate variation in the problem-solving strategy. Whereas, for creative writing tasks, we may expect variation in key narrative components (e.g. plot, genre, setting, etc), beyond the vocabulary or embedding diversity produced by temperature-sampling. Previous work addressing output homogenization often fails to conceptualize diversity in a task-dependent way. We address this gap in the literature directly by making the following contributions. (1) We present a task taxonomy comprised of eight task categories that each have distinct conceptualizations of output homogenization. (2) We introduce task-anchored functional diversity to better evaluate output homogenization. (3) We propose a task-anchored sampling technique that increases functional diversity for task categories where homogenization is undesired, while preserving homogenization where it is desired. (4) We challenge the perceived existence of a diversity-quality trade-off by increasing functional diversity while maintaining response quality. Overall, we demonstrate how task dependence improves the evaluation and mitigation of output homogenization.

[Arxiv](https://arxiv.org/abs/2509.21267)