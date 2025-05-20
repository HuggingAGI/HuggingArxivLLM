# 通过指导式优化提升开放领域对话中的用户导向主动性

发布时间：2025年05月18日

`LLM应用

理由：这篇论文专注于将大型语言模型（LLMs）应用于对话系统，特别是提升对话的主动性和用户导向主动性。论文提出了具体的方法和训练策略，以增强LLMs在实际应用中的表现，属于LLM的实际应用领域。` `社交机器人` `智能助手`

> Enhancing User-Oriented Proactivity in Open-Domain Dialogues with Critic Guidance

# 摘要

> # 摘要
开放领域对话系统致力于生成自然且引人入胜的对话，为社交机器人和个人助理等实际应用带来重要价值。大型语言模型（LLMs）的出现推动了这一领域的显著进步，显著提升了对话的上下文理解和流畅性。然而，现有基于LLMs的对话系统在主动感知用户偏好并引导对话向用户关注的主题发展方面仍显不足。这种缺乏用户导向主动性的特点会导致用户在人机交互中感到不受重视，从而降低其满意度和继续对话的意愿。

为解决这一问题，我们提出了一种用户导向主动聊天机器人（UPC），以增强对话中的用户导向主动性。具体而言，我们首先构建了一个基于LLMs的批评家（critic），用于评估对话中的主动性。鉴于高质量训练数据的稀缺性，我们随后利用该批评家引导聊天机器人与用户代理之间的对话，生成具有增强用户导向主动性的语料库。为了确保用户背景的多样性，我们引入了ISCO-800，这是一个用于构建用户代理的多样化用户背景数据集。

此外，考虑到不同用户的沟通难度不同，我们提出了一种迭代课程学习方法，从易于沟通的用户开始训练聊天机器人，逐步过渡到更具挑战性的用户，从而逐步提升其性能。实验结果表明，我们提出的训练方法适用于不同的LLMs，能够显著提升开放领域对话中用户导向主动性和吸引力。


> Open-domain dialogue systems aim to generate natural and engaging conversations, providing significant practical value in real applications such as social robotics and personal assistants. The advent of large language models (LLMs) has greatly advanced this field by improving context understanding and conversational fluency. However, existing LLM-based dialogue systems often fall short in proactively understanding the user's chatting preferences and guiding conversations toward user-centered topics. This lack of user-oriented proactivity can lead users to feel unappreciated, reducing their satisfaction and willingness to continue the conversation in human-computer interactions. To address this issue, we propose a User-oriented Proactive Chatbot (UPC) to enhance the user-oriented proactivity. Specifically, we first construct a critic to evaluate this proactivity inspired by the LLM-as-a-judge strategy. Given the scarcity of high-quality training data, we then employ the critic to guide dialogues between the chatbot and user agents, generating a corpus with enhanced user-oriented proactivity. To ensure the diversity of the user backgrounds, we introduce the ISCO-800, a diverse user background dataset for constructing user agents. Moreover, considering the communication difficulty varies among users, we propose an iterative curriculum learning method that trains the chatbot from easy-to-communicate users to more challenging ones, thereby gradually enhancing its performance. Experiments demonstrate that our proposed training method is applicable to different LLMs, improving user-oriented proactivity and attractiveness in open-domain dialogues.

[Arxiv](https://arxiv.org/abs/2505.12334)