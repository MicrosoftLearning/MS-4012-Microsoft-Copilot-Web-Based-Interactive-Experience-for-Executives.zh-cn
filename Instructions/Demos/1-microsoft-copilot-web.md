---
demo:
  title: 演示：Microsoft Copilot (copilot.microsoft.com)
---

[返回到索引](https://microsoftlearning.github.io/MS-4012-Microsoft-Copilot-Web-Based-Interactive-Experience-for-Executives/)

# Microsoft Copilot (copilot.microsoft.com)

## Copilot 和大型语言模型

### 讲座要点

Microsoft Copilot 为你提供了一个 AI 支持的个人助手，可以回答问题并帮助完成常规任务。 我可以问它问题，它会给出答案，并且是受过高等教育的人所给出的答案水平。

当你或你的组织将 Copilot 与商业数据保护配合使用时，将不会保存聊天。 所有数据都经过加密，Microsoft 不会保留任何提示或响应。 不会使用这些数据来训练模型，因此可以确信你的个人信息和组织信息都是保密的。

例如，我可以提出这样的一般知识性问题，并获得大量有用的信息。 你可以认为它拥有一个可用于回答问题的全球基本概念模型。

**示例：**
- **提示：** 你能告诉关于大象的什么信息？
- **响应：**（讨论响应）

Copilot 使用基于大量信息（包括必应搜索和结果）训练的大型语言模型 (LLM)。 但 Copilot 不会检查内容的真实性。 我们可以将 Copilot 用作一般推理引擎，可以随机回答你的问题并给出原因。 在这个行业，我们称之为推理。

**示例：**
- **提示：** 我对大象的力量更感兴趣。 如果进行拔河比赛，需要多少人才能赢过一头大象？ 注意：请注意区域和受众，不是每个人都知道“拔河比赛”这个词，因此可能需要相应地修改。 
- **响应：**（讨论响应）

Copilot 能够做出假设，并在知识点之间建立联系，给我一个更微妙的答案来回答我的问题。 在我们改进 Copilot 的过程中，我们会了解这些 LLM 擅长什么，以及不擅长什么，我们在生成产品时也会将这类知识纳入其中。

### 演示步骤

> **注意：** 如果要使用自己的提示，请从你或客户感兴趣的一般知识主题开始。

1. 若要启动 Microsoft Copilot，请打开新的 Edge 浏览器选项卡并导航到 <a href="https://copilot.microsoft.com" target="_blank">copilot.microsoft.com</a>。

1. 登录到非工作 Microsoft 帐户。

    > **备注：** 如果登录到工作帐户，则会重定向到 Business Chat (m365.cloud.microsoft/chat) 

1. 在“**Message Copilot**”文本框中，从提示库文档中复制并粘贴提示或键入：

    ```text
    What can you tell me about elephants?
    ```
1. 选择“提交”**** 按钮。
1. 在“**给 Copilot 发送消息**”文本框中，复制并粘贴提示：

    ```text
    I’m more interested in the power of an elephant. How many humans would it take to win a tug-of-war with an elephant?
    ```
1. 选择“提交”**** 按钮。

## 上下文关联

### 讲座要点

但是，要将这一能力提升到下一级别，就要能够将 Copilot 置于外部数据和知识中。 有时这称为“检索增强生成”(RAG)。 这是向与手头任务相关的语言模型提供额外信息的过程。

我们可以根据各种数据和文档提出问题，例如美国劳工统计局的就业报告。 这是一份每年发布的大型文件，其中包含有关美国就业情况和就业趋势的全面数据。 Copilot 能够访问外部内容，找到这些信息，理解信息，并实时解答我的问题。 它还提供了参考内容，显示 Copilot 从何处获得这些信息，例如劳工统计局网站。 这意味着我可以查看 Copilot 在哪里获取信息并获得更多上下文，因为这是 Copilot，而不是 Autopilot。

### 演示步骤

1. 通过单击“**查看历史记录**”，然后单击“**开始新聊天**”来开启新主题。

1. 在“**给 Copilot 发送消息**”文本框中，复制并粘贴提示：

    ```text
    Can you give me a list of the labor force participation rates from the Bureau of Labor Statistics over the last 5 years?
    ```
1. 选择“提交”**** 按钮。
1. 在响应中的“**了解详细信息**”旁边，将鼠标悬停在一条或两条参考内容上。

## 其他 Copilot 技能

### 讲座要点

这很好，但我确实希望看到此数据的图形。 不幸的是，Copilot 现在无法绘制图形，但这并不意味着我们停滞不前。 生成 Copilot 时，我们将添加不同的技能。 技能是 Copilot 利用其推理能力解决问题的方式。

我知道 Copilot 的另一项功能是编码。 我要提醒 Copilot，它知道如何编写代码，看看能否让它为我想要的图形编写 Python 代码。

**示例：**
- **提示：** 可以给我一份过去 5 年美国劳工统计局的劳动力参与率清单吗？ 我还听说你可以编码。 是否可以从 bls.gov 获取数据，然后编写生成要查找的图形的 Python 代码？
- **响应：**（讨论响应）

随着时间的推移，我们期望这些类型的流程变得更加简单和自动化。

### 演示步骤

1. 通过单击“**查看历史记录**”，然后单击“**开始新聊天**”来开启新主题。

1. 在“**给 Copilot 发送消息**”文本框中，复制并粘贴提示：

    ```text
    Can you give me a list of the labor force participation rates from the Bureau of Labor Statistics over the last 5 years? I also heard that you could code. Can you grab the data from bls.gov and then write the Python code that would produce the graph I'm looking for?
    ```

1. 选择“提交”**** 按钮。

## 可选演示步骤

### 识别图像

首先下载以下内容：[**此图像是什么.png**](https://github.com/MicrosoftLearning/MS-4012-Microsoft-Copilot-Unlocked/raw/master/Resourcefiles/what_is_this_image.PNG)

1. 通过单击“**查看历史记录**”，然后单击“**开始新聊天**”来开启新主题。

1. 在页面底部，选择加号 (**+**) 图标。

1. 浏览到下载图像的位置，选择“**What is this picture.png**”，然后选择“**打开**”。
1. 在“**给 Copilot 发送消息...**”中 文本框键入提示：

    ```text
    What is this picture?
    ```

1. 选择“提交”**** 按钮。

### 显示 Copilot 如何创建图像

1. 在“**给 Copilot 发送消息**”文本框中，复制并粘贴提示：

    ```text
    Copilot, make a banner for a hamburger stand. Make it friendly and show people enjoying a hamburger.
    ```

1. 选择“提交”**** 按钮。

[返回到索引](https://microsoftlearning.github.io/MS-4012-Microsoft-Copilot-Web-Based-Interactive-Experience-for-Executives/)
