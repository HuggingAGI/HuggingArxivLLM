# 迈向地球观测领域的LLM智能体研究

发布时间：2025年04月16日

`LLM应用

LLM应用` `地球科学` `环境科学`

> Towards LLM Agents for Earth Observation

# 摘要

> 地球观测 (EO) 为环境监测、灾害管理、气候科学等科学领域提供了关键数据支持。我们提出一个问题：AI系统是否已准备好可靠地进行地球观测？为此，我们引入了\datasetnamenospace基准测试，该基准包含来自NASA地球观测站文章的140个是/否问题，覆盖13个主题和17个卫星传感器。借助Google Earth Engine API，尽管LLM代理展现了潜力，但其准确率仅为33%，主要原因在于超过58%的时间代码无法正常运行。通过微调合成数据，我们显著降低了开源模型的失败率，使得较小规模的模型（如Llama-3.1-8B）能够达到与更大模型（例如DeepSeek-R1）相当的准确率。我们的研究揭示了AI代理在自动化地球观测方面面临的重大挑战，并提出了可行的解决方案。项目详情请访问https://iandrover.github.io/UnivEarth。

> Earth Observation (EO) provides critical planetary data for environmental monitoring, disaster management, climate science, and other scientific domains. Here we ask: Are AI systems ready for reliable Earth Observation? We introduce \datasetnamenospace, a benchmark of 140 yes/no questions from NASA Earth Observatory articles across 13 topics and 17 satellite sensors. Using Google Earth Engine API as a tool, LLM agents can only achieve an accuracy of 33% because the code fails to run over 58% of the time. We improve the failure rate for open models by fine-tuning synthetic data, allowing much smaller models (Llama-3.1-8B) to achieve comparable accuracy to much larger ones (e.g., DeepSeek-R1). Taken together, our findings identify significant challenges to be solved before AI agents can automate earth observation, and suggest paths forward. The project page is available at https://iandrover.github.io/UnivEarth.

[Arxiv](https://arxiv.org/abs/2504.12110)