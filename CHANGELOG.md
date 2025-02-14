## 0.5.24
_2025-02-13_

![CleanShot 2025-02-13 at 18 58 51@2x](https://github.com/user-attachments/assets/0134a276-7527-4c14-913b-6270d1eea796)

Redesigned, more intuitive chat flow. 

- Messages that are part of the conversation now shift to the left
- Synthesize button moved to left
- You can now add any model to a response
- LM Studio base URL is customizable (Settings -> API Keys)

Let us know if the new flow is a regression in any way! We love your feedback :) 
founders@melty.sh

## 0.5.23

_2025-02-12_

Onboarding tweaks.

## 0.5.22

_2025-02-11_

![CleanShot 2025-02-11 at 19 55 57@2x](https://github.com/user-attachments/assets/5a453c11-b5f8-4dec-ae80-d38a25b80edf)

Ollama models can now handle text files and web urls.

## 0.5.21

_2025-02-11_

![CleanShot 2025-02-11 at 17 43 27@2x](https://github.com/user-attachments/assets/87732975-5149-4df1-bc67-b0505138456f)

- Ambient chats have their own folder in sidebar
- Better error handling
- Updated onboarding to include vision mode


## 0.5.20

_2025-02-10_

- Fix an issue affecting chat titles and sharing

## 0.5.19

_2025-02-08_

![CleanShot 2025-02-08 at 14 31 24@2x](https://github.com/user-attachments/assets/128f2f38-8263-4b09-a65c-60564e2a3e32)

- Stop / Regenerate buttons
- ⁠Re-open Chorus by clicking dock icon (fix CMD+W bug)
- Taller code blocks
- Improved update dialog


## 0.5.18

_2025-02-07_

- Hotfix: home screen crashing bug

## 0.5.16

_2025-02-07_

- Ambient Chat shortcut is now configurable
- Fixed Gemini + OpenRouter failing if you used your own API keys
- Ambient Chat polishing (background changes on focus, easier to drag)

## 0.5.15

_2025-02-05_

- Add eye animation to Ambient Chat
- Fix a bug that causes vision mode to overflow context window after a few messages
- Fix misc bugs in Ambient Chat
- Add Ambient Claude custom prompt:
```
Respond concisely. Use one or two sentences if possible.

If the user has vision mode enabled, whenever they send a message, the system will automatically attach a screenshot showing the current state of their computer screen. Use these screenshots as needed to help answer the user's questions. There's no need to describe the screenshot or comment on it except insofar as it relates to the user's question.
```

## 0.5.14

_2025-02-05_

![CleanShot 2025-02-05 at 13 47 48@2x](https://github.com/user-attachments/assets/8ff6a41a-6188-4563-bb8e-f9bdd7184cf8)

[New models from Gemini](https://developers.googleblog.com/en/gemini-2-family-expands/), and optimized image uploads for faster vision mode.

## 0.5.13

_2025-02-04_

![CleanShot 2025-02-04 at 21 01 48@2x](https://github.com/user-attachments/assets/b5745af4-c900-4b5a-9149-ba19e40f57ea)

Ambient chats can now see your screen while in vision mode. Toggle with `⌘I`. 

- Fixed Sonar Perplexity citations not rendering
- Rename quick chat to ambient chat

## 0.5.12


_2025-02-03_

![CleanShot 2025-02-03 at 17 47 04@2x](https://github.com/user-attachments/assets/abce5767-db40-4877-820e-fc931ff3928a)

You can now share chats! Click `share` or press  `⌘⇧S` to generate a private shareable link to your chat.

## 0.5.11

_2025-02-01_

![CleanShot 2025-02-01 at 18 43 58@2x](https://github.com/user-attachments/assets/506bae1d-4590-4615-bb06-e8e02e2ab2c7)

Chorus can now run terminal commands for you! 

Fixes:
- Image uploads now look nicer
- Fixed a synthesis bug

## 0.5.10

_2025-02-01_

![CleanShot 2025-02-01 at 13 39 13@2x](https://github.com/user-attachments/assets/996d8cdb-bb61-4435-94a8-1c0cdd144190)

Quick chat improvements:
- You can now change quick chat model from the quick chat window (no need to go to settings)
- Changing the model happens live (no need to make a new quick chat to try the new model)
- Shortcut for changing the model

Other fixes:
- Sidebar button appears when sidebar is closed
- Home screen page is now draggable


## 0.5.9

_2025-01-31_

<img width="673" alt="image" src="https://github.com/user-attachments/assets/9f35bb01-c846-4500-befe-b5c55bd5e37f" />

- Render `<think>` tags as collapsible for reasoning models from DeepSeek and Ollama.
- o1 and o3-mini are now better at markdown
- Allow for users to choose whether we convert long pasted text into file attachments
- Add option to view raw output

## 0.5.8

_2025-01-31_

![CleanShot 2025-01-31 at 11 44 13@2x](https://github.com/user-attachments/assets/84116afb-9732-4da1-b4a7-2d7a7b3c5023)


- Fixed a bunch of jank. Scrolling is smooth, and new chats start faster
- Added o3-mini
- Quick chat max size is larger


## 0.5.7

_2025-01-30_

- New onboarding flow
- Make quick chat window resizable
- Quick chat window follows theme
- If main window is hidden and quick chat is initiated, don't show main window
- Better OpenRouter errors

## 0.5.6

_2025-01-29_

![quickchat](https://github.com/user-attachments/assets/6ea3a783-f883-4b92-addf-7f123672263f)

Quick chat with any model, anywhere on your Mac. Activate by pressing Alt+Space. 

- Max width on expanded messages
- Add status badge for pro users


## 0.5.5

_2025-01-28_

![CleanShot 2025-01-28 at 20 24 06@2x](https://github.com/user-attachments/assets/4a416c81-4250-44af-9e46-63dccf118c6f)

We've added Deepseek and Groq as providers. 

- Expand message view
- Moved copy message button to top of message

## 0.5.4

_2025-01-27_

- ⁠Users now get 100 free AI messages through Chorus (plus unlimited messages through API keys).
- “Selected” messages are now called “included” messages
- Fix [object Object] showing up in code blocks
- ⁠Fix up search behavior in the new model picker
- ⁠Fix a bug where synthesis would display alongside original responses

## 0.5.3

_2025-01-24_

<img width="596" alt="image" src="https://github.com/user-attachments/assets/e0bff906-4b5d-4438-ae64-2e483e6a14ce" />

We made the model picker better, and added a new shortcut — open it with ⌘J in a chat.

Fixes
- Model pills wrapping weirdly on smaller screens
- New tooltip that explains which messages are in context
- Rename 'Talk to a human' to 'Feedback'
- Design tweaks


## 0.5.2

_2025-01-23_

![CleanShot 2025-01-23 at 18 38 06@2x](https://github.com/user-attachments/assets/dfbfe78e-f800-4fe9-9b83-eb1b0f6e2dbf)

Anthropic models now support citations, and we've added the two latest models from Perplexity, Sonar and Sonar Pro.

Features:
- Citations
- Sonar + Sonar Pro
- You can now use any model as a base prompt for a custom prompt

## 0.5.1

_2025-01-21_

![CleanShot 2025-01-21 at 17 29 16@2x](https://github.com/user-attachments/assets/076320d2-18a2-407d-a02a-8cb202b5993b)

Code blocks now have syntax highlighting. 

Features:
- Syntax highlighting
- Copy user message button

Fixes:
- Add model button is now a plus sign
- Model picker now always opens upwards

## 0.5.0

_2025-01-20_

![CleanShot 2025-01-20 at 18 59 32@2x](https://github.com/user-attachments/assets/a94431d2-581a-4fb9-9d4c-43645b23349a)

You can now synthesize chat responses! Try it with ⌘S.

Features:
- Synthesize responses
-⁠ ⁠New onboarding flow
- Company logos in model picker

Fixes:
- ⁠Our mailserver is back up -- if the "Talk to human" button didn't work for you, please give it one more shot!
- ⁠New model additions always add to the right side of the screen


## 0.4.5

_2025-01-19_

Restores chat title generation.

(Chat title generation on versions <= 0.4.4 is deactivated since 2025-01-19 2:20 P.M. PST so that we can rotate API keys.)

## 0.4.4

_2025-01-17_

![CleanShot 2025-01-17 at 11 18 49@2x](https://github.com/user-attachments/assets/afa99ce1-e248-48ac-87c4-fc7a1cd002bb)


Features:

- Renders [GitHub-Flavored Markdown](https://github.github.com/gfm/), including tables
- Add a "recommended" section in the model picker

Bug fixes

- Fixed: issue preventing some users from attaching webpages
- Fixed: switch chats while messages are streaming
- Fixed: click dock icon to open the app when it's been quit
- Fixed: delete old messages

## 0.4.3

_2025-01-16_

Bug fixes:

- OpenRouter models are back online
- Fix "Attachment is not a webpage" error
- Improvements to URL handling on paste
- Add "Talk to a human" button

## 0.4.2

_2025-01-16_

- Paste a URL to attach it to a message
- Model selection once again persists across chats

Bugs

- Fixed an issue with dragging models

## 0.4.1

_2025-01-14_

- Autoscroll!
- New delete message button
- New max width on messages
- Attachments look better
- Sleeker updating flow

Bugs

- Fixed scroll jankiness on streaming
- Code block rendering

## 0.4.0

_2025-01-13_

![CleanShot 2025-01-13 at 14 47 02@2x](https://github.com/user-attachments/assets/b574f526-e537-4001-a0ce-7f13fc3025c4)

- New model selection interface
- Better attachment support, including text attachments
- Models page is renamed to Prompts page
- Fixed API keys not saving

## 0.3.32

_2025-01-09_

![CleanShot 2025-01-09 at 08 38 53@2x](https://github.com/user-attachments/assets/7fc0193d-fd49-4395-97d5-3379119bf3e8)

- Intel Mac support
- Partial LaTeX support
- Styling improvements
- Make home page alert dismissible

Bugs

- Fixed copy/paste weirdness
- More reliable update server
- Fix switching chat jankiness
- Don't override ctrl+k on Mac
- Scrollbar color on dark mode

## 0.3.31

_2025-01-07_

<img width="221" alt="image" src="https://github.com/user-attachments/assets/174a3457-e736-4279-88de-2f0bce4c597f" />

- Adding options to select all messages (or none!)
- Bug fixes

---

## 0.3.30

_2025-01-05_

Button to load more OpenRouter models

---

## 0.3.29

_2025-01-05_

![CleanShot 2025-01-09 at 08 19 34@2x](https://github.com/user-attachments/assets/25fe4a18-6535-4674-b509-14cfa399587e)

- OpenRouter support. Run any model on OpenRouter, including DeepSeek and Grok. Bring your own API key, or use our proxy.
- Paste in image support. If you copy and image to your clipboard, you can now paste it into Chorus.

Bug fixes

- Chat titles generate again
- Chats are now deletable again

---

## 0.3.28

_2025-01-04_

![CleanShot 2025-01-06 at 11 17 00@2x](https://github.com/user-attachments/assets/eb932c59-e939-4134-b480-abc2b144de64)

- Image support for GPT 4o and Claude
- PDF support (with caching) for Claude
- Full width chat on wide screens
- Option to set LM Studio local network URL
- Faster rendering (React fixes)

---

## 0.3.27

_2025-01-02_

Fix bugs

---

## 0.3.26

_2025-01-02_

- Fix React mistake that was causing slowness on typing
- Optional sign-in

---

## 0.3.25

_2025-01-01_

Fixed some weirdness with markdown rendering

---

## 0.3.24

_2024-12-31_

![CleanShot 2025-01-06 at 11 16 05@2x](https://github.com/user-attachments/assets/3256b11a-bc4f-4246-b7f0-9b935f6250dd)

Features

- Added Perplexity and [Gemini Flash Thinking](https://simonwillison.net/2024/Dec/19/gemini-thinking-mode/)
- Added link preiews for Wikipedia links
- Improed title generation

Bugs

- Fixed O1 not rendering bug
- Added note about enabling CORS for LM Studio models
- Fixed code block rendering
- Allow for selection of parts of an answer

---

## 0.3.23

_2024-12-30_

![CleanShot 2025-01-06 at 11 17 21@2x](https://github.com/user-attachments/assets/1520e440-f6be-4804-9601-43bf8949a01b)

You can now run local models! Download [Ollama](https://ollama.com) or [LM Studio](https://lmstudio.ai) (or both) and go to the /models page (cmd+shift+m) to try it out.

---

## 0.3.22

_2024-12-30_

Add bring your own API key option

---

## 0.3.20

_2024-12-29_

Fixed O1

---

## 0.3.19

_2024-12-29_

Tweaks

---

## 0.3.18

_2024-12-29_

Updated styling, proxy

---

## 0.3.16

_2024-12-29_

Home page tweaks

---

## 0.3.15

_2024-12-28_

Settings page styling updates

---

## 0.3.14

_2024-12-28_

Redirect to / on chat deletion

---

## 0.3.13

_2024-12-28_

- Graph view
- Add a new model after generations
- CMD+L to focus on textarea
- Empty states

---

## 0.3.11

_2024-12-27_

Updater fixed

---

## 0.3.9

_2024-12-27_

CMD+index shortcut to select

---

## 0.3.8

_2024-12-27_

Tweaks

---

## 0.3.7

_2024-12-26_

New data model, UI improements

---

## 0.3.6

_2024-12-24_

Chorus is updated! Check the changelog for details.

---

## 0.3.3

_2024-12-24_

Renamed to Chorus, design updates.

---

## 0.3.2

_2024-12-22_

Fix new model bug.

---

## 0.2.18

_2024-12-20_

Multichat experiment

---

## 0.3.1

_2024-12-21_

Fix gemini

---

## 0.3.0

_2024-12-21_

Multi chats!

---

## 0.2.17

_2024-12-11_

Makeover!
