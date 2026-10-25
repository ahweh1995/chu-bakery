# Chu Bakery website

The public website for Chu Bakery, Muar, Johor: a 3D shop you scroll into, a menu book, an events wall and the team badges.

## How to change things

1. Go to **https://app.pagescms.org** and sign in with GitHub.
2. Open **chu-bakery**.
3. Pick what to change: **Menu · 菜单**, **Events & dessert tables · 活动与甜品台**, **Team · 团队** or **Shop links · 店铺链接**.
4. Type your changes or upload a photo, then press **Save**.

The live website updates about a minute after each Save. Phone photos are shrunk automatically on the website, so you can upload them as they are.

An empty photo shows the drawn sample picture (示意图) instead.

## What is in here

| File | What it is |
| --- | --- |
| `index.html` | The website itself (design, 3D shop, menu book) |
| `content/*.json` | The text the editor changes: cakes, events, team, shop links |
| `media/` | Photos uploaded in the editor |
| `.pages.yml` | The editor's forms |
| `.github/workflows/publish.yml` | Publishes the site to GitHub Pages on every change |
