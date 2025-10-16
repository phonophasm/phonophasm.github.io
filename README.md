# GitHub Pages Portfolio + Blog (Jekyll)

A tiny, no-fuss starter that runs on **GitHub Pages** using the official **Minimal** theme.
- Blog posts in `_posts/`
- Project pages in `_projects/` (custom collection)
- Simple nav: Home / Blog / Projects / About
- Typewriter-style mono font via `_includes/head-custom.html` + `assets/css/custom.css`

## 1) Create your repo
For a user site, name it exactly: `your-username.github.io` (replace `your-username`).

## 2) Push these files
```
git init
git add .
git commit -m "Initial commit: portfolio blog starter"
git branch -M main
git remote add origin https://github.com/your-username/your-username.github.io.git
git push -u origin main
```

GitHub Pages should publish automatically at `https://your-username.github.io`.

## 3) Customize
- Edit `_config.yml`: set `title`, `description`, `author`, and your real `url`.
- Replace `Your Name` in `index.md`, `about.md`.
- Add posts in `_posts/` as `YYYY-MM-DD-title.md` with front matter:
  ```yaml
  ---
  title: "My Post"
  tags: [unity, audio, vr]
  ---
  Content here...
  ```
- Add projects in `_projects/` with front matter:
  ```yaml
  ---
  title: "Project Title"
  summary: "One-liner about it"
  tags: [tagA, tagB]
  featured: true   # show on home
  weight: 2        # lower = higher up in lists
  links:
    - { label: "GitHub", url: "https://..." }
  ---
  Longer writeup...
  ```

## 4) Local preview (optional)
If you want to run locally:
1. Install Ruby and Bundler.
2. Add a `Gemfile` with:
   ```ruby
   source "https://rubygems.org"
   gem "github-pages", group: :jekyll_plugins
   ```
3. Then:
   ```bash
   bundle install
   bundle exec jekyll serve
   ```
Visit <http://localhost:4000>.

## 5) Custom domain (optional)
Set a CNAME in repo settings (Pages) and add a `CNAME` file with your domain.

---

Enjoy! Keep it simple, ship often.
