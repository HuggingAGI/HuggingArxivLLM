# 行动胜于言辞：代理决策揭示语言模型中的隐性偏见

发布时间：2025年01月29日

`LLM理论

理由：这篇论文主要探讨了LLM在模拟人类行为时可能存在的隐性偏见，并提出了一种技术来系统性地揭示这些偏见。研究涉及对多个LLM的测试和评估，重点关注LLM在决策场景中的表现和潜在的偏见问题。这属于对LLM内部机制和行为的研究，因此归类为LLM理论。` `人工智能` `社会科学`

> Actions Speak Louder than Words: Agent Decisions Reveal Implicit Biases in Language Models

# 摘要

> 尽管公平性和对齐性的进展缓解了LLM在明确提示下的明显偏见，但我们推测这些模型在模拟人类行为时仍可能存在隐性偏见。为此，我们提出了一种技术，通过评估具有LLM生成的社会人口统计信息角色的代理之间的决策差异，系统性地揭示这些偏见。我们在三个社会人口统计群体和四个决策场景中测试了六个LLM，结果显示，最先进的LLM在几乎所有模拟中都表现出显著的社会人口统计差异，尽管减少了明显偏见，但更先进的模型隐性偏见更大。此外，与实证研究中的现实世界差异相比，我们揭示的偏见方向一致但明显放大。这种方向一致性表明我们的技术能有效揭示LLM中的系统性偏见，而非随机变化；隐性偏见的存在和放大则凸显了解决这些偏见的迫切需求。

> While advances in fairness and alignment have helped mitigate overt biases exhibited by large language models (LLMs) when explicitly prompted, we hypothesize that these models may still exhibit implicit biases when simulating human behavior. To test this hypothesis, we propose a technique to systematically uncover such biases across a broad range of sociodemographic categories by assessing decision-making disparities among agents with LLM-generated, sociodemographically-informed personas. Using our technique, we tested six LLMs across three sociodemographic groups and four decision-making scenarios. Our results show that state-of-the-art LLMs exhibit significant sociodemographic disparities in nearly all simulations, with more advanced models exhibiting greater implicit biases despite reducing explicit biases. Furthermore, when comparing our findings to real-world disparities reported in empirical studies, we find that the biases we uncovered are directionally aligned but markedly amplified. This directional alignment highlights the utility of our technique in uncovering systematic biases in LLMs rather than random variations; moreover, the presence and amplification of implicit biases emphasizes the need for novel strategies to address these biases.

[Arxiv](https://arxiv.org/abs/2501.17420)