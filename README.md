# Kaidala

A personal wiki — notes, plans, and build documentation, written as plain Markdown so it stays readable in an editor, on GitHub, or anywhere else.

Every page lives in a topic folder. Each folder has its own index, and this page is the top of the tree.

---

## Contents

### [DIY projects](diy_projects/)

Plans and build notes for things made by hand — dimensions, cut lists, materials, and the mistakes worth avoiding.

- [Gokulashtami Mantapam](diy_projects/GokulashtamiMantapam.md) — 40" × 40" × 70" knock-down lattice mantapam with a 5 × 5 hook grid and bolt-off legs
- [Mailbox Post](diy_projects/MailboxPost.md) — 31" × 64" solar-lit kerbside cedar mailbox post, built to the USPS height and setback rules

---

## How this wiki is organised

```
.
├── README.md              ← you are here (wiki home)
└── diy_projects/
    ├── README.md          ← section index
    └── *.md               ← one page per project
```

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
