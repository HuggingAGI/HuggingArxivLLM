# 探索、回答、验证：寻找真相的智能体

发布时间：2025年07月04日

`LLM应用`

> Recon, Answer, Verify: Agents in Search of Truth

# 摘要

> 基于大型语言模型（LLMs）的自动事实核查提供了一种可扩展的替代方案，替代了传统的手动验证。然而，事实核查的评估面临挑战，因为现有基准数据集通常包含声明后的分析和标注者提示，而这些信息在现实世界中声明被立即验证时并不存在。这限制了当前评估的现实性。我们提出了Politi Fact Only（PFO），一个包含2,982个政治声明的5类基准数据集，其中所有声明后的分析和标注者提示均已手动移除。这确保了模型仅根据声明验证前可用的信息进行评估。在PFO上评估LLMs时，与未过滤版本相比，平均macro F1值下降了22%。基于现有LLM事实核查系统所面临的挑战，我们提出了RAV（Recon Answer Verify），一个包含三个智能体的智能体框架：问题生成器、答案生成器和标签生成器。我们的管道会迭代地生成并回答子问题，以验证声明的不同方面，最后生成标签。RAV在不同领域和标签粒度上具有良好的泛化能力，并在知名基准数据集RAWFC（事实核查，3类）上比现有最优方法高出25.28%，在HOVER（百科全书，2类）上分别在2跳、3跳和4跳的子类别上高出1.54%、4.94%和1.78%。当我们将PFO与其未过滤版本进行比较时，RAV在macro F1值上的性能下降幅度最小，仅为16.3%。

> Automated fact checking with large language models (LLMs) offers a scalable alternative to manual verification. Evaluating fact checking is challenging as existing benchmark datasets often include post claim analysis and annotator cues, which are absent in real world scenarios where claims are fact checked immediately after being made. This limits the realism of current evaluations. We present Politi Fact Only (PFO), a 5 class benchmark dataset of 2,982 political claims from politifact.com, where all post claim analysis and annotator cues have been removed manually. This ensures that models are evaluated using only the information that would have been available prior to the claim's verification. Evaluating LLMs on PFO, we see an average performance drop of 22% in terms of macro f1 compared to PFO's unfiltered version. Based on the identified challenges of the existing LLM based fact checking system, we propose RAV (Recon Answer Verify), an agentic framework with three agents: question generator, answer generator, and label generator. Our pipeline iteratively generates and answers sub questions to verify different aspects of the claim before finally generating the label. RAV generalizes across domains and label granularities, and it outperforms state of the art approaches on well known baselines RAWFC (fact checking, 3 class) by 25.28%, and on HOVER (encyclopedia, 2 class) by 1.54% on 2 hop, 4.94% on 3 hop, and 1.78% on 4 hop, sub categories respectively. RAV shows the least performance drop compared to baselines of 16.3% in macro f1 when we compare PFO with its unfiltered version.

[Arxiv](https://arxiv.org/abs/2507.03671)