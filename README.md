# 个人配置

> ios hamster 配置文件

修改自 [rime-wubi86-jidian](https://github.com/KyleBing/rime-wubi86-jidian)

- `五笔、拼音、英文` 混合输入
- 自定义了常用符号
- 自定义了 `ios` 键盘文件

## tree

```
├── default.custom.yaml       # 自定义配置
├── ios_keyboard.yaml         # ios键盘文件
├── en.dict.yaml              # 词库: 英文
├── melt_eng.schema.yaml      # 方案: 英文, 混输方案依赖
├── pinyin_simp.dict.yaml     # 词库: 拼音
├── pinyin_simp.schema.yaml   # 方案: 拼音, 混输方案依赖
├── wubi86_jidian.dict.yaml   # 词库: 五笔86, 复制自rime-wubi86-jidian
├── thincen.schema.yaml       # 方案: 混输方案
├── rime.lua                  # 配置, 输出时间、计算器
├── README.md                 # 说明文件
└── rime-wiki.md              # rime配置备忘, 随便复制来的
```

## 符号

自定义了部分常用符号于 `default.custom.yaml` 中 `symbols`

- `/[数字]` 中西文数字, 如: `/2` 可选 `[ 2, 二, 貳, ₂, ², Ⅱ, ⅱ, ②, ➁, ❷, ➋, ⓶, ⑵, ⒉, ２, ㊁, ㈡, 弍, 弐, 貮, 㒃, 㒳, 兩, 倆, ㆓]`  
- `/lm` 小写罗马数字
- `/lmd` 大写罗马数字

