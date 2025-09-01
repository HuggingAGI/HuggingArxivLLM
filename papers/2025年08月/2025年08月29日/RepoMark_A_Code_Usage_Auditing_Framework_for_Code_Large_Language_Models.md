# RepoMark：代码大语言模型的代码使用审计框架

发布时间：2025年08月29日

`LLM应用` `法律科技`

> RepoMark: A Code Usage Auditing Framework for Code Large Language Models

# 摘要

> 面向代码生成的大型语言模型（LLMs）发展迅猛，它们以前所未有的效率实现了编码任务的自动化，彻底改变了软件开发模式。
然而，这些模型在开源代码仓库（如GitHub）上的训练引发了严峻的伦理与法律问题，尤其是在数据授权和开源许可证合规性方面。开发人员也越发质疑：模型训练者在使用仓库进行训练前是否获得了适当授权？尤其是数据收集过程还缺乏透明度的情况下。
为解决这些问题，我们提出了一种全新的数据标记框架RepoMark，用于审计代码LLM的数据使用情况。该方法能让仓库所有者验证自己的代码是否被用于训练，同时确保语义保留、不可感知性以及理论上的假检率（FDR）保证。RepoMark通过生成多个语义等效的代码变体，在代码文件中嵌入数据标记；检测时，则借助一种新颖的基于排序的假设检验来识别模型对代码的记忆情况。与现有数据审计方法相比，RepoMark的样本效率显著提升，即使用户仓库仅有少量代码文件，也能实现高效审计。
实验显示，在严格控制假检率（FDR）为5%的前提下，RepoMark对小型代码仓库的检测成功率超过90%。这相比现有数据标记技术是一项重大突破——在相同条件下，现有技术的准确率均低于55%。

> The rapid development of Large Language Models (LLMs) for code generation has transformed software development by automating coding tasks with unprecedented efficiency.
  However, the training of these models on open-source code repositories (e.g., from GitHub) raises critical ethical and legal concerns, particularly regarding data authorization and open-source license compliance. Developers are increasingly questioning whether model trainers have obtained proper authorization before using repositories for training, especially given the lack of transparency in data collection.
  To address these concerns, we propose a novel data marking framework RepoMark to audit the data usage of code LLMs. Our method enables repository owners to verify whether their code has been used in training, while ensuring semantic preservation, imperceptibility, and theoretical false detection rate (FDR) guarantees. By generating multiple semantically equivalent code variants, RepoMark introduces data marks into the code files, and during detection, RepoMark leverages a novel ranking-based hypothesis test to detect memorization within the model. Compared to prior data auditing approaches, RepoMark significantly enhances sample efficiency, allowing effective auditing even when the user's repository possesses only a small number of code files.
  Experiments demonstrate that RepoMark achieves a detection success rate over 90\% on small code repositories under a strict FDR guarantee of 5\%. This represents a significant advancement over existing data marking techniques, all of which only achieve accuracy below 55\% under identical settings. This further validates RepoMark as a robust, theoretically sound, and promising solution for enhancing transparency in code LLM training, which can safeguard the rights of repository owners.

[Arxiv](https://arxiv.org/abs/2508.21432)