# Arthur Augusto · KitsuneSemCalda

I build tools for Linux and software development, from keyboard hardware support to desktop applications and testing libraries. My interests include systems programming, Linux internals, and experimental tooling.

*Lost the tail, kept the curiosity.*

## Selected projects

| Project | What I built | Explore |
|---|---|---|
| [Dareu EK75 + OpenRGB](https://github.com/KitsuneSemCalda/Dareu-EK75-OpenRGB-Compat) | Keyboard lighting support over USB and a wireless receiver, with protocol research and tests that run without the hardware. | [Protocol notes](https://github.com/KitsuneSemCalda/Dareu-EK75-OpenRGB-Compat/blob/master/docs/RESEARCH.md) |
| [Feader RSS](https://github.com/KitsuneSemCalda/Feader-RSS) | An RSS reader for Omarchy with a Go backend, SQLite storage, full-text search, and backup/restore. | [Screenshots and installation](https://github.com/KitsuneSemCalda/Feader-RSS#readme) |
| [Cest](https://github.com/KitsuneSemCalda/Cest) | A header-only testing framework for C and related languages, also used by the Dareu controller tests. | [Quick start](https://github.com/KitsuneSemCalda/Cest#quick-start) |

## Around my desktop

- [iae](https://github.com/KitsuneSemCalda/iae): editor, coding agent, shell, and git in a tmux workspace that adapts to terminal size.
- [Sword Art Omarchy](https://github.com/KitsuneSemCalda/omarchy-sword-art-theme): an Omarchy theme inspired by Aincrad, with screenshots and installation instructions.
- [Dotfiles](https://github.com/KitsuneSemCalda/Dotfiles): my Linux and Windows setup, tested installers, and a library of coding-agent skills.

<details>
<summary>A little about me, in code</summary>

```golang
package main

import (
    "fmt"
    "curiosity"
    "linux"
    "tooling"
)

type Kitsune struct {
    Name   string
    Alias  string
    Focus  []string
    Mantra string
}

func main() {
    me := Kitsune{
        Name:   "Arthur Augusto",
        Alias:  "KitsuneSemCalda",
        Focus:  []string{"Kernels", "Linux Internals", "Experimental Tooling"},
        Mantra: "lost the tail, kept the curiosity",
    }

    fmt.Println(me.Introduce())
}
```

```c
#include "cest.h"

describe("KitsuneSemCalda", {

    it("lost its tail, kept its curiosity", {
        expect(Cest).toBeA("header-only C testing framework");
        expect(ghCleaner).toBeA("Go CLI for GitHub cleanup");
    });

    it("explores systems deeply", {
        expect(linux).toBeInfinite();
        expect(kernel).toBe(endlesslyFascinating);
    });
});
```

</details>

<details>
<summary>GitHub statistics</summary>

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=KitsuneSemCalda&show_icons=true&hide_border=true&bg_color=00000000&text_color=c3d6dd&icon_color=4f8dff&title_color=3ee8ff" width="410" alt="GitHub activity statistics">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=KitsuneSemCalda&layout=compact&hide_border=true&bg_color=00000000&text_color=c3d6dd&title_color=3ee8ff" width="330" alt="Languages across my GitHub repositories">
</div>

---

### ⭐ Most Starred

<!-- TOP_STARS:START -->
| Project | Lang | Description |
|---|---|---|
| [**omarchy-sword-art-theme**](https://github.com/KitsuneSemCalda/omarchy-sword-art-theme) | Python | An Omarchy theme inspired by Season 1 of Sword Art Online — carbon-black Aincrad system windows with a cyan 'Link Start' glow |
| [**Cest**](https://github.com/KitsuneSemCalda/Cest) | Objective-C | Header-only testing framework for C, C++, Objective-C, and Objective-C++, with expressive assertions and test hooks. |
| [**gh-cleaner**](https://github.com/KitsuneSemCalda/gh-cleaner) | Go | Interactive Go CLI to review and delete GitHub repositories, with dry-run mode and Bayesian ranking from local decisions. |
| [**iae**](https://github.com/KitsuneSemCalda/iae) | Shell | Tmux-based agentic-dev TUI for Omarchy Linux — editor, agent, shell, and git/logs panes in one script |
| [**Feader-RSS**](https://github.com/KitsuneSemCalda/Feader-RSS) | Go | An Omarchy plugin to read RSS offline, with local caching, full-text search, and OPML support. |
<!-- TOP_STARS:END -->

</details>

### 🤝 Selected merged contributions

A selection of my pull requests merged into other repositories.

| Project | Contribution | Merged PR |
|---|---|---|
| [Akita's blog](https://github.com/akitaonrails/akitaonrails.github.io) | YouTube shortcode. | [#3](https://github.com/akitaonrails/akitaonrails.github.io/pull/3) |
| [GoAnime](https://github.com/alvarorichard/GoAnime) | Anime sorting for fuzzy search. | [#46](https://github.com/alvarorichard/GoAnime/pull/46) |
| [arrays](https://github.com/w1tchCrafter/arrays) | `forEach` behavior aligned with the MDN documentation. | [#8](https://github.com/w1tchCrafter/arrays/pull/8) |
| [freebsd_desktop](https://github.com/mbnunes/freebsd_desktop) | WindowMaker applications. | [#4](https://github.com/mbnunes/freebsd_desktop/pull/4) |
| [Barium](https://github.com/VitorCarvalho67/Barium) | Camera-based mouse control with OpenCV. | [#24](https://github.com/VitorCarvalho67/Barium/pull/24) |

---

<div align="center">
  <a href="https://foxtechworld.github.io"><code>foxtechworld.github.io</code></a>
  <span>&nbsp;·&nbsp;</span>
  <a href="https://discord.gg/WTMr49Nfp5"><code>discord</code></a>
  <span>&nbsp;·&nbsp;</span>
  <a href="https://github.com/KitsuneSemCalda"><code>github/KitsuneSemCalda</code></a>
</div>
