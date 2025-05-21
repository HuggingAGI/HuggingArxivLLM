# # AMAQA: 为RAG系统打造的基于元数据的问答数据集

发布时间：2025年05月19日

`RAG` `网络安全`

> AMAQA: A Metadata-based QA Dataset for RAG Systems

# 摘要

> 基于检索增强的生成（RAG）系统在问答任务中广泛应用，但现有基准测试缺乏元数据整合，限制了在需要结合文本数据和外部信息场景下的评估能力。为解决这一问题，我们推出全新开源问答数据集AMAQA，专为评估结合文本与元数据的任务而设计。元数据整合在网络安全与情报等需要快速处理大量数据的领域尤为重要，及时获取相关信息对这些领域至关重要。AMAQA包含从26个公开Telegram群组收集的约110万条英文消息，并补充了时间戳、主题、情感基调和毒性指标等元数据，支持基于特定标准筛选文档，实现精准和情境化的查询。该数据集还包括450对高质量问答，成为推动基于元数据的问答与RAG系统研究的宝贵资源。据我们所知，AMAQA是首个整合元数据与标签（如消息主题）的单跳问答基准。我们在该基准上进行了广泛测试，为未来研究树立了新的标准。我们展示了利用元数据将准确率从0.12提升至0.61，突显了结构化上下文的价值。在此基础上，我们探索了多种策略，通过迭代提供的上下文并利用噪声文档进行丰富，进一步优化了大语言模型的输入，相比最佳基线提升了3个百分点，相比简单的元数据过滤提高了14个百分点。该数据集可在https://anonymous.4open.science/r/AMAQA-5D0D/获取。

> Retrieval-augmented generation (RAG) systems are widely used in question-answering (QA) tasks, but current benchmarks lack metadata integration, hindering evaluation in scenarios requiring both textual data and external information. To address this, we present AMAQA, a new open-access QA dataset designed to evaluate tasks combining text and metadata. The integration of metadata is especially important in fields that require rapid analysis of large volumes of data, such as cybersecurity and intelligence, where timely access to relevant information is critical. AMAQA includes about 1.1 million English messages collected from 26 public Telegram groups, enriched with metadata such as timestamps, topics, emotional tones, and toxicity indicators, which enable precise and contextualized queries by filtering documents based on specific criteria. It also includes 450 high-quality QA pairs, making it a valuable resource for advancing research on metadata-driven QA and RAG systems. To the best of our knowledge, AMAQA is the first single-hop QA benchmark to incorporate metadata and labels such as topics covered in the messages. We conduct extensive tests on the benchmark, establishing a new standard for future research. We show that leveraging metadata boosts accuracy from 0.12 to 0.61, highlighting the value of structured context. Building on this, we explore several strategies to refine the LLM input by iterating over provided context and enriching it with noisy documents, achieving a further 3-point gain over the best baseline and a 14-point improvement over simple metadata filtering. The dataset is available at https://anonymous.4open.science/r/AMAQA-5D0D/

[Arxiv](https://arxiv.org/abs/2505.13557)