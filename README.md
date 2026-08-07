# splatoon-2-schinese-patch / Splatoon2 中文化项目
由于本人精力有限且是斯普拉遁大菜逼，我个人无法校验所有文本的准确性，若有错误还请指正。  
歌曲名称等专有名词由于没有官方译名所以尽量保持原文展示。

## 文本 / 翻译来源
- Splatoon 2 (Ver. 5.5.0) 日语文本
- Splatoon 3 (Ver. 1.1.2) 简体中文UI/可共用专有名词/物品/小部分固定短句文本
- 剩余文本是基于 Deepseek-v4-flash 进行的 AI 翻译，不一定准确且不一定贴合官方翻译口吻，且由于我不懂日语，只能基于英语文本确定 / 查询日语、Splatoon3官方中文相关资料。
- GPT-5.6-Terra 二次润色

## 翻译进度（按条目统计）

统计基准：`CommonMsg_JPja_release_szs/` 与 `LayoutMsg_JPja_release_szs/` 下 KUP 文件的 `<edited>` 字段，
与 `<original>` 不同即计为已完成粗翻。进度会随提交更新。
统计口径：仅统计需要翻译的条目；原文为纯控制码模板 / 占位符（如 `BynameGearName_*`、
`BynameWeaponName_*` 等由游戏动态填充的空模板）或纯符号的条目不计入总数。

| 分组 | 已完成 / 总数 | 完成度 |
| --- | --- | --- |
| 主线剧情（TalkMission） | 760 / 762 | 99.7% |
| 英雄模式对话（Talk*，含主线） | 2326 / 2327 | 100.0% |
| 剧情旁白（Narration*） | 102 / 102 | 100.0% |
| Octo 扩展剧情（Octa_*） | 2691 / 2741 | 98.2% |
| Byname 系列（武器/装备名） | 70 / 74 | 94.6% |
| 其他 CommonMsg 文本（含名词等） | 1485 / 1583 | 93.8% |
| LayoutMsg 界面文本 | 1479 / 1780 | 83.1% |
| **合计** | **8153 / 8607** | **94.7%** |

注：主线剧情（TalkMission）是 `Talk*` 的子集，合计按条目去重。

original part of localization released under cc-by-nc-sa 3.0

Some of materials may be copyrighted by Nintendo and respective owners.
