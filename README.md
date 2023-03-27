# 🤖 Awesome ChatGPT Plugins

⚡ An up-to-date collection of info about plugins for ChatGPT from OpenAI⚡

### Introduction of ChatGPT plugins:
- [OpenAI Blog announcement](https://openai.com/blog/chatgpt-plugins)

### Awesome Demos / Use cases:
- [Restaurant-booking/Recipe-ingredient-order demo](https://twitter.com/gdb/status/1638949234681712643)
- [Retrieval Demo (MP4 file)](https://cdn.openai.com/chat-plugins/retrieval-gh-repo-readme/Retrieval-Final.mp4)
- [On-demand video processing](https://twitter.com/gdb/status/1638971232443076609)
- [Summarizing a HackerNews thread](https://twitter.com/gdb/status/1638986918947082241)
- [Emulator for Plugins](https://play.chatplugin.app)

### Creating a plugin:
- [Full documentation](https://platform.openai.com/docs/plugins/introduction)
- [Various example plugins](https://platform.openai.com/docs/plugins/examples) (todo list, sports stats, search-and-retrieval)
- The steps for creating a plugin are ([Source](https://openai.com/blog/chatgpt-plugins)):
  - Build an API with endpoints you’d like a language model to call (this can be a new API, an existing API, or a wrapper around an existing API specifically designed for LLMs).
  - Create an OpenAPI specification documenting your API, and a manifest file that links to the OpenAPI spec and includes some plugin-specific metadata.
  - When starting a conversation on chat.openai.com, users can choose which third-party plugins they’d like to be enabled. Documentation about the enabled plugins is shown to the language model as part of the conversation context, enabling the model to invoke appropriate plugin APIs as needed to fulfill user intent. For now, plugins are designed for calling backend APIs, but we are exploring plugins that can call client-side APIs as well.

### Plugin-related tips:
- [Using GPT-4-32k to generate manifest files for ChatGPT Plugins](https://gist.github.com/danielgross/0e7a00ea882797acd92ae6779126abe3) (from this [tweet](https://twitter.com/danielgross/status/1639040289816866818))

### Awesome Plugin Repos:
- [chatgpt-retrieval-plugin](https://github.com/openai/chatgpt-retrieval-plugin)
- [gerev-chatgpt-plugin](https://github.com/gerevai/gerev)

### Awesome Plugins:
- Browsing: An experimental model that knows when and how to browse the internet
- Code interpreter: An experimental ChatGPT model that can use Python, handle uploads and downloads
- Retrieval
