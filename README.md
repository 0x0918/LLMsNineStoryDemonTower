# LLMsNineStoryDemonTower LLMs九层妖塔

【LLMs九层妖塔】分享一下打怪(ChatGLM、Chinese-LLaMA-Alpaca、MiniGPT-4、小羊驼 Vicuna、LLaMA、GPT4ALL等)实战与经验，

- [LLMsNineStoryDemonTower LLMs九层妖塔](#llmsninestorydemontower-llms九层妖塔)
  - [【LLMs 入门实战系列】](#llms-入门实战系列)
    - [第一层 LLMs to Natural Language Processing (NLP)](#第一层-llms-to-natural-language-processing-nlp)
      - [第一重 ChatGLM-6B](#第一重-chatglm-6b)
      - [第二重 Stanford Alpaca 7B](#第二重-stanford-alpaca-7b)
      - [第三重 Chinese-LLaMA-Alpaca](#第三重-chinese-llama-alpaca)
      - [第四重 小羊驼 Vicuna](#第四重-小羊驼-vicuna)
      - [第五重 GPT4ALL](#第五重-gpt4all)
      - [第六重 MOSS](#第六重-moss)
      - [第七重 BLOOMz](#第七重-bloomz)
      - [第八重 BELLE](#第八重-belle)
      - [第九重 ChatRWKV](#第九重-chatrwkv)
      - [第十重 ChatGPT](#第十重-chatgpt)
      - [第十一重 OpenBuddy](#第十一重-openbuddy)
    - [第二层 LLMs to Intelligent Retrieval (IR)](#第二层-llms-to-intelligent-retrieval-ir)
      - [第一重 langchain](#第一重-langchain)
    - [第三层 LLMs to Text-to-Image](#第三层-llms-to-text-to-image)
      - [第一重 Stable Diffusion](#第一重-stable-diffusion)
    - [第四层 LLMs to Visual Question Answering (VQA)](#第四层-llms-to-visual-question-answering-vqa)
      - [第一重 BLIP](#第一重-blip)
      - [第二重 BLIP2](#第二重-blip2)
      - [第三重 MiniGPT-4](#第三重-minigpt-4)
      - [第四重 VisualGLM-6B](#第四重-visualglm-6b)
    - [第五层 LLMs to Automatic Speech Recognition (ASR)](#第五层-llms-to-automatic-speech-recognition-asr)
      - [第一重 Massively Multilingual Speech (MMS，大规模多语种语音)](#第一重-massively-multilingual-speech-mms大规模多语种语音)
    - [第六层 LLMs to Text To Speech (TTS)](#第六层-llms-to-text-to-speech-tts)
      - [第一重 Massively Multilingual Speech (MMS，大规模多语种语音)](#第一重-massively-multilingual-speech-mms大规模多语种语音-1)
    - [第七层 LLMs to Artifact](#第七层-llms-to-artifact)
      - [第一重 AutoGPT](#第一重-autogpt)
    - [第八层 LLMs to Parameter Efficient Fine-Tuning (PEFT)](#第八层-llms-to-parameter-efficient-fine-tuning-peft)
      - [第一重 LLMTune](#第一重-llmtune)
      - [第二重 Guanaco](#第二重-guanaco)
    - [第九层 LLMs to Vertical Field (VF)](#第九层-llms-to-vertical-field-vf)
      - [第一重 聚宝盆(Cornucopia)](#第一重-聚宝盆cornucopia)
  - [学习群](#学习群)
  - [优秀笔记](#优秀笔记)
    - [第一层](#第一层)
    - [优秀笔记](#优秀笔记-1)
  - [参考](#参考)

## 【LLMs 入门实战系列】

### 第一层 LLMs to Natural Language Processing (NLP)

#### 第一重 ChatGLM-6B

1. [【ChatGLM-6B入门-一】清华大学开源中文版ChatGLM-6B模型学习与实战](ChatGLM-6B/induction.md)
   1. 介绍：ChatGLM-6B 环境配置 和 部署
2. [【ChatGLM-6B入门-二】清华大学开源中文版ChatGLM-6B模型微调实战](ChatGLM-6B/ptuning.md)
   1. ChatGLM-6B P-Tuning V2 微调：Fine-tuning the prefix encoder of the model.
3. [【ChatGLM-6B入门-三】ChatGLM 特定任务微调实战](https://articles.zsxq.com/id_3b42ukjdkwpt.html)
4. [【ChatGLM-6B入门-四】ChatGLM + LoRA 进行finetune](https://articles.zsxq.com/id_e2389qm0w0sx.html)
   1. 介绍：ChatGLM-6B LoRA 微调：Fine-tuning the low-rank adapters of the model.
5. [ChatGLM-6B 小编填坑记](https://articles.zsxq.com/id_fw7vn0mhdsnq.html)
   1. 介绍：ChatGLM-6B 在 部署和微调 过程中 会遇到很多坑，小编掉坑了很多次，为防止 后人和小编一样继续掉坑，小编索性把遇到的坑都填了。
6. [【LLMs学习】关于大模型实践的一些总结](https://articles.zsxq.com/id_il58nxrs9jxr.html)
7. [【LLMs 入门实战 —— 十一 】基于 🤗PEFT 的高效 🤖ChatGLM-6B 微调](https://articles.zsxq.com/id_7rz5jtfguuc5.html)
   1. 微调方式：
      1. ChatGLM-6B Freeze 微调：Fine-tuning the MLPs in the last n blocks of the model.
      2. ChatGLM-6B P-Tuning V2 微调：Fine-tuning the prefix encoder of the model.
      3. ChatGLM-6B LoRA 微调：Fine-tuning the low-rank adapters of the model.

#### 第二重 Stanford Alpaca 7B 

- [【LLMs 入门实战 —— 五 】Stanford Alpaca 7B 模型学习与实战](https://articles.zsxq.com/id_xnt3fvp2wxz0.html)
  - 介绍：本教程提供了对LLaMA模型进行微调的廉价亲民 LLMs 学习和微调 方式，主要介绍对于 Stanford Alpaca 7B 模型在特定任务上 的 微调实验，所用的数据为OpenAI提供的GPT模型API生成质量较高的指令数据（仅52k）。

#### 第三重 Chinese-LLaMA-Alpaca 

- [【LLMs 入门实战 —— 六 】Chinese-LLaMA-Alpaca 模型学习与实战](https://articles.zsxq.com/id_dqvusswrdg6c.html)
  - 介绍：本教程主要介绍了 Chinese-ChatLLaMA,提供中文对话模型 ChatLLama 、中文基础模型 LLaMA-zh 及其训练数据。 模型基于 TencentPretrain 多模态预训练框架构建

#### 第四重 小羊驼 Vicuna

- [【LLMs 入门实战 —— 七 】小羊驼 Vicuna模型学习与实战](Vicuna/readme.md)
  - 介绍：UC伯克利学者联手CMU、斯坦福等，再次推出一个全新模型70亿/130亿参数的Vicuna，俗称「小羊驼」（骆马）。小羊驼号称能达到GPT-4的90%性能

#### 第五重 GPT4ALL

- [【LLMs 入门实战 —— 八 】GPT4ALL 模型学习与实战](https://articles.zsxq.com/id_ff0w6czthq25.html)
  - 介绍：一个 可以在自己笔记本上面跑起来的  Nomic AI 的助手式聊天机器人，成为贫民家孩子的 福音！

#### 第六重 MOSS

- [【LLMs 入门实战 —— 十三 】MOSS 模型学习与实战](https://articles.zsxq.com/id_4vwpxod23zrc.html)
  - 介绍：MOSS是一个支持中英双语和多种插件的开源对话语言模型，moss-moon系列模型具有160亿参数，在FP16精度下可在单张A100/A800或两张3090显卡运行，在INT4/8精度下可在单张3090显卡运行。MOSS基座语言模型在约七千亿中英文以及代码单词上预训练得到，后续经过对话指令微调、插件增强学习和人类偏好训练具备多轮对话能力及使用多种插件的能力。
  - 局限性：由于模型参数量较小和自回归生成范式，MOSS仍然可能生成包含事实性错误的误导性回复或包含偏见/歧视的有害内容，请谨慎鉴别和使用MOSS生成的内容，请勿将MOSS生成的有害内容传播至互联网。若产生不良后果，由传播者自负。

#### 第七重 BLOOMz

- [【LLMs 入门实战 —— 十四 】 BLOOMz 模型学习与实战](https://articles.zsxq.com/id_wd97899pkjqj.html)
  - 介绍：大型语言模型（LLMs）已被证明能够根据一些演示或自然语言指令执行新的任务。虽然这些能力已经导致了广泛的采用，但大多数LLM是由资源丰富的组织开发的，而且经常不对公众开放。作为使这一强大技术民主化的一步，我们提出了BLOOM，一个176B参数的开放性语言模型，它的设计和建立要感谢数百名研究人员的合作。BLOOM是一个仅有解码器的Transformer语言模型，它是在ROOTS语料库上训练出来的，该数据集包括46种自然语言和13种编程语言（共59种）的数百个来源。我们发现，BLOOM在各种基准上取得了有竞争力的性能，在经历了多任务提示的微调后，其结果更加强大。
  - 模型地址：https://huggingface.co/bigscience/bloomz

#### 第八重 BELLE

- [【LLMs 入门实战 —— 十五 】 BELLE 模型学习与实战](https://articles.zsxq.com/id_gxebzsadfpr2.html)
  - 介绍：相比如何做好大语言模型的预训练，BELLE更关注如何在开源预训练大语言模型的基础上，帮助每一个人都能够得到一个属于自己的、效果尽可能好的具有指令表现能力的语言模型，降低大语言模型、特别是中文大语言模型的研究和应用门槛。为此，BELLE项目会持续开放指令训练数据、相关模型、训练代码、应用场景等，也会持续评估不同训练数据、训练算法等对模型表现的影响。BELLE针对中文做了优化，模型调优仅使用由ChatGPT生产的数据（不包含任何其他数据）。
  - github 地址: https://github.com/LianjiaTech/BELLE

#### 第九重 ChatRWKV

- [【LLMs 入门实战 —— 十八 】 ChatRWKV 模型学习与实战](https://articles.zsxq.com/id_dw7jhxq736bw.html)
  - 目前 RWKV 有大量模型，对应各种场景，各种语言，请选择合适的模型：
    - Raven 模型：适合直接聊天，适合 +i 指令。有很多种语言的版本，看清楚用哪个。适合聊天、完成任务、写代码。可以作为任务去写文稿、大纲、故事、诗歌等等，但文笔不如 testNovel 系列模型。
    - Novel-ChnEng 模型：中英文小说模型，可以用 +gen 生成世界设定（如果会写 prompt，可以控制下文剧情和人物），可以写科幻奇幻。不适合聊天，不适合 +i 指令。
    - Novel-Chn 模型：纯中文网文模型，只能用 +gen 续写网文（不能生成世界设定等等），但是写网文写得更好（也更小白文，适合写男频女频）。不适合聊天，不适合 +i 指令。
    - Novel-ChnEng-ChnPro 模型：将 Novel-ChnEng 在高质量作品微调（名著，科幻，奇幻，古典，翻译，等等）。
  - github: https://github.com/BlinkDL/ChatRWKV
  -  模型文件：https://huggingface.co/BlinkDL

#### 第十重 ChatGPT

- [《ChatGPT Prompt Engineering for Developers》 学习 之 如何 编写 Prompt？](https://articles.zsxq.com/id_2wutbr4eehzm.html)
  - [吴恩达老师与OpenAI合作推出《ChatGPT Prompt Engineering for Developers》](https://learn.deeplearning.ai/chatgpt-prompt-eng/lesson/1/introduction)
  - 动机：吴恩达老师与OpenAI合作推出《ChatGPT Prompt Engineering for Developers》课程
  - 介绍：如何编写 Prompt:
    - 第一个方面：编写清晰、具体的指令
    - 第二个方面：给模型些时间思考
- [《ChatGPT Prompt Engineering for Developers》 学习 之 如何 优化 Prompt？](https://articles.zsxq.com/id_swisqrpd8vi2.html)
  - [吴恩达老师与OpenAI合作推出《ChatGPT Prompt Engineering for Developers》](https://learn.deeplearning.ai/chatgpt-prompt-eng/lesson/1/introduction)
  - 动机：吴恩达老师与OpenAI合作推出《ChatGPT Prompt Engineering for Developers》课程
  - 介绍：优化编写好 Prompt
- [《ChatGPT Prompt Engineering for Developers》 学习 之 如何使用 Prompt 处理 NLP特定任务？](https://articles.zsxq.com/id_uazuhqdkesq4.html)
  - [吴恩达老师与OpenAI合作推出《ChatGPT Prompt Engineering for Developers》](https://learn.deeplearning.ai/chatgpt-prompt-eng/lesson/1/introduction)
  - 动机：吴恩达老师与OpenAI合作推出《ChatGPT Prompt Engineering for Developers》课程
  - 介绍：如何构建ChatGPT Prompt以处理文本摘要、推断和转换(翻译、纠错、风格转换、格式转换等)这些常见的NLP任务

#### 第十一重 OpenBuddy

- [【LLMs 入门实战 —— 二十八 】 OpenBuddy 模型学习与实战](https://articles.zsxq.com/id_g2tmn66fearf.html)
  - 论文名称：OpenBuddy - Open Multilingual Chatbot based on Falcon
  - github 地址：https://github.com/OpenBuddy/OpenBuddy
  - 动机：虽然目前 很多人 LLMs 层出不穷，但是他们并不能 在 多语言支持无缝衔接（eg: LLaMA 模型由于是用 英语训练，所以在 中文等其他语种上效果并不好）
  - 介绍：基于 Tii 的 Falcon 模型和 Facebook 的 LLaMA 模型构建，OpenBuddy 经过微调，包括扩展词汇表、增加常见字符和增强 token 嵌入。通过利用这些改进和多轮对话数据集，OpenBuddy 提供了一个强大的模型，能够回答各种语言的问题并执行翻译任务。

### 第二层 LLMs to Intelligent Retrieval (IR)

#### 第一重 langchain

1. [【LLMs 入门实战 —— 十二 】基于 本地知识库 的高效 🤖langchain-ChatGLM ](https://articles.zsxq.com/id_54vjwns5t6in.html)
   1. 介绍：langchain-ChatGLM是一个基于本地知识的问答机器人，使用者可以自由配置本地知识，用户问题的答案也是基于本地知识生成的。

### 第三层 LLMs to Text-to-Image

#### 第一重 Stable Diffusion

- [【LLMs 入门实战 —— 二十二 】Stable Diffusion 模型学习与实战](https://github.com/km1994/LLMsNineStoryDemonTower/tree/main/text2img/stable_diffusion)
  - Github 地址：https://github.com/gediz/lstein-stable-diffusion
  - 预训练模型：https://huggingface.co/CompVis/stable-diffusion
  - 介绍：Stable Diffusion是一种潜在扩散模型（Latent Diffusion Model），能够从文本描述中生成详细的图像。它还可以用于图像修复、图像绘制、文本到图像和图像到图像等任务。简单地说，我们只要给出想要的图片的文字描述在提Stable Diffusion就能生成符合你要求的逼真的图像！
- [【LLMs 入门实战 —— 二十三 】Stable Diffusion Webui 模型学习与实战](https://github.com/km1994/LLMsNineStoryDemonTower/tree/main/text2img/stable_diffusion_webui)
  - Github 地址：https://github.com/AUTOMATIC1111/stable-diffusion-webui
  - 预训练模型：https://huggingface.co/CompVis/stable-diffusion
  - 介绍：Stable Diffusion是一款功能异常强大的AI图片生成器。它不仅支持生成图片，使用各种各样的模型来达到你想要的效果，还能训练你自己的专属模型。WebUI使得Stable Diffusion有了一个更直观的用户界面，更适合新手用户。
- [【LLMs 入门实战 —— 二十四 】Novelai 模型学习与实战](https://github.com/km1994/LLMsNineStoryDemonTower/tree/main/text2img/novelai)
- [【LLMs 入门实战 —— 二十五 】lora 模型学习与实战](https://github.com/km1994/LLMsNineStoryDemonTower/tree/main/text2img/lora)
  - Github 地址：https://github.com/microsoft/LoRA
  - 预训练模型：https://huggingface.co/johnsmith007/LoRAs/tree/main
  - 介绍：LoRA的全称是LoRA: Low-Rank Adaptation of Large Language Models，可以理解为stable diffusion（SD)模型的一种插件，和hyper-network，controlNet一样，都是在不修改SD模型的前提下，利用少量数据训练出一种画风/IP/人物，实现定制化需求，所需的训练资源比训练SD模要小很多，非常适合社区使用者和个人开发者。

### 第四层 LLMs to Visual Question Answering (VQA)

#### 第一重 BLIP

- [【LLMs 入门实战 —— 二十二】 BLIP 模型学习与实战](https://articles.zsxq.com/id_mpckrd9ccfdn.html)
  - 论文名称：BLIP: Bootstrapping Language-Image Pre-training for Uniﬁed Vision-Language Understanding and Generation
  - 论文地址：https://arxiv.org/abs/2201.12086
  - 代码地址：https://github.com/salesforce/BLIP
  - 局限性:
    - **模型角度**: 
      - 现有方法：大多数方法要么采用基于编码器的模型，要么采用编码器-解码器模型。
      - 存在问题：**基于编码器的模型不太容易直接转换到文本生成任务（例如图像字幕）**，而**编码器-解码器模型尚未成功用于图像文本检索任务**；
    - **数据角度**: 大多数SOTA的方法（如CLIP、ALBEF等）都在从web上收集到的图文对上进行预训练。尽管通过扩展数据集获得了性能提升，但 BLIP 的研究表明，对于视觉语言学习来说，有噪声的网络文本是次优的。
  - BLIP总体思路：作为新的 VLP 框架，**BLIP 用于统一视觉语言理解和生成的 Bootstrapping Language-Image 预训练，可以灵活地迁移到视觉语言理解和生成任务。 BLIP 通过引导字幕有效地利用了嘈杂的网络数据，字幕生成器生成合成字幕，过滤器去除嘈杂的字幕**
  - 贡献:
    - （1） **编码器-解码器 (MED) 的多模式混合**：一种用于有效多任务预训练和灵活迁移学习的新模型架构。MED可以作为单模态编码器、基于图像的文本编码器或基于图像的文本解码器工作。**该模型与三个视觉语言目标联合预训练：图像文本对比学习、图像文本匹配和图像条件语言建模**。
    - （2） **字幕和过滤（Captioning and Filtering，CapFilt）**：一种新的数据集增强方法，用于**从噪声图像-文本对中学习**。作者将预先训练的MED分为两个模块: **一个字幕器，用于生成给定web图像的合成字幕**，以及**一个过滤器，用于从原始web文本和合成文本中删除嘈杂的字幕**。

#### 第二重 BLIP2

- [【LLMs 入门实战 —— 二十六】 BLIP2 模型学习与实战](https://articles.zsxq.com/id_lcwp2s597vrr.html)
  - 论文名称：BLIP-2: Bootstrapping Language-Image Pre-training with Frozen Image Encoders and Large Language Models
  - 单位：Salesforce 研究院
  - 论文地址：https://arxiv.org/abs/2301.12597
  - 代码地址：https://github.com/salesforce/LAVIS/tree/main/projects/blip2
  - HF上的Demo：https://huggingface.co/spaces/Salesforce/BLIP2
  - 动机
    - 由于大规模模型的端到端训练，视觉和语言预训练的成本变得越来越高
    - 为了降低计算成本并抵消灾难性遗忘的问题，希望在 Vision-language pre-training (VLP) 中固定视觉模型参数与语言模型参数。然而，由于语言模型在其单模态预训练期间没有看到图像，因此冻结它们使得视觉语言对齐尤其具有挑战性
   - 介绍：
     - BLIP-2， 一种通用而有效的预训练策略，它从现成的冻结预训练图像编码器和冻结的大型语言模型中引导视觉语言预训练。
     - 通过一个轻量级的 Querying Transformer （Q-Former是一个轻量级的 transformer，它使用一组可学习的查询向量来从冻结图像编码器中提取视觉特征，为LLM提供最有用的视觉特征，以输出所需的文本） 弥补了模态 gap，该 Transformer 分两个阶段进行预训练:
      - 第一阶段：从冻结图像编码器引导视觉语言表示学习，强制 Q-Former 学习与文本最相关的视觉表示；
      - 第二阶段：将视觉从冻结的语言模型引导到语言生成学习，将Q-Former的输出连接到冻结的LLM，并对Q-Former进行训练，使其输出视觉表示能够被LLM解释。

#### 第三重 MiniGPT-4 

- [【LLMs 入门实战 —— 八 】MiniGPT-4 模型学习与实战](mingpt/readme.md)
  - Github 链接： https://github.com/Vision-CAIR/MiniGPT-4
  - 介绍： MiniGPT-4，是来自阿卜杜拉国王科技大学的几位博士做的，它能提供类似 GPT-4 的图像理解与对话能力

#### 第四重 VisualGLM-6B

- [【LLMs 入门实战 —— 十七 】 VisualGLM-6B 模型学习与实战](https://articles.zsxq.com/id_4pzgwnwl2zjc.html) 
  - Github 链接： https://github.com/THUDM/VisualGLM-6B
  - Huggingface 链接：https://huggingface.co/THUDM/visualglm-6b
  - 动机：OpenAI 的GPT-4样例中展现出令人印象深刻的多模态理解能力，但是能理解图像的中文开源对话模型仍是空白。
  - 介绍：VisualGLM-6B 是一个开源的，支持图像、中文和英文的多模态对话语言模型，语言模型基于 ChatGLM-6B，具有 62 亿参数；图像部分通过训练 BLIP2-Qformer 构建起视觉模型与语言模型的桥梁，整体模型共 78 亿参数。VisualGLM-6B 依靠来自于 CogView 数据集的30M高质量中文图文对，与 300M 经过筛选的英文图文对进行预训练，中英文权重相同。该训练方式较好地将视觉信息对齐到 ChatGLM 的语义空间；之后的微调阶段，模型在长视觉问答数据上训练，以生成符合人类偏好的答案。
  - github 地址:https://github.com/THUDM/VisualGLM-6B

### 第五层 LLMs to Automatic Speech Recognition (ASR)

#### 第一重 Massively Multilingual Speech (MMS，大规模多语种语音)

- [【LLMs 入门实战 —— 二十 】 Massively Multilingual Speech (MMS，大规模多语种语音) 模型学习与实战](https://github.com/km1994/LLMsNineStoryDemonTower/tree/main/speech_MMS_21)
  - 论文：[Scaling Speech Technology to 1,000+ Languages](https://research.facebook.com/publications/scaling-speech-technology-to-1000-languages/)
  - 代码：[fairseq/tree/main/examples/mms](https://github.com/facebookresearch/fairseq/tree/main/examples/mms)
  - 公告：https://ai.facebook.com/blog/multilingual-model-speech-recognition/
  - 介绍：Meta 在 GitHub 上再次开源了一款全新的 AI 语言模型——Massively Multilingual Speech (MMS，大规模多语种语音)，它与 ChatGPT 有着很大的不同，这款新的语言模型可以识别 4000 多种口头语言并生成 1100 多种语音（文本到语音）。

### 第六层 LLMs to Text To Speech (TTS)

#### 第一重 Massively Multilingual Speech (MMS，大规模多语种语音)

- [【LLMs 入门实战 —— 二十 】 Massively Multilingual Speech (MMS，大规模多语种语音) 模型学习与实战](https://github.com/km1994/LLMsNineStoryDemonTower/tree/main/speech_MMS_21)
  - 论文：[Scaling Speech Technology to 1,000+ Languages](https://research.facebook.com/publications/scaling-speech-technology-to-1000-languages/)
  - 代码：[fairseq/tree/main/examples/mms](https://github.com/facebookresearch/fairseq/tree/main/examples/mms)
  - 公告：https://ai.facebook.com/blog/multilingual-model-speech-recognition/
  - 介绍：Meta 在 GitHub 上再次开源了一款全新的 AI 语言模型——Massively Multilingual Speech (MMS，大规模多语种语音)，它与 ChatGPT 有着很大的不同，这款新的语言模型可以识别 4000 多种口头语言并生成 1100 多种语音（文本到语音）。

### 第七层 LLMs to Artifact

#### 第一重 AutoGPT

- [AutoGPT 使用和部署](https://articles.zsxq.com/id_pli0z9916126.html)
  - 介绍：Auto-GPT是一个基于ChatGPT的工具，他能帮你自动完成各种任务，比如写代码、写报告、做调研等等。使用它时，你只需要告诉他要扮演的角色和要实现的目标，然后他就会利用ChatGPT和谷歌搜索等工具，不断“思考”如何接近目标并执行，你甚至可以看到他的思考过程。

### 第八层 LLMs to Parameter Efficient Fine-Tuning (PEFT)

#### 第一重 LLMTune

- [【LLMs 入门实战 —— 十六 】 LLMTune 模型学习与实战](https://articles.zsxq.com/id_1hg51c292bu6.html)
  - 动机：大语言模型虽然能力很强，目前开源生态也很丰富，但是在特定领域微调大模型依然需要大规格的显卡。例如，清华大学发布的ChatGLM-6B，参数规模60亿，在没有量化的情况下微调需要14GB显存（parameter-efficient fine-tuning，PEFT)。在没有任何优化的前提下，每10亿参数的全精度（32bit）模型载入到显存中就需要4GB，而int8量化后也需要1GB显存。而目前开源最强的模型LLaMA，其最高参数维650亿规模，全精度模型载入就需要260GB，显然已经超出了大部分人的硬件水平。更不要说对模型进行微调（微调需要训练更新参数，推理只需要前向计算即可，因此，微调需要更多的显存才能支持）。
  - 介绍：Cornell Tech开源的LLMTune就是为了降低大模型微调难度所提出的一种解决方案。对于650亿参数的LLaMA模型微调仅需要40GB显存即可。
  - github 地址: https://github.com/kuleshov-group/llmtune

#### 第二重 Guanaco

- [【LLMs 入门实战 —— 二十 】 Guanaco 模型学习与实战]()
  - [https://huggingface.co/BlinkDL](https://huggingface.co/BlinkDL)
  - [artidoro/qlora](https://github.com/artidoro/qlora)
  - 模型：[timdettmers (Tim Dettmers)](https://huggingface.co/timdettmers)
  - 量化代码：[TimDettmers/bitsandbytes](https://github.com/TimDettmers/bitsandbytes)
  - BLOG : [Making LLMs even more accessible with bitsandbytes, 4-bit quantization and QLoRA](https://huggingface.co/blog/4bit-transformers-bitsandbytes)
  - Demo环境：[Guanaco Playground Tgi - a Hugging Face Space by uwnlp](https://huggingface.co/spaces/uwnlp/guanaco-playground-tgi)
  - 介绍：5月24日华盛顿大学的研究者发布了QLoRA技术及用其生成的Guanaco大模型。
    - 特点：
      - 在Vicuna基准测试中表现优于所有先前公开发布的模型，达到ChatGPT性能水平的99.3%，仅需要单个GPU上的24小时微调时间；
      - QLORA引入了一些创新来节省内存而不牺牲性能：
        - （a）4位NormalFloat（NF4），这是一种对于正态分布权重来说在信息论上是最优的数据类型；
        - （b）双量化，通过量化量化常数来减少平均内存占用；
        - （c）分页优化器，用于管理内存峰值。

- [【LLMs 入门实战 —— 二十七 】【QLoRA实战】使用单卡高效微调bloom-7b1]()
  - [https://huggingface.co/BlinkDL](https://huggingface.co/BlinkDL)
  - [artidoro/qlora](https://github.com/artidoro/qlora)
  - 模型：[timdettmers (Tim Dettmers)](https://huggingface.co/timdettmers)
  - 量化代码：[TimDettmers/bitsandbytes](https://github.com/TimDettmers/bitsandbytes)
  - BLOG : [Making LLMs even more accessible with bitsandbytes, 4-bit quantization and QLoRA](https://huggingface.co/blog/4bit-transformers-bitsandbytes)

### 第九层 LLMs to Vertical Field (VF)

#### 第一重 聚宝盆(Cornucopia) 

- [【LLMs 入门实战 —— 十九】 聚宝盆(Cornucopia) 模型学习与实战](https://github.com/km1994/LLMsNineStoryDemonTower/tree/main/Cornucopia_19)
  - 聚宝盆(Cornucopia) 开源了经过中文金融知识指令精调/指令微调(Instruct-tuning) 的LLaMA-7B模型。通过中文金融公开数据+爬取的金融数据构建指令数据集，并在此基础上对LLaMA进行了指令微调，提高了 LLaMA 在金融领域的问答效果。
  - github: [jerry1993-tech/Cornucopia-LLaMA-Fin-Chinese](https://github.com/jerry1993-tech/Cornucopia-LLaMA-Fin-Chinese/tree/main)

## 学习群

![[学习群二维码](img/20230516092740.jpg)](img/20230516092740.jpg)
> 二维码如果过期，可以加 wx: yzyykm666 加群

## 优秀笔记

### 第一层

### 优秀笔记

1. [杨夕](https://mp.weixin.qq.com/s/4QNgF6nAUo8imSaIB_OWmg)
2. [奔腾](https://articles.zsxq.com/id_k2qzsps7zw21.html)
3. [逸尘](https://articles.zsxq.com/id_zzfqt88sw4rl.html)
4. [此方一泉](https://t.zsxq.com/0dEp8PDcW)
5. [vezel](http://t.csdn.cn/hWn9D)
6. [徐生](https://zhuanlan.zhihu.com/p/627358709)
7. [多点微笑](https://articles.zsxq.com/id_velwvtmfhrwz.html)
8. [小固](https://zhuanlan.zhihu.com/p/627333187)
9. [土狼](https://zhuanlan.zhihu.com/p/627358709)
10. [0](https://github.com/Wesley12138/LLM)
11. [Welch](https://t.zsxq.com/0dJhaaGRW)
12. [九猫](https://articles.zsxq.com/id_7g0g65fbsluo.html)


## 参考

1. [ChatGLM-6B](https://github.com/THUDM/ChatGLM-6B)
2. [Stanford Alpaca 7B](https://github.com/tatsu-lab/stanford_alpaca)
3. [Chinese-LLaMA-Alpaca](https://github.com/ymcui/Chinese-LLaMA-Alpaca)
4. [Vicuna](https://github.com/lm-sys/FastChat)
5. [MiniGPT-4](https://github.com/Vision-CAIR/MiniGPT-4)
6. [GPT4ALL](https://github.com/nomic-ai/gpt4all)
7. [Auto-GPT](https://github.com/Significant-Gravitas/Auto-GPT)
8. [MOSS](https://github.com/OpenLMLab/MOSS/tree/main)
