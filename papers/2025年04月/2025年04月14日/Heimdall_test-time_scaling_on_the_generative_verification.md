# Heimdall：测试时间扩展在生成式验证中的应用

发布时间：2025年04月14日

`LLM应用` `人工智能` `计算机科学`

> Heimdall: test-time scaling on the generative verification

# 摘要

> AI系统能够构建和维护知识，但这一切都取决于它能否验证这些知识。近期关于长链式推理的研究展示了LLMs在解决竞争性问题上的巨大潜力，但它们的验证能力仍然较弱且未得到充分研究。本文中，我们提出了Heimdall，这是一个专注于长链式推理验证的LLM，能够准确判断解决方案的正确性。通过纯粹的强化学习，我们在竞争性数学问题上将验证准确率从62.5%提升至94.5%。借助重复采样的扩展方法，准确率进一步提升至97.5%。通过人工评估，Heimdall展现了令人印象深刻的泛化能力，成功检测出大多数具有挑战性的数学证明中的问题，而这些问题类型在训练过程中并未涉及。此外，我们提出了悲观验证方法，以扩展Heimdall的功能，从而提升问题求解的扩展性。该方法通过让Heimdall评估求解器模型提供的解决方案，并基于悲观原则，选择不确定性最小且最可能正确的解决方案。以DeepSeek-R1-Distill-Qwen-32B作为求解器模型，在16倍计算预算下，Pessimistic Verification将AIME2025问题的求解准确率从54.2%提升至70.0%，在更高计算预算下进一步提升至83.3%。使用更强大的求解器Gemini 2.5 Pro，准确率可达93.0%。最后，我们构建了一个自动知识发现系统，这是一个由三个部分组成的系统：一个问题提出者、一个解决方案提供者和一个解决方案验证者。通过使用数据合成工具NuminaMath来实现前两个部分，Heimdall能够有效识别数据集中的问题记录，并揭示近半数的数据存在缺陷，这一发现有趣地与NuminaMath近期的消融研究结果相吻合。

> An AI system can create and maintain knowledge only to the extent that it can verify that knowledge itself. Recent work on long Chain-of-Thought reasoning has demonstrated great potential of LLMs on solving competitive problems, but their verification ability remains to be weak and not sufficiently investigated. In this paper, we propose Heimdall, the long CoT verification LLM that can accurately judge the correctness of solutions. With pure reinforcement learning, we boost the verification accuracy from 62.5% to 94.5% on competitive math problems. By scaling with repeated sampling, the accuracy further increases to 97.5%. Through human evaluation, Heimdall demonstrates impressive generalization capabilities, successfully detecting most issues in challenging math proofs, the type of which is not included during training. Furthermore, we propose Pessimistic Verification to extend the functionality of Heimdall to scaling up the problem solving. It calls Heimdall to judge the solutions from a solver model and based on the pessimistic principle, selects the most likely correct solution with the least uncertainty. Taking DeepSeek-R1-Distill-Qwen-32B as the solver model, Pessimistic Verification improves the solution accuracy on AIME2025 from 54.2% to 70.0% with 16x compute budget and to 83.3% with more compute budget. With the stronger solver Gemini 2.5 Pro, the score reaches 93.0%. Finally, we prototype an automatic knowledge discovery system, a ternary system where one poses questions, another provides solutions, and the third verifies the solutions. Using the data synthesis work NuminaMath for the first two components, Heimdall effectively identifies problematic records within the dataset and reveals that nearly half of the data is flawed, which interestingly aligns with the recent ablation studies from NuminaMath.

[Arxiv](https://arxiv.org/abs/2504.10337)