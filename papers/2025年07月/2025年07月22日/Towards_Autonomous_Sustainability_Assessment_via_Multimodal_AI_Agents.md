# # 摘要  
最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

发布时间：2025年07月22日

`LLM应用` `环境科学` `可持续发展`

> Towards Autonomous Sustainability Assessment via Multimodal AI Agents

# 摘要

> 近年来，可持续性信息的关注度显著提升。然而，用于将产品制造到报废过程中的材料和流程映射到环境影响（EI）的生命周期评估（LCA）所需的数据往往难以获取。在此，我们通过引入多模态AI代理，重新构想传统的LCA方法，模拟LCA专家与产品经理和工程师等利益相关者之间的互动，从而计算电子设备从摇篮到大门（生产阶段）的碳排放。这些AI代理利用定制的数据抽象方法和从维修社区及政府认证中提取在线文本和图像信息的软件工具，迭代生成详细的生命周期清单。这种方法将原本需要数周或数月的专家工作时间缩短至不到一分钟，同时填补了数据可用性缺口，并在不依赖专有数据的情况下，使碳足迹估算结果与专家LCA结果相差不到19%。此外，我们还开发了一种直接通过将输入与具有相似描述和已知碳足迹的产品集群进行比较来估算环境影响的方法。该方法在笔记本电脑上运行仅需3毫秒，对电子产品的平均绝对百分比误差（MAPE）为12.28%。进一步，我们开发了一种基于数据的方法来生成排放因子。我们利用未知材料的属性，将其表示为相似材料排放因子的加权和。与人类专家手动选择最接近的LCA数据库条目相比，这种方法将MAPE提高了120.26%。我们对数据进行了分析，计算了该方法的扩展性，并探讨了其对未来LCA工作流程的影响。

> Interest in sustainability information has surged in recent years. However, the data required for a life cycle assessment (LCA) that maps the materials and processes from product manufacturing to disposal into environmental impacts (EI) are often unavailable. Here we reimagine conventional LCA by introducing multimodal AI agents that emulate interactions between LCA experts and stakeholders like product managers and engineers to calculate the cradle-to-gate (production) carbon emissions of electronic devices. The AI agents iteratively generate a detailed life-cycle inventory leveraging a custom data abstraction and software tools that extract information from online text and images from repair communities and government certifications. This approach reduces weeks or months of expert time to under one minute and closes data availability gaps while yielding carbon footprint estimates within 19% of expert LCAs with zero proprietary data. Additionally, we develop a method to directly estimate EI by comparing an input to a cluster of products with similar descriptions and known carbon footprints. This runs in 3 ms on a laptop with a MAPE of 12.28% on electronic products. Further, we develop a data-driven method to generate emission factors. We use the properties of an unknown material to represent it as a weighted sum of emission factors for similar materials. Compared to human experts picking the closest LCA database entry, this improves MAPE by 120.26%. We analyze the data and compute scaling of this approach and discuss its implications for future LCA workflows.

[Arxiv](https://arxiv.org/abs/2507.17012)