Capstone checklist

- [ ] repository contains: README.md, LICENSE, .gitignore
- [ ] notebooks/ includes weekly notebooks and capstone/ contains capstone-starter.ipynb
- [ ] submission/paper_url.txt exists and will contain the final deployed paper URL (one line)
- [ ] Data section in paper documents dataset release and exclusions (public-safe)
- [ ] Methodology includes feature list, label definition, baseline, and validation split
- [ ] Results include model vs baseline on same validation split and supporting charts
- [ ] Limitations are explicitly stated (observational, decision-support phrasing)
- [ ] Ranked recommendations with short reason codes
- [ ] Reproducibility: links to notebooks, notes about HF dataset token and release id
- [ ] Deploy page: docs/paper.html or docs/index.html links to generated notebooks and paper

Merging this PR will run CI that executes notebooks and publishes docs/ to GitHub Pages. After merging, verify Actions completed and open the Pages URL from repository settings -> Pages.
