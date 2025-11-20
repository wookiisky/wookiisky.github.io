# 快速上手教程

## 配置大模型
在扩展设置页面，选择『语言模型』，点击右上角『添加新模型』按钮创建新的大模型配置。
然后需要获取大模型的API信息，现在大多平台都有免费使用的额度。

### 国外（需要可以访问国外的网络）
#### 谷歌的Gemini（推荐）
获取API key
1. 访问 [https://aistudio.google.com/api-keys](https://aistudio.google.com/api-keys),登录账号
2. 点击"Create API key"按钮
3. 输入名称，没有project则随便创建一个
4. 复制API Key部分的文本（AI开头的长串）

配置：
1. Base URL配置：https://generativelanguage.googleapis.com
2. 模型id可以选择：
  - gemini-2.5-pro: 强大，但速度慢
  - gemini-flash-latest：比上一个快，效果不如pro
  - gemini-3-pro-preview：需要是付费账户

免费额度参考：https://ai.google.dev/gemini-api/docs/pricing
