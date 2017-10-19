# Dict2Anki
##### **只支持 Anki 2.0.x.** **Only supports Anki 2.0.x.**  
**Dict2Anki** 是一款方便[有道词典](http://cidian.youdao.com/multi.html)、[欧陆词典](https://www.eudic.net/)用户同步生成本地单词本卡片至[Anki](https://apps.ankiweb.net/#download)的插件  
**Dict2Anki** is a Anki addon makes it easy for [Youdao](http://cidian.youdao.com/multi.html) and [Eudict](https://www.eudic.net/) user to sync their wordBook card to [Anki](https://apps.ankiweb.net/#download)

## 特点介绍 Feature
- 支持导入有道词典、欧陆词典生词本  
  Support Youdao and Eudict 

- 支持Mac、Windows平台  
  Support Mac and Windows operating system

- 检测词典软件的生词变化,并在Anki中相应的添加删除卡片  
  Detect the change of the wordlist and do the corresponding process
## 预览 Preview
- ### 界面 GUI
  <img src = "https://raw.githubusercontent.com/megachweng/Dict2Anki/master/screenshots/Mac-0.png" width=400>

- ### 卡片 Cards
  <span><img src = "https://raw.githubusercontent.com/megachweng/Dict2Anki/master/screenshots/card-front.png" width=400></span>
  <span><img src = "https://raw.githubusercontent.com/megachweng/Dict2Anki/master/screenshots/card-back.png" width=400></span>
## 如何安装 How to Install
- ### 从源码安装（推荐）Install from source(highly suggest)
    - 在[Release](https://github.com/megachweng/Dict2Anki/releases/tag/v1.0)中下载最新版本  
    Download lastest version from [Release](https://github.com/megachweng/Dict2Anki/releases/tag/v1.0)

    - 解压`Zip`  
    Unzip

    - 把`Dict2Anki.py` 放入Anki的`Addons`目录  
    Move `Dict2Anki.py` to `Addons` directary

    - 重启Anki  
    Restart Anki 
- ### 从AnkiWeb安装 Install from AnkiWeb
    - 打开 `工具` -> `插件` -> `浏览&安装`  
    Click `Tools` -> `Add-ons` -> `Browse&Install` 

    - `代码` : `480644339`  
    `Code`: `480644339`

    - 重启Anki  
    Restart Anki 
## 如何使用 How to Use
<span><img src = "https://raw.githubusercontent.com/megachweng/Dict2Anki/master/screenshots/youdao.gif" ></span>
<span><img src = "https://raw.githubusercontent.com/megachweng/Dict2Anki/master/screenshots/eudict.gif" ></span>
## 已知问题 Known issue
- Windows平台下多次同步可能会造成程序崩溃，重启Anki即可  
The programe may crash while serveral syncs, just Restart Anki after every syncronize
