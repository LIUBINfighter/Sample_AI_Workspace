[README_EN](README_EN.md)

这是我在南方科技大学24秋季学期，EBA203管理信息系统课程的个人AI项目。

# Obsidian+AI工作流

本仓库是为了向Obsidian新手介绍Obsidian中的AI工作流而打造的。

Obsidian的学习曲线本就比较陡峭，如果再加上自己部署LLM服务则要同时学习LLM部署和Obsidian各AI插件的对接。我对本仓库的设计以及对应文档的写作就是Obsidian新手加快将AI融入Obsidian工作流的进程，按图索骥修改配置后根据效果自行取舍和进行个性化设置。

为了更大程度发挥各AI插件的功能，我根据我自己的习惯设置了其他的插件，包括：

- [Kanban](Kanban.md)
    看板插件，所有文档分类一目了然
- [Surfing](Surfing.md)
    在Obsidian中内置浏览器，进行搜索和在线LLM使用
- [Git packup](Git%20packup.md)
    远程同步github仓库，保存你的项目进度
    （保持本地化可直接取消+删除插件）
# 聊天Copilot 写作LocalGPT 在线Kimi

[Documentation | Copilot for Obsidian (obsidiancopilot.com)](https://www.obsidiancopilot.com/en/docs)



#### 插件横纵对比
主观

| Name        | Repo                                                                                | Download | Star | Update      |
| ----------- | ----------------------------------------------------------------------------------- | -------- | ---- | ----------- |
| Copilot     | [logancyang/obsidian-copilot](https://github.com/logancyang/obsidian-copilot)       |          | 3.1k | 9 hours ago |
| LocalGPT    | [pfrankov/obsidian-local-gpt](https://github.com/pfrankov/obsidian-local-gpt)       |          | 328  | last week   |
| Smart2Brain | [your-papa/obsidian-Smart2Brain](https://github.com/your-papa/obsidian-Smart2Brain) |          | 633  | 6months ago |

功能：
支持

阅读选定内容


| Name        | 选定内容输入 | 解读特定文件 | 输出外链跳转 |
| ----------- | ------ | ------ | ------ |
| Copilot     |        |        |        |
| LocalGPT    |        |        |        |
| Smart2Brain |        |        |        |




客观
截止2024年11月22日晚，



# 样例工作流介绍


# 快速开始

本栏目是为了快速使用配置最简单基础，最快速的LocalGPT插件。

你可以在Obsidian下查看[AI Project View](AI%20Project%20View.md)以浏览感兴趣的其他设置和插件介绍。

下载安装包（git clone有时会卡住）
![下载仓库压缩包](下载仓库压缩包.png)

解压缩到你想要的位置，通过压缩包下载后解压将不会有.git文件夹。如果你会使用git则可自行修改仓库名称并添加到repo。

## 使用Obsidian打开
![|280](使用Obsidian打开本地仓库.png)

我建议从这一步开始就在Obsidian里查看本教程并进行其他操作。

## 配置Ollama

### Windows
![DownloadOllama|600](DownloadOllama.png)

`win+r`呼出
win+R输入cmd运行enter确定
![|350](win+R输入cmd运行enter确定.png)

输入
```bash
ollama list
```

![](ollama_list.png)

如果你刚下载Ollama，那么应当只有NAME-ID-SIZE-MODIFIED一行,没有其他的模型。

我们要使用llama3.2（LocalGPT只需要这个）以及nomic-embed-text（Copilot以及Smart2Brain额外需要）.

![](ollama_pull_llama3.2_.png)

### Ubuntu

我们用snap下载ollama，其他操作和windows没有太大区别。

```bash
sudo snap install ollama
```

更多个性化配置参考[[Ollama]]以及Ollama官网 https://ollama.com/


# 本地 vs 在线







使用本仓库

