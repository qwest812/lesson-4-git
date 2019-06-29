http://onedev.net/post/25
настройка git + phpstorm https://www.youtube.com/watch?v=iQqDce_9y3k


Открыть настройки программы
Ctrl + Alt + S
Переключение между открытыми вкладками
Ctrl + Tab
Открыть окно поиска по проекту
Double Shift
Добавить строчный комментарий
Ctrl + /
Добавить блочный комментарий
Ctrl + Shift + /
Вернуться к предыдущему месту редактирования
Ctrl + Shift + Backspace
Дублировать строку под курсором.
Ctrl+D
Удалить строку под курсором.
Ctrl+Y
Переместить строку
Ctrl+Shift+->
Обернуть HTML тегом выделенный текст или текущую строку.
Ctrl+Alt+J
Переименовать переменную (или теги HTML элемента) везде, где она используется
Shift+F6
формитирование текста
Ctrl +Alt + L
replace
Ctrl + Shift + R
найти файл
Ctrl + Shift +N


1) install git
https://git-scm.com/download/win
2) phpstorm instal plagin gitignore

 git init - инициализация git
git add * , git add . , git add file_name - добавить файлы для текинга
git status - посомтреть статус
git commit -m "first commit" - сделать коммит
git revert **** удалить коммит  - удалить коммит где *** - номер коммита, можно посомтерть в git log
git reset  HEAD~1 удалить последний коммит начиная от heaD включительно   если есть ключ --hard то удаляется и код
git checkout text.html  отменить изменения в файле
git commit --amend переименовать последний коммит
git log --graph --oneline --all  - графически отоброзить  изменения
git remote add *** https://github.com/qwest812/test-git.git  - добавить репозиторий где *** любое имя
git remote -v - посмотреть список репозиториев

 git config --global user.name "John Doe"  -добавить имя
 git config --global user.email johndoe@example.com - добавить email

git branch -посомтреть список веток

git checkout -b ***   добавить и перейти на ветку с названием ***

git push *** master - отправка данных на удаленный сервер с именем ***
git pull origin master  -выгрузить последние изменения
git log - посмотреть логи git
git merge ***  - обьеденить ветки, где ветка с именем *** вливается в ветку. в которой находитесь

Пример файла
.gitignore
/node_modules
/public/hot
/public/storage
/storage/*.key
/vendor
.env
.phpunit.result.cache
Homestead.json
Homestead.yaml
npm-debug.log
yarn-error.log

merge request https://docs.gitlab.com/ee/gitlab-basics/add-merge-request.html

https://webhamster.ru/mytetrashare/index/mtb0/143575842521lohpnj4q