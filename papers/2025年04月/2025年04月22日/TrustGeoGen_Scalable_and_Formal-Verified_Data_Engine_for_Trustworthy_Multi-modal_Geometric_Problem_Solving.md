# TrustGeoGen: 可扩展且形式化验证的数据引擎，助力可信多模态几何问题求解

发布时间：2025年04月22日

`其他`

> TrustGeoGen: Scalable and Formal-Verified Data Engine for Trustworthy Multi-modal Geometric Problem Solving

# 摘要

> 数学几何问题解决（GPS）需要有效整合多模态信息，同时确保逻辑推理的严谨性和可验证性。尽管大型语言模型在通用问题解决上取得了快速发展，但针对GPS任务的方法论和基准构建仍面临诸多挑战。现有合成GPS基准往往缺乏自洽性，且因LLMs的局限性而存在噪声和矛盾信息。为此，我们提出了一种名为TrustGeoGen的可扩展数据引擎，通过形式化验证为GPS研究提供了一个可靠基准。TrustGeoGen通过四项创新实现几何数据的高效合成：1）图表、文本描述与分步解答的多模态协同生成；2）基于规则的推理路径形式化验证；3）递归状态生成的复杂性自举机制；4）同时生成多解决方案变体与自我反思回溯轨迹的GeoExplore系列算法。通过严格的形式逻辑验证，TrustGeoGen生成了包含20万高质量样本的GeoTrust-200K数据集，以及专门用于评估的GeoTrust-test测试集。实验结果表明，现有最先进的模型在GeoTrust-test上的准确率仅为49.17%，凸显了该基准的高评价标准。值得注意的是，基于GeoTrust数据集训练的模型在GeoQA任务中实现了显著的OOD泛化能力，与基于OpenAI-o1的伪标签标注相比，逻辑不一致问题大幅减少。我们的代码已在GitHub上开源，欢迎访问https://github.com/Alpha-Innovator/TrustGeoGen获取。

> Mathematical geometric problem solving (GPS) often requires effective integration of multimodal information and verifiable logical coherence. Despite the fast development of large language models in general problem solving, it remains unresolved regarding with both methodology and benchmarks, especially given the fact that exiting synthetic GPS benchmarks are often not self-verified and contain noise and self-contradicted information due to the illusion of LLMs. In this paper, we propose a scalable data engine called TrustGeoGen for problem generation, with formal verification to provide a principled benchmark, which we believe lays the foundation for the further development of methods for GPS. The engine synthesizes geometric data through four key innovations: 1) multimodal-aligned generation of diagrams, textual descriptions, and stepwise solutions; 2) formal verification ensuring rule-compliant reasoning paths; 3) a bootstrapping mechanism enabling complexity escalation via recursive state generation and 4) our devised GeoExplore series algorithms simultaneously produce multi-solution variants and self-reflective backtracking traces. By formal logical verification, TrustGeoGen produces GeoTrust-200K dataset with guaranteed modality integrity, along with GeoTrust-test testset. Experiments reveal the state-of-the-art models achieve only 49.17\% accuracy on GeoTrust-test, demonstrating its evaluation stringency. Crucially, models trained on GeoTrust achieve OOD generalization on GeoQA, significantly reducing logical inconsistencies relative to pseudo-label annotated by OpenAI-o1. Our code is available at https://github.com/Alpha-Innovator/TrustGeoGen

[Arxiv](https://arxiv.org/abs/2504.15780)