# 几何不确定性：大型语言模型（LLMs）幻觉的检测与纠正

发布时间：2025年09月17日

`LLM应用` `医疗健康`

> Geometric Uncertainty for Detecting and Correcting Hallucinations in LLMs

# 摘要

> 大型语言模型在各类任务中表现亮眼，但仍存在幻觉问题——会生成语言通顺却与事实不符的答案。不确定性量化被视作检测幻觉的有效策略，但现有黑盒方法均无法同时估计全局和局部不确定性：前者针对一批响应，后者则聚焦单个响应。现有局部方法通常依赖模型内部状态的白盒访问，而黑盒方法仅能提供全局不确定性估计。为此，我们提出一种几何框架，仅通过黑盒模型访问采样响应批次，基于原型分析实现上述目标。在全局层面，我们提出“几何体积”指标，通过响应嵌入生成原型，再计算其凸包体积；在局部层面，我们提出“几何怀疑度”指标，可按可靠性对响应排序，并通过优先选择可靠响应减少幻觉。与仅输出单一全局分数的传统离散度方法不同，我们的方法能提供语义边界点，可用于评估单个响应的可靠性。实验表明，在短文本问答数据集上，我们的框架性能与现有方法相当甚至更优；而在幻觉风险极高的医疗数据集上，该框架表现尤为突出。我们还通过证明凸包体积与熵的关联，为该框架提供了理论支撑。

> Large language models demonstrate impressive results across diverse tasks but are still known to hallucinate, generating linguistically plausible but incorrect answers to questions. Uncertainty quantification has been proposed as a strategy for hallucination detection, but no existing black-box approach provides estimates for both global and local uncertainty. The former attributes uncertainty to a batch of responses, while the latter attributes uncertainty to individual responses. Current local methods typically rely on white-box access to internal model states, whilst black-box methods only provide global uncertainty estimates. We introduce a geometric framework to address this, based on archetypal analysis of batches of responses sampled with only black-box model access. At the global level, we propose Geometric Volume, which measures the convex hull volume of archetypes derived from response embeddings. At the local level, we propose Geometric Suspicion, which ranks responses by reliability and enables hallucination reduction through preferential response selection. Unlike prior dispersion methods which yield only a single global score, our approach provides semantic boundary points which have utility for attributing reliability to individual responses. Experiments show that our framework performs comparably to or better than prior methods on short form question-answering datasets, and achieves superior results on medical datasets where hallucinations carry particularly critical risks. We also provide theoretical justification by proving a link between convex hull volume and entropy.

[Arxiv](https://arxiv.org/abs/2509.13813)