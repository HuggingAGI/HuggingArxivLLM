# SWE-Mirror：跨仓库问题镜像助力问题解决数据集扩展

发布时间：2025年09月10日

`Agent` `基础理论`

> SWE-Mirror: Scaling Issue-Resolving Datasets by Mirroring Issues Across Repositories

# 摘要

> 构建大规模可验证的问题解决任务训练数据集意义重大，却也向来是个棘手难题。目前，针对现实问题自动搭建Gym环境的方法成功率低、成本高，效果不佳；与此同时，在现有Gym环境中生成新任务的做法，又让海量真实的人工上报问题仍未得到有效利用。为充分利用现有Gym环境和GitHub上丰富的问题解决历史数据，我们开发了SWE-Mirror——这一流程能够提取现实问题的语义核心，将其映射到已配置Gym环境的另一个仓库中，并重新生成为可验证的问题解决任务。SWE-Mirror通过复用现有Gym环境和GitHub上的海量问题解决历史数据，构建了一个包含映射后真实可验证任务的大规模数据集。我们将其应用于4种语言的40个仓库，最终得到含60,671个问题解决任务的数据集，并通过训练和评估不同规模的编码智能体验证了该数据集的价值。训练后的实验显示，基于该数据集训练的模型在问题解决能力上显著提升。此外，通过将数据集规模扩展到超过12,000条高质量轨迹，我们在OpenHands智能体框架上，基于Qwen2.5-Coder-Instruct的大型语言模型中刷新了最先进水平（SOTA）——7B模型在SWE-Bench-Verified上的解决率提升21.8%，32B模型提升46.0%，充分验证了我们方法的有效性。

> Creating large-scale verifiable training datasets for issue-resolving tasks is a critical yet notoriously difficult challenge. Existing methods on automating the Gym environment setup process for real-world issues suffer from low success rates and high overhead. Meanwhile, synthesizing new tasks within existing Gym environments leaves the vast pool of authentic, human-reported problems untapped. To maximize the utilization of existing Gym environments and also the rich data of issue-resolving history on GitHub, we introduce SWE-Mirror, a pipeline that distills a real-world issue's semantic essence, mirrors it into another repository with a configured Gym environment, and re-animates it as a verifiable issue-resolving task. SWE-Mirror reuses existing Gym environments along with the vast pool of issue-resolving history hosted on GitHub to construct a large-scale dataset of mirrored authentic and verifiable tasks. Applying SWE-Mirror to 40 repositories across 4 languages, we have curated a dataset with 60,671 issue-resolving tasks and demonstrated the value of our dataset by training and evaluating coding agents at various scale. Post-training experiments show that models trained with the dataset exhibit improvements in issue-resolving capabilities. Furthermore, by extending the dataset size to over 12,000 high-quality trajectories, we established a new state-of-the-art (SOTA) among Qwen2.5-Coder-Instruct based LLMs on the OpenHands agent framework, which increases the resolve rate on SWE-Bench-Verified by +21.8% for the 7B model and +46.0% for the 32B model and validates the effectiveness of our approach.

[Arxiv](https://arxiv.org/abs/2509.08724)