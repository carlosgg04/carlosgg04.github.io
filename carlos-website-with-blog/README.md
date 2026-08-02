# Carlos A. González-Gutiérrez — website with Research Notes

Upload the complete contents of this folder to the root of your GitHub Pages
repository.

## Included files

- `index.html` — main personal webpage.
- `research-light-matter.png`
- `research-structured-environments.png`
- `research-quantum-magnonics.png`
- `blog/index.html` — list of all notes.
- `blog/why-structured-reservoirs-remember.html` — working example.
- `blog/post-template.html` — reusable template.
- `blog/blog.css` — styling shared by the blog pages.
- `.nojekyll` — tells GitHub Pages to serve these files as a plain static site.

## Add a new research note

1. Open the `blog` folder.
2. Copy `post-template.html`.
3. Rename the copy using lowercase words separated by hyphens, for example:
   `quantizing-a-spin-wave.html`.
4. Edit the title, date, category, introduction, and article text.
5. Add LaTeX using:
   - inline equation: `\( E = \hbar\omega \)`
   - displayed equation: `\[ E = \hbar\omega \]`
6. Upload figures to the repository and use a relative path in the `<img>` tag.
7. Copy one post-card block in `blog/index.html` and update its link and text.
8. Optionally add the newest post to the Research Notes section in the root
   `index.html`.

## Figures

For a figure stored in the root of the repository:

```html
<figure class="article-figure">
  <img src="../my-figure.png" alt="Description of the figure">
  <figcaption>Your caption.</figcaption>
</figure>
```

For a figure stored inside the `blog` folder, remove the `../`.

## Important

Keep the folder structure unchanged. The blog links use relative paths.
