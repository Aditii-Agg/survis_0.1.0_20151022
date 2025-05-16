# SurVis - Visual Literature Browser (Customized for COMP4037 Coursework)

SurVis is a flexible browser to visualize and interactively explore scientific literature collections. It was developed to support authors of survey articles, theses, and books who want to present their references in an engaging and searchable way.

## 🎓 Student Information
- **Name:** Aditi Kapil Agarwal
- **Student ID:** 20662359
- **Module:** COMP4037 Research Methods  
- **Coursework Title:** Virtual Reality and Cognitive Training in Older Adults  
- **Papers Included:** 10 peer-reviewed academic papers  

## 📂 Project Setup

### Contents
- `bib/references.bib` — Contains 10 annotated academic papers in BibTeX format.
- `src/data/generated/` — Contains `bib.js`, `tags.js`, `keywords.js` (auto-generated via `update_data.py`)
- `src/data/tag_categories.js` — Defines colored tag groups for visual timelines.
- `src/data/authorized_tags.js` — Provides tooltip support for important tags.
- `.nojekyll` — Required for GitHub Pages to render SurVis correctly.
- `index.html` — Redirects to `src/index.html`

### Tag Categories for Coloring
Defined in `tag_categories.js`:
```js
{
  "technology": ["virtual reality", "video games", "brain-computer interface", "neurofeedback"],
  "study": ["RCT", "systematic review", "meta-analysis"],
  "population": ["elderly", "older adults", "predementia", "mild cognitive impairment"],
  "cognition": ["memory training", "executive function", "visuospatial function", "wellbeing", "cognitive rehabilitation"]
}
