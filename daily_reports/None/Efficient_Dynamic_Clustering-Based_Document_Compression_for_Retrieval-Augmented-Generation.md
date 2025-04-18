# 高效动态聚类文档压缩：让检索增强生成（RAG）性能提升30%的秘诀
发布时间：2025年04月04日


> Efficient Dynamic Clustering-Based Document Compression for Retrieval-Augmented-Generation
>
> 检索增强生成（RAG）近年来已成为大型语言模型（LLM）推理过程中知识整合的主流方法。然而，现有RAG实现难以有效应对检索内容中的噪声、重复和冗余问题，这主要源于其在利用细粒度跨文档关系方面的局限性。为突破这一限制，我们提出了一种高效动态聚类的文档压缩框架——	extbf{E}fficient 	extbf{D}ynamic 	extbf{C}lustering-based document 	extbf{C}ompression（	extbf{EDC	extsuperscript{2}-RAG}），该框架不仅能够有效挖掘潜在的跨文档关系，还能同时去除无关信息和冗余内容。我们基于GPT-3.5构建的方法在多个常用的知识问答和幻觉检测数据集上进行了验证。实验结果表明，该方法在各种场景和实验设置下均实现了性能的显著提升，展现出强大的鲁棒性和广泛的适用性。我们的代码和数据集可在https://github.com/Tsinghua-dhy/EDC-2-RAG获取。
>
> https://arxiv.org/abs/2504.03165

![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2025/02/12/1739367812022-81912e8f-5f91-4b9d-b4b2-52b0e322d137.png)
**添加请注明**
**如遇无法添加，请+ vx: iamxxn886**
<hr />



## 为什么需要高效动态聚类文档压缩技术？

### 1.1 大语言模型（LLM）的挑战
大语言模型（LLM, Large Language Models）在自然语言处理任务中表现出色，比如问答、代码生成甚至医疗诊断。然而，LLM 面临两大挑战：知识更新成本高和“幻觉”问题。幻觉指的是模型生成的内容与事实不符，导致误导性输出。例如，当被问及“谁发明了电话？”时，LLM 可能会错误地生成“爱迪生”作为答案，而正确答案是“贝尔”。这种幻觉问题不仅影响模型的可靠性，还可能导致用户对模型的信任度下降。

### 1.2 检索增强生成（RAG）的局限性
为了解决这些问题，检索增强生成（RAG, Retrieval-Augmented Generation）技术应运而生。RAG 通过结合检索和生成技术，允许 LLM 访问外部知识，无需更新模型参数，从而减少幻觉并提高可靠性。然而，现有的 RAG 方法在处理检索内容时，常常面临噪声、重复和冗余问题。例如，当检索与“电话发明”相关的文档时，可能会返回多篇内容高度相似的文档，导致信息冗余，影响 LLM 的推理质量。

### 1.3 当前 RAG 方法的不足
现有的 RAG 方法通常基于查询与候选文档的相似性进行检索，忽略了文档间的内容关联。这可能导致事实冲突和重复内容，影响 LLM 的推理质量。尽管图基 RAG 方法通过构建知识图提高了检索灵活性，但仍无法有效解决内容冗余和冲突问题。例如，当检索与“电话发明”相关的文档时，可能会返回多篇内容高度相似的文档，导致信息冗余，影响 LLM 的推理质量。

为了解决这些问题，我们提出了一种高效动态聚类文档压缩框架（EDC2-RAG），通过利用文档间的细粒度关系，同时去除无关信息和冗余内容，显著提升了 RAG 系统的性能。我们的实验表明，该方法在各种场景和实验设置下均能实现一致的性能提升，展示了强大的鲁棒性和适用性。




## 高效动态聚类文档压缩技术是什么？

### 2.1 核心技术原理

高效动态聚类文档压缩技术（Efficient Dynamic Clustering-based document Compression, EDC²-RAG）是一种针对检索增强生成（Retrieval-Augmented Generation, RAG）框架的优化技术，旨在解决检索内容中的噪声、重复和冗余问题。其核心原理包括以下四个步骤：

1. **文档编码**：首先，将检索到的文档通过嵌入模型（embedding model）编码为更密集的内容表示。这种表示方式能够捕捉文档的语义信息，便于后续的相似度计算和聚类操作。例如，使用BERT或SimCSE等模型将文档转换为向量表示。

2. **动态聚类**：基于文档之间的语义相似度，将文档聚集成簇。这一步骤通过动态扩展簇的大小，逐步将相似文档分组，从而减少内容冲突和重复。例如，选择与查询最相似的文档作为簇的根，然后计算其他文档与根文档的相似度，逐步形成簇。

3. **提示引导压缩**：利用提示技术（prompt-based techniques）指导大语言模型（LLM）进行查询特定的压缩。通过设计特定的提示词，LLM能够从文档中提取与查询最相关的信息，生成更简洁的摘要。例如，提示LLM从文档中提取直接支持或反驳查询的关键证据。

4. **生成响应**：将压缩后的内容整合到提示中，生成最终响应。这一步骤确保LLM能够基于高质量的输入生成更准确和可靠的答案。

### 2.2 动态聚类策略

动态聚类策略是EDC²-RAG的核心创新之一，它通过迭代扩展簇的大小，确保高效分组的同时控制计算成本。具体步骤如下：

1. **选择根文档**：从检索到的文档中选择与查询相似度最高的文档作为簇的根。例如，使用余弦相似度计算文档与查询的相似度，选择得分最高的文档。

2. **计算相似度**：计算所有文档与根文档的相似度，生成相似度矩阵。这一步骤通常使用嵌入模型生成的向量表示进行计算。

