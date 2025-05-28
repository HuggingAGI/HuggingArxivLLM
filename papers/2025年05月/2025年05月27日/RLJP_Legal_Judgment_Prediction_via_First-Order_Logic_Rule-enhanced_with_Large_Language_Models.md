# # 标题
RLJP: 结合法规推理的大型语言模型在法律判决预测中的应用

发布时间：2025年05月27日

`LLM应用` `法律AI`

> RLJP: Legal Judgment Prediction via First-Order Logic Rule-enhanced with Large Language Models

# 摘要

> 法律判决预测（LJP）是法律AI领域的核心任务。现有的语义增强型LJP模型虽然通过整合司法判例和法律知识实现了高性能预测，但忽视了法律推理逻辑这一判决中的关键要素。法律推理逻辑需要严格的逻辑分析，而现有方法虽能利用这一逻辑提升预测质量，却因逻辑刚性限制了其在不同案例逻辑框架中的适应性，尤其在复杂、冗长且细节繁多的案件中表现不足。为此，我们提出了一种基于一阶逻辑（FOL）形式化和对比学习（CL）的规则增强法律判决预测框架，旨在构建法律判决逻辑的自适应调整机制，进一步提升LJP性能。受人类备考过程启发，我们的方法采用三阶段策略：首先，利用FOL形式化初始化判决规则，准确捕捉复杂推理逻辑；其次，提出基于易混淆案例测验的困惑感知对比学习（CACL），动态优化判决规则；最后，利用优化后的规则进行法律判决预测。在两个公开数据集上的实验结果表明，我们的方法在所有指标上均表现优异。代码已公开发布{https://anonymous.4open.science/r/RLJP-FDF1}。

> Legal Judgment Prediction (LJP) is a pivotal task in legal AI. Existing semantic-enhanced LJP models integrate judicial precedents and legal knowledge for high performance. But they neglect legal reasoning logic, a critical component of legal judgments requiring rigorous logical analysis. Although some approaches utilize legal reasoning logic for high-quality predictions, their logic rigidity hinders adaptation to case-specific logical frameworks, particularly in complex cases that are lengthy and detailed. This paper proposes a rule-enhanced legal judgment prediction framework based on first-order logic (FOL) formalism and comparative learning (CL) to develop an adaptive adjustment mechanism for legal judgment logic and further enhance performance in LJP. Inspired by the process of human exam preparation, our method follows a three-stage approach: first, we initialize judgment rules using the FOL formalism to capture complex reasoning logic accurately; next, we propose a Confusion-aware Contrastive Learning (CACL) to dynamically optimize the judgment rules through a quiz consisting of confusable cases; finally, we utilize the optimized judgment rules to predict legal judgments. Experimental results on two public datasets show superior performance across all metrics. The code is publicly available{https://anonymous.4open.science/r/RLJP-FDF1}.

[Arxiv](https://arxiv.org/abs/2505.21281)