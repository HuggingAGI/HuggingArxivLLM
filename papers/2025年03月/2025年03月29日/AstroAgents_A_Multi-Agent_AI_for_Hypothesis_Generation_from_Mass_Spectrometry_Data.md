# AstroAgents：一个从质谱数据中生成假设的多智能体 AI系统

发布时间：2025年03月29日

`LLM应用

理由：这篇论文主要描述了如何利用基于大型语言模型的多智能体系统（AstroAgents）来处理质谱数据并生成科学假设。虽然涉及了多个智能体的协作，但其核心应用是利用LLM进行科学假设生成，因此归类为LLM应用。` `天文学` `人工智能`

> AstroAgents: A Multi-Agent AI for Hypothesis Generation from Mass Spectrometry Data

# 摘要

> 随着太阳系样本返回任务的临近和质谱分析数据的激增，我们亟需在现有天体生物学文献背景下分析这些数据，并提出关于地球生命起源的合理假设。然而，从质谱数据生成假设面临诸多挑战，例如环境污染物干扰、光谱峰复杂难辨以及难以与以往研究匹配。为解决这些问题，我们开发了AstroAgents——一个基于大型语言模型的多智能体AI系统，专注于从质谱数据中生成科学假设。AstroAgents由八个协作型智能体组成：数据分析师、规划师、三位领域科学家、积累者、文献综述者和批评者。系统不仅处理质谱数据，还结合用户提供的研究论文。数据分析师负责解读数据，规划师将特定数据段分配给科学家智能体深入分析。积累者收集并整理生成的假设，文献综述者借助Semantic Scholar查找相关文献。批评者则对假设进行评估，并提出改进建议。为了验证AstroAgents的效果，一位天体生物学专家评估了来自八颗陨石和十个土壤样本数据生成的一百多个假设，其中36%的假设被认为合理，而这些合理假设中66%具有创新性。了解更多：https://astroagents.github.io/

> With upcoming sample return missions across the solar system and the increasing availability of mass spectrometry data, there is an urgent need for methods that analyze such data within the context of existing astrobiology literature and generate plausible hypotheses regarding the emergence of life on Earth. Hypothesis generation from mass spectrometry data is challenging due to factors such as environmental contaminants, the complexity of spectral peaks, and difficulties in cross-matching these peaks with prior studies. To address these challenges, we introduce AstroAgents, a large language model-based, multi-agent AI system for hypothesis generation from mass spectrometry data. AstroAgents is structured around eight collaborative agents: a data analyst, a planner, three domain scientists, an accumulator, a literature reviewer, and a critic. The system processes mass spectrometry data alongside user-provided research papers. The data analyst interprets the data, and the planner delegates specific segments to the scientist agents for in-depth exploration. The accumulator then collects and deduplicates the generated hypotheses, and the literature reviewer identifies relevant literature using Semantic Scholar. The critic evaluates the hypotheses, offering rigorous suggestions for improvement. To assess AstroAgents, an astrobiology expert evaluated the novelty and plausibility of more than a hundred hypotheses generated from data obtained from eight meteorites and ten soil samples. Of these hypotheses, 36% were identified as plausible, and among those, 66% were novel. Project website: https://astroagents.github.io/

[Arxiv](https://arxiv.org/abs/2503.23170)