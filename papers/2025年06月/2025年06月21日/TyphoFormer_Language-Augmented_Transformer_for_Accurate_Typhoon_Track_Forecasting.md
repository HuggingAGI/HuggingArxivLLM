# TyphoFormer：语言增强的Transformer模型，助力台风路径精准预测

发布时间：2025年06月21日

`LLM应用` `灾害管理`

> TyphoFormer: Language-Augmented Transformer for Accurate Typhoon Track Forecasting

# 摘要

> 准确预测台风轨迹对灾害预警和应急响应至关重要。尽管基于Transformer的模型在建模智能城市中人类和车辆轨迹的时间动态方面表现出色，但它们通常缺乏对稀疏气象轨迹（如台风路径）的上下文知识，这限制了预测的可靠性。为了解决这一问题，我们提出了TyphoFormer——一个结合自然语言描述作为辅助提示的创新框架，以提升台风轨迹预测的准确性。针对每个时间步，我们利用大型语言模型（LLM）基于北大西洋飓风数据库中的数值属性生成简洁的文本描述。这些语言描述能够捕捉高层气象语义，并作为辅助特殊标记附加到数值时间序列输入之前。通过在一个统一的Transformer编码器中整合文本和序列信息，TyphoFormer使模型能够利用通过数值特征本身无法获取的上下文线索。在HURDAT2基准数据集上的广泛实验表明，TyphoFormer在具有挑战性的非线性路径偏移和有限历史观测的情况下，始终优于其他最先进的基线方法。


> Accurate typhoon track forecasting is crucial for early system warning and disaster response. While Transformer-based models have demonstrated strong performance in modeling the temporal dynamics of dense trajectories of humans and vehicles in smart cities, they usually lack access to broader contextual knowledge that enhances the forecasting reliability of sparse meteorological trajectories, such as typhoon tracks. To address this challenge, we propose TyphoFormer, a novel framework that incorporates natural language descriptions as auxiliary prompts to improve typhoon trajectory forecasting. For each time step, we use Large Language Model (LLM) to generate concise textual descriptions based on the numerical attributes recorded in the North Atlantic hurricane database. The language descriptions capture high-level meteorological semantics and are embedded as auxiliary special tokens prepended to the numerical time series input. By integrating both textual and sequential information within a unified Transformer encoder, TyphoFormer enables the model to leverage contextual cues that are otherwise inaccessible through numerical features alone. Extensive experiments are conducted on HURDAT2 benchmark, results show that TyphoFormer consistently outperforms other state-of-the-art baseline methods, particularly under challenging scenarios involving nonlinear path shifts and limited historical observations.

[Arxiv](https://arxiv.org/abs/2506.17609)