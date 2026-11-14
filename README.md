# sparecrew.dev

Public site and devlog for Sparecrew. Plain static HTML served by GitHub Pages, no build step.

- Add a post: copy `templates/post.html` to `posts/YYYY-MM-DD-slug.html`, fill it in, delete its `robots` line, and add a card to the Devlog list in `index.html` (newest first).
- Every post has a cover: a meme picture on the post's topic, saved as `assets/covers/YYYY-MM-DD-slug.png` (16:9, under 500 KB) with real `alt` text. The release post and its meme are one post; there is no separate meme page.
  On the index card, put the same picture first: `<img class="thumb" src="/assets/covers/YYYY-MM-DD-slug.png" alt="…">`.
- Never publish money, shares, personal data, internal hostnames or links to private code.
