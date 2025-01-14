# 探索与缓解投票制排行榜的对抗性操纵

发布时间：2025年01月13日

`LLM应用

**理由**：这篇论文主要讨论了如何通过对抗性操纵来影响基于投票的LLM评估基准（如Chatbot Arena），并提出了相应的防御措施。这涉及到LLM在实际应用中的评估和安全性问题，属于LLM在实际场景中的应用和优化，因此分类为LLM应用。` `人工智能` `网络安全`

> Exploring and Mitigating Adversarial Manipulation of Voting-Based Leaderboards

# 摘要

> # 摘要
如今，评估大型语言模型（LLMs）的常见方法是让人类手动投票来评估模型输出，这与评估特定任务知识或技能的典型基准不同。Chatbot Arena 是这类基准中最受欢迎的，它通过让用户在两个随机选择的模型之间选择更好的响应来对模型进行排名（不透露哪个模型生成了响应）。这些平台被广泛认为是衡量LLM能力的公平且准确的工具。在本文中，我们展示了如果未实施机器人保护和其他防御措施，这些基于投票的基准可能容易受到对抗性操纵。具体来说，我们展示了一个攻击者可以以大约一千票的成本改变排行榜（以推广他们喜欢的模型或贬低竞争对手）（在Chatbot Arena的模拟离线版本中验证）。我们的攻击包括两个步骤：首先，我们展示了攻击者如何以超过95%的准确率确定哪个模型生成了给定的回复；然后，攻击者可以利用这些信息持续投票支持（或反对）目标模型。与Chatbot Arena开发者合作，我们识别、提出并实施了缓解措施，以提高Chatbot Arena对抗对抗性操纵的鲁棒性，根据我们的分析，这大大增加了此类攻击的成本。其中一些防御措施在我们合作之前已经存在，例如使用Cloudflare进行机器人保护、恶意用户检测和速率限制。其他措施，包括reCAPTCHA和登录，正在集成以增强Chatbot Arena的安全性。

> It is now common to evaluate Large Language Models (LLMs) by having humans manually vote to evaluate model outputs, in contrast to typical benchmarks that evaluate knowledge or skill at some particular task. Chatbot Arena, the most popular benchmark of this type, ranks models by asking users to select the better response between two randomly selected models (without revealing which model was responsible for the generations). These platforms are widely trusted as a fair and accurate measure of LLM capabilities. In this paper, we show that if bot protection and other defenses are not implemented, these voting-based benchmarks are potentially vulnerable to adversarial manipulation. Specifically, we show that an attacker can alter the leaderboard (to promote their favorite model or demote competitors) at the cost of roughly a thousand votes (verified in a simulated, offline version of Chatbot Arena). Our attack consists of two steps: first, we show how an attacker can determine which model was used to generate a given reply with more than $95\%$ accuracy; and then, the attacker can use this information to consistently vote for (or against) a target model. Working with the Chatbot Arena developers, we identify, propose, and implement mitigations to improve the robustness of Chatbot Arena against adversarial manipulation, which, based on our analysis, substantially increases the cost of such attacks. Some of these defenses were present before our collaboration, such as bot protection with Cloudflare, malicious user detection, and rate limiting. Others, including reCAPTCHA and login are being integrated to strengthen the security in Chatbot Arena.

[Arxiv](https://arxiv.org/abs/2501.07493)