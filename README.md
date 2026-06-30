# Surface Magic Example

Private Jekyll rebuild concept for Surface Magic, LLC.

## Local development

```bash
bundle install
bundle exec jekyll serve
```

## GitHub Pages

This repository is private. GitHub returned `Your current plan does not support GitHub Pages for this repository` when Pages enablement was attempted for `jules-the-ai/surface-magic-example`.

The included workflow currently builds the Jekyll site on every push so the source remains verified. To deploy via GitHub Pages, either make the repository public or use an account/organization plan that supports Pages for private repositories, then switch the workflow to `actions/configure-pages`, `actions/upload-pages-artifact`, and `actions/deploy-pages`.

## Notes

- Preserves the existing Surface Magic purple/blue/black palette and logo.
- Reuses publicly available images from the current Surface Magic website as requested.
- Omits embedded chat/accessibility widgets and third-party quote integrations for a cleaner static prototype.
