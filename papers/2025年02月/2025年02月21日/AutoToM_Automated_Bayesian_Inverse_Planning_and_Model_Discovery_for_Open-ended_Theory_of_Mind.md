# AutoToM：面向开放性心智理论的自动化贝叶斯逆向规划与模型发现

发布时间：2025年02月21日

`Agent` `社交智能` `认知科学`

> AutoToM: Automated Bayesian Inverse Planning and Model Discovery for Open-ended Theory of Mind

# 摘要

> 理解他人心理状态的能力——心智理论（ToM），是开发社交智能代理的核心。当前的心智理论推理方法存在两极分化：一种依赖于通过提示大型语言模型（LLMs），这种方法容易出现系统性错误；另一种则采用 rigid、手工打造的贝叶斯心智理论（BToM）模型，这类模型虽更为稳健，但无法跨领域泛化。在本研究中，我们提出了 AutoToM，这是一种实现开放域机器心智理论的自动化贝叶斯心智理论方法。AutoToM 拥有三大核心优势：在任何领域中运行、推断任何心理变量、进行任意阶数的稳健心智理论推理。面对一个心智理论推理问题，AutoToM 的工作流程如下：首先提出一个初始的 BToM 模型，然后基于该模型进行自动化贝叶斯逆向规划，利用 LLM 作为后端支持。根据推理的不确定性，它会通过引入额外的心理变量和/或在上下文中增加更多时间步来迭代优化模型。在多个心智理论基准上的实证评估表明，AutoToM 一致实现了最先进的性能，为机器心智理论提供了一种可扩展、稳健且可解释的方法。


> Theory of Mind (ToM), the ability to understand people's mental variables based on their behavior, is key to developing socially intelligent agents. Current approaches to Theory of Mind reasoning either rely on prompting Large Language Models (LLMs), which are prone to systematic errors, or use rigid, handcrafted Bayesian Theory of Mind (BToM) models, which are more robust but cannot generalize across different domains. In this work, we introduce AutoToM, an automated Bayesian Theory of Mind method for achieving open-ended machine Theory of Mind. AutoToM can operate in any domain, infer any mental variable, and conduct robust Theory of Mind reasoning of any order. Given a Theory of Mind inference problem, AutoToM first proposes an initial BToM model. It then conducts automated Bayesian inverse planning based on the proposed model, leveraging an LLM as the backend. Based on the uncertainty of the inference, it iteratively refines the model, by introducing additional mental variables and/or incorporating more timesteps in the context. Empirical evaluations across multiple Theory of Mind benchmarks demonstrate that AutoToM consistently achieves state-of-the-art performance, offering a scalable, robust, and interpretable approach to machine Theory of Mind.

[Arxiv](https://arxiv.org/abs/2502.15676)