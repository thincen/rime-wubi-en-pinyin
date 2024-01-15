
```
# speller:
# alphabet: 定義本方案輸入鍵
# initials: 定義僅作始碼之鍵
# finals: 定義僅作末碼之鍵
# delimiter: 上屛時的音節間分音符
# algebra: 拼寫運算規則，由之算出的拼寫匯入prism中
# max_code_length: 形碼最大碼長，超過則頂字上屛〔number〕
# auto_select: 自動上屛〔true或false〕
# auto_select_pattern: 自動上屏規則，以正則表達式描述，當輸入串可以被匹配時自動頂字上屏。
# use_space: 以空格作輸入碼〔true或false〕
# speller的演算包含：
# xform --改寫〔不保留原形〕
# derive --衍生〔保留原形〕
# abbrev --簡拼〔出字優先級較上兩組更低〕
# fuzz --畧拼〔此種簡拼僅組詞，不出單字〕
# xlit --變換〔適合大量一對一變換〕
# erase --刪除
```
