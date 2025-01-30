# RICoTA: 野外对话的红队测试尝试

发布时间：2025年01月29日

`LLM应用

理由：这篇论文主要讨论了用户与聊天机器人（CAs）的互动，特别是关于越狱尝试和用户测试意图的识别。论文提出了一个数据集RICoTA，用于评估LLMs在识别这些互动中的能力，并从中得出聊天机器人设计的启示。这涉及到LLMs在实际应用中的表现和设计改进，因此属于LLM应用类别。` `聊天机器人` `网络安全`

> RICoTA: Red-teaming of In-the-wild Conversation with Test Attempts

# 摘要

> # 摘要
在高度防护的LLMs时代，用户与CAs的互动正在发生变化。随着用户突破编程边界，探索与这些系统建立关系，人们越来越担心未经授权的访问或操纵（即“越狱”）的可能性。此外，对于高度人性化的CAs，用户倾向于发起亲密的性互动或试图驯服聊天机器人。为了将这些真实世界中的互动反映到聊天机器人设计中，我们提出了RICoTA，一个包含609个提示的韩国红队数据集，挑战LLMs捕捉真实用户对话中的越狱尝试。我们利用了一个类似韩国Reddit的社区中用户自我发布的对话，这些对话包含针对社交聊天机器人的特定测试和游戏意图。通过这些提示，我们旨在评估LLMs识别对话类型和用户测试目的的能力，以得出减轻越狱风险的聊天机器人设计启示。我们的数据集将通过GitHub公开提供。

> User interactions with conversational agents (CAs) evolve in the era of heavily guardrailed large language models (LLMs). As users push beyond programmed boundaries to explore and build relationships with these systems, there is a growing concern regarding the potential for unauthorized access or manipulation, commonly referred to as "jailbreaking." Moreover, with CAs that possess highly human-like qualities, users show a tendency toward initiating intimate sexual interactions or attempting to tame their chatbots. To capture and reflect these in-the-wild interactions into chatbot designs, we propose RICoTA, a Korean red teaming dataset that consists of 609 prompts challenging LLMs with in-the-wild user-made dialogues capturing jailbreak attempts. We utilize user-chatbot conversations that were self-posted on a Korean Reddit-like community, containing specific testing and gaming intentions with a social chatbot. With these prompts, we aim to evaluate LLMs' ability to identify the type of conversation and users' testing purposes to derive chatbot design implications for mitigating jailbreaking risks. Our dataset will be made publicly available via GitHub.

[Arxiv](https://arxiv.org/abs/2501.17715)