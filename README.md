# Web-Project
   this reposetory embed with 2 submodules

-  client (Frontend)
-  server (Backend)

---

## installtion instruction

1. clone repo include submodules (client,server)
   ```bash
   git clone --recurse-submodules https://github.com/cruzboj/web-project.git

---

# update web-project repo
   ```bash
   cd client
   git pull origin main
   cd ..
   cd server
   git pull origin main
   cd ..

   git add client server
   git commit -m "Update submodules to latest commit"
   git push

---

# conflict commends
   git status                       # Check current status
   git checkout main               # Make sure you're on main
   git pull --rebase origin main   # Rebase with latest remote changes

   # If there are conflicts, resolve them manually, then:
   git add .                       # Mark conflicts as resolved
   git rebase --continue           # Continue rebase

   # Finally, push changes:
   git push                        # Use --force only if necessary


   //github commands

git pull when in main
git checkout -b new-branch-name

// make changes
git add (.)
git commit -m "message"
git push

// error
git push --set-upstream new-branch-name

// in case of conflicts in the pr
git fetch
// resolve conflicts
// hit + in the course control (git)
git merge --continue

// when you want to push after this
git push --force