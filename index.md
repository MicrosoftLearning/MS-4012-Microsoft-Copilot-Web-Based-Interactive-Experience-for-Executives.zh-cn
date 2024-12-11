---
title: 联机托管说明
permalink: index.html
layout: home
---

# MS-4012：Microsoft Copilot Interactive Experience for Executives 

## 内容目录

本课程的演示基于加速器工具包“[演示指南和话题.docx](https://microsoft.seismic.com/Link/Content/DCJC9CXBThjcFGfJjJXMQ2jXqfCG)”中的演示。

在提供此培训之前，请务必熟悉演示。 对于多个实验室，将利用示例文档和预先创建的 Teams 会议和电子邮件。

- 请在[此处](https://github.com/MicrosoftLearning/MS-4012-Microsoft-Copilot-Unlocked/tree/master/Resourcefiles)预下载所有示例文档。
- 按照[此处](https://microsoft.seismic.com/Link/Content/DCFPQWmT2DMXC8WJjgjP4H44GWXG)的说明设置 Teams 会议和电子邮件线程。
- 熟悉[此处](https://aka.ms/CopilotWebEE)找到的交互式体验。



## 课程描述

探索 Microsoft Copilot 的变革潜力及其对组织效率的影响。 此体验专为没有 Copilot 许可证的高管和企业领导者设计，深入探讨创建有效提示的艺术，提供交互式体验，并演示 Microsoft 365 Copilot 如何无缝集成到日常业务工作流中，以提高工作效率并推动创新。

此交付的主要目标是：

- 教授如何制作有效的提示
- 演示 Microsoft Copilot（Web 范围）并引导参与者完成交互式体验
- 演示 office 应用中的 Microsoft 365 Copilot （最多 3 个演示）
- 邀请参与者下载并尝试 Microsoft Copilot for Mobile

## 课时安排（估计） 

| # | 主题                                 | 详细信息                                                                                          | 总时间      |
|---|---------------------------------------|--------------------------------------------------------------------------------------------------|-----------------|
| 1 | 在 Microsoft 365 Copilot 中制作有效提示 | - 提示的艺术页面 <br> - 生成提示页面 <br> - Copilot 实验室页面 | 10 分钟    |
| 2 | Microsoft Copilot 网页版          | - 演示 Microsoft Copilot（Web 模式） <br> - 交互式的体验  <br> - 共享“体验”页面 | 30 分钟      |
| 3 | 工作中的 Microsoft 365 Copilot     | - Microsoft Graph 页面 <br> - 在 Word 中演示 Copilot、Microsoft Copilot（工作模式）、Outlook 中的 Copilot 和 Teams 中的 Copilot <br> - 推荐页面 <br> - Microsoft Copilot on Mobile 页面 | 20 分钟      |
|   |                                       |                                                                                                  | **总时间 60 分钟** |


下面列出了每个演示的超链接。

## 演示

{% assign demos = site.pages | where_exp:"page", "page.url contains '/Instructions/Demos'" %}
| 演示 |
| --- |
{% for activity in demos  %}| [{{ activity.demo.title }}]({{ site.github.url }}{{ activity.url }}) |
{% endfor %}
