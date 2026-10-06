# Push to GitHub (one-time)

`gh` is not authenticated in this environment. On a machine where you are logged in as **popododo0720**:

```bash
cd /path/to/sus-lab-demo-quartz   # or clone after create
gh auth login
gh repo create popododo0720/quartz-notes --public --source=. --remote=origin --push
```

If the empty remote already exists and `origin` is set:

```bash
git push -u origin main
```

Suggested public repo name: **quartz-notes**  
Local remotes already: `origin` → `https://github.com/popododo0720/quartz-notes.git`, `upstream` → jackyzha0/quartz.
