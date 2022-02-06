
# دستورات کاربردی گیت

# شروع دستورات در گیت
```
git init
```
# مشاهده وضعیت
```
git status
```
# ساختن فایل جدید
```
touch index.php
```
# اضافه کردن فایل به گیت 
```
git add index.php
```
# کامیت کردن تغییرات 
```
git commit -m 'message'
```
# مشاهده کردن کامیت ها 
```
git log
```
# مشاهده تاریخچه تغییرات
```
git diff head
```

# اونایی که ادد شدن قبل از کامیت شدن چیش تغییر کرده
```
git diff --staged
```
# خارج کردن فایل از مرحله stage
```
git reset file.php
```
# برگرداندن فایل به کامیت اخر
```
git checkout --file.php
```

# مشاهده branch ها
```
git branch
```
# اضافه کردن branch
```
git branch branch-name
```
# داخل برنچ شدن
```
git checkout branch-name
```

# مرج کردن برنچ فرعی با برنچ اصلی
```
git merg branch-name
```

# ادیتور vim
```
vim index.php
```
پس از وارد شدن به ادیتور دکمه ی i را می زنیم تا به حالت insert برویم و برای خارج شدن و سیو کردن دکمه ی Esc را میزنیم سپس :wq را تایپ کرده و سپس اینتر می زنیم

# پاک کردن فایل
```
git rm file.php
```
# نمایش محتوی فایل
```
cat index.php
```
# پاک کردن برنچ
```
git branch -d branch-name
```
# اضافه کردن فایل به گیت هاب
```
git remote add origin repositoryURL
git push origin main
```
# اضافه کردن ورژن 
```
git tag -a V1.0 `m 'message
git show V1.8
git push origin V1.0
git checkout 'v1.8'
```
