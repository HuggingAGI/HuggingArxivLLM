# Bohdi：异构大语言模型融合结合自动数据探索

发布时间：2025年06月04日

`LLM应用` `合成数据`

> Bohdi: Heterogeneous LLM Fusion with Automatic Data Exploration

# 摘要

> 异构大语言模型（LLM）融合通过巧妙融合多个架构各异的源LLM的优势，构建出一个计算开销低的目标LLM。尽管前景广阔，现有方法仍存在两大局限：1）依赖于特定领域的实际数据进行知识融合，导致目标LLM无法充分掌握跨领域知识；2）采用固定的跨领域数据分配比例，无法根据目标LLM在不同领域能力的波动进行动态调整，造成能力失衡。为克服这些限制，我们提出Bohdi——一个仅基于合成数据的异构LLM融合框架。通过将知识领域组织成层次树状结构，Bohdi借助多模型协作实现自动化的领域探索与多领域数据生成，从而全面提取源LLM的知识。将知识树上的领域扩展与数据采样比例分配形式化为分层多臂老虎机问题，Bohdi借助设计的DynaBranches机制，可根据目标LLM在各领域的能力反馈，自适应地调整采样比例。结合我们提出的内省-重生（IR）机制，DynaBranches通过滑动窗口二项式似然比检验（SWBLRT），动态追踪目标LLM更新过程中的能力变化，进一步提升其在线适应能力。在全面基准测试中的对比实验结果表明，Bohdi显著超越现有基线，在多个目标LLM上表现出更高的数据效率，并几乎消除了目标LLM的能力失衡。我们的代码可在https://github.com/gjq100/Bohdi.git获取。


> Heterogeneous Large Language Model (LLM) fusion integrates the strengths of multiple source LLMs with different architectures into a target LLM with low computational overhead. While promising, existing methods suffer from two major limitations: 1) reliance on real data from limited domain for knowledge fusion, preventing the target LLM from fully acquiring knowledge across diverse domains, and 2) fixed data allocation proportions across domains, failing to dynamically adjust according to the target LLM's varying capabilities across domains, leading to a capability imbalance. To overcome these limitations, we propose Bohdi, a synthetic-data-only heterogeneous LLM fusion framework. Through the organization of knowledge domains into a hierarchical tree structure, Bohdi enables automatic domain exploration and multi-domain data generation through multi-model collaboration, thereby comprehensively extracting knowledge from source LLMs. By formalizing domain expansion and data sampling proportion allocation on the knowledge tree as a Hierarchical Multi-Armed Bandit problem, Bohdi leverages the designed DynaBranches mechanism to adaptively adjust sampling proportions based on the target LLM's performance feedback across domains. Integrated with our proposed Introspection-Rebirth (IR) mechanism, DynaBranches dynamically tracks capability shifts during target LLM's updates via Sliding Window Binomial Likelihood Ratio Testing (SWBLRT), further enhancing its online adaptation capability. Comparative experimental results on a comprehensive suite of benchmarks demonstrate that Bohdi significantly outperforms existing baselines on multiple target LLMs, exhibits higher data efficiency, and virtually eliminates the imbalance in the target LLM's capabilities. Our code is available at https://github.com/gjq100/Bohdi.git.

[Arxiv](https://arxiv.org/abs/2506.15721)