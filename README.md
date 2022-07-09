# GitHub ga yangi repository qo'yish.
***
### 1-qadam.
Terminal orqali github ga qo'ymoqchi bo'lgan proyektimiz turgan papkaga borib olamiz.
### 2-qadam.
Va quyidagi buyruqni yozamiz.\
```git config --global user.name "Ism"```\
Bu yerda "Ism" ni o'rniga o'z ismingizni yoki github username ingizni yozing.\
### 3-qadam.
```git config --global user.email "Email"```\
Bu yerda ham "Email" orniga email ingizni kiriting.\
### 4-qadam.
```git config --global push.default matching```
### 5-qadam
```git config --global alias.co checkout```
### 6-qadam.
Va nixoyat endi git ni intialize qilamiz ya'ni ishga tushuramiz\
```git init```
### 7-qadam.
```git add .```
### 8-qadam.
Endi commit qilamiz ya'ni githubga topshiramiz.
```git commit -am "init commit"```
### 9-qadam.
```git branch -M main```
### 10-qadam.
GitHub sahifangizga kirib yangi repozitoriy yarating.
### 11-qadam.
```git remote add origin https://github.com/<github_user_name>/<repo_name>.git```\
Bu yerda <github_user_name> o'rniga o'zingizning github username ingiz yani foydalanuvchi nomini <repo_name> orniga esa yuqorida yaratgan repozitoriy nomini kiriting\
### 12-qadam.
Endi shaxsiy manba tokenini oling.\
Qadamlar\
Profile>Settings>DeveloperSettings>Personal acces tokens
### 13-qadam.
```git remote set-url origin https://<personal_acces_token>@github.com/<github_user_name>/<repo_name>.git```
Bu yerda ham <personal_acces_token> o'rniga yuqorida olgan tokeningiz,<github_user_name> o'rniga user_name <repo_name> o'rniga repozitoryingiz nomini yozing.
### 14-qadam.
Va nihoyat endi proyektimizni GitHub ga qo'yamiz.\
```git push origin main```
# *O'zgartirishlar uchun:
### 1-qadam.
```git commit -am 'init <fayl_nomi>'```
### 2-qadam.
```git push```
