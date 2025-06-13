# AI5GTest：AI驱动的规范感知5G O-RAN组件自动化测试与验证

发布时间：2025年06月11日

`LLM应用` `测试自动化`

> AI5GTest: AI-Driven Specification-Aware Automated Testing and Validation of 5G O-RAN Components

# 摘要

> 开放无线接入网络（O-RAN）的出现推动了电信行业的变革，促进了互操作性、供应商多样性以及快速创新的实现。然而，其分散式架构带来了复杂的测试挑战，特别是在验证多供应商组件是否符合O-RAN联盟和3GPP规范方面。现有的框架，如开放测试与集成中心（OTICs）提供的框架，严重依赖手动流程，分散且容易出错，导致不一致性和扩展性问题。为了解决这些问题，我们提出了AI5GTest——一个基于AI、了解规范的测试框架，旨在自动化验证O-RAN组件。AI5GTest采用了一种协作式大型语言模型（LLM）框架，包括Gen-LLM、Val-LLM和Debug-LLM。Gen-LLM根据3GPP和O-RAN规范自动生成测试用例的预期流程，Val-LLM则将信令消息与这些流程进行交叉核对，以验证合规性并检测偏差。如果出现异常，Debug-LLM会进行根本原因分析，揭示故障原因。为了提高透明度和可信度，AI5GTest整合了人工参与机制，即在进行验证之前，Gen-LLM会向测试人员展示top-k相关的官方规范以供审批。通过使用从O-RAN TIFG和WG5-IOT测试规范中获取的一系列测试用例进行评估，AI5GTest在保持高验证准确性的同时，与传统手动方法相比，显著减少了整体测试执行时间。

> The advent of Open Radio Access Networks (O-RAN) has transformed the telecommunications industry by promoting interoperability, vendor diversity, and rapid innovation. However, its disaggregated architecture introduces complex testing challenges, particularly in validating multi-vendor components against O-RAN ALLIANCE and 3GPP specifications. Existing frameworks, such as those provided by Open Testing and Integration Centres (OTICs), rely heavily on manual processes, are fragmented and prone to human error, leading to inconsistency and scalability issues. To address these limitations, we present AI5GTest -- an AI-powered, specification-aware testing framework designed to automate the validation of O-RAN components. AI5GTest leverages a cooperative Large Language Models (LLM) framework consisting of Gen-LLM, Val-LLM, and Debug-LLM. Gen-LLM automatically generates expected procedural flows for test cases based on 3GPP and O-RAN specifications, while Val-LLM cross-references signaling messages against these flows to validate compliance and detect deviations. If anomalies arise, Debug-LLM performs root cause analysis, providing insight to the failure cause. To enhance transparency and trustworthiness, AI5GTest incorporates a human-in-the-loop mechanism, where the Gen-LLM presents top-k relevant official specifications to the tester for approval before proceeding with validation. Evaluated using a range of test cases obtained from O-RAN TIFG and WG5-IOT test specifications, AI5GTest demonstrates a significant reduction in overall test execution time compared to traditional manual methods, while maintaining high validation accuracy.

[Arxiv](https://arxiv.org/abs/2506.10111)