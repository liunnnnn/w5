## APP 说明


- 官方文档：https://iyuu.cn/

## 动作列表

### 微信通知

**参数：**

|  参数   | 类型  |  必填   | 备注             |
|  ----  | ----  |  ----  |----------------|
| **key**  | text | `是` | 点击开始使用后,扫码获取令牌 |
| **text**  | text | `是` | 通知标题           |
| **desp**  | text | `否` | 通知内容           |

**返回值：**

```
# 正常
{'errcode': 0, 'errmsg': 'ok', 'data': []}
```