3. **形成簇**：根据相似度将文档分组，逐步扩展簇的大小。例如，设置一个阈值，将相似度高于该阈值的文档归入同一簇。

4. **移除已聚类文档**：将已聚类的文档从候选集中移除，继续下一轮聚类。这一步骤确保每个文档只被分配到一个簇中，避免重复聚类。

### 2.3 开源地址

EDC²-RAG的代码和数据集已开源，研究人员和开发者可以通过以下地址访问：[EDC²-RAG GitHub](https://github.com/Tsinghua-dhy/EDC-2-RAG)。开源项目包括完整的实现代码、实验数据集以及详细的文档说明，便于复现和扩展研究。




## 3. 高效动态聚类文档压缩技术的应用效果如何？

### 3.1 知识问答数据集上的表现
在知识问答数据集（如NQ和WebQ）上的实验表明，EDC²-RAG在噪声和冗余处理方面表现出色。具体结果如下：

- **噪声处理**：在40%噪声水平下，EDC²-RAG在TriviaQA数据集上的F1得分比RALM提高了0.76。这意味着即使在高噪声环境下，EDC²-RAG仍能有效过滤无关信息，保持较高的回答准确性。
  
- **冗余处理**：在高冗余率（40%）下，EDC²-RAG在WebQ数据集上的F1得分比RALM提高了1.61。这表明EDC²-RAG能够有效去除重复内容，提升信息密度，从而生成更精准的回答。

### 3.2 幻觉检测数据集上的表现
在幻觉检测数据集（如FELM、WikiBio GPT-3和HaluEval）上的实验显示，EDC²-RAG在减少幻觉方面显著优于基线方法。例如，在FELM数据集上，EDC²-RAG的平衡准确率达到了64.03，比基线方法提高了6.61。这说明EDC²-RAG能够更好地识别和过滤模型生成内容中的错误信息，提升回答的可靠性。

### 3.3 鲁棒性和泛化能力
EDC²-RAG在不同实验设置和场景下均表现出稳定的性能提升，展示了其强大的鲁棒性和泛化能力。例如，在WebQ数据集上，EDC²-RAG的平均F1得分比RALM提高了0.48。这一结果表明，EDC²-RAG不仅在特定数据集上表现优异，还能适应多种任务和场景，具有广泛的应用潜力。

### 技术点与应用案例
- **技术点**：EDC²-RAG通过动态聚类和压缩技术，有效去除文档中的噪声和冗余内容，提升信息密度。
- **应用案例**：在TriviaQA数据集上，EDC²-RAG在高噪声环境下仍能保持较高的F1得分，展示了其在复杂场景下的强大处理能力。

通过这些实验结果，我们可以看到EDC²-RAG在提升问答系统性能和减少幻觉方面的显著优势，为未来的研究和应用提供了新的方向。




## 四、总结

高效动态聚类文档压缩技术通过深入挖掘和利用文档间的细粒度关系，显著提升了RAG（Retrieval-Augmented Generation，检索增强生成）系统的性能和鲁棒性。该技术不仅有效减少了噪声和冗余，还增强了大型语言模型（LLM）的长上下文处理能力，为解决LLM的幻觉问题和知识更新挑战提供了新的方向。

### 技术必要性
在当前的RAG系统中，检索到的文档往往包含大量噪声和冗余信息，这直接影响了LLM的推理质量。传统的RAG方法通常基于查询与文档的相似性进行检索，但忽略了文档之间的内容级联系。这种简单粗暴的检索方式可能导致文档中的事实冲突或重复内容，进而影响LLM的生成结果。此外，现有的图结构RAG方法虽然通过构建大规模知识图谱提高了检索的灵活性，但仍然无法有效解决内容冗余和冲突的问题。

为了解决这些问题，我们提出了基于高效动态聚类的文档压缩框架（EDC²-RAG）。该框架通过聚类技术将语义相似的文档聚合在一起，减少了内容冲突和重复，同时利用提示技术引导LLM进行查询特定的压缩，进一步提高了信息密度。实验结果表明，该方法在多种场景和实验设置下均实现了显著的性能提升，展现了强大的鲁棒性和适用性。

### 技术解析
EDC²-RAG的核心在于动态聚类和文档压缩。首先，我们通过嵌入模型将文档编码为更密集的内容表示，然后基于相似性进行聚类，将语义相似的文档聚合在一起。这种聚类策略不仅减少了冗余，还帮助LLM更好地理解文档之间的关系。接下来，我们利用提示技术引导LLM对聚类后的文档进行压缩，提取出与查询最相关的信息，并去除冗余和噪声。最后，将压缩后的内容整合到提示中，生成最终的响应。

### 应用评估
我们在多个广泛使用的数据集上验证了EDC²-RAG的有效性，包括开放域问答和幻觉检测任务。实验结果表明，该方法在不同设置下均实现了显著的性能提升。特别是在处理噪声和冗余信息时，EDC²-RAG展现了强大的鲁棒性。例如，在WebQ数据集上，我们的方法在噪声率为40%的情况下，F1分数比传统RAG方法提高了0.76。此外，该方法还增强了LLM的长上下文处理能力，减少了幻觉现象的发生。

### 结论
通过深入挖掘和利用文档间的细粒度关系，EDC²-RAG显著提升了RAG系统的性能和鲁棒性。该技术不仅减少了噪声和冗余，还增强了LLM的长上下文处理能力，为解决LLM的幻觉问题和知识更新挑战提供了新的方向。未来，我们将进一步验证该方法的泛化能力，并探索其在更多应用场景中的潜力。



<hr />

- 论文原文: [https://arxiv.org/abs/2504.03165](https://arxiv.org/abs/2504.03165)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)