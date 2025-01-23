# RIME Pinvin（rime-pinvin-simp） -- IME for Simplified Chinese by The Tonal Spelling of Mandarin

## 说明
此输入法方案需要 [RIME | 中州韵输入法引擎](https://rime.im/)

default.custom.yaml 文件为用户重要配置文件，其中schema_list字段后是所有可选配方，可自行增删（行首用“#”号注释表示不引入）。

### 输入法码表
pinvin_simp.schema.yaml  
pinvin_simp.dict.yaml
pinvin_simp_ext2.dict.yaml
pinvin_simp_ext3.dict.yaml
pinvin_simp_ext4.dict.yaml
pinvin_simp_ext5.dict.yaml
pinvin_simp_ext6.dict.yaml
pinvin_simp_ext7.dict.yaml

## 安裝
### 通用方式
[安装rime](https://rime.im/)后，把码表复制到 Rime用户设定目录，然后重新部署。  
 部署位置：  
##### Windows 10+
```
    %APPDATA%\Rime
``` 
##### Mac OSX
```
    ~/Library/Rime          
```
##### Linux (部署后最好重启一次)
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
