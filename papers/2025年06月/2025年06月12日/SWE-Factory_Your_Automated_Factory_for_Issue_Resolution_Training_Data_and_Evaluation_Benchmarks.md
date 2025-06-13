# # SWE工厂：为您自动化生成问题解决训练数据与评估基准的智能平台。

发布时间：2025年06月12日

`LLM应用` `软件工程` `自动化`

> SWE-Factory: Your Automated Factory for Issue Resolution Training Data and Evaluation Benchmarks

# 摘要

> # 摘要  
构建GitHub问题解决任务的大规模数据集对于训练和评估大型语言模型（LLMs）的软件工程能力至关重要。然而，传统创建此类基准的过程以众所周知的困难和劳动密集型著称，尤其是在搭建评估环境、评分测试结果和验证任务实例的阶段。  

本文中，我们提出了SWE-Factory，一个旨在解决这些挑战的自动化管道。为了解决这些问题，我们的管道集成了三个核心自动化组件。  

首先，我们介绍了SWE-Builder，一个多智能体系统，它能够自动化评估环境的构建。该系统采用了四个专门的智能体，它们以协作、迭代的循环工作，并利用环境记忆池来提高效率。其次，我们引入了一种基于退出代码的标准评分方法，这消除了手动编写自定义解析器的需要。最后，我们利用这些可靠的退出代码信号来自动化fail2pass验证过程。  

在四种编程语言的671个问题上的实验表明，我们的管道能够有效地构建有效的任务实例。例如，使用GPT-4.1-mini，我们的SWE-Builder以每实例$0.045的成本构建了269个有效实例；而使用Gemini-2.5-flash，则以最低的每实例$0.024成本实现了相当的性能。我们还展示了，与人工检查相比，我们的基于退出代码的评分达到了100%的准确率，而我们的自动化fail2pass验证达到了0.92的精度和1.00的召回率。  

我们希望我们的自动化管道将加速大规模、高质量GitHub问题解决数据集的收集，无论是用于训练还是评估。我们的代码和数据集已发布在https://github.com/DeepSoftwareAnalytics/swe-factory。


> Constructing large-scale datasets for the GitHub issue resolution task is crucial for both training and evaluating the software engineering capabilities of Large Language Models (LLMs). However, the traditional process for creating such benchmarks is notoriously challenging and labor-intensive, particularly in the stages of setting up evaluation environments, grading test outcomes, and validating task instances. In this paper, we propose SWE-Factory, an automated pipeline designed to address these challenges. To tackle these issues, our pipeline integrates three core automated components. First, we introduce SWE-Builder, a multi-agent system that automates evaluation environment construction, which employs four specialized agents that work in a collaborative, iterative loop and leverages an environment memory pool to enhance efficiency. Second, we introduce a standardized, exit-code-based grading method that eliminates the need for manually writing custom parsers. Finally, we automate the fail2pass validation process using these reliable exit code signals. Experiments on 671 issues across four programming languages show that our pipeline can effectively construct valid task instances; for example, with GPT-4.1-mini, our SWE-Builder constructs 269 valid instances at $0.045 per instance, while with Gemini-2.5-flash, it achieves comparable performance at the lowest cost of $0.024 per instance. We also demonstrate that our exit-code-based grading achieves 100% accuracy compared to manual inspection, and our automated fail2pass validation reaches a precision of 0.92 and a recall of 1.00. We hope our automated pipeline will accelerate the collection of large-scale, high-quality GitHub issue resolution datasets for both training and evaluation. Our code and datasets are released at https://github.com/DeepSoftwareAnalytics/swe-factory.

[Arxiv](https://arxiv.org/abs/2506.10954)