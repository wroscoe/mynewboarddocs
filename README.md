# Welcome — your new board document site

You just created a copy of the **Modern Board Docs** starter. Follow the steps below to make it yours. Total time: about 5 minutes.

You don't need to install anything on your computer. Every step happens in your web browser.

---

## Step 1 — Turn on the website (one click)

1. Click the **Settings** tab at the top of this repository.
2. Click **Pages** in the left sidebar.
3. Under **Build and deployment → Source**, select **GitHub Actions**.
4. That's it. Wait about a minute for the site to build (the **Actions** tab shows progress).

Your site is now live at:
**`https://<your-github-username>.github.io/<this-repo-name>/`**

For example, if your username is `myschool` and you named the repo `board-docs`, your site is at `https://myschool.github.io/board-docs/`.

---

## Step 2 — Add your district's name

1. Open [`boreddocs.yml`](./boreddocs.yml) in this repository (just click the filename).
2. Click the pencil icon (✏️) in the top right to edit.
3. Replace the placeholder values:
   - `name: "Your School District"` → your district's full name
   - `short_name: "YSD"` → a short version (initials are fine)
   - `mission_statement` and `vision_statement` → your district's statements
   - Set `base_url: "/<this-repo-name>"` (e.g. `base_url: "/board-docs"`) so links work correctly. Leave blank if you set up a custom domain.
4. Scroll down, write a short message ("Set up district info"), and click **Commit changes**.
5. The site automatically rebuilds in about a minute.

---

## Step 3 — Add your first agenda

1. Open [`content/meetings/`](./content/meetings) in this repository.
2. Either edit the example file (`2026-01-13-regular.md`) or create a new one named `YYYY-MM-DD-regular.md` (use the meeting's date).
3. Replace the section titles with your meeting's actual sections.
4. Commit the change. Your new agenda appears on the site within a minute.

---

## Step 4 — Add your first set of minutes (after the meeting)

1. Open the agenda file you created.
2. Change `type: agenda` to `type: minutes` at the top.
3. Add an `attendance:` block listing who attended (see the example minutes file `2025-12-09-regular-minutes.md` for the format).
4. Under each Action Item, add a `::motion` block with the motion text and voting record (again, the example minutes file shows the format).
5. Rename the file to add `-minutes` at the end so the agenda is preserved alongside the minutes.
6. Commit. The minutes appear on the site within a minute.

---

## What's next?

- **Add real policies**: replace the example files in [`content/policies/`](./content/policies) with your district's actual policies. Use the same format as the examples.
- **Set a custom domain** (like `boards.yourdistrict.org`): see GitHub's [custom domain guide](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site). Then set `site.url` in `boreddocs.yml` and clear `base_url`.
- **Replace the logo**: drop your district's logo at `overrides/static/img/logo.svg` and it'll show in the header.
- **Customize the look**: drop a `overrides/static/styles.css` file to add custom styling on top of the default theme.

---

## Need help?

- Project home: [www.boreddocs.com](https://www.boreddocs.com)
- Source code: [github.com/wroscoe/boreddocs](https://github.com/wroscoe/boreddocs)
- Open an issue: [github.com/wroscoe/boreddocs/issues](https://github.com/wroscoe/boreddocs/issues)

---

You can delete this README after setup, or replace it with one for your district's editors.
