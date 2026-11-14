# DAD 492: Programming for Sound Design (Spring 2027)

Course site built with Hugo, the [Console theme](https://github.com/DSU-Digital-Sound-Design/t-console-theme)
for course pages, and [reveal-hugo](https://github.com/dzello/reveal-hugo) for
lecture decks. Same setup as the Fall 2026 DAD 310 site.

```bash
git submodule update --init --recursive
hugo server
```

## Where things go

| What | Where |
|---|---|
| Day-by-day plan | `content/schedule.md` (`## 1/20` starts a class day; tags are set in `hugo.toml`) |
| Slide deck | `content/lectures/week-N/<name>/_index.md` |
| Lab handout | `content/lectures/week-N/<name>.md` |
| Starter patches (.pd) | `static/patches/`, linked with `{{< rel "patches/file.pd" >}}` |
| Projects | `content/assignments/*.md` (rendered by the theme's projects layout) |
| Resource links | `data/resources.yaml` |
| Syllabus | `content/syllabus.md`; put the signed PDF at `static/syllabus.pdf` |

New pages from templates (both start as drafts; remove `draft: true` to publish):

```bash
hugo new content lectures/week-2/messages-and-signals/_index.md --kind lectures
hugo new content lectures/week-2/utility-plugin.md --kind lab
```

When a deck or handout exists, link the matching schedule item to it.

## Still to fill in

- Meeting time, room, and office hours (`hugo.toml`, `content/syllabus.md`)
- Final exam time once the university schedule is out
- Signed syllabus PDF
- AI policy wording (marked TODO in the syllabus)
- Where portfolios are submitted (marked TODO in the portfolio page)
- Toolchain install steps for the current plugdata version (marked TODO in the week 1 setup page)

## Deploy

`.github/workflows/hugo.yml` builds and deploys to GitHub Pages on every push
to `main`, and rebuilds daily so the "this week" markers stay current.
