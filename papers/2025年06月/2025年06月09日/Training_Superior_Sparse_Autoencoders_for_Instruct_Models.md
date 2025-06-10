# 打造卓越的稀疏自编码器，助力指令模型性能提升

发布时间：2025年06月09日

`LLM理论` `人工智能` `模型解释性`

> Training Superior Sparse Autoencoders for Instruct Models

# 摘要

> 随着大型语言模型 (LLMs) 的规模和能力不断提升，理解其内部机制变得日益重要。稀疏自动编码器 (SAEs) 已经成为机制可解释性领域中的关键工具，能够从 LLMs 中提取人类可解释的特征。然而，现有的 SAE 训练方法主要针对基础模型设计，当应用于指令模型时，导致重建质量和可解释性下降。为了填补这一空白，我们提出了一种全新的训练方法——$underline{	extbf{F}}$inetuning-$underline{	extbf{a}}$ligned $underline{	extbf{S}}$equential $underline{	extbf{T}}$raining ($	extit{FAST}$)，该方法专为指令模型量身定制。$	extit{FAST}$ 将训练过程与指令模型特有的数据分布和激活模式相匹配，显著提升了重建质量和特征可解释性。在 Qwen2.5-7B-Instruct 上，$	extit{FAST}$ 在令牌重建中实现了 0.6468 的均方误差，远超基线方法 5.1985 和 1.5096 的误差。在特征可解释性方面，$	extit{FAST}$ 生成了更高比例的高质量特征，针对 Llama3.2-3B-Instruct，有 $21.1\%$ 的特征处于最佳水平，而 $	extit{BT(P)}$ 和 $	extit{BT(F)}$ 分别仅为 $7.0\%$ 和 $10.2\%$。令人惊讶的是，我们发现通过 SAEs 干预特殊令牌的激活可以提升输出质量，这为实现对模型行为的精细控制提供了新的可能性。代码、数据和 240 个训练好的 SAEs 可在 https://github.com/Geaming2002/FAST 获取。

> As large language models (LLMs) grow in scale and capability, understanding their internal mechanisms becomes increasingly critical. Sparse autoencoders (SAEs) have emerged as a key tool in mechanistic interpretability, enabling the extraction of human-interpretable features from LLMs. However, existing SAE training methods are primarily designed for base models, resulting in reduced reconstruction quality and interpretability when applied to instruct models. To bridge this gap, we propose $\underline{\textbf{F}}$inetuning-$\underline{\textbf{a}}$ligned $\underline{\textbf{S}}$equential $\underline{\textbf{T}}$raining ($\textit{FAST}$), a novel training method specifically tailored for instruct models. $\textit{FAST}$ aligns the training process with the data distribution and activation patterns characteristic of instruct models, resulting in substantial improvements in both reconstruction and feature interpretability. On Qwen2.5-7B-Instruct, $\textit{FAST}$ achieves a mean squared error of 0.6468 in token reconstruction, significantly outperforming baseline methods with errors of 5.1985 and 1.5096. In feature interpretability, $\textit{FAST}$ yields a higher proportion of high-quality features, for Llama3.2-3B-Instruct, $21.1\%$ scored in the top range, compared to $7.0\%$ and $10.2\%$ for $\textit{BT(P)}$ and $\textit{BT(F)}$. Surprisingly, we discover that intervening on the activations of special tokens via the SAEs leads to improvements in output quality, suggesting new opportunities for fine-grained control of model behavior. Code, data, and 240 trained SAEs are available at https://github.com/Geaming2002/FAST.

[Arxiv](https://arxiv.org/abs/2506.07691)