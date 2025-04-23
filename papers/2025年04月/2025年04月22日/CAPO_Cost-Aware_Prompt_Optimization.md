# CAPO：智能提示优化，成本感知设计

发布时间：2025年04月22日

`LLM应用

摘要讨论了如何优化大型语言模型的提示工程，提出了一种新的优化算法CAPO，以提高效率和效果，属于LLM的应用层面改进。` `人工智能`

> CAPO: Cost-Aware Prompt Optimization

# 摘要

> 大型语言模型（LLMs）通过简单地根据提示（prompt）指导，已经彻底改变了自然语言处理，能够解决各种各样的任务。然而，它们的性能对提示的制定方式高度敏感。虽然自动化提示优化通过寻找最优提示解决了这一挑战，但目前的方法需要大量 LLM 调用和输入标记，使得提示优化变得昂贵。我们引入了 CAPO（Cost-Aware Prompt Optimization），一种通过集成 AutoML 技术来提高提示优化效率的算法。CAPO 采用进化方法，将 LLM 作为运算器，结合了竞速机制以节省评估次数，并采用多目标优化来平衡性能与提示长度。它同时优化指令和少量示例，同时利用任务描述以提高鲁棒性。我们在多样化的数据集和 LLM 上进行了广泛实验，结果表明 CAPO 在 15 个案例中的 11 个案例中优于最先进的离散提示优化方法，提升幅度高达 21%。我们的算法在较小的预算下已经实现了更好的性能，通过竞速节省了评估次数，并通过长度惩罚减少了平均提示长度，使其既经济高效又具备成本意识。即使没有少量示例，CAPO 也优于其竞争对手，并且通常对初始提示保持稳健。CAPO 代表了通过提高成本效益使提示优化更强大和更易用的重要一步。

> Large language models (LLMs) have revolutionized natural language processing by solving a wide range of tasks simply guided by a prompt. Yet their performance is highly sensitive to prompt formulation. While automated prompt optimization addresses this challenge by finding optimal prompts, current methods require a substantial number of LLM calls and input tokens, making prompt optimization expensive. We introduce CAPO (Cost-Aware Prompt Optimization), an algorithm that enhances prompt optimization efficiency by integrating AutoML techniques. CAPO is an evolutionary approach with LLMs as operators, incorporating racing to save evaluations and multi-objective optimization to balance performance with prompt length. It jointly optimizes instructions and few-shot examples while leveraging task descriptions for improved robustness. Our extensive experiments across diverse datasets and LLMs demonstrate that CAPO outperforms state-of-the-art discrete prompt optimization methods in 11/15 cases with improvements up to 21%p. Our algorithm achieves better performances already with smaller budgets, saves evaluations through racing, and decreases average prompt length via a length penalty, making it both cost-efficient and cost-aware. Even without few-shot examples, CAPO outperforms its competitors and generally remains robust to initial prompts. CAPO represents an important step toward making prompt optimization more powerful and accessible by improving cost-efficiency.

[Arxiv](https://arxiv.org/abs/2504.16005)