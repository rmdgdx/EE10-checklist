# Upload and Publish on GitHub

## Option 1: Upload through the GitHub website

1. Extract the downloaded ZIP archive.
2. Sign in to GitHub and select **New repository**.
3. Enter a repository name, such as `ee-proposal-evaluator`.
4. Choose **Public** or **Private**.
5. Do not initialize the repository with another README, `.gitignore`, or license because these files are already included.
6. Select **Create repository**.
7. Choose **uploading an existing file**.
8. Drag all extracted files—including `.nojekyll` and `.gitignore`—into the upload area.
9. Enter a commit message such as `Initial release of proposal evaluator`.
10. Select **Commit changes**.

GitHub does not automatically extract an uploaded ZIP into repository files. Extract the archive first, then upload its contents.

## Option 2: Upload with Git

Run these commands from inside the extracted project folder. Replace the example URL with the URL of your empty GitHub repository.

```bash
git init
git add .
git commit -m "Initial release of proposal evaluator"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/ee-proposal-evaluator.git
git push -u origin main
```

## Publish with GitHub Pages

1. Open the repository on GitHub.
2. Select **Settings**.
3. In the left sidebar, select **Pages**.
4. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
5. Select the `main` branch and the `/ (root)` folder.
6. Select **Save**.
7. Wait for GitHub to complete the deployment.

The public address normally follows this format:

```text
https://YOUR-USERNAME.github.io/ee-proposal-evaluator/
```

If the repository name or account name is different, GitHub will show the exact address in the Pages settings.

## Update the evaluator later

Replace or edit `index.html`, commit the change, and push it to the `main` branch. GitHub Pages will publish the updated version automatically.

