# ReCUT：通过逐步推理轨迹与偏好优化，在大型语言模型中实现推理长度与准确性的平衡

发布时间：2025年06月12日

`LLM应用`

> ReCUT: Balancing Reasoning Length and Accuracy in LLMs via Stepwise Trails and Preference Optimization

# 摘要

> 思维链提示（CoT）的最新进展显著提升了大型语言模型（LLMs）的推理能力。然而，现有方法常因过度思考而导致推理轨迹冗长或重复。针对这一问题，现有方法尝试通过整理多条推理链来优化LLMs训练，但受限于数据质量且易过拟合。为此，我们提出了一种平衡推理轨迹准确性和长度的新方法——通过分步试验进行推理压缩（ReCUT）。ReCUT采用分步探索机制和长短时切换采样策略，使LLMs能够逐步生成多样化的推理路径。这些路径经过评估后，用于训练两个专用模型：一个优化推理准确性，另一个优化推理长度。最终通过插值这两个模型的参数，得到一个集成模型。实验结果显示，ReCUT在多个数学推理数据集和主干模型上，将推理长度显著减少了约30-50%，同时保持或提高了推理准确性。所有代码和数据将在GitHub上公开发布。


> Recent advances in Chain-of-Thought (CoT) prompting have substantially improved the reasoning capabilities of Large Language Models (LLMs). However, these methods often suffer from overthinking, leading to unnecessarily lengthy or redundant reasoning traces. Existing approaches attempt to mitigate this issue through curating multiple reasoning chains for training LLMs, but their effectiveness is often constrained by the quality of the generated data and prone to overfitting. To address the challenge, we propose Reasoning Compression ThroUgh Stepwise Trials (ReCUT), a novel method aimed at balancing the accuracy and length of reasoning trajectory. Specifically, ReCUT employs a stepwise exploration mechanism and a long-short switched sampling strategy, enabling LLMs to incrementally generate diverse reasoning paths. These paths are evaluated and used to construct preference pairs to train two specialized models (Gemini LLMs)-one optimized for reasoning accuracy, the other for shorter reasoning. A final integrated model is obtained by interpolating the parameters of these two models. Experimental results across multiple math reasoning datasets and backbone models demonstrate that ReCUT significantly reduces reasoning lengths by approximately 30-50%, while maintaining or improving reasoning accuracy compared to various baselines. All codes and data will be released via https://github.com/NEUIR/ReCUT.

[Arxiv](https://arxiv.org/abs/2506.10822)