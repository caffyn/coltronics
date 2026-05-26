# coltronics.net

Personal site for Colton Shepard. Static HTML/CSS, no build step. Served from
Cloudflare Pages with `coltronics.net` as the custom domain.

To make changes: edit `index.html` / `style.css`, commit, push. Cloudflare
Pages picks up `main` automatically.

To update the resume PDF: rebuild from
[`resumes/base.tex`](https://github.com/caffyn/resumes) (or wherever the
source lives at the time), then copy the resulting `base.pdf` into this
repo as `resume.pdf`.
