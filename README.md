mkdir mening-loyiham && cd mening-loyiham
git init
echo '<!DOCTYPE html><html lang="uz"><head><meta charset="UTF-8"><title>Mening loyiham</title></head><body><h1>Salom, dunyo!</h1></body></html>' > index.html
git add index.html
git commit -m "index.html sahifasi qo'shildi"
printf '# Mening loyiham\n\nBu Git va GitHub o'"'"'rganish uchun yaratilgan oddiy veb-sahifa loyihasi.\n' > README.md
git add README.md
git commit -m "README.md loyiha tavsifi bilan qo'shildi"
git branch -M main
git remote add origin https://github.com/USERNAME/mening-loyiham.git
git push -u origin main
