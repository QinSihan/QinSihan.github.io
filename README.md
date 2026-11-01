# Sihan Qin's personal website

Research experience, publications, and selected projects in robot learning and software development.

**Website:** https://qinsihan.github.io/

This site is built with HTML and CSS and hosted on GitHub Pages.

## Pages

- `index.html`: a wide-screen layout with profile and background alongside an introduction, selected work, and publications. On smaller screens, work precedes the background sections.
- `cv.html`: a language selection page linking to the official English and Chinese resume PDFs.
- `publications.html`: paper summaries, original figures, and resource links.
- `experience.html`: research and internship experience.
- `projects.html`: software projects and confirmed individual contributions.
- `styles.css`: shared responsive styles.

Each page has a Chinese counterpart named `*-zh.html`. The language links switch to the corresponding page, and navigation stays within the selected language. Both versions are plain HTML and work without JavaScript. Keep facts in sync across languages, but adapt Chinese prose to natural usage rather than translating sentence by sentence. Paper titles, project names, and familiar technical terms can retain their original spelling. CV links use the official English and Chinese PDFs in `assets/cv/`, copied without edits from the owner's Profile folder.

The homepage currently features Zotero Paper Partner followed by BrainCo semi-autonomous prosthetics. Each selected project uses the same `work-summary` row: a thumbnail on the left, with its title, description, resource links, and tags on the right. The four tags are `Attention`, `Reasoning Ability`, `Intention`, and `Manipulation Ability`; Zotero uses the first pair, and prosthetics uses the second. Tags use pastel pills in two aligned columns. Add future selections as additional rows.

## Project thumbnails

- `assets/projects/zotero-paper-partner-demo.gif`: the original animated [README demo](https://github.com/QinSihan/zotero-paper-partner/blob/main/assets/demo.gif), copied without modification from the Zotero Paper Partner repository.
- `assets/projects/revo3-human-handshake-v2.png`: a stylized illustration generated with the built-in Imagegen tool, showing a BrainCo Revo 3 hand shaking a human hand. The exterior follows the [official product reference](https://brainco.tech/docs/revolimb-hand/images/revo3_rendering.png), and the pose follows a [handshake photograph](https://www.mediakatalogas.lt/nuotrauka/1225452/rankos-sveiki-pasveikinimas-ranka-sutartis-susitarti-vienybe-pazadas-rankos-judesys). This is a decorative illustration, not a photograph or a technical depiction of the project hardware.
- `assets/icons/`: four SVG interest icons for football, orienteering, running, and hiking, using charcoal outlines and muted terracotta accents.

Experience details are grounded in the English and Chinese CVs in `assets/cv/`. Project descriptions also use the projects' public READMEs, and paper summaries are checked against the linked papers. Keep personal contributions separate from a paper's overall method and results. BrainCo descriptions stay at the public overview level: semi-automated prosthetics combining human intent with learned control policies. Zotero Paper Partner retains its Open Prompt, Vibe Coding, and agent reproduction information.

## Publication figures

Figures are stored locally in `assets/publications/` and attributed beside each figure on the publications page.

| File | Source |
| --- | --- |
| `par.png` | [PAR, Figure 1, arXiv v4](https://arxiv.org/html/2508.09822v4) |
| `physgen.png` | [PhysGen, Figure 5, arXiv v2](https://arxiv.org/html/2603.00110v2) |
| `siri-bench.png` | [SIRI-Bench, Figure 1, arXiv v4](https://arxiv.org/html/2506.14512v4) |

## Local preview

Run `python3 -m http.server 8000` in this directory and open `http://localhost:8000`.
