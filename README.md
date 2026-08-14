# Kaidala

A personal wiki — notes, plans, and build documentation, written as plain Markdown so it stays readable in an editor, on GitHub, or anywhere else.

Every page lives in a topic folder. Each folder has its own index, and this page is the top of the tree. The whole thing is also published as a website: **[dankanacharya.github.io/kaidala](https://dankanacharya.github.io/kaidala/)**.

---

## Contents

### [DIY projects](diy_projects/)

Plans and build notes for things made by hand — dimensions, cut lists, materials, and the mistakes worth avoiding.

- [Gokulashtami Mantapam](diy_projects/GokulashtamiMantapam.md) — 40" × 40" × 70" knock-down lattice mantapam with a 5 × 5 hook grid and bolt-off legs

---

## How this wiki is organised

```
.
├── README.md              ← you are here (wiki home)
├── diy_projects/
│   ├── README.md          ← section index
│   ├── images/            ← SVG drawings
│   └── *.md               ← one page per project
├── _config.yml            ← site build settings
├── _layouts/default.html  ← page shell: header, sidebar, footer
└── assets/css/            ← site styling
```

The `_config.yml`, `_layouts/` and `assets/` entries only exist to publish the
site. Nothing in them affects reading the Markdown directly.

**Conventions**

- One topic per file; one folder per subject area.
- Every folder gets a `README.md` index listing its pages with a one-line description.
- Link between pages with relative paths (`../diy_projects/Foo.md`) so links work on GitHub and in local editors alike.
- Start each page with an `# H1` title and a short paragraph saying what it is, before any detail.
- Prefer tables for anything with units — dimensions, quantities, costs.

**Adding a page**

1. Drop the `.md` file in the right topic folder (create the folder and its `README.md` if it's a new subject).
2. Add a line to that folder's index.
3. If it's a new topic folder, add it to the Contents list above.

---

## Licence

Content and files in this repository are licensed under the [GNU General Public License v3.0](LICENSE).
