# 语言引导的物体搜索在农业环境中的应用

发布时间：2025年03月02日

`Agent` `自动化` `业务流程管理`

> Language-Guided Object Search in Agricultural Environments

# 摘要

> # 摘要
最近大型语言模型（LLMs）的突破性进展引领了一场从机器人流程自动化到智能体流程自动化的革命性转变，这一转变通过基于LLMs自动化工作流编排过程实现了。

> Creating robots that can assist in farms and gardens can help reduce the mental and physical workload experienced by farm workers. We tackle the problem of object search in a farm environment, providing a method that allows a robot to semantically reason about the location of an unseen target object among a set of previously seen objects in the environment using a Large Language Model (LLM). We leverage object-to-object semantic relationships to plan a path through the environment that will allow us to accurately and efficiently locate our target object while also reducing the overall distance traveled, without needing high-level room or area-level semantic relationships. During our evaluations, we found that our method outperformed a current state-of-the-art baseline and our ablations. Our offline testing yielded an average path efficiency of 84%, reflecting how closely the predicted path aligns with the ideal path. Upon deploying our system on the Boston Dynamics Spot robot in a real-world farm environment, we found that our system had a success rate of 80%, with a success weighted by path length of 0.67, which demonstrates a reasonable trade-off between task success and path efficiency under real-world conditions. The project website can be viewed at https://adi-balaji.github.io/losae/

[Arxiv](https://arxiv.org/abs/2503.01068)