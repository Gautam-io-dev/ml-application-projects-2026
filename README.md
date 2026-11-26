# ML Application Projects 2026 – Revised Article Submissions

Machine Learning (B.Sc. (Hons.) Computer Science, Semester VI) · Department of Computer Science, Ramanujan College, University of Delhi

This repository collects the **revised versions of your ML application project articles**. After you receive your individual publication-readiness feedback, revise your paper and code, then submit the revised article here by opening a **pull request**. Your instructor reviews each submission and gives final comments before you submit the paper to an external conference or journal.

---

## What to submit

Create one folder named after your problem number and university roll number:

```
submissions/P<NN>_<UniversityRollNo>/
├── paper.pdf          the revised article (required)
├── source/            LaTeX (.tex, .bib, figures) or Word (.docx) source of the article (required)
├── metadata.yml       your details and links (required) – copy from submissions/_TEMPLATE
└── CHANGES.md         how you addressed each point of your feedback (required)
```

- `NN` is your two-digit problem number (e.g. `P07`, `P45`).
- Example: `submissions/P10_24020570014/`.
- **Code and data stay in your own project repository** (link it in `metadata.yml`). Do not upload datasets, large files (> 20 MB), API keys or passwords here.

## How to submit (step by step)

1. **Fork** this repository (button at the top right of the page) into your own GitHub account.
2. In your fork, copy `submissions/_TEMPLATE/` to `submissions/P<NN>_<UniversityRollNo>/`.
   - On the GitHub website: open the template files, use *Add file → Create new file*, and type the new folder path in the file name box, e.g. `submissions/P10_24020570014/metadata.yml`.
   - Or with git: `git clone https://github.com/<your-username>/ml-application-projects-2026.git`, copy the folder, then `git add`, `git commit`, `git push`.
3. Add `paper.pdf`, the `source/` files, and fill in `metadata.yml` and `CHANGES.md`.
4. Open a **pull request** from your fork to this repository. Title it `P<NN> <Your Name> – revised article`.
5. An automatic check confirms the folder name and the required files. Fix anything it reports by pushing again to the same branch – the pull request updates itself.
6. Your instructor will review and comment on the pull request. Reply and push revisions in the same pull request; **do not open a new one**.

Only change files inside your own folder. Pull requests that touch other folders will not be accepted.

## Before you open the pull request – checklist

- [ ] Every point in your feedback is addressed, and `CHANGES.md` says how (or why not).
- [ ] No template placeholders remain (e.g. `[x.y]`, `[add link]`, `[Student Name]`, `accessed [date]`).
- [ ] Abstract of 150–250 words with key numbers; 4–8 keywords.
- [ ] A simple baseline is compared under the same validation protocol; the validation protocol suits the data (time-ordered or grouped splits where needed, test set used once).
- [ ] Every number, table and figure in the paper is produced by the code in your repository.
- [ ] Your repository has a README with run steps, a `requirements.txt`, and the data or a download script; it runs end to end from a fresh clone.
- [ ] 15–30 real, complete references with DOIs, each verified on Google Scholar or the publisher's site; the dataset is cited with its licence and access date.
- [ ] An honest AI-use statement saying which AI tools you used and for what.
- [ ] Similarity index below 10 % (check with the plagiarism tool available in the college).
- [ ] The paper uses a conference template (the LaTeX starter in `templates/latex/` or the venue's own template).

## Article template

`templates/latex/` contains a starter article in the Springer LNCS-style layout used for the class proceedings. The easiest way to use it is on Overleaf: create a project from Overleaf's *Springer LNCS* template, then replace its `.tex` file with `templates/latex/main.tex`. If your target venue has its own template (IEEE, ACM, Elsevier, MDPI), use that instead.

## Review process

1. You open the pull request.
2. The automatic check runs.
3. Your instructor reviews it and either requests changes or approves it.
4. After approval, the submission is merged into `submissions/`. You may then submit the paper to the venue you have chosen. Check the venue's deadline, scope, indexing (Scopus, Web of Science, DOAJ) and fees on its official page first, and avoid predatory venues.

Questions: ask your instructor in class or open a GitHub *Discussion* or *Issue* in this repository (do not post personal contact details).

## Licence

Each article remains the work and property of its author. By submitting, you agree that the article may be shown in this repository for review.
