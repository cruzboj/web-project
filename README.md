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