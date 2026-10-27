# gregos5.github.io

Personal portfolio page. A single static `index.html`

- Edit `index.html` to update links, timeline, skills or projects.
- The CV download lives at `assets/Idan_Malka_CV.pdf`.

link: [https://gregos5.github.io](https://gregos5.github.io)

## Adding images

Keep the page fast: put only optimised WebP files in `assets/`.

- Export as **WebP**, about twice the size it's displayed at: max 800 px wide for project photos, 128–160 px tall for timeline logos. Quality 75–85 is plenty.
- Give every `<img>` its real `width`/`height` attributes so the layout doesn't jump.
- Add `loading="lazy" decoding="async"` to anything below the header.
- Animated GIFs → animated WebP (usually ~40% smaller).
