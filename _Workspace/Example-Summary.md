
效果供参考

均使用ollama， llama3.2模型

太长不看版：




### Text Generator

配置：输出Token 2k限制

帮我概括一下文档内容。

触发：`ctrl+j`

> [!ai]+ AI
>
> This is a README file for a personal AI project on Obsidian, a knowledge management tool. The author aims to introduce the concept of integrating AI into Obsidian's workflow and provides an overview of their experience with various plugins.
> The repository contains documentation and configuration files for different AI plugins, including:
> 1. Text Generator: allows users to generate text based on input prompts.
> 2. Local GPT: uses a local GPT model for writing assistance.
> 3. Copilot: integrates with the Obsidian plugin ecosystem.
> 4. Smart2Brain: an older plugin that is no longer actively maintained.
> The author also mentions other plugins, such as Kanban and Surfing, which provide additional features like project management and web browsing.
> The README includes:
> 1. A table comparing different AI plugins, including download statistics and update frequencies.
> 2. Information about each plugin's functionality and customization options.
> 3. The author's subjective evaluation of the plugins' effectiveness.
> 4. A demonstration of how to trigger certain actions with keyboard shortcuts (e.g., `ctrl+j` for text summarization).
> Overall, this README provides a comprehensive introduction to Obsidian's AI workflow and offers guidance for users looking to integrate AI into their knowledge management system.

特别：如果出现报错Textgenerator会输出报错块，比如：

> [!failure]- Failure 
>   TypeError: Failed to fetch
>   
>   - plugin:obsidian-textgenerator-plugin:525 iwt
>     plugin:obsidian-textgenerator-plugin:525:8259
>   
>   - iwt.next
>   
>   - plugin:obsidian-textgenerator-plugin:526 PuI
>     plugin:obsidian-textgenerator-plugin:526:155
>   
>   - PuI.next
>   
>   - plugin:obsidian-textgenerator-plugin:526 PYe._streamResponseChunks
>     plugin:obsidian-textgenerator-plugin:526:6143
>   
>   - plugin:obsidian-textgenerator-plugin:526 async PYe._call
>     plugin:obsidian-textgenerator-plugin:526:6567
>   
>   - async Promise.all
>   
>   - plugin:obsidian-textgenerator-plugin:502 async PYe._generate
>     plugin:obsidian-textgenerator-plugin:502:40488
>   
>   - plugin:obsidian-textgenerator-plugin:502 async PYe._generateUncached
>     plugin:obsidian-textgenerator-plugin:502:37972
>   
>   - plugin:obsidian-textgenerator-plugin:502 async PYe.invoke
>     plugin:obsidian-textgenerator-plugin:502:35775
>   
>  

### Local GPT

帮我概括一下文档内容。（不要这句话也行,直接选中命令）

触发：

1.`ctrl+alt+g`调出菜单(自行设置)

2.↑↓箭头选中，回车
![|300](docs/attachment/img/LocalGPT-README.png)


Here is a concise summary of the key points in the text:

**Introduction**

The text is about an Obsidian knowledge management tool AI project, with instructions for using various plugins to integrate AI into Obsidian's workflow.

**AI Plugins**

The author presents several AI plugins, including:

* Text Generator: allows users to generate text based on input prompts
* Local GPT: uses a local GPT model for writing assistance
* Copilot: integrates with the Obsidian plugin ecosystem
* Smart2Brain: an older plugin that is no longer actively maintained

**Comparison Table**

A table compares the different AI plugins, including download statistics and update frequencies.

**Customization Options**

Each plugin has its own customization options, such as defining input prompts and output formats.

**Usage Examples**

The author provides examples of how to use each plugin, such as using Local GPT for writing assistance or Copilot for generating text based on user input.

**Other Plugins**

The author mentions other plugins that can be used with Obsidian, including Kanban for project management and Surfing for browsing online content.

**Conclusion**

The text concludes by encouraging users to explore the different AI plugins and customization options available in Obsidian.


### Copilot


### Smart2Brain
这个插件有独立边栏（sidebar）
![|300](docs/attachment/Second2Brain-Sidebar.png)

提示词：
```prompt
summarize[README](README.md)
```

**Summary of [[README]]**

The Obsidian AI workflow is designed to integrate with various plugins for writing assistance, research, and organization. The workspace aims to provide an AI-powered environment.

#### Plugin Comparison Table

| Plugin | Edge Case Support | Input Type | File Support | Linking | Customization Options |
| --- | --- | --- | --- | --- | --- |
| Text Generator | High | Complete customization | No | Limited | High |

The plugins include:
* Local GPT: A local LLM model for writing assistance, providing trigger actions with keyboard shortcuts.
* Copilot: A new plugin offering more accurate results, but with limited customization options.
* Smart2Brain: An older plugin with less stable performance and fewer customization options.

#### Ollama and Kimi Integration

Instructions are provided on integrating Ollama and Kimi into the Obsidian workflow:
* Ollama: A local LLM model for writing assistance, offering simple operation and integration with plugins.
* Kimi: A powerful long-text ability and file upload/search ability, accessible through the Surfing plugin.

#### Quick Start Guide

A quick start guide is available for using Local GPT plugins in Obsidian:
* Download and installation instructions
* Configuration instructions for Ollama as a local LLM service

#### Additional Resources

For customized configurations, refer to:
* [Ollama](docs/BaseLLM/Ollama.md) and the Ollama website https://ollama.com/
* [[README]] Part 3 for using llama3.2 (LocalGPT) for chat and nomic-embed-text for Copilot and Smart2Brain indexing.

This summary provides an overview of the Obsidian AI workflow, plugin comparison, and integration instructions for Ollama and Kimi.
