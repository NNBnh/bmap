<h1 align="center">Bmap</h1>
<p align="center">SuperB Keymap System</p>
<p align="center">
  <a href="https://github.com/NNBnh/bmap/blob/main/LICENSE"><img src="https://img.shields.io/github/license/NNBnh/bmap?labelColor=585858&color=F7CA88&style=for-the-badge" alt="License: GPL-3.0"></a>
  <a href="https://gist.github.com/NNBnh/9ef453aba3efce26046e0d3119dab5a7#development-completed"><img src="https://img.shields.io/github/last-commit/NNBnh/bmap?labelColor=585858&color=FFC387&style=for-the-badge" alt="Work in progress"></a>
</p>

## 💡 About

**Bmap** is a universal keymap system design for almost all applications and even games. By define each key on the keyboard with a meanings, the applications can map there own set of shortcuts/actions to fit those meanings.

<br>

### 📔 Story

_#TODO_

<br>

### ✨ Features

_#TODO_

<!--
- Familiarity: The design is taking from standard keymap from many popular applications, there for it's:
  - Easy to get used to.
  - Many GUI applications have already roughly follow this keymap system.
- Ergonomic:
  - Have left-handed variant.
-->

<br><br>

## 📒 Design

Here is the full design where each keys is define with a meaning:

<p align="center"><img src="https://user-images.githubusercontent.com/43980777/148636068-9fdcd829-30d4-4c2b-928d-84c140178a67.png"></p>
<p align="center"><a href="http://www.keyboard-layout-editor.com/#/gists/99f29c7a0a3c4bceab6afa28003b5987">KLE file</a></p>

<br>

### 🔰 Basic

#### 🚥 Mods

These key don't do anything by itself, but it can be combined with each other and other key to alter the meaning.

<p align="center"><img src="https://user-images.githubusercontent.com/43980777/148636069-315df6d9-f1ac-4e63-b134-6ed9451097ec.png"></p>

- Shift: Do something stronger, wider of do in reverse.
- Control: Do something more focus, more specific or with more control.
- Mod: Do something but differently, with small change or do in alternative meta.
- System: Do systemwide operation.

<br>

#### 🧰 Functions

<p align="center"><img src="https://user-images.githubusercontent.com/43980777/148636499-f38cd30c-c34f-4b56-a145-59d1c6adee63.png"></p>

Further explanation:
- Area: Switch tabs, open panel, expand drawing area, toggle GUI.
- Advance: Open advance/pipe menu, jump (in game).

<br><br>

### ❤️ Core

_#TODO_

<br>

#### 🔄 Movement

<p align="center"><img src="https://user-images.githubusercontent.com/43980777/148636070-6f1a9db4-d0fe-49f1-8d84-bd54c2799a21.png"></p>

<br>

#### 🅰️ Action

_#TODO_

<p align="center"><img src="https://user-images.githubusercontent.com/43980777/148636071-73b2fc38-57ea-4d5d-ac33-ca8800dcf68a.png"></p>

<br><br>

### 🧩 Extra

#### 🐎 ZXCV

Four famous standard keys appear on literally every application.

<p align="center"><img src="https://user-images.githubusercontent.com/43980777/148636072-c54d8359-221f-4f4f-84a8-f9650c1ecee4.png"></p>

Further explanation:
- Time: Undo/redo, timeline operation, open history, running (in game).
- Cut: Delete (but also copy), close.
- In: Copy, interac to get/set something from the environment (e.g: get items, talk to NPC, toggle zoom).
- Out: Paste, interac to give/put something from the environment (e.g: fire special weapon).

<br>

#### 📃 Modern standard

Standard from modern productivity tools and editors.

<p align="center"><img src="https://user-images.githubusercontent.com/43980777/148636508-7a90e045-b164-4668-8d2c-c33da7da806a.png"></p>

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

<p align="center"><img src="https://user-images.githubusercontent.com/43980777/148636076-ef52e6b8-6a26-4088-a82f-9341dba36a2c.png"></p>

Further explanation:
- Assign: Select a register.
- Command: Open command prompt.

<br>

#### 🎮 Gaming standard

<p align="center"><img src="https://user-images.githubusercontent.com/43980777/148636077-94ad73d2-b30c-4905-9455-2ce0ab63d396.png"></p>

Further explanation:
- Focus: Crawl, stealthily, change operating range.
- Self: Flip selection cursor and anchor, do something to/about self, taunt.
- Cycle: Rotate main selection, cycle through items, switch item.
- Item: Rotate selection contents, open inventory.

Reason:
- Focus: _#TODO_
- Self: _#TODO_
- Cycle: _#TODO_
- Item: _#TODO_

<br>

#### 🎲 Other

<p align="center"><img src="https://user-images.githubusercontent.com/43980777/148636078-199e2ad5-cca1-4925-9ffc-f6929398cf68.png"></p>

Further explanation:
- Local: Do something in close range.
- Movement: Jump (in text editor), quick teleport, open map.

<br><br>

## 🚀 Implements

We are currently focus on heavy keyboard usage productivity applications, specifically [text editor](http://www.keyboard-layout-editor.com/#/gists/e12289897003889ee40f5628e31975ca) (WIP).

<br><br>

## 💌 Credits

Special thanks to:
- [**Keybinding design blogs**](http://xahlee.info/kbd/keybinding_index.html) by [Xah Lee](http://xahlee.info/index.html)
- [**Ergoemacs-mode**](https://ergoemacs.github.io) by [Xah Lee, David Capello, Kin Storm, Walter Landry and Matthew Fidler](https://github.com/ergoemacs/ergoemacs-mode/graphs/contributors)
- [**Vim keymap**](https://www.vim.org) by [Bram Moolenaar](https://en.wikipedia.org/wiki/Bram_Moolenaar)
- [**Kakoune keymap**](https://kakoune.org) by [Maxime Coste](https://github.com/mawww)
- [**Helix keymap**](https://helix-editor.com) by [Blaž Hrastnik](https://github.com/archseer)
- [**Pepper keymap**](https://github.com/vamolessa/pepper) by [Matheus Lessa](https://github.com/vamolessa)

<br><br><br><br>

---

> <h1 align="center">Made with ❤️ by <a href="https://github.com/NNBnh"><i>NNB</i></a></h1>
>
> <p align="center"><a href="https://www.buymeacoffee.com/nnbnh"><img src="https://img.shields.io/badge/buy_me_a_coffee%20-%23F7CA88.svg?logo=buy-me-a-coffee&logoColor=333333&style=for-the-badge" alt="Buy Me a Coffee"></a></p>
