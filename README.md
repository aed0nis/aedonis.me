# Deviant Games

This site serves as a digital home for my tabletop creations, one-shot adventures, and community projects.  

---

## 🕹️ About

**Deviant Games** is a space for:
- Sharing original TTRPG one-shots and homebrew content  
- Hosting information about community games and ongoing campaigns  
- Offering downloadable materials such as PDFs, player handouts, and GM resources  
- Showcasing design work and world-building projects

---

## ⚙️ Tech Stack

- **Static Site Generator:** [Jekyll](https://jekyllrb.com/)  
- **Theme Base:** Minimal Mistakes (heavily customized)  
- **Language:** HTML, Markdown, Liquid, SCSS  
- **Deployment:** GitHub Pages  
- **Design:** Custom dark UI with Iceland font and grid-based layout

---

### 💡 Common Front Matter Variables

| Variable | Type | Description |
|-----------|------|-------------|
| `title` | String | Page or game title |
| `subtitle` | String | Short descriptive phrase shown under the title |
| `status` | String | Used for status pill (e.g. `Active`, `Recruiting`, `Full`) |
| `system` | String | TTRPG system (e.g. `D&D 5e`, `Daggerheart`) |
| `schedule` | String | Game time or cadence |
| `players` | Integer | Number of players in the group |
| `thumb` | URL | Path to the hero thumbnail image |
| `resources` | List | Optional — appears only if present; used for download or external links |
| `short-description` | String | A concise teaser for use in grids or cards |
| `description` | Markdown | Full description content for the game or product |

These variables are referenced throughout the templates using standard Liquid tags,  
and unused fields gracefully fail (for example, `resources` only displays if defined).

---

## 🧩 Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/<your-username>/<repo-name>.git
   cd <repo-name>
   ```

2. **Install dependencies**
   ```bash
   bundle install
   ```

3. **Run locally**
   ```bash
   bundle exec jekyll serve
   ```
   Then open [http://localhost:4000](http://localhost:4000)

---

## 🪶 Content & License

All creative content, including TTRPG adventures, art, names, and original writing,  
is **© 2025 Aedonis / Deviant Games. All rights reserved.**

You may view the source code for educational purposes,  
but redistribution or reuse of the content is **not permitted** without explicit permission.

If you want to reuse or adapt the **layout or code only**, you may do so under the **MIT License** found below.

---

## 📄 License

```
MIT License (applies to code only)
----------------------------------

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, subject to the following conditions:

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED.
```

---

## 💬 Contact

If you’d like to collaborate, join a campaign, or discuss TTRPG design,  
you can find me on **Discord** or through the community links on the site.

---

> “Unholy. Unapologetic. Deviant.”  
> *Aedonis / Deviant Games*
