# 探索决策政策的关键测试场景：LLM 之法

发布时间：2024年12月09日

`LLM应用` `自动驾驶` `机器人技术`

> Exploring Critical Testing Scenarios for Decision-Making Policies: An LLM Approach

# 摘要

> 近年来，自动驾驶、机器人技术等领域的决策政策取得了惊人成就。鉴于存在可能危及可靠性的关键场景，决策政策的测试至关重要。众多研究都致力于这些政策的测试。然而，仍存在重大挑战，比如因政策和测试环境复杂导致的测试效率低、多样性差。受大型语言模型（LLMs）出色能力的启发，本文提出了一个由LLM驱动的在线测试框架，用于高效测试决策政策。其核心思想是运用基于LLM的测试场景生成器，通过思考和推理智能生成有挑战性的测试用例。具体来说，我们先设计了“生成 - 测试 - 反馈”流程，并应用模板化提示工程充分发挥LLM的知识和推理能力。接着，引入多尺度场景生成策略，解决LLM在微调时面临的固有难题，进一步提升测试效率。最后，在五个广泛使用的基准上对LLM驱动的方法进行评估。实验结果显示，我们的方法在发现关键和多样场景方面显著优于基线方法。

> Recent years have witnessed surprising achievements of decision-making policies across various fields, such as autonomous driving and robotics. Testing for decision-making policies is crucial with the existence of critical scenarios that may threaten their reliability. Numerous research efforts have been dedicated to testing these policies. However, there are still significant challenges, such as low testing efficiency and diversity due to the complexity of the policies and environments under test. Inspired by the remarkable capabilities of large language models (LLMs), in this paper, we propose an LLM-driven online testing framework for efficiently testing decision-making policies. The main idea is to employ an LLM-based test scenario generator to intelligently generate challenging test cases through contemplation and reasoning. Specifically, we first design a "generate-test-feedback" pipeline and apply templated prompt engineering to fully leverage the knowledge and reasoning abilities of LLMs. Then, we introduce a multi-scale scenario generation strategy to address the inherent challenges LLMs face in making fine adjustments, further enhancing testing efficiency. Finally, we evaluate the LLM-driven approach on five widely used benchmarks. The experimental results demonstrate that our method significantly outperforms baseline approaches in uncovering both critical and diverse scenarios.

[Arxiv](https://arxiv.org/abs/2412.06684)