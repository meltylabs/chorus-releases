## 0.9.0
_2025-05-27_

### Introducing Chorus Projects, a new way of managing shared context across chats. 

![CleanShot 2025-05-27 at 19 57 47@2x](https://github.com/user-attachments/assets/22f74a2d-a89d-4f74-9046-6201b1dd6236)

You can add text and attachments to a project's editor. Anything you add to a project is share across chats in that project.

We've also added a new tool called Magic Context. When Magic Context is on, Chorus takes key information from your chats and *automatically* adds it to that project's context.

![CleanShot 2025-05-27 at 20 10 57@2x](https://github.com/user-attachments/assets/a65859be-303e-434e-9502-d46d20320b7c)
![CleanShot 2025-05-27 at 20 17 40@2x](https://github.com/user-attachments/assets/f1f8b434-b836-42c6-88c4-d7ce6b34fd49)

![CleanShot 2025-05-27 at 20 16 39@2x](https://github.com/user-attachments/assets/3e991f3a-f712-4582-ad80-0f6a9c0004bb)


## 0.8.10
_2025-05-22_

![CleanShot 2025-05-22 at 10 36 38@2x](https://github.com/user-attachments/assets/499a36af-0484-42b4-b32b-ca1bfafc6884)

We've added Claude 4 Sonnet and Opus.

## 0.8.9
_2025-05-22_

Fix a bug that caused strange behavior from delete chat dialogs, attachment preview dialogs, and message fullscreen dialogs

## 0.8.8
_2025-05-20_

- We've added information about what [data we collect](http://docs.chorus.sh/privacy)
- Tab now works in form fields
- Only one dialog can be open at once
- Top bar no longer goes across sidebar
- Chats with tool calls can now be branched
- Reviews now regenerate when you regenerate a response
- Mermaid theme works in light/dark mode
- Model picker now remembers if you clicked "show OpenRouter models"

## 0.8.7
_2025-05-19_

We've added a new GitHub connection so you can manage repos, code, issues, and PRs from Chorus.

![CleanShot 2025-05-19 at 19 59 47@2x](https://github.com/user-attachments/assets/d1f6437f-cce3-446b-ab14-36c5f84e33aa)

We've also added LaTeX rendering in compare mode and fixed a rendering bug in default mode.

![CleanShot 2025-05-19 at 20 02 01@2x](https://github.com/user-attachments/assets/3114d8e5-72e3-482c-9e9d-5aaae595e0a8)



## 0.8.6
_2025-05-17_

![CleanShot 2025-05-17 at 18 14 23@2x](https://github.com/user-attachments/assets/d7108a7a-9806-4fb7-ad82-d8235d819c63)

- Branch chats now have an icon and a link to their parent
- Fixed chat re-ordering when you unpin or rename
- Buttons are now rounded
- Copy button in connections now copies full command
- Models are now searchable by provider name
- Add settings button to sidebar

## 0.8.5
_2025-05-14_

- You can have now only one blank new chat at time
- New onboarding video
- "Add" models in compare mode now persist

## 0.8.4
_2025-05-13_

- Much improved Ambient Chat custom keybindings recorder
- Tool execution errors now show up in the UI
- Fixed crash that can happen on dialogs


## 0.8.3

_2025-05-12_

Fixed bug that can cause images to silently fail

## 0.8.2

- Bug fixes affecting reviews and synthesis
- The Image Generator tools are now more reliable in rendering the images
- Messages are now slightly wider

## 0.8.1

Fix a permissions issue that disabled all models

## 0.8.0

### New default mode + tab to think harder

- There's a new default mode (formerly "Connections") where Chorus can access tools and MCP servers
- In default mode, you can press `Tab` to run a more powerful model on the same prompt

We've also added two new connections: Image Generator, which is powered by `gpt-image-1`, and Coder, which writes and edits source code files.

![CleanShot 2025-05-12 at 11 14 12@2x](https://github.com/user-attachments/assets/c306256c-24f1-42a0-86d1-93be6c152031)

![CleanShot 2025-05-12 at 11 14 48@2x](https://github.com/user-attachments/assets/1304e3fe-c3a4-44ff-b2a8-da473cd205db)

![CleanShot 2025-05-12 at 11 14 28@2x](https://github.com/user-attachments/assets/5539a854-784d-4737-8821-91dba5992c38)



## 0.7.27

![CleanShot 2025-05-09 at 10 33 31@2x](https://github.com/user-attachments/assets/1d9f9430-67ed-4d21-b918-4c7c2ab7d4fd)

We've overhauled the connections tab to make it easier to add MCPs and see their status. 

## 0.7.26

![CleanShot 2025-05-08 at 10 29 44@2x](https://github.com/user-attachments/assets/d73e9c5d-ac2e-487e-ab1c-49467061330e)

Improved thinking blocks and fixed a reviewer bug.

## 0.7.24
_2025-05-07_
![CleanShot 2025-05-07 at 09 56 35@2x](https://github.com/user-attachments/assets/a1188011-8dbd-4449-80b9-3562829de577)


We updated Gemini 2.5 Pro to the [latest version](https://blog.google/products/gemini/gemini-2-5-pro-updates/) and fixed a re-render bug that happens during sign in.


## 0.7.23
_2025-05-06_

**Whoops, we broke updating**

If you have Chorus 0.7.21 or 0.7.22, please manually update to 0.7.23 by [downloading Chorus again](https://app.chorus.sh/download) and replacing the old version. 

![DragChorus](https://github.com/user-attachments/assets/7e2a1cca-1d66-4f14-b11d-c7b22546c0c6)

Sorry about this. Once you're on 0.7.23, updates will work again.

> Curious how we messed this up? Our `package.json` and `Cargo.toml` had different versions of the Tauri updater. We got them out of sync during a merge conflict. 


## 0.7.22
_2025-05-05_

![CleanShot 2025-05-05 at 17 27 06@2x](https://github.com/user-attachments/assets/fdb47169-b7f1-4ce8-9748-775491a9b79d)

Import your MCPs from Claude in one click.

## 0.7.21
_2025-05-03_

### Introducing Connections!

![CleanShot 2025-05-03 at 14 58 03@2x](https://github.com/user-attachments/assets/08db5e91-dd18-4dac-a273-7aa1ebb1e6c4)



Chorus can now search the web, use your terminal, and run any MCP server.
 
## 0.7.19
_2025-05-01_

- Added o4-mini as reviewer
- Improved delete chat flow
- UI tweaks on share chat modal


## 0.7.18
_2025-05-01_

Fixed bug that can cause app to crash if reviewers are on and you're using your own API keys

## 0.7.17
_2025-04-29_

![CleanShot 2025-04-29 at 20 41 14@2x](https://github.com/user-attachments/assets/f8679151-6b82-431d-bdee-cde7c1484a60)


- Added Mac menubar shortcut for Ambient Chat
- Fixed crash loop if you're on waitlist
- Bugfix for Claude image support

## 0.7.16
_2025-04-24_

- Fixed menu bar.
- Reduced new update available toast from every 30 seconds to every 5 minutes

## 0.7.14
_2025-04-23_

![CleanShot 2025-04-23 at 19 27 12@2x](https://github.com/user-attachments/assets/891de85b-ac53-4bac-adb8-e7a5384539ee)

We improved the CMD+K search.

## 0.7.13
_2025-04-18_

![CleanShot 2025-04-18 at 16 34 34@2x](https://github.com/user-attachments/assets/9eb7ccbe-782b-468b-ac7b-b0748d10719c)

Added web search to o3 and o4-mini, and fixed their markdown rendering.

## 0.7.12
_2025-04-17_

We added Gemini 2.5 Flash Preview, a new lightweight model from Google.

## 0.7.11
_2025-04-15_

<img width="819" alt="image" src="https://github.com/user-attachments/assets/1292956a-ade7-485b-a692-e9920b040890" />

We added o3 and o4-mini, new reasoning models from OpenAI.

## 0.7.10
_2025-04-14_

![CleanShot 2025-04-14 at 10 39 42@2x](https://github.com/user-attachments/assets/57ed81ee-5baf-4f89-b3bb-023fec1ef966)

We added GPT-4.1, OpenAI's new flagship model, and GPT-4.1 Mini. Both come with web search enabled by default.

## 0.7.9
_2025-04-13_

Bugfixes.

## 0.7.8
_2025-04-12_

![CleanShot 2025-04-12 at 16 03 16@2x](https://github.com/user-attachments/assets/3086add4-0a7c-4edc-a157-0478c795bd08)

You can now refresh summaries. Also, some bugfixes.

## 0.7.7
_2025-04-08_

![CleanShot 2025-04-09 at 16 37 53@2x](https://github.com/user-attachments/assets/c573534c-d1b7-4508-b83d-80ecd16e84c6)

We added the Grok 3 models.

## 0.7.6 
_2025-04-08_

Fixes broken upgrade button

## 0.7.5
_2025-04-07_

Features

- Option to make the enter key insert a new line (cmd+enter to submit) in Settings -> Appearance

Fixes

- Bring Grok, OpenRouter, and DeepSeek models up to compatibility with latest version of the Chorus server
- Fix a bug where entering special characters in the command menu crashes the app
- Remove the nonfunctional "Reply to selection" button (for now)

## 0.7.4
_2025-04-06_

- Set Gemini 2.5 Pro to the default chat and Ambient Chat model
  
## 0.7.3
_2025-04-05_

- Choose your own Ambient Chat model
- Add vision capabilities to Llama 4 models
- Fix bug that causes chats with old reviewers to crash

## 0.7.2
_2025-04-05_

![CleanShot 2025-04-05 at 14 28 53@2x](https://github.com/user-attachments/assets/282edc05-3f48-4def-bdeb-fc3a9ecb575a)

You can now branch chats, and edit messages. Click any human message to edit it.

We've also added Llama 4 Scout and Maverick.

New
- Branch conversations
- Edit user messages
- Llama 4 Scout and Maverick
- Gemini 2.5 is now a reviewer (and no longer experimental)
- Drag target on top of chat window
- ⌘G / ⌘+Shift+G for next / previous in find in chat

Fixes
- View local models again
- Scroll to bottom on new chat
- Chat spacing
- Google models no longer complain about empty text parameters

## 0.7.1
_2025-04-02_
![CleanShot 2025-04-03 at 15 07 36@2x](https://github.com/user-attachments/assets/c60b7c41-8d64-49db-8fa8-3c32ebeba2f7)

We've simplified our [pricing](https://chorus.sh/pricing), and overhauled the model picker to separate models into fast, plus, and frontier. 

All users now have unlimited access to "fast" models, gpt-4o-mini and Gemini Flash 2.0. 

Tweaks
- Added a hover state for sidebar buttons
- Aligned buttons in chat input
- Indicator to show if you're using your own API keys

Fixes

- Ambient chats no longer cost 3 requests per message


## 0.7.0

_2025-04-01_

<img width="1206" alt="image" src="https://github.com/user-attachments/assets/33f3916a-5ad2-446c-8f19-7709419a7f62" />

New features:

- Find in chat
- Summarize chat (pictured above)
- Spinner in sidebar indicates which chats have messages that are streaming

Big improvements under the hood, including:

- Seamlessly switch between chats
- Long chats are faster, thanks to incremental loading

Other improvements:

- In chat mode, sending a message will stop any previous messages that are still streaming
- The pin button in the sidebar is moved to avoid cutting off chat names
- Message drafts now autosave
- Chorus no longer generates reviews for messages that you send while reviews are hidden. When reviews are shown, you can add them by clicking "Generate reviews".

Removed: reply to selection, model reordering in compare mode.

## 0.6.14
_2025-03-25_

![CleanShot 2025-03-25 at 20 39 28@2x](https://github.com/user-attachments/assets/154e15b8-96c1-4679-8334-d895a1542aad)

We've added support for [Gemini 2.5 Pro Experimental](https://blog.google/technology/google-deepmind/gemini-model-thinking-updates-march-2025/#gemini-2-5-pro), Google's most advanced model.


## 0.6.13
_2025-03-24_

<img width="849" alt="image" src="https://github.com/user-attachments/assets/736febe0-3eae-4d94-aa1c-74770152c1ab" />

- Horizontal scroll for model pills in Compare mode
- Fix Ambient Chat text overlap
- Fixed image resizing bug
- Dark mode UI tweaks


## 0.6.12
_2025-03-20_

![CleanShot 2025-03-20 at 16 29 51@2x](https://github.com/user-attachments/assets/2a6177df-7e7f-40c2-896a-67cc63460809)

We've added support for o1-pro, OpenAI's most powerful model.

## 0.6.11 
_2025-03-20_

Add syntax highlight support for more langauges and fixed a bug that can cause app to crash.

## 0.6.10
_2025-03-19_

![CleanShot 2025-03-19 at 15 18 59@2x](https://github.com/user-attachments/assets/82c2ab9a-9f11-4cce-9a33-31230b750b68)

We've added a new brainstorm mode. We've also made it easier to switch between "compare mode" (previously called "legacy mode") and regular chatting.

Improvements
- The model list on the prompts page is now sorted alphabetically. Also, to make it more searchable, we removed OpenRouter models from that list.
- Faster code rendering
- Faster model streaming
- Reduced the message font size slightly

Fixes
- Fixed an issue where messages with code blocks in Ambient chat would be wider than the window
- Fixed an issue where the "CMD+L to focus" text was sometimes unreadable

## 0.6.8
_2025-03-15_

![CleanShot 2025-03-15 at 17 35 43@2x](https://github.com/user-attachments/assets/e9e235e6-d85e-4c70-a427-943075905336)

We've added web search for GPT 4o. 

- Faster PDF uploads for OpenAI models (we switched to using the Responses API)
- Potential MacOS 13.0+ compatability (thanks Roman!)
- Free tier usage reduced to 50 Chorus requests for new users 

Fixes
- Fixed a bug where submitting while an attachment was loading would cause the input to clear
- Ensure space at bottom for reading last message when text input is full


## 0.6.7
_2025-03-12_

![CleanShot 2025-03-12 at 20 02 26@2x](https://github.com/user-attachments/assets/ab0cefa5-967d-4c24-a1d9-49519e77a9bc)

![CleanShot 2025-03-12 at 20 04 44@2x](https://github.com/user-attachments/assets/904508e8-9d0b-4593-bf74-58427ce13d37)


You can now undo, regenerate, and hide reviews. They also look a bit nicer now.

- Fixed stroke width for @TheXeophon
- Modals blur background
- UI touch-ups


## 0.6.6
_2025-03-11_

![CleanShot 2025-03-11 at 19 50 40@2x](https://github.com/user-attachments/assets/7ef2e8d6-596f-415a-a161-53d5157fd0c8)

Chorus is now more beautiful! We've updated the UI to be a lot more consistent and pretty. 

## 0.6.5
_2025-03-08_

- You can now use GPT-4.5 through your own OpenAI API key

## 0.6.4
_2025-03-07_

- GPT-4.5 Preview is now Pro user only
- Improved permissions flow during onboarding
- Site now makes it clear how to download for Silicon vs. Intel Mac
- Added [Windows waitlist](https://forms.gle/ogL63pTWVKV8DAVXA)
- Re-ordering suggested models 

## 0.6.3
_2025-03-06_

![CleanShot 2025-03-06 at 20 00 22@2x](https://github.com/user-attachments/assets/cbf285d2-8ca5-4682-bcce-0a9cab0440a6)


We've added Perplexity's R1, Sonar Reasoning Pro, and Sonar Deep Research. And fixed lots of bugs.

Fixes
- Update Ambient Chat permissions request during onboarding
- Fix code block rendering in Ambient Chat
- Change add -> select in model picker
- Update the reviewer order
- Don't show update dialog in Ambient Chat window
- Make opening Ambient Chats less weird
- Less bold markdown headers


## 0.6.2
_2025-03-05_

<img width="959" alt="image" src="https://github.com/user-attachments/assets/97e0e4b8-e44d-4cab-8d75-a1e88641205a" />

We've added Perplexity Sonar Pro as a reviewer, and added support for PDFs for GPT-4o and GPT-4.5.

Other fixes:
- Agreement is more subtle
- We now ask for screen sharing permissions in onboarding if you want to use vision mode

## 0.6.1
_2025-03-03_

Bug fixes

## 0.6.0
_2025-03-03_

![PHOTO-2025-03-03-11-02-55](https://github.com/user-attachments/assets/ecedd76f-dbc3-47ef-b58c-d8490a8f6af1)

Introducing Reviews! 

AIs now review each other&rsquo;s messages for accuracy and clarity. Only one AI responds at a time.

If you prefer to see responses side-by-side, you can turn on Legacy Mode in settings.

## 0.5.36
_2025-02-27_

![CleanShot 2025-02-27 at 13 34 19@2x](https://github.com/user-attachments/assets/a26a3d82-1e3f-4df3-98c8-069b5236f9c5)

GPT-4.5 Preview and o3-mini-high are now live in Chorus.

![CleanShot 2025-02-27 at 13 35 04@2x](https://github.com/user-attachments/assets/abb6554d-a8e7-47d3-a372-002cdb1e7f0c)

We've also added a highlight to reply tooltip.

## 0.5.35
_2025-02-26_

![CleanShot 2025-02-26 at 20 35 21@2x](https://github.com/user-attachments/assets/c73a5d56-b0c3-4f58-afae-13b3e2092c15)

Ambient chat now works on 2 monitor setups, and views whatever screen it is open on. It's also more obvious :)

- Image resizing and uploading is now 10x faster
- Add toggle for URL auto-scraping
- Fix MELTY_PLACEHOLDER bug

## 0.5.34
_2025-02-25_

- Clean up the settings page
- ⁠Fix a bug where the scroll-to-bottom button would appear in Ambient Chat
- ⁠Add review mode (experimental)

## 0.5.33
_2025-02-24_

![CleanShot 2025-02-24 at 13 46 43@2x](https://github.com/user-attachments/assets/5325e45f-f96e-4653-962c-544dfe22e80e)

Show Claude's thinking tokens.

## 0.5.32
_2025-02-24_

![CleanShot 2025-02-24 at 12 57 24@2x](https://github.com/user-attachments/assets/15ceaf97-2616-4ff1-8894-0f364ebcfa61)


Claude 3.7 is live!

## 0.5.31
_2025-02-23_

Fix broken synthesis.

## 0.5.30
_2025-02-22_

- Allow skipping the ambient chat step in onboarding
- Markdown rendering fixes

## 0.5.29
_2025-02-21_

Lots of clean up!*
- Improve code blocks performance
- Fix Claude cache-control issue
- Widen responses
- Less fade on secondary responses
- Remove max height on messages
- Remove delete button
- Remove double scroll bars and hidden scroll bars
- New chats are faster to load

*(Fix some of Fred and Michael's problems)

## 0.5.28
_2025-02-18_

![CleanShot 2025-02-18 at 18 25 29@2x](https://github.com/user-attachments/assets/94a62efd-32d1-4cb6-9734-ec22928fbe37)

Support for OpenRouter model image attachments. 

- Settings moved to `Chorus` section on menu bar
- Address an occasional issue where enter would not cause a message to submit

## 0.5.27
_2025-02-17_

![CleanShot 2025-02-17 at 18 21 15@2x](https://github.com/user-attachments/assets/e13283a5-7d2f-450e-a352-386a7bd7c03c)

- Show time to first token and approximate tokens/sec (we're using the 4o tokenizer right now)
- Ambient chat takes precedence over full screen apps

## 0.5.26
_2025-02-17_

- Fix sidebar button
- Show auth pop-up if you're not logged in

## 0.5.25
_2025-02-15_

![CleanShot 2025-02-15 at 19 09 07@2x](https://github.com/user-attachments/assets/301db189-61f3-4ed0-9fe0-4f22b71c9cc2)

- Synthesis is easier to toggle
- Added a max height for non primary messages
- Fixed Ambient Chat not working in onboarding
- Automatic images resizing
- Improved error messages



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
