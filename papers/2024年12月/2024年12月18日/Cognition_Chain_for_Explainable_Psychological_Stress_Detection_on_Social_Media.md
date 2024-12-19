# 用于社交媒体心理压力检测的可解释性认知链

发布时间：2024年12月18日

`LLM应用` `心理健康`

> Cognition Chain for Explainable Psychological Stress Detection on Social Media

# 摘要

> 压力是全球性的普遍健康问题，会引发严重的心理健康问题。早期检测有助于及时干预和预防压力相关病症。当下的早期检测模型进行“黑箱”推理，存在解释性和可信度不足的情况，阻碍了其在实际临床中的应用。得益于大型语言模型（LLMs）的生成特性，这类模型的决策和预测通过相应描述具备了半可解释性。然而，现有的LLMs大多是为通用目的训练的，缺少心理认知理论的引导。为此，我们首先通过观察专为压力检测定制的思维链所带来的性能提升，突出了先验理论的重要性。这种名为认知链的方法基于认知评估理论，以刺激→评估→反应→压力状态的逐步认知视角，阐释了压力的产生，引导LLMs给出全面的推理解释。我们进一步探究了所提出的认知链格式的益处，将其用作LLMs指令调整的综合数据集生成模板，并引入了CogInstruct，这是一个用于压力检测的指令调整数据集。该数据集通过三阶段的自我反思注释流程开发而成，能让LLMs自主生成和优化教学数据。利用CogInstruct对Llama3进行指令调整，我们开发出了CogLLM，这是一个可解释的压力检测模型。评估显示，CogLLM在增强可解释性的同时表现出色。我们的工作将认知理论融入LLM推理过程，贡献了新的思路，为未来可解释的AI研究指明了有前景的方向。

> Stress is a pervasive global health issue that can lead to severe mental health problems. Early detection offers timely intervention and prevention of stress-related disorders. The current early detection models perform "black box" inference suffering from limited explainability and trust which blocks the real-world clinical application. Thanks to the generative properties introduced by the Large Language Models (LLMs), the decision and the prediction from such models are semi-interpretable through the corresponding description. However, the existing LLMs are mostly trained for general purposes without the guidance of psychological cognitive theory. To this end, we first highlight the importance of prior theory with the observation of performance boosted by the chain-of-thoughts tailored for stress detection. This method termed Cognition Chain explicates the generation of stress through a step-by-step cognitive perspective based on cognitive appraisal theory with a progress pipeline: Stimulus $\rightarrow$ Evaluation $\rightarrow$ Reaction $\rightarrow$ Stress State, guiding LLMs to provide comprehensive reasoning explanations. We further study the benefits brought by the proposed Cognition Chain format by utilising it as a synthetic dataset generation template for LLMs instruction-tuning and introduce CogInstruct, an instruction-tuning dataset for stress detection. This dataset is developed using a three-stage self-reflective annotation pipeline that enables LLMs to autonomously generate and refine instructional data. By instruction-tuning Llama3 with CogInstruct, we develop CogLLM, an explainable stress detection model. Evaluations demonstrate that CogLLM achieves outstanding performance while enhancing explainability. Our work contributes a novel approach by integrating cognitive theories into LLM reasoning processes, offering a promising direction for future explainable AI research.

[Arxiv](https://arxiv.org/abs/2412.14009)