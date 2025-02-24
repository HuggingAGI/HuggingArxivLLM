# # 安全标准是否对每个人都一视同仁？大型语言模型的用户个性化安全评估

发布时间：2025年02月20日

`LLM应用` `人工智能`

> Is Safety Standard Same for Everyone? User-Specific Safety Evaluation of Large Language Models

# 摘要

> 随着大型语言模型（LLM）代理的蓬勃发展，其安全漏洞也逐渐显现。现有的基准测试主要依赖通用标准来评估LLM的安全性，却忽视了用户特定的安全标准。然而，LLM的安全标准可能因用户而异，而非统一适用。这引出了一个关键问题：在考虑用户特定安全标准时，LLM代理是否能够安全运行？尽管这对确保LLM的安全使用至关重要，但目前尚无基准数据集可用于评估LLM的用户特定安全性。为解决这一问题，我们推出了U-SAFEBENCH，这是首个专注于评估LLM用户特定安全性的基准测试。通过对18个广泛使用的LLM的评估，我们发现当前LLM在考虑用户特定安全标准时仍存在安全隐患，这一发现填补了该领域的空白。为应对这一安全漏洞，我们提出了一种基于链式思考的简单解决方案，并验证了其在提升用户特定安全性方面的有效性。我们的基准测试和代码已在GitHub上开源，地址为https://github.com/yeonjun-in/U-SafeBench。

> As the use of large language model (LLM) agents continues to grow, their safety vulnerabilities have become increasingly evident. Extensive benchmarks evaluate various aspects of LLM safety by defining the safety relying heavily on general standards, overlooking user-specific standards. However, safety standards for LLM may vary based on a user-specific profiles rather than being universally consistent across all users. This raises a critical research question: Do LLM agents act safely when considering user-specific safety standards? Despite its importance for safe LLM use, no benchmark datasets currently exist to evaluate the user-specific safety of LLMs. To address this gap, we introduce U-SAFEBENCH, the first benchmark designed to assess user-specific aspect of LLM safety. Our evaluation of 18 widely used LLMs reveals current LLMs fail to act safely when considering user-specific safety standards, marking a new discovery in this field. To address this vulnerability, we propose a simple remedy based on chain-of-thought, demonstrating its effectiveness in improving user-specific safety. Our benchmark and code are available at https://github.com/yeonjun-in/U-SafeBench.

[Arxiv](https://arxiv.org/abs/2502.15086)