# 上下文感知的科学知识提取：使用大型语言模型处理链接开放数据

发布时间：2025年06月21日

`LLM应用

理由：这篇论文主要讨论了如何利用大型语言模型（LLM）来构建一个智能科学知识提取工作流系统（WISE），以应对科学文献爆炸带来的知识提取与合成挑战。论文的重点在于LLM的应用，特别是将其与搜索功能结合，构建结构化的工作流系统，以提升知识提取和综合的效率和效果。因此，这篇论文应归类为LLM应用。` `科学文献` `知识提取`

> Context-Aware Scientific Knowledge Extraction on Linked Open Data using Large Language Models

# 摘要

> 科学文献的爆炸式增长给知识提取与合成带来了巨大挑战。传统搜索引擎虽能提供大量信息来源，却难以给出直接、详尽的答案；通用大型语言模型（LLMs）虽能快速生成回答，但往往缺乏深度或遗漏最新信息。具备搜索功能的LLMs同样受限于上下文窗口，难以生成完整详尽的回答。针对这些局限，我们提出WISE（智能科学知识提取工作流），一个通过结构化工作流从多样化来源中提取、精炼和排序特定查询知识的系统。WISE采用LLM驱动的树状架构，专注于与查询高度对齐、上下文感知且非冗余的信息。通过动态评分和排名机制，WISE能够优先考虑各来源的独特贡献；而自适应停止标准则有效降低了处理开销。WISE通过系统性探索和综合来自多样化来源的知识，最终提供详尽、有条理的回答。实验结果表明，在HBB基因相关疾病领域，WISE将处理文本量减少80%以上，同时实现显著高于搜索引擎和其他LLM方法的召回率。ROUGE和BLEU指标显示WISE的输出比其他系统更具独特性，而一种新型层次化指标则表明其提供更深入的信息。此外，我们还探讨了WISE工作流在药物发现、材料科学和社会科学等多样化领域中的适应性，展示了其在从非结构化科学论文和网络资源中高效提取和综合知识方面的潜力。

> The exponential growth of scientific literature challenges researchers extracting and synthesizing knowledge. Traditional search engines return many sources without direct, detailed answers, while general-purpose LLMs may offer concise responses that lack depth or omit current information. LLMs with search capabilities are also limited by context window, yielding short, incomplete answers. This paper introduces WISE (Workflow for Intelligent Scientific Knowledge Extraction), a system addressing these limits by using a structured workflow to extract, refine, and rank query-specific knowledge. WISE uses an LLM-powered, tree-based architecture to refine data, focusing on query-aligned, context-aware, and non-redundant information. Dynamic scoring and ranking prioritize unique contributions from each source, and adaptive stopping criteria minimize processing overhead. WISE delivers detailed, organized answers by systematically exploring and synthesizing knowledge from diverse sources. Experiments on HBB gene-associated diseases demonstrate WISE reduces processed text by over 80% while achieving significantly higher recall over baselines like search engines and other LLM-based approaches. ROUGE and BLEU metrics reveal WISE's output is more unique than other systems, and a novel level-based metric shows it provides more in-depth information. We also explore how the WISE workflow can be adapted for diverse domains like drug discovery, material science, and social science, enabling efficient knowledge extraction and synthesis from unstructured scientific papers and web sources.

[Arxiv](https://arxiv.org/abs/2506.17580)