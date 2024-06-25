# Khởi tạo repo
git init  
echo "# BaiTapCoBanGit" >> README.md  
git add README.md  
git commit -m "add README.md"  
git remote add origin https://github.com/MaxHolmes221B/BaiTapCoBanGit.git  
git push -u origin main  
# Clone repo
git clone https://github.com/MaxHolmes221B/BaiTapCoBanGit
# Tạo branch
git checkout -b ducdeptrai
# Kiểm tra list branch
git branch  
# Push với main branch
git add .
git push origin main
# Pull từ repo github nhánh main về repo local
git pull origin main  
