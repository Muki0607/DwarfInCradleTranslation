![](DICT_Logo.png)
[English](README.md) | 简体中文 | [日本語](README.ja.md)
# 「摇篮里的矮人语」翻译工程（DICT）
本项目(DICT, Dwarf In Cradle Translation)是玩家社区自制的一个语言包，适用于 [NanameHacha](https://nanamehacha.dev/about) 开发的动作游戏 AliceInCradle。安装后，游戏内出现的所有矮人语将会根据游戏语言，自动追加英语/简体中文/繁体中文/日语的翻译内容。

具体而言，游戏第二章「幽灵」中新出场的女主角「爱丽丝」的台词使用了一种特殊的语言「矮人语」。在储存台词的文件中，矮人语主要通过平假名和部分汉字表示。而在游戏中，它们会显示成有规律的表意符号。您可以在本项目下的```alphabet.png```查看这些符号（不包括标点）。

为了让玩家同时看到原文和译文，本项目在爱丽丝的每句台词之前添加译文，例如：

```AliceInCradle localization
<m scary>精灵追来了！        //这是译文
<dwarf><m scary>え来了!     //这是原文
```

## 下载
通过Code -> [Download Zip](https://github.com/Muki0607/DwarfInCradleTranslation/archive/refs/heads/main.zip) 即可下载。
## 安装(Windows)
1. (可选)备份游戏路径内的 ```AliceInCradle_Data/StreamingAssets/localization```文件夹。**注意：不执行该步骤会导致无法卸载本补丁。**
2. 复制本项目内的```localization```文件夹，并粘贴到```AliceInCradle_Data/StreamingAssets/```文件夹内，在"替换或跳过文件"中选择"替换目标中的文件"。(如果您没有收到这样的弹窗，说明您很有可能将它们粘贴到了错误的文件夹。)

## 卸载(Windows)
1. 确保您拥有备份的```localization```文件夹。
2. 选中并复制您备份的文件夹内的所有文件，在0.29d版本中，它们应当包含13个项目。
3. 将它们粘贴到 ```AliceInCradle_Data/StreamingAssets/localization```文件夹内，在"替换或跳过文件"中选择"替换目标中的文件"。(如果您没有收到这样的弹窗，说明您很有可能将它们粘贴到了错误的文件夹。)

# Alphabet.png
![](alphabet.png)