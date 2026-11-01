# helian

Animeko 在线源订阅。在 Ani 的数据源订阅设置中添加：

```text
https://raw.githubusercontent.com/SXP-Simon/animeko-sources/main/helian.json
```

| 源 | 线路与提示 |
|---|---|
| girigiri | 简中、繁中 |
| 秋之动漫 | 超高画三线 |
| 路漫漫 | dev云播 |
| 稀饭动漫 Next | 支持播放器切集复用查询结果 |
| MX动漫 | ikun；部分视频含插入广告，备用优先级 |
| AGE动漫 | 可能需要手动完成人机验证，暂未验证播放 |
| 黑猫动漫 | 播放Ⅵ；视频内广告明显，仅供手动查找 |

2026-11-01 新增源的短时实播样本：

| 源 | 已验证集数 |
|---|---|
| 路漫漫 | 葬送的芙莉莲第1、2集；药屋少女的呢喃第一季第1集，各15秒 |
| MX动漫 | 葬送的芙莉莲第1集；孤独摇滚！第1、2集，各15秒 |
| 黑猫动漫 | 葬送的芙莉莲第1、2集；孤独摇滚！第1集，10至25秒 |

已对照 KazumiRules 的18份规则并按站点去重、适配和抽样检查；完整结果见 [verification.json](verification.json)。未通过本次验证的源未加入。短时样本通过不代表整集或长期在线率。

规则参考 [Ani 内置订阅](https://sub.creamycake.org/v1/css1.json)、[MajoSissi/animeko-source](https://github.com/MajoSissi/animeko-source) 和 [Predidit/KazumiRules](https://github.com/Predidit/KazumiRules/tree/2967d7babafffa92dbf35fbcb69d0fd964139e63)。
