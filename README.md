# .files

The config files can be found in their respective folders.

## Re-install

A couple of weeks ago I cleaned up (delete+reinstall) my Macbook. I didn't back-up anything as I comitted myself to finally switch to VSC after having used Atom + Hyper terminal with custom configs. However, due to not wanting to spend too much time on my setup after re-installing MacOS, I took a look at the dotfiles of @dandevri, because I trust his taste.

## Tools

### Visual Studio Code

> Visual Studio Code is a source code editor developed by Microsoft for Windows, Linux and macOS. It includes support for debugging, embedded Git control, syntax highlighting, intelligent code completion, snippets, and code refactoring. It is also customizable, so users can change the editor's theme, keyboard shortcuts, and preferences. It is free and open-source, although the official download is under a proprietary license.

[source](https://en.wikipedia.org/wiki/Visual_Studio_Code)

You can get it right over [here](https://code.visualstudio.com/docs/editor/command-line).

#### Theme
* Using the default theme
* Using the seti file icons

#### Plugins
* ```$ code --install-extension ms-vscode.atom-keybindings```
* ```$ code --install-extension EditorConfig.EditorConfig```
* ```$ code --install-extension shinnn.stylelint```
* ```$ code --install-extension eamodio.gitlens```
* ```$ code --install-extension Zignd.html-css-class-completion``` !!!
* ```$ code --install-extension akamud.vscode-javascript-snippet-pack```
* ```$ code --install-extension dbaeumer.vscode-eslint```

### Shell: oh-my-zsh framework for zsh

>Oh-My-Zsh is an open source, community-driven framework for managing your ZSH configuration. It comes bundled with a ton of helpful functions, helpers, plugins, themes, and a few things that make you shout...

Install

```$ sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"```

#### Plugins
* [Trash](https://github.com/sindresorhus/trash-cli)

>In contrast to rm which is dangerous and permanently delete files, this only moves them to the trash, which is much safer and reversible. I would also recommend reading my guide on safeguarding rm.

  ```$ npm install --global trash-cli```

* [Z](https://github.com/rupa/z/blob/master/z.sh)

>Tracks your most used directories, based on 'frecency'.
>
>After  a  short  learning  phase, z will take you to the most 'frecent' directory that matches ALL of the regexes given on the command line, in order.
>
>For example, z foo bar would match /foo/bar but not /bar/foo.
