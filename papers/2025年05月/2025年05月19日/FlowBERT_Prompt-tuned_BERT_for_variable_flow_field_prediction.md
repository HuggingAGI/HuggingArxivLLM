# <翻译失败>

发布时间：2025年05月19日

`LLM应用

摘要中提到的论文主要探讨了如何将大型语言模型（LLM）应用于计算流体动力学（CFD）中的流场预测，通过知识迁移和特定的文本模板设计来提升模型的预测性能和泛化能力。这属于将LLM应用于具体领域的问题，因此归类为LLM应用。` `流体动力学`

> FlowBERT: Prompt-tuned BERT for variable flow field prediction

# 摘要

> 本研究提出了一种基于大型语言模型（LLM）知识迁移的通用流场预测框架，旨在解决传统计算流体动力学（CFD）方法计算成本高昂以及现有深度学习模型跨条件迁移能力有限的问题。该框架创新性地将主成分正交分解（POD）降维技术与预训练LLM的微调策略相结合，其中POD有助于流场特征的压缩表示，而微调模型则学习在状态空间中编码系统动力学。为了提升模型对流场数据的适应能力，我们专门设计了面向流体动力学的文本模板，通过丰富的上下文语义信息提升预测性能。实验结果表明，与传统的Transformer模型相比，我们的框架在少量样本学习场景下表现更优，同时在各种来流条件和翼型几何上展现出卓越的泛化能力。消融研究揭示了FlowBERT架构中关键组件的贡献。与传统需要数小时计算的Navier-Stokes方程求解器相比，我们的方法将预测时间缩短至数秒，同时保持超过90%的准确性。所提出的知识迁移范式为流体动力学的快速预测开辟了新方向，其潜在应用可扩展至气动优化、流动控制及其他工程领域。

> This study proposes a universal flow field prediction framework based on knowledge transfer
  from large language model (LLM), addressing the high computational costs of traditional
  computational fluid dynamics (CFD) methods and the limited cross-condition transfer capability
  of existing deep learning models. The framework innovatively integrates Proper Orthogonal
  Decomposition (POD) dimensionality reduction with fine-tuning strategies for pretrained LLM,
  where POD facilitates compressed representation of flow field features while the fine-tuned model
  learns to encode system dynamics in state space. To enhance the model's adaptability to flow field
  data, we specifically designed fluid dynamics-oriented text templates that improve predictive
  performance through enriched contextual semantic information. Experimental results demonstrate
  that our framework outperforms conventional Transformer models in few-shot learning scenarios while
  exhibiting exceptional generalization across various inflow conditions and airfoil geometries.
  Ablation studies reveal the contributions of key components in the FlowBERT architecture. Compared
  to traditional Navier-Stokes equation solvers requiring hours of computation, our approach reduces
  prediction time to seconds while maintaining over 90% accuracy. The developed knowledge transfer
  paradigm establishes a new direction for rapid fluid dynamics prediction, with potential
  applications extending to aerodynamic optimization, flow control, and other engineering domains.

[Arxiv](https://arxiv.org/abs/2506.08021)