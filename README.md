# 宇宙最全大模型 ChatBot 及 API 导航

## 说明：
- 汇总自己用过的大模型 ChatBot 及 API

## 大模型 ChatBot
ChatGPT 以及类 ChatGPT 网页地址：

* 🤖 	ChatGPT	https://chat.openai.com/
* 🤖 	Claude	https://claude.ai/
* 🤖 	阿里通义千问	https://qianwen.aliyun.com/
* 🤖 	月之暗面 Kimi 智能助手	https://kimi.moonshot.cn/
* 🤖 	百川智能	https://chat.baichuan-ai.com/
* 🤖 	Google Gemini	https://gemini.google.com/
* 🤖 	智谱清言	https://chatglm.cn/
* 🤖 	360智脑	https://chat.360.cn/
* 🤖 	抖音豆包（云雀大模型）	https://www.doubao.com/
* 🤖 	阶跃星辰跃问	https://stepchat.cn/chats/
* 🤖 	稀宇科技海螺AI	https://hailuoai.com/
* 🤖 	Meta AI	https://www.meta.ai/
* 🤖 	Microsoft Copilot	https://www.bing.com/chat
* 🤖 	讯飞星火	https://xinghuo.xfyun.cn/
* 🤖 	百度文心一言	https://yiyan.baidu.com/
* 🤖 	腾讯混元大模型	https://hunyuan.tencent.com/bot/chat
* 🤖 	HuggingChat	https://huggingface.co/chat/
* 🤖 	昆仑万维天工大模型	https://tiangong.kunlun.com/
* 🤖 	面壁露卡	https://luca.cn/chat
* 🤖 	YAYI雅意	https://yayi.wenge.com/
* 🤖 	Mistral	https://chat.mistral.ai/chat/
* 🤖 	元象大模型	https://chat.xverse.cn/xchat/index.html
* 🤖 	深度求索 DeepSeek	https://chat.deepseek.com/
* 🤖 	MOSS	https://moss.fastnlp.top/moss/#/
* 🤖 	孟子	https://www.langboat.com/product/mchat
* 🤖 	好未来 MathGPT	https://www.mathgpt.com/
* 🤖 	妙想金融大模型	https://ai.eastmoney.com/chat
* 🤖 	同花顺HithinkGPT	https://aimiai.com/popular/hithinkChat
* 🤖 	商汤商量	https://chat.sensetime.com/
* 🤖 	零一万物万知	https://www.wanzhi.com/

## 大模型 API

