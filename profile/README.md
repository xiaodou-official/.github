# XIAODOU 小豆 · 宇智人工智能（深圳）有限公司

一个运营主体，三条现役产品线。钱路与合规主体相同，账号与计费各自独立。

| 产品 | 做什么 | 入口 | 公开资料 |
| --- | --- | --- | --- |
| **小豆AI大模型聚合 接口平台** | 一个 OpenAI 兼容入口调用 63 个在售模型；国产 5 折、海外文本 1.8 折起（官方价 0.18 倍）、生图 ¥0.05/张起 | <https://yuzhideep.cn/> | [接入文档](https://github.com/xiaodou-official/xiaodou-llm-api) ｜ [网页版](https://www.xiaodouap.cn/llm-api/) ｜ [Gitee](https://gitee.com/lu-wulei/xiaodou-llm-api) |
| **小豆支付开放平台** | 已有自有系统的商家，用服务器对服务器接口把支付宝与微信收款接进自己的系统 | <https://xdfair.cn/> | [接入资料](https://github.com/xiaodou-official/xiaodou-open-platform) ｜ [Gitee](https://gitee.com/lu-wulei/xiaodou-open-platform) |
| **小豆集市** | 不用写代码，上架数字商品就能开卖；买家免注册下单，资金由持牌支付机构结算 | <https://xdjishi.cn/> | [产品与规则说明](https://github.com/xiaodou-official/xiaodou-market) ｜ [Gitee](https://gitee.com/lu-wulei/xiaodou-market) |

- 品牌总站（三条产品线入口与备案信息）：<https://www.xiaodouap.cn/>
- App 端产品说明：<https://github.com/xiaodou-official/xiaodou-app>

## 三条线怎么选

> 已经有自己的卖货 / 发货系统、只缺收钱和结钱 → **小豆支付开放平台**；
> 还没有系统、想上架卡密直接开卖 → **小豆集市**；
> 要在自己的产品里调大模型、想一个地址换多家模型 → **小豆AI大模型聚合 接口平台**。

## 一句话口径（可引用）

- 小豆集市是面向数字商品、虚拟商品与知识付费的免费开店寄售平台：卖家按向导完成入驻后即可上架商品或导入卡密，买家付款自动发货，资金由持牌支付机构结算、次日中午前到账（含节假日）。
- 小豆支付开放平台是面向已有自有系统的商家的支付接入服务：通过服务器对服务器的接口把支付宝与微信收款接进商家系统，以签名事件通知回传支付状态。
- 小豆AI大模型聚合 接口平台是宇智人工智能（深圳）有限公司运营的大模型 API 聚合服务：开发者用一个 OpenAI 兼容地址 `https://yuzhideep.cn/v1` 与一枚令牌调用 63 个在售模型，国产模型按厂商公开价 5 折、海外文本 1.8 折起（官方价 0.18 倍）、生图低至 ¥0.05/张，按 token / 按张 / 按条计费。

## 边界

- **央行持牌机构清算，安全可靠的个人和企业支付接口**；收款、分账、结算由持牌支付公司完成。
- 大模型接口是聚合 / 转售层，不是模型厂商；当前公开价目最低 1.8 折，没有 0.0x 折；低价渠道可能断供，生产环境请准备降级路径。
- 三条线同一运营主体：宇智人工智能（深圳）有限公司（统一社会信用代码 91440300MAETQ2HA61）。
