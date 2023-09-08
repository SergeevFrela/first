git status
cd c:/Users/serge/Desktop/first_project
git push -u origin master
git status
git remote add origin git@github.com:SergeevFrela/first.git
remote -v
git push -u origin master
git add test.txt
git commit -m "add 678"
git push
history

git log --oneline //Получить сокращённый лог 
cd .git/
ls # посмотрели, какие есть файлы
COMMIT_EDITMSG  ORIG_HEAD  description  index  logs/     refs/
HEAD            config     hooks/       info/  objects/

cat HEAD # команда cat показывает содержимое файла
ref: refs/heads/master # в файле вот такая ссылка 
$ touch fileA.txt
$ git status

