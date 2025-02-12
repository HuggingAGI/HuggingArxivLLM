# # 幻觉CAPTCHA：利用视觉幻觉设计的验证码
# 幻觉CAPTCHA：利用视觉幻觉设计的验证码

发布时间：2025年02月08日

`LLM应用` `网络安全` `人工智能`

> IllusionCAPTCHA: A CAPTCHA based on Visual Illusion

# 摘要

> CAPTCHA长期以来一直是保护应用免受自动化机器人攻击的重要工具。最初，它们被设计成简单的识别问题，以区分人类和机器人。然而，随着恶意攻击者不断采用更复杂的CAPTCHA破解技术，CAPTCHA的难度也不断提升。然而，随着先进大语言模型（LLMs）的出现，现有CAPTCHA的有效性正受到严峻挑战。

为了解决这一问题，我们开展了一项实证研究，评估多模态LLMs在解决CAPTCHA方面的表现，并评估人类用户通常需要多少次尝试才能通过这些验证。研究发现，尽管LLMs能够解决大多数CAPTCHA，但它们在处理需要复杂推理的CAPTCHA时表现不佳，而这类CAPTCHA对人类用户也极具挑战性。有趣的是，我们的用户研究表明，大多数参与者需要第二次尝试才能通过这些推理类CAPTCHA，这一发现并未在以往研究中被报告。

基于实证研究结果，我们提出了IllusionCAPTCHA——一种采用“人易AI难”范式的新型安全机制。这种新CAPTCHA利用视觉错觉，设计出对人类直观但对AI极具迷惑性的任务。此外，我们开发了一种结构化的分步方法，用于生成误导选项，特别引导LLMs做出错误选择，降低它们成功破解CAPTCHA的可能性。我们的评估显示，IllusionCAPTCHA能够100%成功迷惑LLMs。而且，我们的结构化设计显著提高了AI在尝试解决这些挑战时的出错概率。用户研究结果表明，86.95%的参与者在首次尝试时就能成功通过CAPTCHA，优于其他CAPTCHA系统表现。


> CAPTCHAs have long been essential tools for protecting applications from automated bots. Initially designed as simple questions to distinguish humans from bots, they have become increasingly complex to keep pace with the proliferation of CAPTCHA-cracking techniques employed by malicious actors. However, with the advent of advanced large language models (LLMs), the effectiveness of existing CAPTCHAs is now being undermined.
  To address this issue, we have conducted an empirical study to evaluate the performance of multimodal LLMs in solving CAPTCHAs and to assess how many attempts human users typically need to pass them. Our findings reveal that while LLMs can solve most CAPTCHAs, they struggle with those requiring complex reasoning type of CAPTCHA that also presents significant challenges for human users. Interestingly, our user study shows that the majority of human participants require a second attempt to pass these reasoning CAPTCHAs, a finding not reported in previous research.
  Based on empirical findings, we present IllusionCAPTCHA, a novel security mechanism employing the "Human-Easy but AI-Hard" paradigm. This new CAPTCHA employs visual illusions to create tasks that are intuitive for humans but highly confusing for AI models. Furthermore, we developed a structured, step-by-step method that generates misleading options, which particularly guide LLMs towards making incorrect choices and reduce their chances of successfully solving CAPTCHAs. Our evaluation shows that IllusionCAPTCHA can effectively deceive LLMs 100% of the time. Moreover, our structured design significantly increases the likelihood of AI errors when attempting to solve these challenges. Results from our user study indicate that 86.95% of participants successfully passed the CAPTCHA on their first attempt, outperforming other CAPTCHA systems.

[Arxiv](https://arxiv.org/abs/2502.05461)