<div align="center">
  <sub><b>You are here:</b> <a href="#readme">Home</a> > 📄 README.md</sub>
  
  <br>
  <h1>Okay Jarvis, how do I...</h1>

  <p>
    <i>A collection of "I spent 4 hours figuring this out so you don't have to" guides.</i>
  </p>

  <p>
    <img src="https://img.shields.io/badge/Open-Source-brightgreen?style=for-the-badge&logo=dependabot" alt="Status" />
    <img src="https://img.shields.io/badge/PRs-welcome-blue?style=for-the-badge&logo=github" alt="PRs Welcome" />
    <img src="https://img.shields.io/badge/license-MIT-purple?style=for-the-badge" alt="License" />
  </p>
</div>

<hr>

> *"Very well. Initializing setup protocols and bypassing the three hours of AI copy-pasta you were about to do."* — J.A.R.V.I.S. (probably)

Welcome to my personal brain dump of development setups, quirky IDE integrations, and small curiosity projects! If you've ever thought, *'I just want to quickly test [X] in [Y] without breaking my entire system,'*, a beginner just trying to get your foot into the door or want to play around with interesting ideas you are in the right place. I try to keep most of these guides as readable and beginner friendly as possible, but I can't promise : )

## Some of my favorite guides 

Below are some of my favorite guides, or guides I would've thought to be the most useful while fooling around. I tried structuring 
guides into a natural ordering under their topics (such as ASM, C++, CLion, WSL), but if you want to quickly search something, 
you can always check my portfolio site where all guides are indexed and searchable.

| Protocol / Guide | Description | Tech Stack | Updated |                                                                                                                                       Tags                                                                                                                                       |
| :--- | :--- | :---: | :---: |:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|
| [**Assemble in CLion**](./assembly/guides/clion-nasm.md) | How to set up CLion to play around with NASM assembly without losing your mind. | `CLion` `NASM` | 29/04/2026 |                                       ![](https://img.shields.io/badge/ASM-blue?style=for-the-badge) ![](https://img.shields.io/badge/CLion-blue?style=for-the-badge) ![](https://img.shields.io/badge/Setup-orange?style=for-the-badge)     <img src="https://img.shields.io/badge/Beginner_Friendly-pink?style=for-the-badge" alt="tag:Beginner Friendly" /> |
| [**CLion Meets WSL**](./wsl/guides/clion-wsl-setup.md) | Native Linux builds in CLion without leaving Windows — the painless WSL setup. | `CLion` `WSL2` | 29/04/2026 | ![](https://img.shields.io/badge/WSL-green?style=for-the-badge) ![](https://img.shields.io/badge/CLion-blue?style=for-the-badge) ![](https://img.shields.io/badge/Setup-orange?style=for-the-badge) ![](https://img.shields.io/badge/Beginner_Friendly-pink?style=for-the-badge) |

## How to Use This Repo

1. **Find your guide**
2. **Follow the steps.** I try to keep them as copy-paste-friendly and straightforward as possible.
3. **Enjoy the time you saved!** Use it to grab a coffee, learn something new, or build a shiny metal suit.

## Contributions

Did you spend an entire Sunday figuring out a hyper-specific setup that the internet seems to have completely forgotten about, did you go down some rabbit hole and have come to an interesting conclusion or have some cool discovery? Feel free to add it to the archives! 

1. Fork the repo.
2. Create a new `.md` file in the appropriate topic directory (e.g. `wsl/guides/your-guide.md`).
3. Use the standard guide header — copy the block below, fill in the breadcrumb, title, JARVIS quote, metadata line, and tags. The `<!-- tags:start -->` / `<!-- tags:end -->` markers are how my portfolio site finds and parses tags, so **don't remove or rename them**.
```html
<div align="center">
  <sub><b>You are here:</b> <a href="../../README.md#readme">Home</a> > your > path > here </sub>

  <br>
  <h1>Your Guide Title</h1>

  <p>
    <i>One-line tagline for the guide.</i>
  </p>

  <p>
    <img src="https://img.shields.io/badge/Open-Source-brightgreen?style=for-the-badge&logo=dependabot" alt="Status" />
    <img src="https://img.shields.io/badge/PRs-welcome-blue?style=for-the-badge&logo=github" alt="PRs Welcome" />
    <img src="https://img.shields.io/badge/license-MIT-purple?style=for-the-badge" alt="License" />
  </p>

  <!-- tags:start -->
  <p>
    <img src="https://img.shields.io/badge/YourTopic-color?style=for-the-badge" alt="tag:YourTopic" />
    <img src="https://img.shields.io/badge/Setup-orange?style=for-the-badge" alt="tag:Setup" />
  </p>
  <!-- tags:end -->
</div>

<hr>

> *"Your JARVIS quote here."* — J.A.R.V.I.S. (probably)

*Author: Your Name · Last updated: DD/MM/YYYY · Verified against: Tool x.y.z*
```
4. Submit a Pull Request.

### Metadata & tag conventions (so the parser is happy)

- **Metadata line** — single italic line directly under the JARVIS quote, in this exact format:
  `*Author: Name · Last updated: DD/MM/YYYY · Verified against: Tool x.y.z*`. Use middle dots (`·`) as separators. The `Verified against` field is the tool/IDE/language version you actually tested against; leave it off only if there's nothing version-specific in the guide.
- **Tag block** — every tag is a [shields.io](https://shields.io) badge inside the `<!-- tags:start -->` / `<!-- tags:end -->` markers. The parser reads the `alt="tag:X"` attribute, so **always prefix the alt text with `tag:`**.
- **Tag color palette** (reuse before inventing — consistency keeps the index column readable):
  - `WSL` → green
  - `ASM` → blue
  - `CLion` → blue
  - `Setup` → orange
  - `Beginner Friendly` → pink
- **Hide from the portfolio index** — add `<img src="https://img.shields.io/badge/no--index-lightgrey?style=for-the-badge" alt="tag:no-index" />` to the tag block. The badge stays visible on GitHub but the parser skips the guide.

For indexed guides, credits will be attributed. Currently, guides using MDX and similar aren't being parsed, though I might add that in the future :) 

---
<div align="center">
  <b>Created with ☕ and curiosity by <a href="https://github.com/Tund101HD">@Tund101HD</a></b>
</div>
