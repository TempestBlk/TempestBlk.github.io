## Flutter Github Account Website Dev

### Commands for Deploying

OR RUN "make deploy-web"

flutter clean
flutter pub get

flutter build web --base-href /account_website/ --release

cd build\web
git init
git add .
git commit -m "Deploy 2"
git remote add origin https://github.com/TempestBlk/account_website.git
git branch -M main
git push -u --force origin main