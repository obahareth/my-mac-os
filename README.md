# my-mac-os

List of hardware, applications, and tools that make my macOS experience amazing, inspired by https://github.com/nikitavoloboev/my-mac-os (with shameless copy pasting (I hope that's ok 🙏🏼) where I couldn't find better wording).

![](https://imgur.com/uSP1cYN.png)
> Using [screenfetch](https://github.com/KittyKatt/screenFetch)

**Wallpaper: [Icy land beside Jökulsárlón Lake](https://unsplash.com/photos/FRYtAMzphLs)**

##### Contents

- [Hardware](#hardware)
- [Applications](#applications)
  - [Productivity](#productivity)
  - [Code](#code)
  - [Social](#social)
  - [Writing](#writing)
  - [Music](#music)
  - [Images](#images)
  - [Utilities](#utilities)
  - [Browsers](#browsers)
- [Command Line Apps](#command-line-apps)
- [Preference Panes](#preference-panes)
- [Similar Setups](#similar-setups)
- [Related](#related)
- [Contributing](#contributing)

## Hardware

Computer: 14" 2021 Macbook Pro with M1 Pro Chip.

Trackpad: [Apple Magic Trackpad 2](https://www.amazon.com/Apple-Magic-Trackpad-2-MJ2R2LL/dp/B016QO5YWC/ref=sr_1_3?ie=UTF8&qid=1538413611&sr=8-3&keywords=apple+magic+trackpad).

Monitor(s): [LG 34UC98-W](https://www.amazon.com/LG-34UC98-W-34-Inch-UltraWide-Thunderbolt/dp/B019O78DPS).

Keyboards:
- [NuPhy Halo75](https://nuphy.com/collections/keyboards/products/halo75) with Nightbreeze switches for work and programming.
- [Microsoft Universal Foldable Keyboard](https://www.amazon.com/Microsoft-Universal-Foldable-Keyboard-Android/dp/B00UBGU4PY) for typing on the go.
- [NyPhy Field75](https://nuphy.com/collections/keyboards/products/field75) with Fleeting Gold switches for gaming.

## Applications

I'm slowly transitioning to cross-platform software because I want to be able to use the majority of my apps on any OS.

### Productivity

#### [Raycast](https://www.raycast.com) - Launcher

- Raycast is both my launcher and entry point to lots of [awesome extensions](https://wiki.omar.engineer/apps-and-tools/raycast/extensions).
- It has a great community and [amazing extension store](https://www.raycast.com/store) that you can use.
- It's extremely easy to develop extensions for.
- I also made some [extensions](https://www.raycast.com/obahareth) and [scripts](https://github.com/obahareth/raycast-scripts) for it.

Here's a small example of me using it to quickly [run/evaluate Ruby](https://www.raycast.com/obahareth/ruby-evaluate) code:

![](https://i.imgur.com/L2KIaO7.gif)

#### [Paste](https://pasteapp.io) - Clipboard History

- Paste is a clipboard manager that can sync your clipboard history with your iOS devices.
- Available on Setapp (see below)

#### [TickTick](https://ticktick.com/) - All my Tasks in One Place

- TickTick helps me plan out everything I want to do either for the short term or long term (I'm not sure if I follow GTD)
- Tasks, habits (e.g. drink x liters of water), calendar, and reminders all in one app
- The one place I go to to answer the question "What do I have to do today?"
- Has apps on all platforms I use, and a great web app
- Really powerful calendar integration (works just like a standard calendar app) with quick links to join meetings
- It also has global quick add with a hotkey. Together with lists, priorities, powerful search and a lot more

  <img src="https://i.imgur.com/9Xeqsvy.png" width="400" alt="img">

#### [1Password](https://1password.com) - Password manager

- Generate all of my passwords with it and keep everything in a secured and encrypted vault kept secure by a master password and two factor authentication.
- No longer need to remember passwords and I now have a unique password for every website that I am signed up on whilst [activating two factor authentication](https://support.1password.com/one-time-passwords/) wherever possible.

#### [MindNode](https://mindnode.com) - Interactive Mind Mapping

- I write A LOT, too much actually, MindNode helps me write short summaries of my thoughts that I "connect the dots" (or lines) between.

#### [PDF Expert](https://pdfexpert.com/) - PDF reader/editor

- Super fast PDF viewer.
- Best experience for editing PDFs or filling PDF forms.

#### [Bartender](https://www.macbartender.com/) - Menu bar organizer

- Allows you to customize and hide the contents of your menu bar and improve the aesthetics of your OS. Here is how mine looks:
  <img src="https://i.imgur.com/GKjbmZJ.png" width="500" alt="img">
- Available on Setapp (see below)

#### [Magnet](http://magnet.crowdcafe.com/) - Organize your workspace

- Lets me use keyboard shortcuts (or more rarely, drag-drop to edges) to tile windows on my screen.
- Keyboard shortcuts to move windows across monitors.

#### [Little Snitch](https://www.obdev.at/products/littlesnitch/index.html) - Control incoming/outgoing network traffic

- Amazing networking tool that gives you a clear picture of what connections are incoming to your computer and what are outgoing.
- Takes a bit of time to set it up correctly and is quite an insightful experience first turning it on and having it notify every couple of seconds that some app is trying to send data to some server and whether you want to allow that.
- This is essential if you want to take control of what information gets sent out from your computer and what connections have right to connect to your data.

### Code

#### [Visual Studio Code](https://github.com/Microsoft/vscode) - Code editor

- My favorite editor that I use to write code in. I use [many extensions](https://wiki.omar.engineer/apps-and-tools/visual-studio-code/extensions) for it.
- I use the [Nord](https://marketplace.visualstudio.com/items?itemName=arcticicestudio.nord-visual-studio-code) theme, [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme) and the [Pragmata Pro](https://www.fsd.it/shop/fonts/pragmatapro/) font.

Here is how it looks:

![](https://imgur.com/4NQb6wu.png)

#### [Neovim](https://neovim.io/) - Powerful text editor

- Opening, editing, modifying, and searching through huge files.
- Go-to commandline text editor.
- I use [vim-plug](https://github.com/junegunn/vim-plug) to manage plugins.

#### [iTerm 2](https://iterm2.com/) - Terminal Emulator

- I use Fish as my shell together with [Fisher](https://github.com/jorgebucaran/fisher) to install [Fish plugins I use](https://wiki.omar.engineer/apps-and-tools/fish/plugins).
- You can find my dotfiles [here](https://github.com/obahareth/dotfiles).
- I use the [Starship prompt](https://github.com/starship/starship) and the [Nord theme](https://github.com/arcticicestudio/nord-iterm2).

![](https://i.imgur.com/nKiGYD1.png)

#### [Dash](https://kapeli.com/dash) - API Documentation Browser

- Allows you to download any docset that you might want to use, search for any method, class or anything that you need very quickly, comes with the amazing [Alfred workflow](https://www.alfredapp.com/blog/productivity/dash-quicker-api-documentation-search/) to simplify the process of searching for the right things.
- Available on Setapp (see below)


#### [Tower](https://www.git-tower.com) - Git client

- Great Git client that integrates well with GitHub, BitBucket, GitLab, and supports GitFlow.

If you'd like, you can use my [referral link](https://www.git-tower.com/p/refer-a-friend/R-TN7HH96L3E) and you'll get a 10% discount.

#### [Kaleidoscope](https://www.kaleidoscopeapp.com/) - Powerful diff tool

- Really great, precise, and beautiful diffing.
- Great at viewing/merging conflicts.
- Can do directory and image diffs as well.

### Social

#### [Textual](https://www.codeux.com/textual/) - IRC Client

- The best macOS IRC client I've found.

#### [Slack](https://slack.com) - Work chat

- Chatting for work.
- Collaborating with people on some open source projects and great communities.
- I use the [Nord theme for the sidebar](https://github.com/arcticicestudio/nord-slack) and also apply a [Nord stylesheet](https://github.com/tborychowski/slack-nord-theme) so everything looks Nord-ish.

It looks a bit like this (the screenshot is from the slack-nord-theme repo):

![](https://github.com/tborychowski/slack-nord-theme/raw/master/screen.png)


#### [Spark](https://sparkmailapp.com/) - Email client

- Fast.
- Great dark theme.
- I approach all of my email tasks in GTD style. Keeping my email Inbox close to 0 at all times.
- Smart grouping of new emails.
- Quickly take batch actions.

### Writing

#### [Day One](http://dayoneapp.com/) - Digital journal

- Day One is my digital life journal.
- If you don't journal, I suggest you to start, it is a very powerful mind cleanser and acts as a wonderful history record of your life.

#### [Typora](https://typora.io) - Smart WYSIWYG distraction-free markdown editor

- Smart WYSIWYG editor, no need for an editing and preview views like most markdown editors, it's just one view.
- Distraction-free markdown editor, I use it when I want absolute focus.
- Cross-platform.
- Beautiful [themes](http://theme.typora.io/), and even [one that supports RTL](http://theme.typora.io/theme/Middle-East/).
- I use it to edit [my wiki](https://wiki.omar.engineer).


#### [Notion](https://notion.so) - Large writing, scans, and web clips

It's very hard to describe exactly what Notion does, but it's basically a workspace for everything and I'm trying to move everything to it.

- I do my huge writing here.
- If I want to access a document from anywhere, I usually store it here.
- Personal project management.
- Managing lists of things I want to buy, sell, and games I want to play.
- I also use it to keep [a list of public Notion pages](https://www.notion.so/obahareth/Public-04ad2eb582a448b1ae834249d5ada9b9) with ideas I'm working on and more.

### Music

#### [YouTube Music](https://music.youtube.com/) - Music Streaming 2nd solution

- The only music app that has the most kind of songs I like (oldschool videogame music, videogame OSTs, anime OSTs, etc.)

### Images

#### [Google Photos](https://photos.google.com/) - Cloud storage for photos

- Easiest way to backup my photos and access them from multiple places.
- Machine learning, auto detects images.
- 😖 Kind of scary.

### Utilities

#### [Setapp](https://setapp.sjv.io/c/5258220/343321/5114) - One subscription that unlocks many paid apps for macOS and iOS
(This is an affiliate link)

- Has many great paid apps in one place, cheaper than individually buying/subscribing to all those apps.

If you'd like, you can use [my referral link](https://go.setapp.com/invite/cdjvafat) and we'll both get a free month.

#### [xScope](https://xscopeapp.com/) - Measure. Inspect. Test.

- A powerful set of tools for Mac OS X that are ideal for measuring, aligning and inspecting on-screen graphics and layouts.

#### [Dato](https://apps.apple.com/ca/app/dato/id1470584107) - Better clock/calendar widget for menubar

- More configurable than Apple's default widget.
- Has a great calendar popup that shows when you click date/time in the menubar. This is something I was really used to from Windows/Linux that I'm glad to have back again.
- Can show calendar events

#### [TablePlus](https://tableplus.com/) - Modern, Native Tool for Database Management

- Available for many platforms (Mac, Linux, Windows, and iOS so far).
- Part of Setapp.
- Supports many databases (MySQL, PostgreSQL, MongoDB, SQLite, Redis, Cassandra, and more).
- Intelligent autocomplete and great filtering utilities.
- Frequently updated and well-maintained.

#### [Insomnia](https://insomnia.rest/) - Great API tool

- Full-featured HTTP client that lets you test and describe the APIs you build or consume.
- Open source.
- Cross-platform.
- Themeable, I use the [Nord theme](https://github.com/xasx/insomnia-plugin-nord-theme) here as well.

### Browsers

#### [Google Chrome](https://www.google.com/chrome/)

- My main web browser because it easily syncs my extensions across machines.
- I use [these extensions](https://wiki.omar.engineer/apps-and-tools/google-chrome/extensions) and [this theme](https://wiki.omar.engineer/apps-and-tools/google-chrome/theme).

#### [Safari](https://www.apple.com/lae/safari/)

- Incredibly fast/lightweight web browser.
- Since I don't have extensions on it, I use it for when my Chrome extensions break sites.


## Command Line Apps

- [autojump](https://github.com/wting/autojump) - A cd command that learns, easily navigate directories from the command line.
- [asdf](https://github.com/asdf-vm/asdf) - One version manager for all my programming languages.
  - [elixir](https://github.com/asdf-vm/asdf-elixir)
  - [golang](https://github.com/kennyp/asdf-golang)
  - [java](https://github.com/skotchpine/asdf-java)
  - [nodejs](https://github.com/asdf-vm/asdf-nodejs)
  - [redis](https://github.com/smashedtoatoms/asdf-redis)
  - [ruby](https://github.com/asdf-vm/asdf-ruby)
  - [rust](https://github.com/code-lever/asdf-rust)
- [fzf](https://github.com/junegunn/fzf) - Command-line fuzzy finder.
- [colorls](https://github.com/athityakumar/colorls) - Beautify `ls` command with color and font-awesome icons.
- [bat](https://github.com/sharkdp/bat) - Cat clone with wings.
- [git](https://github.com/git/git) - Version control.
- [curl](https://curl.haxx.se/docs/manpage.html) - Transfer data from or to a server.
- [htop](https://github.com/hishamhm/htop) - Interactive text-mode process viewer for Unix systems.
- [httpie](https://github.com/jakubroztocil/httpie) - HTTP client.
- [curl](https://github.com/curl/curl) - Transfer data, supports various protocols.
- [howdoi](https://github.com/gleitz/howdoi) - Instant coding answers.
- [asciinema](https://github.com/asciinema/asciinema) - Terminal session recorder.
- [tldr](https://github.com/tldr-pages/tldr) - Simplified and community-driven man pages.
- [now](https://github.com/zeit/now-cli) - Real time global deployments served over HTTP/2.
- [yarn](https://github.com/yarnpkg/yarn) - Fast, reliable, and secure dependency management.
- [hub](https://github.com/github/hub) - GitHub wrapper.
- [fx](https://github.com/antonmedv/fx) - A great toolkit for interactively exploring, parsing, searching, exporting, and filtering JSON
- [xsv](https://github.com/BurntSushi/xsv) - Fast CSV command line toolkit written in Rust.

## Preference Panes

- [GPG Suite](https://gpgtools.org/) - Encrypt, decrypt, sign and verify files or messages.
  - I use this also for signing my commits.

## Similar Setups

Here you can find more setups by other people that you can take ideas and inspiration from.

- [The original `my-mac-os`](https://github.com/nikitavoloboev/my-mac-os) - The original repo that acted as inspiration for me to build this one.
- [Works for me](https://works-for-me.github.io/) - Collection of developer toolkits.
- [Use This Interviews](https://usesthis.com) - What do people use to get stuff done?

## Related

- [Awesome mac](https://github.com/jaywcjlove/awesome-mac#readme)
- [Interesting macOS apps](https://github.com/learn-anything/macos-apps#readme)
- [Open Source macOS apps](https://github.com/serhii-londar/open-source-mac-os-apps#readme)

## Contributing

If you shared a similar personal setup to this, be it for Windows, Linux or anything else, you can add it in [Similar Setups](#similar-setups) section.

I love finding new awesome tools and apps. If you have a favorite tool or app that you think I missed, please [say it](../../issues/new).
