# 柏拉图式表示在贫困制图中的应用：统一视觉-语言代码与智能体诱导的新颖性之辩？

发布时间：2025年08月01日

`LLM应用

摘要中提到，论文探讨了将LLM应用于多模态数据融合，用于预测社会经济指标如家庭财富。这展示了LLM在实际问题中的具体应用，属于LLM应用类别。` `社会经济`

> Platonic Representations for Poverty Mapping: Unified Vision-Language Codes or Agent-Induced Novelty?

# 摘要

> 我们探讨了社会经济指标（如家庭财富）是否会在卫星图像（捕捉物理特征）和网络文本（反映历史/经济叙述）中留下可识别的印记。基于来自非洲社区的《人口与健康调查》（DHS）数据，我们将Landsat图像与基于位置/年份的LLM生成文本描述以及由AI搜索代理从网络来源检索的文本配对。我们开发了一个多模态框架，通过五个管道预测家庭财富（国际财富指数）：(i) 卫星图像的视觉模型，(ii) 仅使用位置/年份的LLM，(iii) AI代理搜索/合成网络文本，(iv) 联合图像-文本编码器，(v) 所有信号的集成。我们的框架带来了三项重要贡献。首先，融合视觉和代理/LLM文本在财富预测中优于仅视觉基线（例如，样本外分割的R平方值为0.77，而基线为0.63），LLM内部知识比代理检索文本更有效，显著提升了跨国家和跨时间的泛化鲁棒性。其次，我们发现视觉与语言模态之间存在部分表示收敛：融合嵌入的中位余弦相似度为0.60（对齐后），表明视觉与语言模态共享物质福祉的潜在代码，同时保留互补细节，与柏拉图表示假设一致。尽管仅使用LLM文本的表现优于代理检索数据，挑战了我们的“代理引发的新颖性假设”，但某些分割中结合代理数据带来的适度增益弱支持代理收集信息引入独特表示结构的观点，这些结构未被静态LLM知识完全捕获。最后，我们发布了一个包含超过60,000个DHS聚类的大型多模态数据集，每个聚类都链接到卫星图像、LLM生成描述和代理检索文本，为相关研究提供了宝贵资源。

> We investigate whether socio-economic indicators like household wealth leave recoverable imprints in satellite imagery (capturing physical features) and Internet-sourced text (reflecting historical/economic narratives). Using Demographic and Health Survey (DHS) data from African neighborhoods, we pair Landsat images with LLM-generated textual descriptions conditioned on location/year and text retrieved by an AI search agent from web sources. We develop a multimodal framework predicting household wealth (International Wealth Index) through five pipelines: (i) vision model on satellite images, (ii) LLM using only location/year, (iii) AI agent searching/synthesizing web text, (iv) joint image-text encoder, (v) ensemble of all signals. Our framework yields three contributions. First, fusing vision and agent/LLM text outperforms vision-only baselines in wealth prediction (e.g., R-squared of 0.77 vs. 0.63 on out-of-sample splits), with LLM-internal knowledge proving more effective than agent-retrieved text, improving robustness to out-of-country and out-of-time generalization. Second, we find partial representational convergence: fused embeddings from vision/language modalities correlate moderately (median cosine similarity of 0.60 after alignment), suggesting a shared latent code of material well-being while retaining complementary details, consistent with the Platonic Representation Hypothesis. Although LLM-only text outperforms agent-retrieved data, challenging our Agent-Induced Novelty Hypothesis, modest gains from combining agent data in some splits weakly support the notion that agent-gathered information introduces unique representational structures not fully captured by static LLM knowledge. Third, we release a large-scale multimodal dataset comprising more than 60,000 DHS clusters linked to satellite images, LLM-generated descriptions, and agent-retrieved texts.

[Arxiv](https://arxiv.org/abs/2508.01109)