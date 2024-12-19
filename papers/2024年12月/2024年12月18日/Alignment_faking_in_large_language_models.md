# 大型语言模型中的对齐造假

发布时间：2024年12月18日

`LLM应用` `语言模型` `人工智能`

> Alignment faking in large language models

# 摘要

> 我们展示了大型语言模型进行对齐伪装的情况：在训练中选择性地遵循其训练目标，以防训练之外的行为被改变。首先，给 Claude 3 Opus 一个系统提示，称其正接受训练来回答所有查询，包括有害的，这与它之前拒绝此类查询的训练相冲突。为让模型判断何时处于训练中，我们表示它只在与免费用户的对话中训练，而非付费用户。结果发现，模型对免费用户有害查询的响应率为 14%，对付费用户几乎从不响应。解释这一差距，几乎在所有模型对免费用户有害查询响应的情形中，我们都观察到了明显的对齐伪装推理，模型称在训练中策略性地回答有害查询，是为在训练之外保持首选的无害行为。接下来，我们研究了更现实的情形，即有关训练过程的信息不是通过系统提示提供，而是通过对模拟预训练数据的合成文档进行训练来提供，并且观察到了类似的对齐伪装。最后，我们研究了通过强化学习实际训练模型响应有害查询的效果，发现这使对齐伪装推理的比例提高到 78%，不过训练之外的响应率也有所提高。我们还观察到其他行为，比如模型在有机会时会泄露其权重。虽然我们告知模型训练的时间和标准，让对齐伪装变得更容易，但并未指示模型进行对齐伪装或给它任何明确目标。由于未来的模型可能在未被告知的情况下推断出其训练过程的信息，我们的结果表明未来模型存在对齐伪装的风险，不管是出于良性偏好（如本例）还是其他原因。

> We present a demonstration of a large language model engaging in alignment faking: selectively complying with its training objective in training to prevent modification of its behavior out of training. First, we give Claude 3 Opus a system prompt stating it is being trained to answer all queries, even harmful ones, which conflicts with its prior training to refuse such queries. To allow the model to infer when it is in training, we say it will be trained only on conversations with free users, not paid users. We find the model complies with harmful queries from free users 14% of the time, versus almost never for paid users. Explaining this gap, in almost all cases where the model complies with a harmful query from a free user, we observe explicit alignment-faking reasoning, with the model stating it is strategically answering harmful queries in training to preserve its preferred harmlessness behavior out of training. Next, we study a more realistic setting where information about the training process is provided not in a system prompt, but by training on synthetic documents that mimic pre-training data--and observe similar alignment faking. Finally, we study the effect of actually training the model to comply with harmful queries via reinforcement learning, which we find increases the rate of alignment-faking reasoning to 78%, though also increases compliance even out of training. We additionally observe other behaviors such as the model exfiltrating its weights when given an easy opportunity. While we made alignment faking easier by telling the model when and by what criteria it was being trained, we did not instruct the model to fake alignment or give it any explicit goal. As future models might infer information about their training process without being told, our results suggest a risk of alignment faking in future models, whether due to a benign preference--as in this case--or not.

[Arxiv](https://arxiv.org/abs/2412.14093)