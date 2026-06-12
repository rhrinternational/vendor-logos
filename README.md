# vendor-logos

Logo image assets used in RHR dashboards and documentation.

## ⚠️ This repository is intentionally public — do not make it private

Looker Studio dashboards hotlink these images by raw URL, and Looker Studio cannot authenticate to a private repository. Changing this repo's visibility to private **breaks every embedded image at once**. Do not change visibility without first migrating all dashboard image references.

## Usage

Reference any image directly:

```
https://raw.githubusercontent.com/rhrinternational/vendor-logos/main/<filename>
```

URL-encode spaces in filenames as `%20` (e.g. `Looker%20Studio.png`).

## Contributing

Because images here are hotlinked by filename, **renaming or deleting a file breaks live dashboards** — treat existing filenames as a published API. Add new files freely; never remove or rename without checking dashboard references first. Changes go through the standard org workflow: branch → PR → squash merge (`main` is protected).

> Note: this repo contains both `Tableau.png` and `tableau.png` — filenames differing only by case collide on macOS/Windows checkouts (git warns at clone). Avoid adding case-variant duplicates.
