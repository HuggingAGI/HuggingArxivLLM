# # AI 红队自动化：优势尽显

发布时间：2025年04月28日

`LLM应用

理由：这篇论文主要探讨了大型语言模型（LLM）的安全漏洞及其在安全测试中的应用。研究分析了用户在不同攻击方法下的表现，比较了自动化与手动方法的效果，并提出了结合两者以优化安全测试的策略。这些内容属于LLM的实际应用和安全测试领域，因此归类为LLM应用。` `信息安全` `人工智能`

> The Automation Advantage in AI Red Teaming

# 摘要

> 本文基于Crucible的数据，对大型语言模型（LLM）的安全漏洞进行了深入分析，涵盖了1,674名用户在30项LLM挑战中发起的214,271次攻击尝试。研究发现，尽管仅有5.2%的用户采用了自动化方法，但自动化方法的表现显著优于手动方法（成功率分别为69.5%和47.6%）。我们发现，自动化方法在系统性探索和模式匹配挑战中表现出色，而手动方法在某些创造性推理场景中仍保持速度优势，成功时解决问题的速度是自动化的5倍。需要系统性探索的挑战类别最能通过自动化手段有效应对，而直观类挑战有时在解决时间上更倾向于手动方法。这些结果揭示了算法测试如何正在改变AI红队实践，对进攻性安全研究和防御措施都有重要启示。我们的分析表明，最优的安全测试应结合人类的创造力来制定策略，同时借助程序化执行进行彻底探索。

> This paper analyzes Large Language Model (LLM) security vulnerabilities based on data from Crucible, encompassing 214,271 attack attempts by 1,674 users across 30 LLM challenges. Our findings reveal automated approaches significantly outperform manual techniques (69.5% vs 47.6% success rate), despite only 5.2% of users employing automation. We demonstrate that automated approaches excel in systematic exploration and pattern matching challenges, while manual approaches retain speed advantages in certain creative reasoning scenarios, often solving problems 5x faster when successful. Challenge categories requiring systematic exploration are most effectively targeted through automation, while intuitive challenges sometimes favor manual techniques for time-to-solve metrics. These results illuminate how algorithmic testing is transforming AI red-teaming practices, with implications for both offensive security research and defensive measures. Our analysis suggests optimal security testing combines human creativity for strategy development with programmatic execution for thorough exploration.

[Arxiv](https://arxiv.org/abs/2504.19855)