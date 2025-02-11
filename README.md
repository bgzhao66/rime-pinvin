# RIME Pinvin（rime-pinvin-trad） -- IME for Traditional Chinese by The Tonal Spelling of Mandarin

## 說明
此輸入法方案需要 [RIME | 中州韻輸入法引擎](https://rime.im/)

default.custom.yaml 文件為用戶重要配置文件，其中schema_list字段後是所有可選配方，可自行增刪（行首用“#”號註釋表示不引入）。

### 輸入法碼錶
```
pinvin_trad.schema.yaml
pinvin_trad.dict.yaml
pinvin_trad_ext*.dict.yaml
```

## 安裝
### 通用方式
[安裝rime](https://rime.im/)後，把碼錶複製到 Rime用戶設定目錄，然後重新部署。
 部署位置：  
##### Windows 10+
```
    %APPDATA%\Rime
``` 
##### Mac OSX
```
    ~/Library/Rime          
```
##### Linux (部署後最好重啟一次)
###### ibus-rime:
```
    ~/.config/ibus/rime
```
###### fcitx-rime:
```
    ~/.config/fcitx/rime
```
###### fcitx5-rime:
```
    /usr/share/rime-data
```

### 字體
為顯示CJK擴展區數萬漢字，可下載並安裝[HanaMin|花園明朝](https://glyphwiki.org/hanazono/hanazono-20170904.zip)字體庫。
