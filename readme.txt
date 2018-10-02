git clone https://github.com/%user_login%/%repo_name%.git

Переходим в свежесозданную папку репозитория и настраиваем его:
git config user.name ivan.ivanov
git config user.email ivanov@example.com

git status

git add file.**

git commit -m "%commit_message%"

Историю изменений можно посмотреть командой git log или git log --name-only

git push origin master

Выполнение этой команды может закончиться с ошибкой, если в локально репозитории отсутствуют последние изменения, имеющиеся в удаленном репозитории. Для решения этой проблемы надо выполнить команду git pull, которая скачает последние изменения из удаленного репозитория и смержит их с вашими локальными правками, после чего можно повторить команду git push.