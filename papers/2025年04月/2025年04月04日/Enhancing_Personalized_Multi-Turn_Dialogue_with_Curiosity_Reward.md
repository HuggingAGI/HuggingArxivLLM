# 利用好奇心奖励优化个性化对话轮次能力

发布时间：2025年04月04日

`Agent`

> Enhancing Personalized Multi-Turn Dialogue with Curiosity Reward

# 摘要

> 有效的对话代理需要根据用户的偏好、个性和属性调整行为，无论是协助写作还是应用于教育、医疗等领域。当前的强化学习方法（RLHF）虽然注重有用性和安全性，但在实现真正富有同理心和个性化的交互方面仍有欠缺。传统个性化方法依赖大量用户历史数据，难以满足新用户或上下文受限用户的需求。

为此，我们提出了一种结合多轮RLHF的内在动机方法，通过优化对话来提高用户模型的准确性。这种方法鼓励代理主动获取用户特征，从而提供更加个性化的交互体验。我们在教育和健身场景中验证了该方法，结果显示，与传统RLHF基准相比，我们的方法在揭示用户偏好和适应用户需求方面表现更优。

> Effective conversational agents must be able to personalize their behavior to suit a user's preferences, personality, and attributes, whether they are assisting with writing tasks or operating in domains like education or healthcare. Current training methods like Reinforcement Learning from Human Feedback (RLHF) prioritize helpfulness and safety but fall short in fostering truly empathetic, adaptive, and personalized interactions. Traditional approaches to personalization often rely on extensive user history, limiting their effectiveness for new or context-limited users. To overcome these limitations, we propose to incorporate an intrinsic motivation to improve the conversational agents's model of the user as an additional reward alongside multi-turn RLHF. This reward mechanism encourages the agent to actively elicit user traits by optimizing conversations to increase the accuracy of its user model. Consequently, the policy agent can deliver more personalized interactions through obtaining more information about the user. We applied our method both education and fitness settings, where LLMs teach concepts or recommend personalized strategies based on users' hidden learning style or lifestyle attributes. Using LLM-simulated users, our approach outperformed a multi-turn RLHF baseline in revealing information about the users' preferences, and adapting to them.

[Arxiv](https://arxiv.org/abs/2504.03206)