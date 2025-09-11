# *Pygmalion Links*

[Website](https://pygmalion.chat) • [Matrix](https://matrix.to/#/#waifu-ai-collaboration-hub:halogen.city?via=halogen.city) • [GitHub](https://github.com/PygmalionAI) • [Twitter / X](https://x.com/pygmalion_ai) • [HuggingFace](https://huggingface.co/PygmalionAI) • [Reddit Profile](https://www.reddit.com/user/PygmalionAI) • [Subreddit](https://www.reddit.com/r/Pygmalion_AI) • [Telegram](https://t.me/pygmalionai) • [Discord](https://discord.com/invite/pygmalionai)

---

**📜 [The Pygmalion Wiki](https://wikia.schneedc.com)** — **If you're new to Pygmalion, please read this first. This will answer most of your basic questions.**

---

### *Cloud Options*
☁️ ***To run Pygmalion on the cloud, choose one of the links below and follow the instructions to get started***

- **[TextGen WebUI](https://colab.research.google.com/github/oobabooga/text-generation-webui/blob/main/Colab-TextGen-GPU.ipynb)** — Simple CAI-like interface. Also known as Oobabooga. Runs on a Gradio app, but you can also connect it to [SillyTavern](https://github.com/Cohee1207/SillyTavern) for a more feature-rich interface.
- **[KoboldAI Horde](https://lite.koboldai.net)** — The Horde lets you run Pygmalion online with the help of generous people who are donating their GPU resources.
- **[Agnaistic](https://agnai.chat/info)** — Free online interface with no registration needed. It runs on the Horde by default so there's no setup needed, but you can also use any of the AI services it accepts as long as you have the respective access key.

---

### *Local Installation*
🖥️ ***To run Pygmalion locally (on your own computer), follow one of the guides below***

> **Note: Important Note:**  
> Make sure your machine meets the [system requirements](https://wikia.schneedc.com/llm/system-requirements) before downloading.

- **[TextGen WebUI](https://wikia.schneedc.com/en/backend/ooba)** — This guide will help you install the TextGen WebUI (also known as Oobabooga).
- **[KoboldAI](https://wikia.schneedc.com/en/backend/kobold-ai)** — This guide will help you install KoboldAI, a browser-based frontend.
- **[koboldcpp](https://wikia.schneedc.com/en/backend/kobold-cpp)** — Use KoboldCPP to run models on CPU, or a mix of GPU+CPU.
- **[SillyTavern](https://wikia.schneedc.com/en/frontend/silly-tavern)** — Atmospheric interface. This is *only* a UI; you need to connect it to a service like TextGen or Kobold.

---

### *Character Creation*
🤖 ***To create and share characters, refer to the links below***

- **[AI Character Editor](https://avakson.github.io/character-editor)** — Most interfaces use character cards, which are images that have extra data inside them that define the character.
- **[Chub AI](https://chub.ai)** — A place to share and download character cards (the site is SFW by default but has a NSFW toggle)

---

### *Pygmalion Models*

- **[List of Pygmalion models](https://huggingface.co/models?search=pygmalion)**
  - Includes all Pygmalion base models and fine-tunes (models built off of the original). Newer models are recommended.

#### *Pygmalion 2 and Mythalion*

- [Pygmalion 2 7B](https://huggingface.co/PygmalionAI/pygmalion-2-7b) and [Pygmalion 2 13B](https://huggingface.co/PygmalionAI/pygmalion-2-13b) are chat/roleplay models based on Meta's [Llama 2](https://ai.meta.com/resources/models-and-libraries/llama).
- [Mythalion 13B](https://huggingface.co/PygmalionAI/mythalion-13b) is a merge between Pygmalion 2 and Gryphe's [MythoMax](https://huggingface.co/Gryphe/MythoMax-L2-13b).
- [Blog post (including suggested generation parameters for SillyTavern)](https://pygmalionai.github.io/blog/posts/introducing_pygmalion_2)

#### *Quantized by TheBloke*

Quantized models can run on less powerful machines, though they tend to hallucinate more than full-precision models.
GGUF is recommended for those without a powerful GPU, since these models can be offloaded to CPU (although it's a lot slower).

* [Pygmalion 2 7B GPTQ](https://huggingface.co/TheBloke/Pygmalion-2-7B-GPTQ)
* [Pygmalion 2 7B GGUF](https://huggingface.co/TheBloke/Pygmalion-2-7B-GGUF)
* [Pygmalion 2 13B GPTQ](https://huggingface.co/TheBloke/Pygmalion-2-13B-GPTQ)
* [Pygmalion 2 13B GGUF](https://huggingface.co/TheBloke/Pygmalion-2-13B-GGUF)
* [Mythalion 13B GPTQ](https://huggingface.co/TheBloke/Mythalion-13B-GPTQ)
* [Mythalion 13B GGUF](https://huggingface.co/TheBloke/Mythalion-13B-GGUF)

#### *Older Models*
These models are outdated and not guaranteed to work on all text generation services.
- [Metharme 13B](https://huggingface.co/PygmalionAI/metharme-13b) — Instruction model based on Meta's [LLaMA 13B](https://huggingface.co/huggyllama/llama-13b)
- [Metharme 7B](https://huggingface.co/PygmalionAI/metharme-7b) — Instruction model based on Meta's [LLaMA 7B](https://huggingface.co/huggyllama/llama-7b)
- [Pygmalion 13B](https://huggingface.co/PygmalionAI/pygmalion-13b) — Chat model based on Meta's [LLaMA 13B](https://huggingface.co/huggyllama/llama-13b)
- [Pygmalion 7B](https://huggingface.co/PygmalionAI/pygmalion-7b) — Chat model based on Meta's [LLaMA 7B](https://huggingface.co/huggyllama/llama-7b)
- [Pygmalion 6B](https://huggingface.co/PygmalionAI/pygmalion-6b) — Based on EleutherAI's [GPT-J 6B](https://huggingface.co/EleutherAI/gpt-j-6B)
- [Pygmalion 2.7B](https://huggingface.co/PygmalionAI/pygmalion-2.7b) — Based on EleutherAI's [GPT-Neo 2.7B](https://hugfengface.co/EleutherAI/gpt-neo-2.7B)
- [Pygmalion 1.3B](https://huggingface.co/PygmalionAI/pygmalion-1.3b) — Based on EleutherAI's [Pythia 1.3B](https://huggingface.co/EleutherAI/pythia-1.3b-deduped)
- [Pygmalion 350M](https://huggingface.co/PygmalionAI/pygmalion-350m) — Based on Facebook's [OPT 350M](https://huggingface.co/facebook/opt-350m)

---

### *User Interfaces*

> **Note: Colab users:**  
> Due to high resource usage, Google does not allow the string `PygmalionAI` in Colab code. You can still use Colab with other models. Almost all Colabs now use different unbanned versions of Pygmalion.

#### *The Website*

The developers have finished working on an official UI, which is hosted [here](https://pygmalion.chat). It has [paid plans](https://files.catbox.moe/6roufj.png), but you can also enjoy Pygmalion using one of the following interfaces if you don't like it:

#### *TextGen WebUI*
*A combined front-end and back-end for running models like LLaMA, GPT-J, Pythia, etc.*
- [Installation guide](https://github.com/oobabooga/text-generation-webui?tab=readme-ov-file#how-to-install) by Oobabooga
- [Installation guide](https://wikia.schneedc.com/en/backend/ooba) by PygmalionAI
- [Colab](https://colab.research.google.com/github/oobabooga/text-generation-webui/blob/main/Colab-TextGen-GPU.ipynb) — This is your go-to if you want to run ooba without installing locally.
- [Local Installers](https://github.com/oobabooga/text-generation-webui/releases/tag/installers) — One-click installer. For Windows, Linux, and MacOS systems.
- [GitHub](https://github.com/oobabooga/text-generation-webui)
- [Wiki](https://github.com/oobabooga/text-generation-webui/wiki/01-%E2%80%90-Chat-Tab)
- [Subreddit](https://www.reddit.com/r/Oobabooga)

---

#### *KoboldAI*
*A back-end for running a wide range of open language models.*

- [Installation guide](https://wikia.schneedc.com/en/backend/kobold-ai)
- [TPU Colab](https://colab.research.google.com/github/KoboldAI/KoboldAI-Client/blob/main/colab/TPU.ipynb) — Runs larger (20B) models.
- [GPU Colab](https://colab.research.google.com/github/KoboldAI/KoboldAI-Client/blob/main/colab/GPU.ipynb) — Runs smaller (6B/13B) models.
- [Horde Client](https://lite.koboldai.net) ([More info on AI hordes](https://github.com/db0/AI-Horde/blob/main/FAQ.md))
- [GitHub](https://github.com/henk717/KoboldAI)
- [Subreddit](https://reddit.com/r/KoboldAI)

#### *KoboldCPP*
*A backend for running GGUF models for CPU+GPU inference.*

- [Installation guide](https://wikia.schneedc.com/en/backend/kobold-cpp)
- [GitHub](https://github.com/LostRuins/koboldcpp)
- [Colab link](https://colab.research.google.com/github/LostRuins/koboldcpp/blob/concedo/colab.ipynb)

---

#### *SillyTavern*
*An atmospheric interface forked from [TavernAI](https://github.com/TavernAI/TavernAI) that features lots of customization options. Note that SillyTavern is only a front-end; it needs to connect with a back-end such as Kobold or TextGen (see above).*
- [GitHub](https://github.com/SillyLossy/TavernAI)
- [Installation guide](https://wikia.schneedc.com/en/frontend/silly-tavern)
- [SillyTavern Docs](https://docs.sillytavern.app)
- [SillyTavern Subreddit](https://reddit.com/r/SillyTavernAI)

---

#### *Other UIs*
##### *Chat Websites*
> **Warning:** All of the following sites have paid plans, often with very limited free tiers.
- [Harpy Chat](https://harpy.chat)
- [Spicy Chat](https://spicychat.ai)
- [Crushchat](https://crushchat.app/characters)
- [Chub Venus](https://venus.chub.ai)
- [Joyland](https://www.joyland.ai)
- [Charstar](https://charstar.ai)
- [Chatfai](https://chatfai.com)
- [Unhinged AI](https://www.unhinged.ai)
- [OpenCharacters](https://josephrocca.github.io/OpenCharacters/#)
- [Poe](https://poe.com)
##### *Open-source Platforms*
- [miku.gg](https://docs.miku.gg) — Open-source UI to run chatbots. Allows visual and text-to-speech (TTS).
  - [GitHub](https://github.com/miku-gg/miku)
  - [How to make emotion sprites for Miku bots](/EmotionalSprites)
- [RisuAI](https://risuai.xyz) — Tavern-like frontend, feature-rich and has plugins. Run in web or with installer.
  - [GitHub](https://github.com/kwaroran/RisuAI)
- [AgnAIstic](https://agnai.chat) — UI based on [Pygmalion's Galatea interface](https://github.com/PygmalionAI/galatea-ui). Runs chatbots anonymously, no login required.
  - [GitHub](https://github.com/luminai-companion/agn-ai)
- [BACKYARD.ai](https://backyard.ai) — Run open-source LLMs on your computer. Completely offline. Zero configuration.
- [openplayground](https://github.com/nat/openplayground)
- [Laika's LiteVN UI](https://laika-ch.itch.io/laikas-litevn-ui-for-koboldai) — Highly customizable visual novel-like UI.
- [RenAI Chat](https://github.com/Rubiksman78/RenAI-Chat) — Virtual Novel interface to chat with AI models.
- [MonikA.I.](https://github.com/Rubiksman78/MonikA.I) — "This project aims to add new AI based features to Monika After Story mod with the submod API."

---

### *Guides / Tips*
#### *General Guides*
- [Pygmalion Wiki](https://wikia.schneedc.com) — Work-in-progress Wiki. Answers most of your basic questions about Pygmalion and LLMs in general.
- [Alpin's Pygmalion Guide](/pygmalion-guide) — Very thorough guide for installing and running Pygmalion on all types of machines and systems.
  - Spiritual successor to the [original Rentry guide](/pygmalion-ai).
- ["Okay, so what the heck is a chatbot?"](https://docs.sillytavern.app/usage/faq) — Very simple and helpful guide to getting a chatbot up and running on Tavern.
- [CharacterAI chatlog dumping](/chatlog-dumping)
  - [CAI data scraping tool](https://github.com/irsat000/cai-tools?tab=readme-ov-file#links)
- [General guide to open-source chatbots](https://web.archive.org/web/20230104024442/https://www.reddit.com/user/Crataco/comments/zuowi9/opensource_chatbot_companions)
- [The Novice's LLM Training Guide](/llm-training) — Read this if you want to learn how to train your own LLMs

#### *Character Guides*
- [Bot Creation Guide](https://wikia.schneedc.com/en/bot-creation/intro)
- [Ali:Chat](/alichat) — "Ali:Chat's principle idea is using dialogue as the formatting to express and reinforce traits/characteristics. Ali:Chat can either be used by itself or combined with another style."
  - [Ali:Chat Lite](/kingbri-chara-guide) — Token-optimized character format
- [PLists](/kingbri-chara-guide#plists) — "PLists are where you describe the traits of a character. This includes personality, clothing, body, and even the environment of your RP."
  - [Guide for writing a character in PLists + Ali:Chat](/plists_alichat_avakson)
- [Pygmalion Tips](/PygTips)
- [Pygmalion character creation + writing tips](/chai-pygmalion-tips)
- [How to make a character](/create-a-character-for-fucking-idiots)
- [Importing CAI characters to Pygmalion](/chartopyg)

---

### *Character Repositories*
- [Character Hub (Chub)](https://www.chub.ai) — Share and download Tavern cards (SFW; has a NSFW toggle)
- [Tavern card booru](https://booru.plus/+pygmalion) — Share and download Tavern cards (NSFW)
- [BotPrompts](https://botprompts.net) — List of JSON files for Pygmalion (Inactive)
- [/aids/ Prompts](https://aetherroom.club) — Story prompts for KoboldAI bots

---

### *Tools / Scripts*
- [AVAKson's Character Editor](https://avakson.github.io/character-editor)
  - [GitHub](https://github.com/AVAKSon/character-editor)
- [JSON character creator](https://oobabooga.github.io/character-creator.html) — Enter your character info to create Pygmalion-compatible JSON files
- [TAIConvert](https://github.com/Mindus1/TAIConvert) — Convert TavernAI cards to JSON files

- [CAI tools](https://github.com/irsat000/cai-tools) — A Chrome extension made for CAI data scraping. Allows you to download all of your CAI bot's chat history, as well as their definitions (if you have access to them).
  - [More helpful CAI tools and scripts](/newcaitools) — HYW, fix tildes, darken italics, and more.
  - [List of CAI scripts on Greasyfork](https://greasyfork.org/en/scripts?q=character.ai)

---

### *Additional Open Models and Resources*

- [Awesome Marketing Datascience](https://github.com/underlines/awesome-marketing-datascience) — An absolutely exhaustive list of resources and tools regarding LLMs, image/audio generation software, and more.
- [LLM Explorer](https://llm.extractum.io) — Almost every open LLM you can think of is listed here.
- [TheBloke's model list](https://huggingface.co/TheBloke?sort_models=downloads#models) — Thousands of quantized open models to choose from, take your pick.
- [Local Llama Subreddit](https://www.reddit.com/r/LocalLLaMA)
- [Machine Learning subreddit](https://reddit.com/r/MachineLearning)
- [What LLM to Use?](https://github.com/continuedev/what-llm-to-use) — A repository of up-to-date LLM lists.
- [Awesome Totally Open Chatgpt](https://github.com/nichtdax/awesome-totally-open-chatgpt) — A list of open-source alternatives to ChatGPT
- [Pickaxe Project](https://beta.pickaxeproject.com) — Build, manage, and deploy custom LLM tools
- [There's An AI For That](https://theresanaiforthat.com) — Massive list of user-submitted AIs from a wide variety of categories, including conversational, image gen, audio, and a lot more. The site itself was written by ChatGPT.
- [Simon Willison's Weblog](https://simonwillison.net) — News on LLMs and machine learning
- [Local model links](/lmg_models)
- [More local model links](/localmodelslinks)
- [Ayumi's RP Rankings](/ayumi_erp_rating)
- [Local Model General Resource Guide](/lmg-resources)

---

### *Credits*
**Old owner** - Unknown (Not a username)
**New / Current owner** - Clara

[![Fuck AI](https://files.catbox.moe/os5g6k.png)](https://notbyai.fyi)

*(With <3)*

**If you have any feedback you want to give me, please fill in a form [here](https://formulaer.com/f/aa502b70-f46d-4e81-98a2-bd6b2de24540).**

**************
[Go back to the top](#pygmalion-links)
