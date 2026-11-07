# Resume

The source for [joshuamiller.net](https://joshuamiller.net), built with
[Simple-Resume](https://github.com/JoshuaTheMiller/Simple-Resume), a Jekyll theme I made.

- Content lives in `_data/` (`personalInfo.json`, `projects.json`, `employment.json`).
- The theme version is pinned in the `Gemfile`; bump the tag to upgrade, then `bundle update simple-resume`.
- GitHub Actions builds every pull request and deploys `main` to GitHub Pages (`.github/workflows/pages.yml`).
