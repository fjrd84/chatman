# Chatman: a botkit experiment

Minimal example of botkit for the web. All connections to botkit studio have been removed and it can work completely offline.

Embed a bot in any web page or app with Botkit for the Web.

Botkit Anywhere is a self-contained chat server, API and web-based messaging client that has been built on top of the industry leading Botkit development stack.

## How Chatman came to be

- `botkit` was installed globally, and then wizard was executed: 

```bash
npm install -g botkit
botkit new
```

- All connections to Botkit Studio were removed and a random fortune cookie response was added.

## Chat Server and API

Botkit Anywhere's built-in chat server can handle thousands of simultaneous one-on-one conversations with your users.
The chat server provides both a websocket and a webhook based interface for sending and receiving messages.
It is a great solution for including one-on-one chat in a web site or native app.

Additionally, Botkit Anywhere includes APIs for retrieving a user's conversation history,
and account-linking features that enable you to identify existing users to your bot.

* **[Chat Server Overview](docs/botkit_chat_server.md)**
* [Communicating with Websockets](docs/botkit_chat_server.md#using-websockets)
* [Communicating with Webhooks](docs/botkit_chat_server.md#using-webhooks)
* [How to enable message history API](docs/botkit_chat_server.md#enable-message-history)
* [Enable or Disable Learning Mode](docs/botkit_chat_server.md#learning-mode)

# Developer & Support Community

You can find full documentation for Botkit on our [GitHub page](https://github.com/howdyai/botkit/blob/master/readme.md). Botkit Studio users can access the [Botkit Studio Knowledge Base](https://botkit.groovehq.com/help_center) for help in managing their account.

# About Botkit

Botkit is a product of [Howdy](https://howdy.ai) and made in Austin, TX with the help of a worldwide community of botheads.
