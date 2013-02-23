# what can brown dotfiles do for you?

## dotfiles (for zsh)

This is my dotfile collection. I use these whenever I'm setting up a new mac and I want to feel at home as quickly as possible - so that I can be productive as quickly as possible. I've gone through several macs in the past two years so I'm finding this to be an indispensible tool kit.

I forked these dotfiles from https://github.com/holman/dotfiles and it's a wonderful starting point.

## zsh

Note: These dotfiles are compatible with <code>zsh</code>. I'm a newcomer to the dotfile community and until recently I had no idea there were different shells avaialable for Terminal. Terminal defaults to <code>bash</code> (what's bash anyway? Why do I care?). Turns out there's another shell called <code>zsh</code>. I only found this out because after installing these dotfiles, they didn't work as documented. After a bit of research I learned that you need to make sure your terminal app (there is another one avaialble for the mac called iTerm2 which I'll talk about next) is using zsh instead of the default bash. Holman's bootstrap script doesn't switch the shell for you, and there may be a good reason why not, but I've modified the bootstrap script to include this command so I don't have to think about it.

## iTerm2

Even though I've forked this repo from Holman's dotfiles, I have made some of my own customizations that you should be aware of. I've recently switched from using the default Terminal app to using iTerm2. I can't say there's a lot of difference, and I'm not even sure which I like best yet but it's what I'm using at the moment. As such, my dotfiles include some iterm color preferences under the <code>iterm2</code> folder. There's a script that activates the theme file so it will be avaialble for use in iterm.

## install

Clone this repo to your home directory and run the boostrap script:

<pre>
git clone git@github.com:colynb/dotfiles.git ~/.dotfiles
cd ~/.dotfiles
script/bootstrap
</pre>