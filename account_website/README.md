# account_website

A new Flutter project.

## Flutter Github Account Website Dev

flutter clean
flutter pub get

flutter build web --base-href /account_website/ --release

cd build/web
git init
git add .
git commit -m "Deploy 2"
git remote add origin git@github.com:TempestBlk/account_website.git
git push -u origin main -f