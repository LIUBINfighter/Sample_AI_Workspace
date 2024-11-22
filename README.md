[README_EN](README_EN.md)

这是我在南方科技大学24秋季学期，EBA203管理信息系统课程的个人AI项目。

我的博客会陆续更新教程和自己的使用体验，欢迎前来阅读：

- [Huajie's Blog (liubinfighter.github.io)](https://liubinfighter.github.io/Blog/)

# Obsidian+AI工作流

本仓库是为了向Obsidian新手介绍Obsidian中的AI工作流而打造的。

Obsidian的学习曲线本就比较陡峭，如果再加上自己部署LLM服务则要同时学习LLM部署和Obsidian各AI插件的对接。我对本仓库的设计以及对应文档的写作就是Obsidian新手加快将AI融入Obsidian工作流的进程，按图索骥修改配置后根据效果自行取舍和进行个性化设置。

本次使用的AI插件为（排名为个人喜好）：

- [Local GPT](Local%20GPT.md)
    脱离鼠标，只用键盘
    提示词定制程度高，在文档中丝滑写作，添加表情包，概括，整理思路，修改错误
- [Text Generator](Text%20Generator.md)
    定制程度极高，上限高
    可以自行根据LLM服务商手册+Advanced Setting自由定制
- [Copilot](Copilot.md)
    新兴插件，期待前途
- [Smart2Brain](Smart2Brain.md)
    最早入坑的插件，之后效果不是很稳定，现在开发者也不活跃
    （凑数的）

为了更大程度发挥各AI插件的功能，我根据我自己的习惯设置了其他的插件，包括：

- [Kanban](Kanban.md)
    看板插件，所有文档分类一目了然
- [Surfing](Surfing.md)
    在Obsidian中内置浏览器，进行搜索和在线LLM使用（Kimi赛高！）
- [Git packup](Git%20packup.md)
    远程同步github仓库，保存你的项目进度
    （保持本地化可直接zip下载/取消/删除插件）


# 插件横纵对比

Obsidian仓库设置，当然要以插件为主啦！所以我们优先介绍插件。以下内容主要都依据2024年11月22日访问+使用并制表。

如果有些糊涂，可以略过两个枯燥的表格，直接看我的主观体验就行。

对表格中的细节有疑惑，直接点击表格中的文件链接即可跳转（这里假设是obsidian环境）。

> update: 将文件路径替换为完整相对路径后，在github上也可以完整预览本仓库的绝大多数文档。

## 基本情况

| Name                                                    | Repo                                                                                                | Download | Star | Update      |
| ------------------------------------------------------- | --------------------------------------------------------------------------------------------------- | -------- | ---- | ----------- |
| [Text Generator](docs/AI%20Plugins/Text%20Generator.md) | [nhaouari/obsidian-textgenerator-plugin](https://github.com/nhaouari/obsidian-textgenerator-plugin) | 335k     | 1.5k | 3weeks ago  |
| [Local GPT](docs/AI%20Plugins/Local%20GPT.md)           | [pfrankov/obsidian-local-gpt](https://github.com/pfrankov/obsidian-local-gpt)                       | 18.7k    | 328  | last week   |
| [Copilot](docs/AI%20Plugins/Copilot.md)                 | [logancyang/obsidian-copilot](https://github.com/logancyang/obsidian-copilot)                       | 264k     | 3.1k | 9 hours ago |
| [Smart2Brain](docs/AI%20Plugins/Smart2Brain.md)         | [your-papa/obsidian-Smart2Brain](https://github.com/your-papa/obsidian-Smart2Brain)                 | 25.1k    | 633  | 6months ago |

非常感谢社区的插件作者以及其他热衷于分享和帮助他人的参与者！

## 功能介绍

| Name                                                    | 边栏QA | 选定内容输入        | 阅读<br>.md  | 多文件               | 外链跳转           | 定制提示词                 | 定制传输格式 |
| ------------------------------------------------------- | ---- | ------------- | ---------- | ----------------- | -------------- | --------------------- | ------ |
| [Text Generator](docs/AI%20Plugins/Text%20Generator.md) |      |               |            |                   |                |                       | 完全定制   |
| [Local GPT](docs/AI%20Plugins/Local%20GPT.md)           | ❌    | ✔<br>选中+自设快捷键 | ✔          | ❌<br>只支持在编辑的文档中解读 | ❌不能多文件联动       | 🔥插件面板设置<br>+社区支持     | ❌      |
| [Copilot](docs/AI%20Plugins/Copilot.md)                 | ✔    | ✔<br>选中+右键    | ✔<br>提示词模板 | ✔<br>可调整文件数       | ✔较准确<br>❌跳转抽风  | 只支持1种自定义System Prompt | ❌      |
| [Smart2Brain](docs/AI%20Plugins/Smart2Brain.md)         | ✔    | ❌<br>手动复制粘贴   | ✔          | ✔<br>可调整相似度       | 🤔不太准<br>✔跳转稳定 | ❌                     | ❌      |
|                                                         |      |               |            |                   |                |                       |        |

## 主观评价






# QA&Writing



## Copilot

[Documentation | Copilot for Obsidian (obsidiancopilot.com)](https://www.obsidiancopilot.com/en/docs)


# 本地Ollama 在线Kimi

## Ollama

Ollama目前是本地部署LLM的首选之一。操作以及对接插件非常简单

部署Ollama可继续往下看 **[快速开始](https://github.com/LIUBINfighter/Sample_AI_Workspace?tab=readme-ov-file#%E5%BF%AB%E9%80%9F%E5%BC%80%E5%A7%8B)** ，或者[点击查看Ollama详细介绍](Ollama.md).

## Kimi

Kimi以强大的长文本能力，文件上传和联网搜索能力（以及context window <20w字免费）占据了独特的C端生态位（反正我是不能没有Kimi了）。

在Obsidian中如果按照常规的思路去使用api，那正是太屈才了！但是开两个窗口分屏实在是太麻烦了，能不能再Obsidian里使用Kimi呢？我们使用[Surfing](Surfing.md)插件就可以将Obsidian变为浏览器。目前本仓库的设置下你应当可以在Obsidian里直接打开以下链接：[kimi.moonshot](https://kimi.moonshot.cn/).

![](docs/attachment/img/Obsidian-Surfing-Kimi.png)

扫码登录一气呵成。如果你喜欢暗色主题也可以用Suring切换。

![](docs/attachment/img/Obsidian-Surging-DarkMode.png)





# 样例工作流介绍


# 快速开始

本栏目是为了快速使用配置最简单基础，最快速的LocalGPT插件。

你可以在Obsidian下查看[AI Project View](AI%20Project%20View.md)以浏览感兴趣的其他设置和插件介绍。

下载安装包（git clone有时会卡住）
![下载仓库压缩包](docs/attachment/img/下载仓库压缩包.png)

解压缩到你想要的位置，通过压缩包下载后解压将不会有.git文件夹。如果你会使用git则可自行修改仓库名称并添加到repo。

## 使用Obsidian打开
![|280](docs/attachment/img/使用Obsidian打开本地仓库.png)


打开后你可以在Obsidian里阅读本教程了。当然，别急着关网页！涉及Obsidian设置一类操作的时候还是要看网页的。我建议从这一步之后就在Obsidian里查看本教程并进行其他操作。

插件已经预设完成，我们去配置Ollama作为本地LLM服务。


## 配置Ollama

### Windows
![DownloadOllama|600](docs/attachment/img/DownloadOllama.png)

`win+r`呼出
win+R输入cmd运行enter确定
![|350](docs/attachment/img/win+R输入cmd运行enter确定.png)

输入
```bash
ollama list
```

![](docs/attachment/img/ollama_list.png)

如果你刚下载Ollama，那么应当只有NAME-ID-SIZE-MODIFIED一行,没有其他的模型。

我们要使用llama3.2（LocalGPT只需要这个，用于Chat）以及nomic-embed-text（Copilot以及Smart2Brain额外需要用于索引）.

![](docs/attachment/img/ollama_pull_llama3.2_.png)

我C盘够大，模型随便下。但是如果C盘本来空间不多，可能需要修改ollama配置使得模型文件保存在其他位置。

### Ubuntu

我们用snap下载ollama，其他操作和windows没有太大区别。

```bash
sudo snap install ollama
```

更多个性化配置参考[Ollama](docs/BaseLLM/Ollama.md)以及Ollama官网 https://ollama.com/


# 本地 vs 在线







使用本仓库

# 多余的话

## Obsidian链接与Git Repo

为了保证README能在repo上完整呈现，我将所有照片等附件都改为了完整相对路径，例如：`![](docs/attachment/img/kimi.png)`。可在设置中重新设置为最简形式，形如：`[[Kimi]]`或者 `![[Kimi.png]]`。

文档中不定期出现链接错误，是由于Obsidian本地使用和github在线阅读之间的取舍不同。你可以在issue区写下问题和你的建议。

