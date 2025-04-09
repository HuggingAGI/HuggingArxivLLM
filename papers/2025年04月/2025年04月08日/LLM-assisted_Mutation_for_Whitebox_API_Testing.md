# 基于LLM的变异方法用于白盒API测试

发布时间：2025年04月08日

`LLM应用

摘要讨论了使用大型语言模型（LLM）进行API测试的方法，属于LLM在实际应用中的创新使用。` `云计算` `软件工程`

> LLM-assisted Mutation for Whitebox API Testing

# 摘要

> 云计算应用之间依赖API进行通信和数据交换，而云服务提供商广泛采用API测试技术来保障应用的可靠性。然而，传统API测试方法由于缺乏覆盖率指标提供的梯度，难以满足严苛条件，这一问题被称为适应性 plateau。为了解决这个问题，我们提出了MioHint，这是一种基于大型语言模型（LLM）代码理解能力的新型白盒API测试方法。

基于LLM的API测试关键挑战在于系统级测试，这需要关注跨函数和文件的请求依赖关系，从而将整个代码库作为分析对象。然而，受限于LLM上下文长度和短时记忆的限制，直接将整个代码库输入LLM并不现实。MioHint通过结合静态分析与LLM来应对这一挑战，通过语句级数据依赖性分析检索相关代码，包括目标函数中使用的变量的def-use分析，以及目标函数调用的子函数的函数扩展。

为了验证我们方法的有效性，我们在16个真实世界的REST API服务上进行了实验。研究结果表明，与基线方法EvoMaster相比，MioHint在代码行覆盖率上平均绝对值提升了4.95%，同时在变异准确率方面实现了67倍的显著提升。此外，我们的方法成功覆盖了超过57%的难以覆盖的目标，而基线方法的覆盖率不足10%。

> Cloud applications heavily rely on APIs to communicate with each other and exchange data. To ensure the reliability of cloud applications, cloud providers widely adopt API testing techniques. Unfortunately, existing API testing approaches are insufficient to reach strict conditions, a problem known as fitness plateaus, due to the lack of gradient provided by coverage metrics. To address this issue, we propose MioHint, a novel white-box API testing approach that leverages the code comprehension capabilities of Large Language Model (LLM) to boost API testing. The key challenge of LLM-based API testing lies in system-level testing, which emphasizes the dependencies between requests and targets across functions and files, thereby making the entire codebase the object of analysis. However, feeding the entire codebase to an LLM is impractical due to its limited context length and short memory. MioHint addresses this challenge by synergizing static analysis with LLMs. We retrieve relevant code with data-dependency analysis at the statement level, including def-use analysis for variables used in the target and function expansion for subfunctions called by the target.
  To evaluate the effectiveness of our method, we conducted experiments across 16 real-world REST API services. The findings reveal that MioHint achieves an average increase of 4.95% absolute in line coverage compared to the baseline, EvoMaster, alongside a remarkable factor of 67x improvement in mutation accuracy. Furthermore, our method successfully covers over 57% of hard-to-cover targets while in baseline the coverage is less than 10%.

[Arxiv](https://arxiv.org/abs/2504.05738)