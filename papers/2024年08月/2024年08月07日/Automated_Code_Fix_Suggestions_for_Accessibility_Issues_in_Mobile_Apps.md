# 为移动应用的无障碍问题提供自动代码修复建议

发布时间：2024年08月07日

`LLM应用` `软件工程` `人工智能`

> Automated Code Fix Suggestions for Accessibility Issues in Mobile Apps

# 摘要

> 可访问性是实现包容性应用的关键，但开发人员常因意识不足、专业技能有限及工具缺乏，难以有效识别和修复应用中的可访问性问题。现有的可访问性测试工具虽能检测到问题，却往往无法提供解决方案。为此，我们推出FixAlly——一款专为自动化可访问性扫描器检测到的问题提供源代码修复建议的工具。FixAlly借助多智能体LLM架构，能够生成修复策略、定位代码问题并提出修改建议。实证研究显示，FixAlly在提出修复建议方面表现出色，77%的建议具有实际可行性。此外，针对12名iOS开发人员的调查显示，他们对69.4%的修复建议持接受态度。

> Accessibility is crucial for inclusive app usability, yet developers often struggle to identify and fix app accessibility issues due to a lack of awareness, expertise, and inadequate tools. Current accessibility testing tools can identify accessibility issues but may not always provide guidance on how to address them. We introduce FixAlly, an automated tool designed to suggest source code fixes for accessibility issues detected by automated accessibility scanners. FixAlly employs a multi-agent LLM architecture to generate fix strategies, localize issues within the source code, and propose code modification suggestions to fix the accessibility issue. Our empirical study demonstrates FixAlly's capability in suggesting fixes that resolve issues found by accessibility scanners -- with an effectiveness of 77% in generating plausible fix suggestions -- and our survey of 12 iOS developers finds they would be willing to accept 69.4% of evaluated fix suggestions.

[Arxiv](https://arxiv.org/abs/2408.03827)