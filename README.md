仮名を万葉仮名みたいなのに変換したり逆変換したりするやつです。  
形態素解析みたいなのじゃないです。

# 使い方

```
kanji_to_kana <変換モード> <テキストファイルへのリンク>
```

# 変換モード

|引数|変換方式|
|:-|:-|
|`--k`|ひらがな、カタカナを漢字に変換します。|
|`--k-hg`|漢字をひらがなに変換します。|
|`--k-kk`|漢字をカタカナに変換します。|
|`--k-hg-kk`|漢字をひらがなとカタカナに変換します。(ひらがな優先)|
|`--k-kk-hg`|漢字をひらがなとカタカナに変換します。(カタカナ優先)|