# 网易云批量歌单 · 29 支乐队 × 29 张经典专辑

> 116 首 · 按你给的顺序排列 · 歌名与歌手均取自网易云现行命名，可直接批量匹配

## 文件说明

| 文件 | 用途 |
| --- | --- |
| `歌单_批量导入.txt` | 每行 `歌名 - 歌手`，喂给「文本转歌单 / 歌单迁移」类工具即可批量识别 |
| `歌单.csv` | 带网易云歌曲 ID 与直链，方便表格里筛选、核对 |
| `index.html` | 可视化歌单页：搜索、按地区筛选、一键复制、逐首直达单曲页（双击本地打开即可） |
| `playlist.json` | 结构化数据，方便你自己写脚本 |

## 关于「歌单链接」

网易云没有「把一段文本直接生成歌单链接」的公开接口——歌单必须在登录状态下创建，链接形如
`https://music.163.com/playlist?id=xxxx`，只能由账号侧生成。所以这里给的是**可直接批量识别**的清单：

1. **最快**：打开 `歌单_批量导入.txt`，全选复制 → 粘进你惯用的「文本转歌单」工具 / 小程序（匹配 `歌名 - 歌手`），一键建单。
2. **手机端**：网易云「我的 → 导入外部歌单」，支持贴 QQ 音乐 / 汽水 / Apple Music 的歌单链接；部分版本支持文本或截图识别。
3. **手动兜底**：打开 `index.html`，每首歌点一下就是单曲页，边听边加，116 首大概 10 分钟。

## 曲目表

