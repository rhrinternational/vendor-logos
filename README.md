# vendor-logos

Image assets referenced by external tools.

## ⚠️ This repository is intentionally public — do not make it private

These images are embedded by raw URL from external tools that cannot authenticate to a private repository. Changing this repository's visibility **breaks those references at once**. Do not change visibility without first migrating every external reference.

## Usage

```
https://raw.githubusercontent.com/rhrinternational/vendor-logos/main/<filename>
```

URL-encode spaces in filenames as `%20`.

## Contributing

Filenames are a published API — never rename or delete a file without checking external references first. Avoid adding filenames that differ only by case (e.g. `Tableau.png` / `tableau.png` collide on case-insensitive filesystems).
