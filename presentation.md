Dotfiles for web developers

Note:
this is a note



How to use this presentation:
- Take away anything you find useful
- Interrupt if you have quesitons or corrections



What are dotfiles?

Note:
- In general:
- In specific: they are personal development environment configs



Why are dotfiles?

Note:
- Bring your environment with you
- Keep your environment organized



[ example ]

Note:
- show simple example



Oh my! Zsh!

Note:
- why is it better than bash?
  - what are some out of the box wins?  
    - Plugins



[ example ]



GNU and you

```
stow -t ~/ <config>
```

Note:

- why use gnu stow?
  - share configs across computers
  - save hours of time and lookups by reusing configs



[ example ]



I use vim, by the way

Note:

- great tings about vim
- complete ----------
- vim motions
- faster navigation
- easy macros
- maximum developer vibe
- <https://en.wikipedia.org/wiki/Vi_(text_editor)>
- <https://en.wikipedia.org/wiki/Vim_(text_editor)>
- Ironically it vi - does infact stand for "visual" text editor



#### Yes I also use Cursor / Kiro / VSCode



Okay But Why Is Vim So Great?



Vim Motions



[ example ]



Literally, customize anything



[ example ]



But Vim is Scary!



[ example ]



True, but it doesn't have to be.



By exenstion



[ example ]



<img src="/assets/lazyvim.png" style="margin: auto;"/>



LazyVim (is awesome)



Aliases

Note:

- what they are
- why they are cool
- example



[ example ]



Functions

Note:

- what they are
- parameters
- all the power of bash scripts!



[ example ]



Dotfiles in the age of Vide Coding



[ example ]



Choosing the right terminal 



<!-- iterm2 -->
<!---->
<!-- ##### pros: -->
<!-- - does what you need it to -->
<!-- - gui settings interface -->
<!-- - more features then you will ever use -->
<!---->
<!-- ##### cons: -->
<!-- - not gpu accelerated -> can feel slow for some tasks -->
<!-- - gui settings interface -->
<!-- - more features then you will ever use -->




[icon] iTerm2
```txt 
=> pros:
   - does what you need it to
   - gui settings interface
   - more features then you will ever use
=> cons:
   - not gpu accelerated -> can feel slow for some tasks
   - gui settings interface
   - more features then you will ever use
```



gpu accelerated terminals

<span style="color=blue;">kitty, alacritty, wezterm, ghostty </span>

```txt 
=> pros:
   - does what you need it to
   - gui settings interface
   - more features then you will ever use
=> cons:
   - not gpu accelerated -> can feel slow for some tasks
   - gui settings interface
   - more features then you will ever use
```

Note:
broadstrokes => pros:
          - gpu acceelrated = better performance
          - file based configs
          -
          cons:
          - not gpu accelerated -> can feel slow for some tasks
          - file based configs
          - more features then you will ever use



alarcitty
- no font ligatures :(



kitty
- unable to use ctrl+cmd+space emoji picker



ghostty
- no search in terminal buffer



WezTerm => my choice
- setting max_fps=240 makes actually feel really fast

cons: 
- tiny little gap around border specifically when running "jankyborders"



Extra Credit for mac:

- Keyboard Maestro
- Karabiner

Extra Credit for everyone (chromium):

- Vimium

Extra reading:

- [github dotfiles documentation](https://dotfiles.github.io/)
- [this presentation](github...)

Q & A:

Note:

this is a test :> [!WARNING]
>
