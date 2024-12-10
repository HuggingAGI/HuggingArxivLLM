# 拒绝令牌：大型语言模型中校准拒绝的简便之法

发布时间：2024年12月09日

`LLM应用` `语言模型` `人工智能`

> Refusal Tokens: A Simple Way to Calibrate Refusals in Large Language Models

# 摘要

> 构建安全可靠的语言模型，关键在于让模型能恰当地拒绝遵循某些指令或回答某些问题。比如，对于不恰当的问题、实施非法行为的指令，或者超出模型知识范畴的查询，我们可能希望模型能输出拒绝消息。由于个人对不同类别拒绝查询的敏感度期望不同，且不同用户期望的拒绝率也各异，所以设计能拒绝回答这类问题的模型颇为复杂。当前的默认做法是训练多个模型，每个模型中各类别拒绝消息的比例不同，以实现期望的拒绝率，这计算成本高昂，且可能需要为满足每个用户对拒绝率的偏好而训练新模型。为应对这些挑战，我们提出了拒绝令牌，可为每个拒绝类别设置一个令牌，也可设置一个通用拒绝令牌，在训练时将其置于模型响应之前。接着，我们展示了在推理过程中如何增减每个类别生成拒绝令牌的概率，从而引导模型的拒绝行为。拒绝令牌能控制单个模型的拒绝率，无需进一步微调，只需在生成过程中有选择地干预即可。

> A key component of building safe and reliable language models is enabling the models to appropriately refuse to follow certain instructions or answer certain questions. We may want models to output refusal messages for various categories of user queries, for example, ill-posed questions, instructions for committing illegal acts, or queries which require information past the model's knowledge horizon. Engineering models that refuse to answer such questions is complicated by the fact that an individual may want their model to exhibit varying levels of sensitivity for refusing queries of various categories, and different users may want different refusal rates. The current default approach involves training multiple models with varying proportions of refusal messages from each category to achieve the desired refusal rates, which is computationally expensive and may require training a new model to accommodate each user's desired preference over refusal rates. To address these challenges, we propose refusal tokens, one such token for each refusal category or a single refusal token, which are prepended to the model's responses during training. We then show how to increase or decrease the probability of generating the refusal token for each category during inference to steer the model's refusal behavior. Refusal tokens enable controlling a single model's refusal rates without the need of any further fine-tuning, but only by selectively intervening during generation.

[Arxiv](https://arxiv.org/abs/2412.06748)