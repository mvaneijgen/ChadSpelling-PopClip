# ChadSpelling

Send the selected text to [ChatGPT](https://openai.com/blog/chatgpt), and gets you three of the most likely spellings back.

It sends the folliwng prompt where `${input.text}` is the word you've selected.

> Spell check: "${input.text}". What is phonetically the most likely spellings? Only include words in the dictionary. Please give me three options, only include the answer in the response on one line with spaces in between, no punctuation.

This extention is based on [@pilotmoon ChatGPT.popclipextz](https://www.popclip.app/extensions/x/1g1Pz)

## Download
Go to [releases](https://github.com/mvaneijgen/ChadSpelling-PopClip/releases/) and download the latest released file `ChadSpelling.popclipext`.

## Description

The main action, **Chat**, sends the selected text to OpenAI's ChatGPT and
appends the response as a new line.

The **Reset** action (broom icon) clears the current chat history to start a
fresh conversation.

### Configuration

#### API Key

To use this extension, you need to provide it with an API Key for an OpenAI
account. To get an API Key:

1. Sign up for an OpenAI Account here: <https://platform.openai.com/>
2. Generate an API key here: <https://platform.openai.com/account/api-keys>
3. Copy and paste the API Key (it starts with `sk-`) into the _API Key_ field in
   the extension's settings.

#### Reset Timer (minutes)

After this many minutes without any messages, the extension will automatically
reset the conversation. Set it blank to never reset, and set it to 0 to always
reset. The default value is 15 minutes.

#### Show Reset Button

Control whether or not to show the reset action in the popup.

### Acknowledgements

Icons:

- "openai" by [Simple Icons](https://simpleicons.org/).
- "broom" by [GameIcons](https://game-icons.net/).

### Requirements

Requires PopClip 2022.12 and an Open AI Platform account.