| # | 乐队 | 经典专辑 | 年份 | 地区 | 收录曲目 |
| --- | --- | --- | --- | --- | --- |
| 01 | **yourboyfriendsucks!**（YBS） | 《第一集》 | 2016 | 大陆 | diu × 3 / Stay/Stayaway / 白鹤 / 波兰首都是上海 |
| 02 | **鼠鼠鼠** | 《the three mice》 | 2024 | 大陆 | 鲁蛇俱乐部 / 凌晨三点 / teenage mice club / stereo mice lab |
| 03 | **紅髮少年殺人事件**（红发少年） | 《BRUTAL GIRL DELUSION》 | 2025 | 台湾 | 黒目少女 / YES,We Love Number Girl / DELUSION / 短髮 |
| 04 | **Chinese Football**（国足） | 《Chinese Football》 | 2015 | 大陆 | 守门员 / 飞鱼转身 / 400米 / 地球上最后一个EMO男孩 |
| 05 | **eli's ladder** | 《polychrome》 | 2024 | 波兰 | show me the castle / simon / medical mechanica / burning circle |
| 06 | **透明杂志**（透明雜誌） | 《透明雜誌FOREVER》 | 2012 | 台湾 | 透明雜誌FOREVER / 野貓 / 萬華的宇宙 / E的鬼魂 |
| 07 | **v是兔子wishtoday**（v是兔子） | 《疼痛部》 | 2025 | 大陆 | 怯懦 / 超人少女 / 桂花 / 一个循环，冬天结束的时候 |
| 08 | **天然味道** | 《少女终末旅行》 | 2024 | 大陆 | 壳中少女 / Yuck ByeBye / 天然味道 / 夏日祭、唯我一人 |
| 09 | **气象限定Quadrant**（气象限定） | 《象限》 | 2026 | 大陆 | 象限外 旷野中(Uncharted Horizon) / 在灰烬里盛放(Growing Desire) / 雷克雅内斯灯塔(Reykjanesviti) / 零与无限(Origin to Infinity) |
| 10 | **VOOID** | 《VOOID》 | 2017 | 台湾 | Into The Void / CANCER [terminal ver.] / 一亿年前 / 生活的答案 [UK Surf] |
| 11 | **午夜乒乓**（Midnight Ping Pong） | 《剧烈物语》 | 2017 | 台湾 | 青春剧烈物语 / Blue Hearts / 巴黎影院 / 午夜的直球对决 |
| 12 | **My Bloody Valentine**（mbv） | 《loveless》 | 1991 | 英国 | only shallow / when you sleep / to here knows when / soon |
| 13 | **返校日 RiotInSchool**（返校日） | 《庆祝一场溃烂》 | 2022 | 台湾 | 解体 / 迪斯科 / 半岛中学 / 风滚草 |
| 14 | **鸽子牛奶**（Vidulgi OoyoO） | 《Aero》 | 2008 | 韩国 | Siren / 너의 눈으로 나를 본다 / Elephant / Aero |
| 15 | **Japanese Football** | 《Reflections Of You EP》 | 2023 | 日本 | Castles / Locked Out / Escape / Reflections Of You |
| 16 | **きのこ帝国**（蘑菇帝国） | 《フェイクワールドワンダーランド》 | 2014 | 日本 | 東京 / クロノスタシス / ヴァージン・スーサイド / You outside my window |
| 17 | **ミドリ**（Midori） | 《あらためまして、はじめまして、ミドリです。》 | 2008 | 日本 | スキ / ゆきこさん / お猿 / ちはるの恋 |
| 18 | **ひとひら**（hitohira（hihohira 二专）） | 《円》 | 2025 | 日本 | 十二月-Departure / 夏至 / 塔は白い / 円 |
| 19 | **Number Girl**（ナンバーガール） | 《School Girl Distortional Addict》 | 1999 | 日本 | 透明少女 / タッチ / 裸足の季節 / YOUNG GIRL SEVENTEEN ******** KNOWING |
| 20 | **東京酒吐座**（Tokyo Shoegazer） | 《crystallize (remastered)》 | 2022 | 日本 | 299 Addiction / Just Alright / Bright / Waltz Matilda |
| 21 | **Mowmowmow**（mowmow） | 《happenings》 | 2024 | 待考 | happenings / another pop song / repeating phrases / death! roll |
| 22 | **GO!GO!7188**（gogo7188） | 《虎の穴》 | 2002 | 日本 | 妖怪人間ベム / 恋の奴隷 / キューティーハニー / 心の旅 |
| 23 | **honeydip** | 《PLANET OF THE HONEY》 | 1999 | 日本 | Echo & The Honeymen / Universal Teenage Frequency / Groovy Indian Summer / Space Camp |
| 24 | **河豚子**（Fugu） | 《你不是人》 | 2012 | 台湾 | 一个人的日子 / 剑龙 / Orca！Orca！ / 少女黑猫 |
| 25 | **くだらない1日**（kudaranai1nichi） | 《rebound》 | 2022 | 日本 | やるせない / 原宿五階秘密基地 / 力水 / こわれはじめてゆく今 |
| 26 | **MASS OF THE FERMENTING DREGS**（world is yours / マスドレ） | 《ワールドイズユアーズ》 | 2009 | 日本 | このスピードの先へ / 青い、濃い、橙色の日 / ワールドイズユアーズ / She is inside, He is outside |
| 27 | **未來電波基地**（未来电波基地） | 《墨田区DEPRESSION》 | 2023 | 日本 | 墨堤通り / 悲しみが溢れて / 或る日の隅田川 / 淀川長治 |
| 28 | **相対性理論**（相对性理论） | 《ハイファイ新書》 | 2009 | 日本 | テレ東 / 地獄先生 / ふしぎデカルト / 四角革命 |
| 29 | **THE MUSMUS**（射的） | 《射的》 | 2006 | 日本 | 射的 / 雨ざらし / M31 / 絵の具 |

## 存疑与取舍

- **mowmow**：网易云有两个候选——`Mowmowmow`（卧室流行 / 梦幻流行，Bandcamp 系）与 `モーモールルギャバン`（MowMow LuLu Gyaban，日系另类摇滚）。按你列表里盯鞋 / emo 的走向取了前者；若你指的是后者，把 txt 里的歌手名换成 `モーモールルギャバン` 即可。
- **hihohira 二专**：按 `ひとひら` 处理，取第二张全长《円》（2025）。你前面还写了一次 `hitohira`，同为 `ひとひら`，一专是《つくる》。
- **world is yours**：取 `MASS OF THE FERMENTING DREGS`（マスドレ）2009 年同名专辑《ワールドイズユアーズ》。
- **射的**：不是乐队名，是 `THE MUSMUS` 2006 年的同名 EP，已按整张收录。
- **ybs**：按广州乐队 `yourboyfriendsucks!` 处理（乐队自称 YBS）。
- **红发少年**：网易云登记为 `紅髮少年殺人事件`。
- 每支乐队只取一张代表作、4 首，若想换成整张专辑，`歌单.csv` 里有专辑 ID，直接展开即可。

## 试听入口

- 可视化页：`index.html`（离线可用）
- 单曲直链格式：`https://music.163.com/#/song?id=<歌曲ID>`
- 专辑直链格式：`https://music.163.com/#/album?id=<专辑ID>`
