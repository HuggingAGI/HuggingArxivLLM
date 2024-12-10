# AlphaVerus：借助自我改进的翻译和树细化来推动形式验证的代码生成

发布时间：2024年12月08日

`LLM应用` `软件开发` `代码生成`

> AlphaVerus: Bootstrapping Formally Verified Code Generation through Self-Improving Translation and Treefinement

# 摘要

> 使用大型语言模型进行自动代码生成颇具吸引力，然而生成代码的正确性难以保证。我们打算借助形式验证为生成代码的正确性提供数学保障。但利用 LLMs 生成经过形式验证的代码面临训练数据稀缺和形式证明复杂的难题。为应对此挑战，我们推出了 AlphaVerus，这是一个能自我完善的框架，通过不断从资源更丰富的语言翻译程序，并利用验证器的反馈来促进经过形式验证的代码生成。AlphaVerus 分三个阶段运作：探索候选翻译、Treefinement（一种利用验证器反馈优化程序的新型树搜索算法），以及过滤不匹配的规范和程序以防奖励作弊。通过这一迭代过程，AlphaVerus 让 LLaMA-3.1-70B 模型无需人工干预或模型微调就能生成经过验证的代码。AlphaVerus 展现出为 HumanEval 和 MBPP 生成经过形式验证的解决方案的能力，为真正可信的代码生成代理奠定了基础。

> Automated code generation with large language models has gained significant traction, but there remains no guarantee on the correctness of generated code. We aim to use formal verification to provide mathematical guarantees that the generated code is correct. However, generating formally verified code with LLMs is hindered by the scarcity of training data and the complexity of formal proofs. To tackle this challenge, we introduce AlphaVerus, a self-improving framework that bootstraps formally verified code generation by iteratively translating programs from a higher-resource language and leveraging feedback from a verifier. AlphaVerus operates in three phases: exploration of candidate translations, Treefinement -- a novel tree search algorithm for program refinement using verifier feedback, and filtering misaligned specifications and programs to prevent reward hacking. Through this iterative process, AlphaVerus enables a LLaMA-3.1-70B model to generate verified code without human intervention or model finetuning. AlphaVerus shows an ability to generate formally verified solutions for HumanEval and MBPP, laying the groundwork for truly trustworthy code-generation agents.

[Arxiv](https://arxiv.org/abs/2412.06176)