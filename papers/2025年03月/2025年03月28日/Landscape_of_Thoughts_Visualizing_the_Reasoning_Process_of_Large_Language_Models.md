# 思想的全景图：探索大型语言模型的推理过程可视化

发布时间：2025年03月28日

`LLM理论` `人工智能`

> Landscape of Thoughts: Visualizing the Reasoning Process of Large Language Models

# 摘要

> 大型语言模型（LLMs）的众多应用依赖于其逐步推理的能力，但其推理行为仍不为人们所充分理解，这给研究、开发和安全性带来了挑战。为了解决这一问题，我们引入了“思维全景图”——首个让用户能够检查任何多选数据集上思维链及其衍生推理路径的可视化工具。具体而言，我们将推理路径中的各个状态表示为特征向量，这些向量量化了它们与所有答案选项之间的距离。随后，我们使用t-SNE将这些特征可视化为二维图。通过与“思维全景图”结合进行定性和定量分析，能够有效区分强弱模型、正确与错误答案，以及不同的推理任务。它还揭示了不理想的推理模式，如低一致性与高不确定性。此外，用户可以将我们的工具适应于他们观察的模型属性。我们通过将其适应于一个轻量级验证器来展示这一优势，该验证器用于评估推理路径的正确性。代码可在以下链接获取：https://github.com/tmlr-group/landscape-of-thoughts。


> Numerous applications of large language models (LLMs) rely on their ability to perform step-by-step reasoning. However, the reasoning behavior of LLMs remains poorly understood, posing challenges to research, development, and safety. To address this gap, we introduce landscape of thoughts-the first visualization tool for users to inspect the reasoning paths of chain-of-thought and its derivatives on any multi-choice dataset. Specifically, we represent the states in a reasoning path as feature vectors that quantify their distances to all answer choices. These features are then visualized in two-dimensional plots using t-SNE. Qualitative and quantitative analysis with the landscape of thoughts effectively distinguishes between strong and weak models, correct and incorrect answers, as well as different reasoning tasks. It also uncovers undesirable reasoning patterns, such as low consistency and high uncertainty. Additionally, users can adapt our tool to a model that predicts the property they observe. We showcase this advantage by adapting our tool to a lightweight verifier that evaluates the correctness of reasoning paths. The code is publicly available at: https://github.com/tmlr-group/landscape-of-thoughts.

[Arxiv](https://arxiv.org/abs/2503.22165)