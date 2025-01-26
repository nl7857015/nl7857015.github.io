## 一、ChatGPT API简介

近期，OpenAI推出了收费计划，开放了ChatGPT和Whisper API。ChatGPT API允许企业在其应用程序、网站和服务中集成其功能，而Whisper API则实现语音转文本的功能。

ChatGPT API的主要用途在于允许企业和个人将ChatGPT的强大功能整合到自有的平台中，以满足不同的需求。其定价为$0.002/1K tokens，十分具有吸引力。

ChatGPT API的开放，类似于乔布斯当时建立的Apple应用商店，为全球的开发者提供了利用人工智能的机会。

## 二、ChatGPT账号申请及充值

在开始之前，确保你已经申请了OpenAI官网账号。如果你还没有，可以先参考相关的新手教程，申请一个账号。申请过程中需要借助接码平台和Depay虚拟信用卡，成本不到1美元，并支持支付宝。

成功申请卡后，登录OpenAI网站，进入右上角的账号信息，选择“Billing”设置付款方式，绑定你刚申请的卡号以便对ChatGPT API进行充值。

## 三、开始使用ChatGPT API

注册完成后，登录界面会显示选项。点击右上角的“View API keys”，然后选择“Create new secret key”，生成你自己的API密钥。请务必在关闭对话框之前将密钥复制并妥善保存，以确保安全。

在左侧栏中，使用“Usage”选项可以清晰查看token的使用情况。OpenAI为每个新注册的账户提供$18的免费token使用额度，费用低廉的情况下，获得了较高的使用额度。

ChatGPT API使用方法相对简单，可以使用curl命令进行测试，只需将`$OPENAI_API_KEY`替换为你的API密钥即可。此外，OpenAI也提供了多种编程语言的实现代码，例如Python，只需导入openai包并使用申请的API密钥即可。

## 四、ChatGPT API使用常见问题

### 1. GPT-3.5-turbo模型

GPT-3.5是OpenAI目前提供的最强大的文本生成模型，其中“turbo”代表其优化版本，具有更快的响应速度。预计GPT-4将在未来发布，gpt-3.5-turbo的成本仅为达芬奇text-davinci-003的十分之一，并将持续更新。

### 2. ChatGPT API的速度

使用体验表明，ChatGPT API的响应速度较快，远超官方的ChatGPT，用户无需等待逐字输出，提高了使用的流畅性。

### 3. 如何为ChatGPT API充值

由于国内无法通过任何银行卡充值，建议使用Depay虚拟信用卡绑定充值，具体操作请参考官方指导文档。如果你已有国外银行卡，充值将更加便捷。

### 4. ChatGPT API Token收费标准

官方的收费标准为$0.002/1K tokens，约750词。虽然1K tokens看似不少，但实际使用中，发送一段文本可能会消耗大量tokens。一个问题的询问通常需要消耗100多个tokens，因此在连续会话中，历史消息的回传也将增加费用。

### 5. ChatGPT API的连续会话能力

ChatGPT API支持上下文联系，提供连续对话的能力。通过在接口参数中传递历史对话内容，可以实现自然流畅的交流，但这也会增加token的消耗。单次传递的token上限为4096，超出限制将返回错误。

### 6. ChatGPT API使用的地区限制

目前有用户反映国内访问API的稳定性有所下降，但仍有用户在正常使用中。未来可能需要依赖国际IP访问。

### 7. 关于套壳APP及网站

随着ChatGPT API的发布，可能会出现一些声称使用最新API的套壳APP或网站。请谨慎使用这些服务，因为token是需要付费的，若要实现优质的连续会话，可能需要消耗大量tokens。

### 8. Whisper API

除了ChatGPT API，OpenAI还推出了Whisper API，这是一个优秀的语音转文字模型，支持按需使用，价格为每分钟0.006美元。Whisper API可以用于转录和翻译，文件格式多样，便于开发者使用。

## 五、ChatGPT Plus是否仍需续费？

有些人可能会问，ChatGPT API推出后是否还需续费ChatGPT Plus。实际上，两者的使用场景有所不同。ChatGPT API更适合程序员和开发者，普通用户使用门槛较高。此外，尽管token看似便宜，但实际使用中需要回传历史消息来维持上下文，费用可能并不低于Plus的$20定价。

API的响应速度较快，但在回答质量方面，当前还是ChatGPT Plus更具优势。

## 六、如何升级到ChatGPT Plus?

👉 [野卡 | 一分钟注册，轻松订阅海外线上服务](https://bit.ly/bewildcard)