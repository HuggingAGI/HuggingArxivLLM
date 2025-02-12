# 学习稀疏叠加特征及其反馈机制的复杂性研究

发布时间：2025年02月11日

`Agent` `机器学习` `特征提取`

> The Complexity of Learning Sparse Superposed Features with Feedback

# 摘要

> 深度网络的成功主要源于其在表示空间中捕捉潜在特征的能力。本研究探讨了模型的潜在学习特征是否能通过智能体（如大型语言模型 (LLM)）提供的反馈，以相对的	extit{三元组比较}形式高效检索。这些特征可能代表多种构建，包括 LLM 中的字典或马氏距离协方差矩阵的组成部分。我们深入分析了在稀疏环境下学习特征矩阵的反馈复杂度。研究结果表明，在允许智能体构建激活时，我们能够建立紧致的界限；而在智能体反馈仅限于分布信息的情况下，我们在稀疏场景中获得了强大的上界。通过在两个不同应用上的实验，我们成功验证了理论发现：从递归特征机器学习模型中恢复特征，以及从大型语言模型训练的稀疏自动编码器中提取字典。

> The success of deep networks is crucially attributed to their ability to capture latent features within a representation space. In this work, we investigate whether the underlying learned features of a model can be efficiently retrieved through feedback from an agent, such as a large language model (LLM), in the form of relative \textit{triplet comparisons}. These features may represent various constructs, including dictionaries in LLMs or components of a covariance matrix of Mahalanobis distances. We analyze the feedback complexity associated with learning a feature matrix in sparse settings. Our results establish tight bounds when the agent is permitted to construct activations and demonstrate strong upper bounds in sparse scenarios when the agent's feedback is limited to distributional information. We validate our theoretical findings through experiments on two distinct applications: feature recovery from Recursive Feature Machine-trained models and dictionary extraction from sparse autoencoders trained on Large Language Models.

[Arxiv](https://arxiv.org/abs/2502.05407)