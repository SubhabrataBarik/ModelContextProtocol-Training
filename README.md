git init
git branch -M main
echo .env >> .gitignore
git add .
git commit -m "Initial commit - cleaned repo"
git remote add origin https://github.com/SubhabrataBarik/ModelContextProtocol-Training.git
git push -u origin main --force
