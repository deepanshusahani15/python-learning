# python-learning started by me

```bash
echo "# python-learning" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/deepanshusahani15/python-learning.git
git push -u origin main
```

## Changed to SSH Authentication

Instead of using the HTTPS remote, I changed it to my **Deepanshu GitHub SSH configuration**:

```bash
git remote set-url origin git@github-deepanshu:deepanshusahani15/python-learning.git
git remote -v
```

### Remote

```text
origin  git@github-deepanshu:deepanshusahani15/python-learning.git (fetch)
origin  git@github-deepanshu:deepanshusahani15/python-learning.git (push)
```

Then pushed successfully:

```bash
git push -u origin main
```

## Final Setup

```text
Mac
 ↓
~/.ssh/deepanshu
 ↓
github-deepanshu
 ↓
GitHub: deepanshusahani15
 ↓
Repository: python-learning
 ↓
Branch: main
```
