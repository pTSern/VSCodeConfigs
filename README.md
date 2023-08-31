<p align="center"><strong>VSCode Configuration</strong></p>
The configuration for the VSCode. 

## Table of contents
- [Extension](#Extension)
- [Install](#Install)

## Extension
- <details><summary> VIM </summary>
  <p>
    <h2 align="center"><img src="icons/vim.png" height="128"><br>VSCodeVim</h2>

    - Why vim?
        - Vim helps you code faster and do a lot of things without using the mouse.

    - Installation
       - [Market Link](https://marketplace.visualstudio.com/items?itemName=vscodevim.vim)
       - [GitHub](https://github.com/VSCodeVim/Vim)

    - My Vim settings

           "vim.statusBarColorControl": true,
           "vim.statusBarColors.normal": "#181818",
           "vim.statusBarColors.insert": "#181818",
           "vim.statusBarColors.visual": "#181818",
           "vim.statusBarColors.visualline": "#181818",
           "vim.statusBarColors.visualblock": "#181818",
           "vim.statusBarColors.replace": "#181818",
           "vim.statusBarColors.commandlineinprogress": "#181818",
           "vim.statusBarColors.searchinprogressmode": "#181818",
           "vim.statusBarColors.easymotionmode": "#181818",
           "vim.statusBarColors.easymotioninputmode": "#181818",
           "vim.statusBarColors.surroundinputmode": "#181818",
           "vim.enableNeovim": true,

           "vim.easymotion": true,
           "vim.incsearch": true,
           "vim.useSystemClipboard": true,
           "vim.useCtrlKeys": true,
           "vim.hlsearch": true,
           "vim.smartRelativeLine": true,

           "vim.insertModeKeyBindings": [
           ],
           "vim.normalModeKeyBindingsNonRecursive": [
             {
               "before": ["<leader>", "d"],
               "commands": [":bd"],
               "silent": true
             },
             {
               "before": ["<leader>", "w"],
               "commands": [":w"],
               "silent": true
             },
             {
               "before": ["<tab>"],
               "after": ["g", "t"],
               "silent": true
             },
             {
               "before": ["<leader>","<tab>"],
               "after": ["g", "T"],
               "silent": true
             },
             {
               "before": ["<C-q>"],
               "commands": [":nohl"]
             },
           ],
           "vim.leader": "<space>",
           "vim.handleKeys": {
             "<C-a>": false,
             "<C-f>": false
           },
</p>
</details>

## Install
- 
