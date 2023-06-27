# ChatGPT plugins quickstart

Get a todo list ChatGPT plugin up and running in under 5 minutes using Python. This plugin is designed to work in conjunction with the [ChatGPT plugins documentation](https://platform.openai.com/docs/plugins). If you do not already have plugin developer access, please [join the waitlist](https://openai.com/waitlist/plugins).

## Setup locally

To install the required packages for this plugin, run the following command:

```bash
pip install -r requirements.txt
```

To run the plugin, enter the following command:

```bash
python main.py
```

Once the local server is running:

1. Navigate to https://chat.openai.com. 
2. In the Model drop down, select "Plugins" (note, if you don't see it there, you don't have access yet).
3. Select "Plugin store"
4. Select "Develop your own plugin"
5. Enter in `localhost:5003` since this is the URL the server is running on locally, then select "Find manifest file".

The plugin should now be installed and enabled! You can start with a question like "What is on my todo list" and then try adding something to it as well! 

## Setup remotely

### Cloudflare workers

### Code Sandbox

### Replit

## Getting help

If you run into issues or have questions building a plugin, please join our [Developer community forum](https://community.openai.com/c/chat-plugins/20).

EE See

See
- https://qiita.com/___monta___/items/19e62804f3026f746cc7
  ChatGPTを使いながらChatGPT Pluginを開発した話 by 人間

- https://tech.nri-net.com/entry/try_to_make_chatgpt_plugin
  ChatGPTプラグインを実際に作成してみる

- https://zenn.dev/ikekou/articles/60f7e88ed6aa4b
  ChatGPT plugins quickstartを動かす方法（2023年6月5日時点）

- https://platform.openai.com/docs/plugins/examples
  Example plugins

- https://zenn.dev/laiso/scraps/0c4d0cd589dc10
  ChatGPT Plugins開発
```
OpenAPI仕様書を公開しておくとGPTがそれを解釈してユーザーの入力からWebリクエストを作って処理してくれる.
各APIのdescriptionをちゃんと書いておけばあとはChatGPT側でよしなにやってくれる.
```
