# Setup — axusmotion profile README

## 1. Create the special repo
Go to https://github.com/new and create a repo named exactly **axusmotion**
(same as your username — this makes it show on your profile).
Make it **Public**, no README, no .gitignore.

## 2. Push these files
Unzip this folder, open a terminal inside it, then:

```bash
git init
git add README.md .github
git commit -m "profile readme"
git branch -M main
git remote add origin https://github.com/axusmotion/axusmotion.git
git push -u origin main
```

## 3. Enable the snake animation
1. Go to https://github.com/axusmotion/axusmotion/settings/actions
   → Workflow permissions → select **Read and write permissions** → Save
2. Go to the **Actions** tab → click **generate snake** → **Run workflow**
3. Wait ~1 min. Snake appears on your profile after it finishes.

## 4. Optional
- Add your socials at the bottom of README.md (look for `<!-- add your own -->`)
- Change accent color: find/replace `22d3ee` (and `38bdf8`, `0ea5e9`) in README.md
