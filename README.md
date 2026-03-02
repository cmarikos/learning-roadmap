# DS / ML / AI Learning Roadmap

My personal learning roadmap for leveling up in Data Science, Machine Learning, and AI, built as a GitHub Page I can check off as I go.

**Live page:** `https://cmarikos.github.io/learning-roadmap/`

---

## How it works

Each item has a **show criteria** button that expands a list of concrete things I need to be able to do or point to before I can check the box.

When I check an item off, I paste a link to the project folder in this repo where I did the work. That link shows up permanently next to the item as `→ view project`. Progress is saved in localStorage so it persists across visits.

At the bottom of the page there's an **export progress** button that downloads a JSON snapshot, and an **import progress** button to restore it on another browser or device.

---

## Repo structure

```
your-repo/
├── index.html          ← the roadmap / GitHub Page
├── README.md           
└── projects/
    ├── numpy-broadcasting/
    ├── pandas-sql-translation/
    └── ...
```

As I complete items I add a folder under `projects/` and link to it from the roadmap. The URL format for a folder is:

```
https://github.com/your-username/your-repo/tree/main/projects/folder-name
```

---

## Forking

Feel free to fork this and build your own version — I won't be approving PRs that add to the `projects/` folder here since those are my own project files.

After forking, enable GitHub Pages under **Settings → Pages → Deploy from branch → main → / (docs)** and you'll have your own live copy.

The roadmap content lives in the `phases` array at the top of the `<script>` block in `index.html` — each phase and item is straightforward to edit, add, or remove. The only rule is that every item needs a unique `id`.

---

## Stack

HTML/CSS/JS. Fonts from Google Fonts (DM Mono + Fraunces).
