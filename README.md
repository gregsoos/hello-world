I am following the steps in the GitHub Docs Hello World page and adjusting it to work with Git and GitHub CLI rather than GitHub Desktop by also following along with the Create a repo GitHub Docs page.

I am editing this a second time, now playing with creating branches using Git since the "Create a repo" page did not have me create another branch. I'm now following "Example: Contribute to an existing repository" from the "About Git" GitHub Docs page to help navigate this.

If it's of interest, my terminal entries so far look something like this:

```
gh repo create
cd hello-world/
echo "I am following the steps in the GitHub Docs Hello World page and adjusting it to work with Git and GitHub CLI rather than GitHub Desktop by also following along with the Create a repo GitHub Docs page." >> README.md
git status
git add README.md && git commit -m "Add README"
git push --set-upstream origin HEAD
git branch readme-edits
git checkout readme-edits
gedit README.md
```
