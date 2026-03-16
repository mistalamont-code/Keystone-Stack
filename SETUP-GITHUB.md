# Push Keystone Stack to GitHub

## Step 1: Create the repo on GitHub

Go to https://github.com/new and create a new repository:
- **Name:** `keystone-stack`
- **Description:** `Deal intelligence platform for real estate developers, municipalities, and investors`
- **Visibility:** Private (recommended until you're ready to launch)
- **Do NOT** initialize with README, .gitignore, or license (we already have those)

## Step 2: Push from your computer

Open a terminal, navigate to this folder, and run:

```bash
cd keystone-stack
git remote add origin https://github.com/YOUR_USERNAME/keystone-stack.git
git push -u origin main
```

Replace `YOUR_USERNAME` with your GitHub username.

If you don't have git configured yet:
```bash
git config --global user.name "Corey Cook"
git config --global user.email "mistalamont@gmail.com"
```

## Step 3: Enable GitHub Pages (optional — for a live demo)

1. Go to your repo on GitHub
2. Settings → Pages
3. Source: Deploy from a branch
4. Branch: `main`, folder: `/ (root)`
5. Save

Your app will be live at: `https://YOUR_USERNAME.github.io/keystone-stack/`

## Important: Keep the repo PRIVATE if you want IP protection

Roland Pierce's advice: Keep the repo private until the LLC is formed, copyright is registered, and trademark is filed. A public repo makes your code visible to the world — which is fine for demonstrating copyright ownership (the timestamp proves it) but also makes it easy to copy.

Once you have the copyright registration filed and "KEYSTONE STACK" trademark application in, you can go public with confidence.
