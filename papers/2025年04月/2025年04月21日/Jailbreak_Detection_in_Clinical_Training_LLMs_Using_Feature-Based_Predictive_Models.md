# 临床训练大型语言模型中的越狱检测：基于特征的预测方法

发布时间：2025年04月21日

`LLM应用` `机器学习`

> Jailbreak Detection in Clinical Training LLMs Using Feature-Based Predictive Models

# 摘要

> 大型语言模型（LLMs）的越狱行为威胁了其在教育等敏感领域的安全使用，让用户绕过了伦理保障措施。本研究聚焦于检测2-Sigma平台中的越狱行为，该平台是一个通过LLMs模拟患者互动的临床教育平台。我们使用四种与越狱行为高度相关的语言变量，标注了158个对话中的2300多个提示。提取的特征被用于训练多个预测模型，包括决策树、基于模糊逻辑的分类器、提升方法和逻辑回归。结果显示，基于特征的预测模型始终优于提示工程，其中模糊决策树表现最佳。我们的研究发现，基于语言特征的模型是越狱检测的有效且可解释的替代方案。我们建议未来研究探索结合提示灵活性与规则鲁棒性的混合框架，用于教育LLMs中的实时、频谱越狱监控。

> Jailbreaking in Large Language Models (LLMs) threatens their safe use in sensitive domains like education by allowing users to bypass ethical safeguards. This study focuses on detecting jailbreaks in 2-Sigma, a clinical education platform that simulates patient interactions using LLMs. We annotated over 2,300 prompts across 158 conversations using four linguistic variables shown to correlate strongly with jailbreak behavior. The extracted features were used to train several predictive models, including Decision Trees, Fuzzy Logic-based classifiers, Boosting methods, and Logistic Regression. Results show that feature-based predictive models consistently outperformed Prompt Engineering, with the Fuzzy Decision Tree achieving the best overall performance. Our findings demonstrate that linguistic-feature-based models are effective and explainable alternatives for jailbreak detection. We suggest future work explore hybrid frameworks that integrate prompt-based flexibility with rule-based robustness for real-time, spectrum-based jailbreak monitoring in educational LLMs.

[Arxiv](https://arxiv.org/abs/2505.00010)