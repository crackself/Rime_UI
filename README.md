# Rime weasel/squirrel输入方案UI及词库配置文件
### 设计思路：
以patch方式，进行模块化自定义修改，不修改默认配置文件，全MacOS、Linux、Windows全桌面平台通用（iOS未测试，Android trime無法處理部分patch，需採用完整拼音方案配置文件）
###  拼音詞庫、中英混输來自[`霧凇拼音`](https://github.com/iDvel/rime-ice)
#### 主题设置包含圆角设置，weasel最低要求版本0.15，最低操作系统要求win10
#### 全量文件使用指南
`词库及配置文件` 內爲完整 `輸入法方案+詞庫+主程序配置+主題` 配置，直接可以用
#### 配置文件说明
```
squirrel.custom.yaml	    # MacOS Squirrel的自定义patch，用於導入主題配置
theme_ui_squirrel.yaml	  # MacOS Squirrel的主窗口布局，包含邊框、圓角、陰影、字體排列、字间距等

weasel.custom.yaml	      # Windows weasel的自定义patch，用於導入主題配置
theme_ui_weasel.yaml      # Windows weasel的主窗口布局，包含邊框、圓角、陰影、字體排列、字间距等
```
#### 通用主題文件说明
```
theme_color.yaml	        # 配色
theme_font.yaml		        # 字体
```
