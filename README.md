# 网易云歌单 · 两份

两组按「一支乐队 / 一位音乐人 → 一张代表作 → 4 首」整理的歌单，每份都带批量导入文本、CSV、可视化页面和曲目表。

| 目录 | 内容 | 规模 |
| --- | --- | --- |
| [`emo-shoegaze/`](emo-shoegaze/) | 两岸三地 + 日本的 emo / 盯鞋：透明杂志、午夜乒乓、返校日、Chinese Football、Number Girl、ミドリ、東京酒吐座、honeydip、mbv… | 29 张专辑 / 116 首 |
| [`jazz/`](jazz/) | Jazz Hiphop（Nujabes、DJ OKAWARI、J Dilla、ATCQ、蛋堡…）+ Jazz Pop（二宮愛、BLU-SWING、Norah Jones、Sade…） | 31 张专辑 / 124 首 |

## 用法

1. `歌单_批量导入.txt`：每行 `歌名 - 歌手`，喂给「文本转歌单 / 歌单迁移」类工具批量识别。
2. `index.html`：双击打开，可搜索、按分类 / 地区筛选、一键复制、逐首直达网易云单曲页。
3. `歌单.csv`：带歌曲 ID 与专辑 ID，方便核对或二次处理。

网易云没有「文本直出歌单链接」的公开接口，歌单需在登录状态下创建；这两个文件负责把「批量识别」这一步做完。
