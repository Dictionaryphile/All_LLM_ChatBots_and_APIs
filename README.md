# 宇宙最全大模型 ChatBot 及 API 导航

## 说明：
- 汇总自己用过的大模型 ChatBot 及 API

## 大模型 ChatBot
ChatGPT 以及类 ChatGPT 网页地址：

* 🤖 	ChatGPT	https://chatgpt.com/
* 🤖 	Claude	https://claude.ai/
* 🤖 	阿里通义	https://tongyi.aliyun.com/qianwen/
* 🤖 	月之暗面 Kimi 智能助手	https://kimi.moonshot.cn/
* 🤖 	百川智能百小应	https://ying.baichuan-ai.com/
* 🤖 	Google Gemini	https://gemini.google.com/
* 🤖 	智谱清言	https://chatglm.cn/
* 🤖 	360智脑	https://chat.360.cn/
* 🤖 	豆包	https://www.doubao.com/
* 🤖 	阶跃星辰跃问	https://yuewen.cn/
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
* 🤖 	秘塔AI搜索	https://metaso.cn/

## 大模型 API

## 说明
- `【1:1 元/千tokens】 = (【输入 元/千tokens】+输出 元/千tokens) /2`
- 最后更新时间 `2024-05-23`。
- 汇率来自[中国人民银行官网人民币汇率中间价对美元](http://www.pbc.gov.cn/rmyh/108976/109428/index.html)，2024-05-22 7.1077。
- 最大上下文长度：10000k。
- 国产最便宜：百度、腾讯、讯飞均有免费 API。
- 国产最昂贵：1:1 输入输出 150.0000 元/百万 tokens。
- 将下面的 Markdown 预览表格复制粘贴到 Excel 中，可供筛选、排序。


| 服务商 | 官方定价页面 | 模型 | 上下文长度 | 1:1 元/千tokens | 1:1 元/百万tokens | 输入 元/千tokens | 输入 元/百万tokens | 输出 元/千tokens | 输出 元/百万tokens | Input 美元/1M tokens | Output 美元/1M tokens |
|-----|--------|----|-------|---------------|----------------|--------------|---------------|--------------|---------------|--------------------|---------------------|
| OpenAI | [API Pricing](https://openai.com/api/pricing/) | gpt-4-turbo | 128k | 0.14215 | 142.1540 | 0.0711 | 71.0770 | 0.2132 | 213.2310 | 10.0000 | 30.0000 |
| OpenAI | [API Pricing](https://openai.com/api/pricing/) | gpt-4 |  | 0.31985 | 319.8465 | 0.2132 | 213.2310 | 0.4265 | 426.4620 | 30.0000 | 60.0000 |
| OpenAI | [API Pricing](https://openai.com/api/pricing/) | gpt-4-32k | 32k | 0.63969 | 639.6930 | 0.4265 | 426.4620 | 0.8529 | 852.9240 | 60.0000 | 120.0000 |
| OpenAI | [API Pricing](https://openai.com/api/pricing/) | gpt-4o | 128k | 0.07108 | 71.0770 | 0.0355 | 35.5385 | 0.1066 | 106.6155 | 5.0000 | 15.0000 |
| OpenAI | [API Pricing](https://openai.com/api/pricing/) | gpt-3.5-turbo-0125 | 16k | 0.00711 | 7.1077 | 0.0036 | 3.5539 | 0.0107 | 10.6616 | 0.5000 | 1.5000 |
| OpenAI | [API Pricing](https://openai.com/api/pricing/) | gpt-3.5-turbo-instruct | 4k | 0.01244 | 12.4385 | 0.0107 | 10.6616 | 0.0142 | 14.2154 | 1.5000 | 2.0000 |
| Claude | [API Pricing](https://www.anthropic.com/api) | Claude 3 Opus | 200k | 0.31985 | 319.8465 | 0.1066 | 106.6155 | 0.5331 | 533.0775 | 15.0000 | 75.0000 |
| Claude | [API Pricing](https://www.anthropic.com/api) | Claude 3 Sonnet | 200k | 0.06397 | 63.9693 | 0.0213 | 21.3231 | 0.1066 | 106.6155 | 3.0000 | 15.0000 |
| Claude | [API Pricing](https://www.anthropic.com/api) | Claude 3 Haiku | 200k | 0.00533 | 5.3308 | 0.0018 | 1.7769 | 0.0089 | 8.8846 | 0.2500 | 1.2500 |
| Claude | [API Pricing](https://www.anthropic.com/api) | Claude 2.1 | 200k | 0.11372 | 113.7232 | 0.0569 | 56.8616 | 0.1706 | 170.5848 | 8.0000 | 24.0000 |
| Claude | [API Pricing](https://www.anthropic.com/api) | Claude 2.0 | 100k | 0.11372 | 113.7232 | 0.0569 | 56.8616 | 0.1706 | 170.5848 | 8.0000 | 24.0000 |
| Claude | [API Pricing](https://www.anthropic.com/api) | Claude Instant | 100k | 0.01137 | 11.3723 | 0.0057 | 5.6862 | 0.0171 | 17.0585 | 0.8000 | 2.4000 |
| Google | [API Pricing](https://ai.google.dev/pricing) | Gemini 1.5 Pro | 1000k | 0.09951 | 99.5078 | 0.0498 | 49.7539 | 0.1493 | 149.2617 | 7.0000 | 21.0000 |
| Google | [API Pricing](https://ai.google.dev/pricing) | Gemini 1.0 Pro |  | 0.00711 | 7.1077 | 0.0036 | 3.5539 | 0.0107 | 10.6616 | 0.5000 | 1.5000 |
| 智谱 ChatGLM | [API Pricing](https://open.bigmodel.cn/pricing) | GLM-4 | 128K | 0.10000 | 100.0000 | 0.1000 | 100.0000 | 0.1000 | 100.0000 |  |  |
| 智谱 ChatGLM | [API Pricing](https://open.bigmodel.cn/pricing) | GML-4V | 2K | 0.10000 | 100.0000 | 0.1000 | 100.0000 | 0.1000 | 100.0000 |  |  |
| 智谱 ChatGLM | [API Pricing](https://open.bigmodel.cn/pricing) | GLM-3-Turbo | 128K | 0.00100 | 1.0000 | 0.0010 | 1.0000 | 0.0010 | 1.0000 |  |  |
| 月之暗面 Moonshot | [API Pricing](https://platform.moonshot.cn/docs/pricing) | moonshot-v1-8k | 8k | 0.01200 | 12.0000 | 0.0120 | 12.0000 | 0.0120 | 12.0000 |  |  |
| 月之暗面 Moonshot | [API Pricing](https://platform.moonshot.cn/docs/pricing) | moonshot-v1-32k | 32k | 0.02400 | 24.0000 | 0.0240 | 24.0000 | 0.0240 | 24.0000 |  |  |
| 月之暗面 Moonshot | [API Pricing](https://platform.moonshot.cn/docs/pricing) | moonshot-v1-128k | 128k | 0.06000 | 60.0000 | 0.0600 | 60.0000 | 0.0600 | 60.0000 |  |  |
| 稀宇科技 MiniMax | [API Pricing](https://www.minimaxi.com/document/price) | abab6.5 | 8k | 0.03000 | 30.0000 | 0.0300 | 30.0000 | 0.0300 | 30.0000 |  |  |
| 稀宇科技 MiniMax | [API Pricing](https://www.minimaxi.com/document/price) | abab6.5s | 245k | 0.01000 | 10.0000 | 0.0100 | 10.0000 | 0.0100 | 10.0000 |  |  |
| 稀宇科技 MiniMax | [API Pricing](https://www.minimaxi.com/document/price) | abab6 | 32k | 0.10000 | 100.0000 | 0.1000 | 100.0000 | 0.1000 | 100.0000 |  |  |
| 稀宇科技 MiniMax | [API Pricing](https://www.minimaxi.com/document/price) | abab5.5 |  | 0.01500 | 15.0000 | 0.0150 | 15.0000 | 0.0150 | 15.0000 |  |  |
| 稀宇科技 MiniMax | [API Pricing](https://www.minimaxi.com/document/price) | abab5.5s | 8k | 0.00500 | 5.0000 | 0.0050 | 5.0000 | 0.0050 | 5.0000 |  |  |
| 文心一言 | [API Pricing](https://cloud.baidu.com/doc/WENXINWORKSHOP/s/hlrk4akp7) | ERNIE 4.0系列 |  | 0.12000 | 120.0000 | 0.1200 | 120.0000 | 0.1200 | 120.0000 |  |  |
| 文心一言 | [API Pricing](https://cloud.baidu.com/doc/WENXINWORKSHOP/s/hlrk4akp7) | ERNIE 3.5系列 |  | 0.01200 | 12.0000 | 0.0120 | 12.0000 | 0.0120 | 12.0000 |  |  |
| 文心一言 | [API Pricing](https://cloud.baidu.com/doc/WENXINWORKSHOP/s/hlrk4akp7) | ERNIE Speed系列 |  | 0.00000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |  |  |
| 文心一言 | [API Pricing](https://cloud.baidu.com/doc/WENXINWORKSHOP/s/hlrk4akp7) | ERNIE Lite系列 |  | 0.00000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |  |  |
| 文心一言 | [API Pricing](https://cloud.baidu.com/doc/WENXINWORKSHOP/s/hlrk4akp7) | ERNIE Tiny系列 |  | 0.00000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |  |  |
| 百川智能 | [API Pricing](https://platform.baichuan-ai.com/price) | Baichuan4 |  | 0.10000 | 100.0000 | 0.1000 | 100.0000 | 0.1000 | 100.0000 |  |  |
| 百川智能 | [API Pricing](https://platform.baichuan-ai.com/price) | Baichuan3-Turbo |  | 0.01200 | 12.0000 | 0.0120 | 12.0000 | 0.0120 | 12.0000 |  |  |
| 百川智能 | [API Pricing](https://platform.baichuan-ai.com/price) | Baichuan3-Turbo-128k |  | 0.02400 | 24.0000 | 0.0240 | 24.0000 | 0.0240 | 24.0000 |  |  |
| 百川智能 | [API Pricing](https://platform.baichuan-ai.com/price) | Baichuan2-Turbo |  | 0.00800 | 8.0000 | 0.0080 | 8.0000 | 0.0080 | 8.0000 |  |  |
| 百川智能 | [API Pricing](https://platform.baichuan-ai.com/price) | Baichuan2-Turbo-192k | 192k | 0.01600 | 16.0000 | 0.0160 | 16.0000 | 0.0160 | 16.0000 |  |  |
| 深度求索 | [API Pricing](https://platform.deepseek.com/api-docs/zh-cn/pricing/) | deepseek-chat | 32k | 0.00150 | 1.5000 | 0.0010 | 1.0000 | 0.0020 | 2.0000 | 0.1400 | 0.2800 |
| 通义千问 | [API Pricing](https://help.aliyun.com/zh/dashscope/developer-reference/tongyi-thousand-questions-metering-and-billing) | qwen-long |  | 0.00125 | 1.2500 | 0.0005 | 0.5000 | 0.0020 | 2.0000 |  |  |
| 通义千问 | [API Pricing](https://help.aliyun.com/zh/dashscope/developer-reference/tongyi-thousand-questions-metering-and-billing) | qwen-max |  | 0.08000 | 80.0000 | 0.0400 | 40.0000 | 0.1200 | 120.0000 |  |  |
| 通义千问 | [API Pricing](https://help.aliyun.com/zh/dashscope/developer-reference/tongyi-thousand-questions-metering-and-billing) | qwen-plus |  | 0.00800 | 8.0000 | 0.0040 | 4.0000 | 0.0120 | 12.0000 |  |  |
| 通义千问 | [API Pricing](https://help.aliyun.com/zh/dashscope/developer-reference/tongyi-thousand-questions-metering-and-billing) | qwen-turbo |  | 0.00400 | 4.0000 | 0.0020 | 2.0000 | 0.0060 | 6.0000 |  |  |
| 腾讯混元 | [API Pricing](https://cloud.tencent.com/document/product/1729/97731) | hunyuan-pro |  | 0.06500 | 65.0000 | 0.0300 | 30.0000 | 0.1000 | 100.0000 |  |  |
| 腾讯混元 | [API Pricing](https://cloud.tencent.com/document/product/1729/97731) | hunyuan-standard |  | 0.00475 | 4.7500 | 0.0045 | 4.5000 | 0.0050 | 5.0000 |  |  |
| 腾讯混元 | [API Pricing](https://cloud.tencent.com/document/product/1729/97731) | hunyuan-lite |  | 0.00000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |  |  |
| 腾讯混元 | [API Pricing](https://cloud.tencent.com/document/product/1729/97731) | hunyuan-standard-256k | 256k | 0.03750 | 37.5000 | 0.0150 | 15.0000 | 0.0600 | 60.0000 |  |  |
| 阶跃星辰 | [API Pricing](https://platform.stepfun.com/docs/overview/concept) | step-1-200k | 200k | 0.15000 | 150.0000 | 0.1500 | 150.0000 | 0.1500 | 150.0000 |  |  |
| 阶跃星辰 | [API Pricing](https://platform.stepfun.com/docs/overview/concept) | step-1-32k | 32k | 0.02400 | 24.0000 | 0.0240 | 24.0000 | 0.0240 | 24.0000 |  |  |
| 阶跃星辰 | [API Pricing](https://platform.stepfun.com/docs/overview/concept) | step-1v-32k | 32k | 0.02400 | 24.0000 | 0.0240 | 24.0000 | 0.0240 | 24.0000 |  |  |
| 零一万物 | [API Pricing](https://platform.lingyiwanwu.com/) | yi-34b-chat-0205 | 4K | 0.00250 | 2.5000 | 0.0025 | 2.5000 | 0.0025 | 2.5000 |  |  |
| 零一万物 | [API Pricing](https://platform.lingyiwanwu.com/) | yi-34b-chat-200k | 200K | 0.01200 | 12.0000 | 0.0120 | 12.0000 | 0.0120 | 12.0000 |  |  |
| MISTRAL | [API Pricing](https://mistral.ai/technology/#pricing) | open-mistral-7b |  | 0.00178 | 1.7769 | 0.0018 | 1.7769 | 0.0018 | 1.7769 | 0.2500 | 0.2500 |
| MISTRAL | [API Pricing](https://mistral.ai/technology/#pricing) | open-mixtral-8x7b |  | 0.00498 | 4.9754 | 0.0050 | 4.9754 | 0.0050 | 4.9754 | 0.7000 | 0.7000 |
| MISTRAL | [API Pricing](https://mistral.ai/technology/#pricing) | open-mixtral-8x22b |  | 0.02843 | 28.4308 | 0.0142 | 14.2154 | 0.0426 | 42.6462 | 2.0000 | 6.0000 |
| MISTRAL | [API Pricing](https://mistral.ai/technology/#pricing) | mistral-small |  | 0.02843 | 28.4308 | 0.0142 | 14.2154 | 0.0426 | 42.6462 | 2.0000 | 6.0000 |
| MISTRAL | [API Pricing](https://mistral.ai/technology/#pricing) | mistral-medium |  | 0.03838 | 38.3816 | 0.0192 | 19.1908 | 0.0576 | 57.5724 | 2.7000 | 8.1000 |
| MISTRAL | [API Pricing](https://mistral.ai/technology/#pricing) | mistral-large |  | 0.11372 | 113.7232 | 0.0569 | 56.8616 | 0.1706 | 170.5848 | 8.0000 | 24.0000 |
| 字节跳动 | [API Pricing](https://www.volcengine.com/docs/82379/1099320) | Doubao-lite-128k | 128k | 0.00090 | 0.9000 | 0.0008 | 0.8000 | 0.0010 | 1.0000 |  |  |
| 字节跳动 | [API Pricing](https://www.volcengine.com/docs/82379/1099320) | Doubao-lite-32k | 32k | 0.00045 | 0.4500 | 0.0003 | 0.3000 | 0.0006 | 0.6000 |  |  |
| 字节跳动 | [API Pricing](https://www.volcengine.com/docs/82379/1099320) | Doubao-lite-4k | 4k | 0.00045 | 0.4500 | 0.0003 | 0.3000 | 0.0006 | 0.6000 |  |  |
| 字节跳动 | [API Pricing](https://www.volcengine.com/docs/82379/1099320) | Doubao-pro-128k | 128k | 0.00700 | 7.0000 | 0.0050 | 5.0000 | 0.0090 | 9.0000 |  |  |
| 字节跳动 | [API Pricing](https://www.volcengine.com/docs/82379/1099320) | Doubao-pro-32k | 32k | 0.00140 | 1.4000 | 0.0008 | 0.8000 | 0.0020 | 2.0000 |  |  |
| 字节跳动 | [API Pricing](https://www.volcengine.com/docs/82379/1099320) | Doubao-pro-4k | 4k | 0.00140 | 1.4000 | 0.0008 | 0.8000 | 0.0020 | 2.0000 |  |  |
| 字节跳动 | [API Pricing](https://www.volcengine.com/docs/82379/1099320) | Skylark2-lite-8k | 8k | 0.00400 | 4.0000 | 0.0040 | 4.0000 | 0.0040 | 4.0000 |  |  |
| 字节跳动 | [API Pricing](https://www.volcengine.com/docs/82379/1099320) | Skylark2-pro-4k | 4k | 0.01300 | 13.0000 | 0.0110 | 11.0000 | 0.0150 | 15.0000 |  |  |
| 字节跳动 | [API Pricing](https://www.volcengine.com/docs/82379/1099320) | Skylark2-pro-character-4k | 4k | 0.01300 | 13.0000 | 0.0110 | 11.0000 | 0.0150 | 15.0000 |  |  |
| 字节跳动 | [API Pricing](https://www.volcengine.com/docs/82379/1099320) | Skylark2-pro-32k | 32k | 0.02400 | 24.0000 | 0.0120 | 12.0000 | 0.0360 | 36.0000 |  |  |
| 字节跳动 | [API Pricing](https://www.volcengine.com/docs/82379/1099320) | Skylark2-pro-turbo-8k | 8k | 0.00750 | 7.5000 | 0.0040 | 4.0000 | 0.0110 | 11.0000 |  |  |
| 商汤日日新 | [API Pricing](https://platform.sensenova.cn/doc?path=/pricingdoc/pricing.md) | SenseChat-5 |  | 0.10000 | 100.0000 |  |  |  |  |  |  |
| 商汤日日新 | [API Pricing](https://platform.sensenova.cn/doc?path=/pricingdoc/pricing.md) | SenseChat |  | 0.01200 | 12.0000 |  |  |  |  |  |  |
| 商汤日日新 | [API Pricing](https://platform.sensenova.cn/doc?path=/pricingdoc/pricing.md) | SenseChat-32K | 32K | 0.03600 | 36.0000 |  |  |  |  |  |  |
| 商汤日日新 | [API Pricing](https://platform.sensenova.cn/doc?path=/pricingdoc/pricing.md) | SenseChat-128K | 128K | 0.06000 | 60.0000 |  |  |  |  |  |  |
| 商汤日日新 | [API Pricing](https://platform.sensenova.cn/doc?path=/pricingdoc/pricing.md) | SenseChat-Turbo |  | 0.00500 | 5.0000 |  |  |  |  |  |  |
| 元象大模型 | [API Pricing](https://help.xverse.cn/docs/api-price) | XVERSE-65B-2 |  | 0.01200 | 12.0000 |  |  |  |  |  |  |
| 元象大模型 | [API Pricing](https://help.xverse.cn/docs/api-price) | XVERSE-13B-2 |  | 0.00500 | 5.0000 |  |  |  |  |  |  |
| 紫东太初 | [API Pricing](https://docs.wair.ac.cn/maas/jiage.html) | Taichu-2.0 | 32K | 0.00200 | 2.0000 |  |  |  |  |  |  |
| 紫东太初 | [API Pricing](https://docs.wair.ac.cn/maas/jiage.html) | Taichu-2.0V | 4K | 0.00500 | 5.0000 |  |  |  |  |  |  |
| 天工 | [API Pricing](https://model-platform.tiangong.cn/pricing) | SkyChat-MegaVerse |  | 0.01000 | 10.0000 |  |  |  |  |  |  |
| 星火大模型 | [API Pricing](https://xinghuo.xfyun.cn/sparkapi) | Spark Lite |  | 0.00000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 | 0.0000 |  |  |
| 星火大模型 | [API Pricing](https://xinghuo.xfyun.cn/sparkapi) | Spark Pro |  |  |  |  |  |  |  |  |  |
| 星火大模型 | [API Pricing](https://xinghuo.xfyun.cn/sparkapi) | Spark3.5 Max |  |  |  |  |  |  |  |  |  |
| 360智脑 | [API Pricing](https://ai.360.com/open) |  |  |  |  |  |  |  |  |  |  |
| Azure OpenAI Service | [API Pricing](https://azure.microsoft.com/en-us/products/ai-services/openai-service) |  |  |  |  |  |  |  |  |  |  |
| Replicate | [API Pricing](https://replicate.com/pricing) |  |  |  |  |  |  |  |  |  |  |
| cohere | [API Pricing](https://cohere.com/pricing) |  |  |  |  |  |  |  |  |  |  |
| groq | [API Pricing](https://wow.groq.com/) |

