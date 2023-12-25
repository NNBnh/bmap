<p align="center"><img width="25%" src="https://user-images.githubusercontent.com/43980777/165583487-a739cd64-7def-43c2-8268-fbe683d2efb1.png"></p>
<p align="center">SuperB Keymap System</p>

## 💡 About

**Bmap** is a universal keymap system design for almost all applications and even games. By define each key on the keyboard with a meanings, the applications can map there own set of shortcuts/actions to fit those meanings.

<br>

<!--

### 📔 Story

_#TODO_ Video

<br>

-->

### ✨ Features

- Familiarity: The design is taking from standard keymap from many popular applications, there for it's:
  - Easy to learn and get used to.
  - Many GUI applications have already roughly follow this keymap system.
- Ergonomic:
  - It keep your hand on home position (unlike WASD and HJKL that shift all your finger to the left 1 key)
  - Have left-handed variant (swap variant).

<br><br>

## 📒 Design

Here is the full design where each keys is define with a meaning:

<p align="center"><img src="https://user-images.githubusercontent.com/43980777/165561508-1b1a59a7-8d96-4f31-a2e5-a7e2eca00076.png"></p>
<p align="center"><a href="http://www.keyboard-layout-editor.com/#/gists/99f29c7a0a3c4bceab6afa28003b5987">KLE file</a></p>

<br>

### 🔰 Basic

#### 🚥 Mods

These key don't do anything by itself, but it can be combined with each other and other key to alter the meaning.

<p align="center"><img src="https://user-images.githubusercontent.com/43980777/165455782-ccd8ea72-341f-4322-ac76-c35624c799d2.png"></p>

- Shift: Do something stronger, wider of do in reverse.
- Control: Do something more focus, more specific or with more control.
- Mod: Do something but differently, with small change or do in alternative meta.
- System: Do systemwide operation.

<br>

#### 🧰 Functions

<p align="center"><img src="https://user-images.githubusercontent.com/43980777/165456038-954c1c9b-50a0-4feb-ae08-89ebaa3aa38a.png"></p>

Further explanation:
- Area: Switch tabs, open panel, expand drawing area, toggle GUI.
- Advance: Open advance/pipe menu, jump (in game).

<br><br>

### ❤️ Core

Bmap have two keymap groups, one for movement and one for action. These are all used frequently and deserve to be place on the most easy to reach and comfortable to press positions:

<br>

#### ↔️ Movement

<p align="center"><img src="https://user-images.githubusercontent.com/43980777/165456922-ace83a36-bf02-476b-907c-522784c911fb.png"></p>


<br>

#### 🅰️ Action

<p align="center"><img src="https://user-images.githubusercontent.com/43980777/165456978-c4701e3e-1251-40f5-a1de-0199b0baf3df.png"></p>

<br>

#### 🔀 Swap variant

Depend on the application, user preference or if you are left handed, you could use this variant.

<p align="center"><img src="https://user-images.githubusercontent.com/43980777/165561282-384fce38-3b4c-47d9-9919-4223cfb49a97.png"></p>

<br><br>

### 🧩 Extra

#### 🐎 ZXCV

Four famous standard keys appear on literally every application.

<p align="center"><img src="https://user-images.githubusercontent.com/43980777/165457045-8c2988b3-c7ad-44da-928a-550034af214a.png"></p>

Further explanation:
- Time: Undo/redo, timeline operation, open history, running (in game).
- Cut: Delete (but also copy), close.
- In: Copy, interac to get/set something from the environment (e.g: get items, talk to NPC, toggle zoom).
- Out: Paste, interac to give/put something from the environment (e.g: fire special weapon).

<br>

#### 📃 Modern standard

Standard from modern productivity tools and editors.

<p align="center"><img src="https://user-images.githubusercontent.com/43980777/165457095-85db9258-3d53-42a6-82a7-487c51639645.png"></p>

Further explanation:
- Target: Jump to next/previous target.
- Play: Play/pause something, print out.
- Previous/Next: Changes selected items to next/previous value.
- Code: Comment, code format.

Reason:
- Target: In many tools: press <kbd>Ctrl</kbd>+<kbd>F</kbd> to "Find", press <kbd>Ctrl</kbd>+<kbd>H</kbd> to "Find and Replace". But because we have already use <kbd>F</kbd> so we will use <kbd>H</kbd> to target.
- Code:
  - <kbd>Ctrl</kbd>+<kbd>/</kbd> often be use to comment lines in many code editor.
  - <kbd>/</kbd> often be use to open console commands in some games.

<br>

#### 📜 classic standard

Standard from [`vi` editor](https://en.wikipedia.org/wiki/Vi).

<p align="center"><img src="https://user-images.githubusercontent.com/43980777/165457161-c067d129-1754-4785-adb7-4289d9f4da3c.png"></p>

Further explanation:
- Assign: Select a register.
- Command: Open command prompt.

<br>

#### 🎮 Gaming standard

These keymap are based on popular game genres keymaps with [ESDF mod](http://use-esdf.org) in mind (every keys are shift to the right 1 key).

<p align="center"><img src="https://user-images.githubusercontent.com/43980777/165457965-958da757-4ec4-4491-89a8-d6924bc57c21.png"></p>

Further explanation:
- Focus: Crawl, stealthily, change operating range.
- Self: Flip selection cursor and anchor, do something to/about self.
- Item: Rotate main selection, cycle through items, switch item.
- Communicated: Talk/chat (with team), ping, taunt.

<br>

#### 🎲 Other

<p align="center"><img src="https://user-images.githubusercontent.com/43980777/165457300-22588ecf-5dcc-47d8-904a-41e54e682b55.png"></p>

Further explanation:
- Local: Do something in close range.
- Movement: Jump (in text editor), quick teleport, open map.

<br><br>

## 🚀 Implements

We are focus on heavy keyboard usage productivity applications, specifically [text editor](http://www.keyboard-layout-editor.com/#/gists/e12289897003889ee40f5628e31975ca).

<br><br>

## 💌 Credits

Special thanks to:
- [**Keybinding design blogs**](http://xahlee.info/kbd/keybinding_index.html) by [Xah Lee](http://xahlee.info/index.html)
- [**Ergoemacs-mode**](https://ergoemacs.github.io) by [Xah Lee, David Capello, Kin Storm, Walter Landry and Matthew Fidler](https://github.com/ergoemacs/ergoemacs-mode/graphs/contributors)
- [**Vim keymap**](https://www.vim.org) by [Bram Moolenaar](https://en.wikipedia.org/wiki/Bram_Moolenaar)
- [**Kakoune keymap**](https://kakoune.org) by [Maxime Coste](https://github.com/mawww)
- [**Helix keymap**](https://helix-editor.com) by [Blaž Hrastnik](https://github.com/archseer)
- [**Pepper keymap**](https://github.com/vamolessa/pepper) by [Matheus Lessa](https://github.com/vamolessa)


<a href="https://nnb.codeberg.page">
  <img
    width="100%"
    src="https://capsule-render.vercel.app/api?type=waving&section=footer&color=0284C7&fontColor=F0F9FF&height=128&desc=Made%20with%20%26lt;3%20by%20NNB&descAlignY=80"
    alt="Made with <3 by NNB"
  />
</a>
