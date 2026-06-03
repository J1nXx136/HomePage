# Xinxiang Jin HomePage

This folder contains the deployable static personal homepage.

## Local Preview

```bash
cd HomePage
python3 -m http.server 8000
```

Then open:

```text
http://127.0.0.1:8000/
```

## GitHub Pages Deployment

1. Create a new GitHub repository.
2. Upload everything inside this `HomePage` folder to the repository root.
3. Make sure `index.html` is at the root of the repository.
4. Go to repository `Settings` -> `Pages`.
5. Under `Build and deployment`, choose:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/ (root)`
6. Click `Save`.
7. Wait for GitHub Pages to publish the site.

The site URL will usually be:

```text
https://<your-github-username>.github.io/<repository-name>/
```

If the repository is named `<your-github-username>.github.io`, the URL will be:

```text
https://<your-github-username>.github.io/
```
