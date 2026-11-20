# dsh-fiction-voices

Five Chinese prose-voice skills for fiction writing, packaged as a DeepSeek Harness bundle. Each skill is a Markdown instruction file that describes a voice — its sentence rhythm, imagery bank, dialogue technique, sample passages, taboos and a pre-writing checklist. The plugin only registers these skills: it adds no tools, no UI and no network access.

五套中文小说笔法技能，打包成一个 DSH bundle。每套是一份 Markdown 指令文件，讲这一路文字怎么呼吸：句子节奏、意象库、对话技术、示范段落、禁区、写作前自检。插件只做注册，不带工具、不带界面、不联网。

## Install / 安装

```sh
dsh plugin --profile <profile> add github:Eddielllllllllllll/dsh-fiction-voices
```

## The five voices / 五套笔法

| 技能 | 一句话 |
| --- | --- |
| `jiangnan-style` | 江南笔法（《龙族》《九州缥缈录》一路）：少年感、孤独、热血、宿命悲剧、沉默的爱、吐槽式对话。 |
| `fanhua-style` | 金宇澄《繁花》笔法：沪语腔、饭局、市井与暧昧，核心是"不响"——用沉默代替回答，用名词代替抒情。 |
| `kuangbiao-style` | 《狂飙》叙事法：三段式时间切片、双雄对峙、强情节钩子、台词记忆点、底层逆袭与道德灰度。 |
| `tangxi-style` | 汤溪笔法：写一个吴语方言岛上的山乡村子——无鼻音韵尾、有音无字、"哈么"这个贬称怎么自己翻身。 |
| `jinhua-style` | 婺州笔法：写一座不上不下的南方小城——上下坡、弄堂、三层话、办事三句话、饭局五段式。 |

Trigger each with its slash command (`/jiangnan`, `/fanhua`, `/kuangbiao`, `/tangxi`, `/jinhua`) or by describing the task ("用繁花的腔调写", "写一座小城").

每套都可以用斜杠命令直接调（`/jiangnan`、`/fanhua`、`/kuangbiao`、`/tangxi`、`/jinhua`），也可以说"用繁花的腔调写""写一座小城"。

## What is inside a skill / 一套技能里有什么

1. **一句话定位** — 这一路文字到底在写什么。
2. **核心气质** — 五条，可判断"写歪了没有"。
3. **句法技术** — 可执行的规则（短句占比、段落长度、回望句频率、对话挂动作）。
4. **意象库 / 场景库 / 器物库** — 直接可取的物件与场面。
5. **示范段落** — 原创，学腔调不抄句子。
6. **禁区** — 五条最常见的写坏方式。
7. **写作前五问** — 动笔前的自检。

## Notes / 说明

- The two dialect skills (`tangxi-style`, `jinhua-style`) encode published linguistic facts: Tangxi is a Wu dialect island whose syllables have lost all nasal and stop codas (曹志耘), while Jinhua keeps nasalization and is the standard pronunciation of 婺剧. 方言词条只用于语感，不用于教学。
- Sample passages in every skill are original text written for the skill; they imitate a register, not an author's sentences.
- No code execution, no file writes at runtime, no telemetry.

## License

MIT
