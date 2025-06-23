# LDI: 局部数据填补

发布时间：2025年06月19日

`LLM应用` `数据处理` `数据分析`

> LDI: Localized Data Imputation

# 摘要

> 缺失值是现实世界表格数据中的常见问题，会对后续分析造成显著影响。虽然大型语言模型（LLMs）在数据插补方面展现出潜力，但现有方法通常依赖宽泛且未经筛选的提示，导致准确性、可扩展性和可解释性方面的妥协。我们提出了LDI（局部化数据插补）这一创新框架，通过为每个缺失值选择一个紧凑且上下文相关的属性和元组子集，显著提升了基于LLM的插补准确性和透明度。这种局部化提示减少了噪声，通过揭示影响每个预测的数据，实现了可追溯性，并且在托管LLMs和轻量级本地模型上均表现优异。我们在四个现实世界数据集上的广泛实验表明，LDI优于现有最优方法，使用托管LLMs时准确率提高了高达8%。与轻量级本地模型配合使用时，增益更为显著，在某些数据集上分别使用3个和10个示例时，准确率达到了近17%和97%。除了更高的准确率，LDI还提供了更好的可解释性和对数据不一致的鲁棒性，使其非常适合高风险和隐私敏感的应用场景。

> Missing values are a common challenge in real-world tabular data and can significantly impair downstream analysis. While Large Language Models (LLMs) have recently shown promise in data imputation, existing methods often rely on broad, unfiltered prompts that compromise accuracy, scalability, and explainability. We introduce LDI (Localized Data Imputation), a novel framework that improves both the accuracy and transparency of LLM-based imputation by selecting a compact, contextually relevant subset of attributes and tuples for each missing value. This localized prompting reduces noise, enables traceability by revealing which data influenced each prediction, and is effective across both hosted LLMs and lightweight local models. Our extensive experiments on four real-world datasets show that LDI outperforms state-of-the-art methods, achieving up to 8% higher accuracy when using hosted LLMs. The gains are more substantial with lightweight local models, reaching nearly 17% and 97% accuracy on some datasets when using 3 and 10 examples, respectively. In addition to higher accuracy, LDI offers improved interpretability and robustness to data inconsistencies, making it well-suited for high-stakes and privacy-sensitive applications.

[Arxiv](https://arxiv.org/abs/2506.16616)