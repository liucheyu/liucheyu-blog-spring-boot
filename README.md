# liucheyu-blog-spring-boot
##github建立專案後，本地端做以下操作

到本地端command

~~~bash
git init
git add .
git commit -m "first commit"
#github預設branch切在main上面，如需改名，請先到github設定改名
git branch -M main
git remote add origin https://github.com/liucheyu/liucheyu-blog-spring-boot.git
git push -u origin main
~~~
