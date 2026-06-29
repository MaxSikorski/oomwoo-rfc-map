# oomwoo · Contribution Map (unofficial prototype)

An interactive **"where do I start?"** map for the open-source robot-vacuum project
[**oomwoo**](https://github.com/makerspet/oomwoo). It turns the project's RFC dependency
graph into something you can click, so newcomers can instantly see which contribution
tracks are **ready to start today** versus which are still blocked.

## ▶️ Live demo

**https://maxsikorski.github.io/oomwoo-rfc-map/**

## What it does

- **Interactive dependency map** — click any track to highlight its prerequisites and
  everything it unblocks, with a link straight to that `contributions/<slug>/` folder.
- **"Ready to start now"** callout that surfaces the unblocked tracks.
- **Filterable table** of every module (by phase / category / "startable now").

## Notes

- It's a **single self-contained HTML file** — vanilla HTML/CSS/JS, no build step, no
  dependencies, no network calls. Open `index.html` by double-clicking, or host it
  anywhere static.
- **Unofficial & community-made** — not affiliated with or endorsed by the oomwoo
  maintainers. The data is parsed from `RFC_MASTER_LIST.md` and `assets/rfc-graph.mmd`;
  the [oomwoo repo](https://github.com/makerspet/oomwoo) is always the source of truth.

## Feedback / discussion

Proposed to the oomwoo team here →
**[oomwoo Discussions](https://github.com/makerspet/oomwoo/discussions)**
*(swap this for the direct thread link once the post is up).*

---

MIT-licensed — use it freely.