## 说明
- `【1:1 元/千tokens】 = (【输入 元/千tokens】+输出 元/千tokens) /2`
- 最后更新时间 `2024-05-12`。
- 汇率来自[中国人民银行官网人民币汇率中间价对美元](http://www.pbc.gov.cn/rmyh/108976/109428/index.html)，2024-05-10 7.1011。
- 最大上下文长度：1000k。
- 国产最便宜：1:1 输入输出 1.0000 元/百万 tokens。
- 国产最昂贵：1:1 输入输出 150.0000 元/百万 tokens。
- 将下面的 Markdown 预览表格复制粘贴到 Excel 中，可供筛选、排序。


| 服务商 | 官方定价页面 | 模型 | 上下文长度 | 1:1 元/千tokens | 1:1 元/百万tokens | 输入 元/千tokens | 输入 元/百万tokens | 输出 元/千tokens | 输出 元/百万tokens | Input 美元/1M tokens | Output 美元/1M tokens |
|-----|--------|----|-------|---------------|----------------|--------------|---------------|--------------|---------------|--------------------|---------------------|
| OpenAI | [API Pricing](https://openai.com/pricing) | gpt-4-turbo-2024-04-09 | 128k | 0.1420 | 142.0220 | 0.0710 | 71.0110 | 0.2130 | 213.0330 | 10.0000 | 30.0000 |
| OpenAI | [API Pricing](https://openai.com/pricing) | gpt-4 |  | 0.3195 | 319.5495 | 0.2130 | 213.0330 | 0.4261 | 426.0660 | 30.0000 | 60.0000 |
| OpenAI | [API Pricing](https://openai.com/pricing) | gpt-4-32k | 32k | 0.6391 | 639.0990 | 0.4261 | 426.0660 | 0.8521 | 852.1320 | 60.0000 | 120.0000 |
| OpenAI | [API Pricing](https://openai.com/pricing) | gpt-3.5-turbo-0125 | 16k | 0.0071 | 7.1011 | 0.0036 | 3.5506 | 0.0107 | 10.6517 | 0.5000 | 1.5000 |
| OpenAI | [API Pricing](https://openai.com/pricing) | gpt-3.5-turbo-instruct | 4k | 0.0124 | 12.4269 | 0.0107 | 10.6517 | 0.0142 | 14.2022 | 1.5000 | 2.0000 |
| Claude | [API Pricing](https://www.anthropic.com/api) | Claude 3 Opus | 200k | 0.3195 | 319.5495 | 0.1065 | 106.5165 | 0.5326 | 532.5825 | 15.0000 | 75.0000 |
| Claude | [API Pricing](https://www.anthropic.com/api) | Claude 3 Sonnet | 200k | 0.0639 | 63.9099 | 0.0213 | 21.3033 | 0.1065 | 106.5165 | 3.0000 | 15.0000 |
| Claude | [API Pricing](https://www.anthropic.com/api) | Claude 3 Haiku | 200k | 0.0053 | 5.3258 | 0.0018 | 1.7753 | 0.0089 | 8.8764 | 0.2500 | 1.2500 |
| Claude | [API Pricing](https://www.anthropic.com/api) | Claude 2.1 | 200k | 0.1136 | 113.6176 | 0.0568 | 56.8088 | 0.1704 | 170.4264 | 8.0000 | 24.0000 |
| Claude | [API Pricing](https://www.anthropic.com/api) | Claude 2.0 | 100k | 0.1136 | 113.6176 | 0.0568 | 56.8088 | 0.1704 | 170.4264 | 8.0000 | 24.0000 |
| Claude | [API Pricing](https://www.anthropic.com/api) | Claude Instant | 100k | 0.0114 | 11.3618 | 0.0057 | 5.6809 | 0.0170 | 17.0426 | 0.8000 | 2.4000 |
| Google | [API Pricing](https://ai.google.dev/pricing) | Gemini 1.5 Pro | 1000k | 0.0994 | 99.4154 | 0.0497 | 49.7077 | 0.1491 | 149.1231 | 7.0000 | 21.0000 |
| Google | [API Pricing](https://ai.google.dev/pricing) | Gemini 1.0 Pro |  | 0.0071 | 7.1011 | 0.0036 | 3.5506 | 0.0107 | 10.6517 | 0.5000 | 1.5000 |
| 智谱 ChatGLM | [API Pricing](https://open.bigmodel.cn/pricing) | GLM-4 | 128K | 0.1000 | 100.0000 | 0.1000 | 100.0000 | 0.1000 | 100.0000 |  |  |
| 智谱 ChatGLM | [API Pricing](https://open.bigmodel.cn/pricing) | GML-4V | 2K | 0.1000 | 100.0000 | 0.1000 | 100.0000 | 0.1000 | 100.0000 |  |  |
| 智谱 ChatGLM | [API Pricing](https://open.bigmodel.cn/pricing) | GLM-3-Turbo | 128K | 0.0010 | 1.0000 | 0.0010 | 1.0000 | 0.0010 | 1.0000 |  |  |
| 月之暗面 Moonshot | [API Pricing](https://platform.moonshot.cn/docs/pricing) | moonshot-v1-8k | 8k | 0.0120 | 12.0000 | 0.0120 | 12.0000 | 0.0120 | 12.0000 |  |  |
| 月之暗面 Moonshot | [API Pricing](https://platform.moonshot.cn/docs/pricing) | moonshot-v1-32k | 32k | 0.0240 | 24.0000 | 0.0240 | 24.0000 | 0.0240 | 24.0000 |  |  |
| 月之暗面 Moonshot | [API Pricing](https://platform.moonshot.cn/docs/pricing) | moonshot-v1-128k | 128k | 0.0600 | 60.0000 | 0.0600 | 60.0000 | 0.0600 | 60.0000 |  |  |
| 稀宇科技 MiniMax | [API Pricing](https://www.minimaxi.com/document/price) | abab6.5 | 8k | 0.0300 | 30.0000 | 0.0300 | 30.0000 | 0.0300 | 30.0000 |  |  |
| 稀宇科技 MiniMax | [API Pricing](https://www.minimaxi.com/document/price) | abab6.5s | 245k | 0.0100 | 10.0000 | 0.0100 | 10.0000 | 0.0100 | 10.0000 |  |  |
| 稀宇科技 MiniMax | [API Pricing](https://www.minimaxi.com/document/price) | abab6 | 32k | 0.1000 | 100.0000 | 0.1000 | 100.0000 | 0.1000 | 100.0000 |  |  |
| 稀宇科技 MiniMax | [API Pricing](https://www.minimaxi.com/document/price) | abab5.5 |  | 0.0150 | 15.0000 | 0.0150 | 15.0000 | 0.0150 | 15.0000 |  |  |
| 稀宇科技 MiniMax | [API Pricing](https://www.minimaxi.com/document/price) | abab5.5s | 8k | 0.0050 | 5.0000 | 0.0050 | 5.0000 | 0.0050 | 5.0000 |  |  |
| 文心一言 | [API Pricing](https://cloud.baidu.com/doc/WENXINWORKSHOP/s/hlrk4akp7) | ERNIE-4.0-8K | 8K | 0.1200 | 120.0000 | 0.1200 | 120.0000 | 0.1200 | 120.0000 |  |  |
| 文心一言 | [API Pricing](https://cloud.baidu.com/doc/WENXINWORKSHOP/s/hlrk4akp7) | ERNIE-3.5-8K | 8K | 0.0120 | 12.0000 | 0.0120 | 12.0000 | 0.0120 | 12.0000 |  |  |
| 百川智能 | [API Pricing](https://platform.baichuan-ai.com/price) | Baichuan2-Turbo |  | 0.0080 | 8.0000 | 0.0080 | 8.0000 | 0.0080 | 8.0000 |  |  |
| 百川智能 | [API Pricing](https://platform.baichuan-ai.com/price) | Baichuan2-Turbo-192k | 192k | 0.0160 | 16.0000 | 0.0160 | 16.0000 | 0.0160 | 16.0000 |  |  |
| 深度求索 | [API Pricing](https://platform.deepseek.com/api-docs/zh-cn/pricing/) | deepseek-chat | 32k | 0.0015 | 1.5000 | 0.0010 | 1.0000 | 0.0020 | 2.0000 | 0.1400 | 0.2800 |
| 通义千问 | [API Pricing](https://help.aliyun.com/zh/dashscope/developer-reference/tongyi-thousand-questions-metering-and-billing) | qwen-max |  | 0.1200 | 120.0000 | 0.1200 | 120.0000 | 0.1200 | 120.0000 |  |  |
| 通义千问 | [API Pricing](https://help.aliyun.com/zh/dashscope/developer-reference/tongyi-thousand-questions-metering-and-billing) | qwen-plus |  | 0.0200 | 20.0000 | 0.0200 | 20.0000 | 0.0200 | 20.0000 |  |  |
| 通义千问 | [API Pricing](https://help.aliyun.com/zh/dashscope/developer-reference/tongyi-thousand-questions-metering-and-billing) | qwen-turbo |  | 0.0080 | 8.0000 | 0.0080 | 8.0000 | 0.0080 | 8.0000 |  |  |
| 腾讯混元 | [API Pricing](https://cloud.tencent.com/document/product/1729/97731) | hunyuan-pro |  | 0.1000 | 100.0000 | 0.1000 | 100.0000 | 0.1000 | 100.0000 |  |  |
| 腾讯混元 | [API Pricing](https://cloud.tencent.com/document/product/1729/97731) | hunyuan-standard |  | 0.0100 | 10.0000 | 0.0100 | 10.0000 | 0.0100 | 10.0000 |  |  |
| 腾讯混元 | [API Pricing](https://cloud.tencent.com/document/product/1729/97731) | hunyuan-lite |  | 0.0080 | 8.0000 | 0.0080 | 8.0000 | 0.0080 | 8.0000 |  |  |
| 阶跃星辰 | [API Pricing](https://platform.stepfun.com/docs/Chat/chat-completion-create) | step-1-200k | 200k | 0.1500 | 150.0000 | 0.1500 | 150.0000 | 0.1500 | 150.0000 |  |  |
| 阶跃星辰 | [API Pricing](https://platform.stepfun.com/docs/Chat/chat-completion-create) | step-1-32k | 32k | 0.0240 | 24.0000 | 0.0240 | 24.0000 | 0.0240 | 24.0000 |  |  |
| 阶跃星辰 | [API Pricing](https://platform.stepfun.com/docs/Chat/chat-completion-create) | step-1v-32k | 32k | 0.0240 | 24.0000 | 0.0240 | 24.0000 | 0.0240 | 24.0000 |  |  |
| 零一万物 | [API Pricing](https://platform.lingyiwanwu.com/) | yi-34b-chat-0205 | 4K | 0.0025 | 2.5000 | 0.0025 | 2.5000 | 0.0025 | 2.5000 |  |  |
| 零一万物 | [API Pricing](https://platform.lingyiwanwu.com/) | yi-34b-chat-200k | 200K | 0.0120 | 12.0000 | 0.0120 | 12.0000 | 0.0120 | 12.0000 |  |  |
| MISTRAL | [API Pricing](https://mistral.ai/technology/#pricing) | open-mistral-7b |  | 0.0018 | 1.7753 | 0.0018 | 1.7753 | 0.0018 | 1.7753 | 0.2500 | 0.2500 |
| MISTRAL | [API Pricing](https://mistral.ai/technology/#pricing) | open-mixtral-8x7b |  | 0.0050 | 4.9708 | 0.0050 | 4.9708 | 0.0050 | 4.9708 | 0.7000 | 0.7000 |
| MISTRAL | [API Pricing](https://mistral.ai/technology/#pricing) | open-mixtral-8x22b |  | 0.0284 | 28.4044 | 0.0142 | 14.2022 | 0.0426 | 42.6066 | 2.0000 | 6.0000 |
| MISTRAL | [API Pricing](https://mistral.ai/technology/#pricing) | mistral-small |  | 0.0284 | 28.4044 | 0.0142 | 14.2022 | 0.0426 | 42.6066 | 2.0000 | 6.0000 |
| MISTRAL | [API Pricing](https://mistral.ai/technology/#pricing) | mistral-medium |  | 0.0383 | 38.3459 | 0.0192 | 19.1730 | 0.0575 | 57.5189 | 2.7000 | 8.1000 |
| MISTRAL | [API Pricing](https://mistral.ai/technology/#pricing) | mistral-large |  | 0.1136 | 113.6176 | 0.0568 | 56.8088 | 0.1704 | 170.4264 | 8.0000 | 24.0000 |
| 字节跳动 | [API Pricing](https://www.volcengine.com/docs/82379/1099320) | Skylark2-lite-8k | 8k | 0.0040 | 4.0000 | 0.0040 | 4.0000 | 0.0040 | 4.0000 |  |  |
| 字节跳动 | [API Pricing](https://www.volcengine.com/docs/82379/1099321) | Skylark2-pro-4k | 4k | 0.0130 | 13.0000 | 0.0110 | 11.0000 | 0.0150 | 15.0000 |  |  |
| 字节跳动 | [API Pricing](https://www.volcengine.com/docs/82379/1099322) | Skylark2-pro-character-4k | 4k | 0.0130 | 13.0000 | 0.0110 | 11.0000 | 0.0150 | 15.0000 |  |  |
| 字节跳动 | [API Pricing](https://www.volcengine.com/docs/82379/1099323) | Skylark2-pro-32k | 32k | 0.0240 | 24.0000 | 0.0120 | 12.0000 | 0.0360 | 36.0000 |  |  |
| 字节跳动 | [API Pricing](https://www.volcengine.com/docs/82379/1099324) | Skylark2-pro-turbo-8k | 8k | 0.0075 | 7.5000 | 0.0040 | 4.0000 | 0.0110 | 11.0000 |  |  |
| 商汤日日新 | [API Pricing](https://platform.sensenova.cn/doc?path=/pricingdoc/pricing.md) | SenseChat-5 |  | 0.1000 | 100.0000 |  |  |  |  |  |  |
| 商汤日日新 | [API Pricing](https://platform.sensenova.cn/doc?path=/pricingdoc/pricing.md) | SenseChat |  | 0.0120 | 12.0000 |  |  |  |  |  |  |
| 商汤日日新 | [API Pricing](https://platform.sensenova.cn/doc?path=/pricingdoc/pricing.md) | SenseChat-32K | 32K | 0.0360 | 36.0000 |  |  |  |  |  |  |
| 商汤日日新 | [API Pricing](https://platform.sensenova.cn/doc?path=/pricingdoc/pricing.md) | SenseChat-128K | 128K | 0.0600 | 60.0000 |  |  |  |  |  |  |
| 商汤日日新 | [API Pricing](https://platform.sensenova.cn/doc?path=/pricingdoc/pricing.md) | SenseChat-Turbo |  | 0.0050 | 5.0000 |  |  |  |  |  |  |
| 元象大模型 | [API Pricing](https://help.xverse.cn/docs/api-price) | XVERSE-65B-2 |  | 0.0120 | 12.0000 |  |  |  |  |  |  |
| 元象大模型 | [API Pricing](https://help.xverse.cn/docs/api-price) | XVERSE-13B-2 |  | 0.0050 | 5.0000 |  |  |  |  |  |  |
| 紫东太初 | [API Pricing](https://docs.wair.ac.cn/maas/jiage.html) | Taichu-2.0 | 32K | 0.0020 | 2.0000 |  |  |  |  |  |  |
| 紫东太初 | [API Pricing](https://docs.wair.ac.cn/maas/jiage.html) | Taichu-2.0V | 4K | 0.0050 | 5.0000 |  |  |  |  |  |  |
| 天工 | [API Pricing](https://model-platform.tiangong.cn/pricing) | SkyChat-MegaVerse |  | 0.0100 | 10.0000 |  |  |  |  |  |  |
| 星火大模型 | [API Pricing](https://xinghuo.xfyun.cn/sparkapi) | V3.5 |  |  |  |  |  |  |  |  |  |
| 星火大模型 | [API Pricing](https://xinghuo.xfyun.cn/sparkapi) | V3.0 |  |  |  |  |  |  |  |  |  |
| 星火大模型 | [API Pricing](https://xinghuo.xfyun.cn/sparkapi) | V1.5 |  |  |  |  |  |  |  |  |  |
| 360智脑 | [API Pricing](https://ai.360.com/open) |  |  |  |  |  |  |  |  |  |  |
| Azure OpenAI Service | [API Pricing](https://azure.microsoft.com/en-us/products/ai-services/openai-service) |  |  |  |  |  |  |  |  |  |  |
| Replicate | [API Pricing](https://replicate.com/pricing) |  |  |  |  |  |  |  |  |  |  |
| cohere | [API Pricing](https://cohere.com/pricing) |  |  |  |  |  |  |  |  |  |  |
| groq | [API Pricing](https://wow.groq.com/) |
