# 分类 vs. 提示：法律需求可追溯性案例研究

发布时间：2025年02月07日

`LLM应用`

> Classification or Prompting: A Case Study on Legal Requirements Traceability

# 摘要

> <翻译失败>

> New regulations are continuously introduced to ensure that software development complies with the ethical concerns and prioritizes public safety. A prerequisite for demonstrating compliance involves tracing software requirements to legal provisions. Requirements traceability is a fundamental task where requirements engineers are supposed to analyze technical requirements against target artifacts, often under limited time budget. Doing this analysis manually for complex systems with hundreds of requirements is infeasible. The legal dimension introduces additional challenges that only exacerbate manual effort.
  In this paper, we investigate two automated solutions based on large language models (LLMs) to predict trace links between requirements and legal provisions. The first solution, Kashif, is a classifier that leverages sentence transformers. The second solution prompts a recent generative LLM based on Rice, a prompt engineering framework.
  On a benchmark dataset, we empirically evaluate Kashif and compare it against a baseline classifier from the literature. Kashif can identify trace links with an average recall of ~67%, outperforming the baseline with a substantial gain of 54 percentage points (pp) in recall. However, on unseen, more complex requirements documents traced to the European general data protection regulation (GDPR), Kashif performs poorly, yielding an average recall of 15%. On the same documents, however, our Rice-based solution yields an average recall of 84%, with a remarkable gain of about 69 pp over Kashif. Our results suggest that requirements traceability in the legal context cannot be simply addressed by building classifiers, as such solutions do not generalize and fail to perform well on complex regulations and requirements. Resorting to generative LLMs, with careful prompt engineering, is thus a more promising alternative.

[Arxiv](https://arxiv.org/abs/2502.04916)