# 在线多LLM选择：通过无结构上下文演进的上下文多臂老虎机实现在线多LLM选择

发布时间：2025年06月21日

`LLM应用` `人工智能` `机器学习`

> Online Multi-LLM Selection via Contextual Bandits under Unstructured Context Evolution

# 摘要

> 大型语言模型（LLMs）在响应行为、成本和优势上各不相同，为特定用户查询选择最合适的LLM颇具挑战性。我们研究了在线环境下自适应多LLM选择问题，学习器通过多步查询精炼与用户互动，在无离线数据集或模型内部访问的情况下依次选择LLMs。非结构化上下文演化是关键挑战：提示根据之前模型输出动态变化，这一黑箱过程无法模拟、建模或学习。为此，我们提出了首个针对非结构化提示动态的上下文强盗框架，用于顺序LLM选择。我们形式化了近视遗憾概念，并开发了基于LinUCB的算法，无需未来上下文预测即可实现次线性遗憾。我们还引入了预算感知和位置感知扩展，以适应可变查询成本和用户对早期高质量响应的偏好。我们的算法理论基础坚实，无需离线微调或特定数据集训练。在多样化基准上的实验表明，我们的方法在准确性和成本效率上均优于现有LLM路由策略，验证了上下文强盗在实时、自适应LLM选择中的强大能力。

> Large language models (LLMs) exhibit diverse response behaviors, costs, and strengths, making it challenging to select the most suitable LLM for a given user query. We study the problem of adaptive multi-LLM selection in an online setting, where the learner interacts with users through multi-step query refinement and must choose LLMs sequentially without access to offline datasets or model internals. A key challenge arises from unstructured context evolution: the prompt dynamically changes in response to previous model outputs via a black-box process, which cannot be simulated, modeled, or learned. To address this, we propose the first contextual bandit framework for sequential LLM selection under unstructured prompt dynamics. We formalize a notion of myopic regret and develop a LinUCB-based algorithm that provably achieves sublinear regret without relying on future context prediction. We further introduce budget-aware and positionally-aware (favoring early-stage satisfaction) extensions to accommodate variable query costs and user preferences for early high-quality responses. Our algorithms are theoretically grounded and require no offline fine-tuning or dataset-specific training. Experiments on diverse benchmarks demonstrate that our methods outperform existing LLM routing strategies in both accuracy and cost-efficiency, validating the power of contextual bandits for real-time, adaptive LLM selection.

[Arxiv](https://arxiv.org/abs/2506.17670)