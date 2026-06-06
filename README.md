# Pipat Portfolio

Bilingual static portfolio site for GitHub Pages.

## Local Preview

Open `index.html` directly in a browser, or run a simple local server:

```powershell
python -m http.server 8080
```

Then visit:

```text
http://localhost:8080
```

## Deploy To GitHub Pages

1. Create a GitHub repository, for example `portfolio` or `Pipatsassana5.github.io`.
2. Push this folder to the repository.
3. In GitHub, open `Settings -> Pages`.
4. Set `Source` to `GitHub Actions`.
5. Push to `main`; the included workflow publishes the static files.

If the repository is named `Pipatsassana5.github.io`, the site URL is:

```text
https://Pipatsassana5.github.io/
```

If the repository is named `portfolio`, the site URL is:

```text
https://Pipatsassana5.github.io/portfolio/
```

## Content Sources

The first version was built from inspected local projects under `C:\Work`, including:

- `Bussiness\Fastbill`
- `Bussiness\Fastbill\fastbill-cloudflare-d1`
- `REDDITBOT`
- `reportmaker`
- `Envi`
- `Fastwork`
- `Bussiness\plaatformporjects\APP`
- Google Drive work archive: `https://drive.google.com/drive/u/0/folders/1rIw2zJthrkPAtGQRgqlckVNQNxY6OCW_`

Drive media handling:

- JPG and HEIC image files are stored under `assets/drive/`.
- JPG images are embedded directly in the archive section.
- HEIC images are linked as local files because browser support is inconsistent.
- Full videos stay as Google Drive links to keep the GitHub Pages site lightweight.

Contact links currently point to:

- GitHub: `https://github.com/SteveJO789`
- Fastwork: `https://fastwork.co/user/roymustang`
