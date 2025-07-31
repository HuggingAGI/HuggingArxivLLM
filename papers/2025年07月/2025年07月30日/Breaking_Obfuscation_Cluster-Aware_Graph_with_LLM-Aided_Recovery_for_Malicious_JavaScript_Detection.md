# 打破混淆：LLM 辅助恢复的聚类感知图用于恶意 JavaScript 检测

发布时间：2025年07月30日

`LLM应用` `信息安全` `网络应用`

> Breaking Obfuscation: Cluster-Aware Graph with LLM-Aided Recovery for Malicious JavaScript Detection

# 摘要

> 随着基于网络的应用程序和云服务的迅速扩展，恶意JavaScript代码持续对用户隐私、系统完整性和企业安全构成重大威胁。然而，由于复杂的代码混淆技术和JavaScript固有的语言特性（特别是其嵌套闭包结构和语法灵活性），检测此类威胁仍面临挑战。我们提出了一种名为DeCoda的混合防御框架，它结合了基于LLM的去混淆技术和代码图学习技术。首先，我们构建了一个多阶段优化的提示学习流水线，其中LLM逐步从混淆输入中重构原始代码结构，并生成标准化的抽象语法树（AST）表示。在JavaScript AST中，动态类型分散了语义相似的节点，而深度嵌套的函数破坏了作用域捕获，导致结构噪声和语义歧义。为此，我们提出了一种基于Cluster-wise Graph的分层代码图表示学习方法，该方法协同整合了图变换网络、节点聚类和节点到簇注意力机制，以同时捕捉局部节点级别的语义和全局簇诱导的结构关系。实验结果表明，我们的方法在两个基准数据集上实现了F1值分别为94.64%和97.71%，分别比现有最优基线方法提高了10.74%和13.85%。在固定FPR水平（0.0001、0.001、0.01）下的误报控制评估中，我们的方法分别比最佳基线方法高出4.82、5.91和2.53的TPR。这些结果不仅突显了基于LLM的去混淆技术的有效性，还强调了在恶意代码检测中建模簇级别关系的重要性。

> With the rapid expansion of web-based applications and cloud services, malicious JavaScript code continues to pose significant threats to user privacy, system integrity, and enterprise security. But, detecting such threats remains challenging due to sophisticated code obfuscation techniques and JavaScript's inherent language characteristics, particularly its nested closure structures and syntactic flexibility. In this work, we propose DeCoda, a hybrid defense framework that combines large language model (LLM)-based deobfuscation with code graph learning: (1) We first construct a sophisticated prompt-learning pipeline with multi-stage refinement, where the LLM progressively reconstructs the original code structure from obfuscated inputs and then generates normalized Abstract Syntax Tree (AST) representations; (2) In JavaScript ASTs, dynamic typing scatters semantically similar nodes while deeply nested functions fracture scope capturing, introducing structural noise and semantic ambiguity. To address these challenges, we then propose to learn hierarchical code graph representations via a Cluster-wise Graph that synergistically integrates graph transformer network, node clustering, and node-to-cluster attention to simultaneously capture both local node-level semantics and global cluster-induced structural relationships from AST graph. Experimental results demonstrate that our method achieves F1-scores of 94.64% and 97.71% on two benchmark datasets, demonstrating absolute improvements of 10.74% and 13.85% over state-of-the-art baselines. In false-positive control evaluation at fixed FPR levels (0.0001, 0.001, 0.01), our approach delivers 4.82, 5.91, and 2.53 higher TPR respectively compared to the best-performing baseline. These results highlight the effectiveness of LLM-based deobfuscation and underscore the importance of modeling cluster-level relationships in detecting malicious code.

[Arxiv](https://arxiv.org/abs/2507.22447)