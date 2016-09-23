## Honukai theme and colors for Oh My ZSH and iTerm by [@oskar](https://twitter.com/oskar)

![](https://raw.githubusercontent.com/oskarkrawczyk/honukai-iterm/master/honukai.png)

[See how it looks with blur and transparency](https://v.usetapes.com/SDGzCBkHh4) (video).

## Installation

### Theme

The theme is based on the wonderfully made [ys](https://github.com/robbyrussell/oh-my-zsh/blob/master/themes/ys.zsh-theme) theme from the official [oh-my-zsh repo](https://github.com/robbyrussell/oh-my-zsh).

1. Drop [`honukai.zsh-theme`](https://raw.githubusercontent.com/oskarkrawczyk/honukai-iterm/master/honukai.zsh-theme) into the `~/.oh-my-zsh/themes/` directory
2. Change the theme variable name to `ZSH_THEME="honukai"` in `~/.zshrc`
3. Reload ZSH with `source ~/.zshrc`

### Colors

1. Open **Preferences** pane on the **Profiles** tab in iTerm
2. Switch to the **Colors** tab and import the [`honukai.itermcolors`](https://raw.githubusercontent.com/oskarkrawczyk/honukai-iterm/master/honukai.itermcolors) (drop-down in the lower right corner)

**NOTE**: You'll need at least iTerm2.9-nightly (aka 3.0)

### Extra eye-candy

There's a bunch of settings you might want to change in your profile in order to get the extra eye-candy.

#### **Text** tab:

**Cursor**

- Set to **Vertical**

**Font**

- Change to **[12pt Fira Mono Medium](https://github.com/mozilla/Fira/tree/master/ttf)** (I personally love the Fira font-face, and highly suggest using it)

**Text Rendering**

- Disable **Draw bold in bold font**
- Disable **Draw bold in bright colors**
- Enable **Draw anti-aliased text with thin strokes**

#### **Window** tab

**Window appearance**

- **Transparency** to **10-15%**
- **Blur** to **40-50%**
