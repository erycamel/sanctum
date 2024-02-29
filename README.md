echo "# sanctum" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/erycamel/sanctum.git
git push -u origin main

```bash
git add .
git commit -m "initial commit"
git branch -M main
git push -u origin main
```

# Installing laravel/ui

```bash
composer require laravel/ui
php artisan ui bootstrap --auth
```
