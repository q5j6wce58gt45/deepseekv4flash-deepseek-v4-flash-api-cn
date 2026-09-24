# DeepSeek V4 Flash API 中文文档（deepseek-v4-flash / deepseekv4flash）

> 按量计费，$1 起充，OpenAI 兼容接口。 **input $0.3429; cached_input $0.0686; output $1.0286**

**[模型页](https://go.apimart.ai/k-7d8ac9) · [实时价格](https://go.apimart.ai/k-50d95f) · [获取 API Key](https://go.apimart.ai/k-ccb7c7)**

## 价格（快照 2026-09-24）

| 档位 | 单价 |
| --- | --- |
| `input` | $0.3429 |
| `cached_input` | $0.0686 |
| `output` | $1.0286 |

按量计费、**$1 起充**，无订阅、无免费额度；每次任务响应返回 `cost` / `credits_cost`。

## 调用示例

```bash
curl --request POST --url https://api.apimart.ai/v1/images/generations \
  --header "Authorization: Bearer $APIMART_API_KEY" --header 'Content-Type: application/json' \
  --data '{"model":"deepseek-v4-flash","prompt":"海边悬崖的现代别墅，黄昏","size":"16:9","n":1}'
```

## 披露

本仓为第三方中转服务 APIMart 的接入说明，与模型提供方无隶属关系；价格以标注快照为准。
