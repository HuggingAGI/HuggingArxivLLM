# 大型语言模型能识别你的偏好吗？研究 LLM 中的个性化偏好遵循。
发布时间：2025年02月13日


> Do LLMs Recognize Your Preferences? Evaluating Personalized Preference Following in LLMs
>
> 大型语言模型（LLMs）越来越多地被用作聊天机器人，但它们根据用户偏好个性化回复的能力仍然有限。我们引入了PrefEval，这是一个用于评估LLMs在长上下文对话场景中推断、记忆和遵循用户偏好的能力的基准测试。PrefEval包含3000个手动整理的用户偏好和查询对，涵盖20个主题。PrefEval以显性和隐性形式包含了用户个性化或偏好信息，并通过生成和分类任务来评估LLM的表现。通过PrefEval，我们在多会话对话中评估了10个开源和专有LLMs的上述偏好遵循能力，对话上下文长度变化范围可达10万tokens。我们使用了各种提示、迭代反馈和检索增强生成方法进行基准测试。我们的基准测试结果表明，最先进的LLMs在对话过程中主动遵循用户偏好的能力面临重大挑战。具体来说，在零-shot设置下，仅在10轮对话（约3k tokens）中，大多数评估模型的偏好遵循准确率低于10%。即使使用先进的提示和检索方法，偏好遵循在长上下文对话中仍然会恶化。此外，我们还展示了在PrefEval上进行微调可以显著提高性能。我们相信PrefEval为衡量、理解和增强LLMs的偏好遵循能力提供了一个有价值的资源，为个性化对话代理铺平了道路。我们的代码和数据集可在https://prefeval.github.io/获取。
>
> https://arxiv.org/abs/2502.09597

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2502.09597](https://arxiv.org/abs/2502.09597)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)