#  Команды Git
>git --version                              : вывести в терминале версию Git
>git config --global user.name ev_levashov  : задание имени пользователя глобально
>git config --global user.email evlsb@ya.ru : задание email пользователя глобально

>git init                       : создать Git репозиторий
>git status                     : показать статус рабочего дерева
>git add .                      : добавить содержимое файла в индекс
>git commit -m "add git add"    : добавление коммита
>git log --oneline              : показать все коммиты
>git checkout 4f4f288           : посмотреть проект в заданной точке коммита (только для просмотра)
>git checkout master            : переход к последнему коммиту текущей ветки
>git revert 4f4f288             : отмена заданного коммита
>:wq                            : выход из редактора vim
>git reset 4f4f288 --hard       : удаление всех коммитов с заданного до последнего

>git branch forum               : добавление новой ветки
>git checkout forum             : переход на другую ветку
>git checkout -b admin          : создание ветки и переход на ее
>git branch -a                  : отобразить в консоле все ветки
>git merge forum                : слияние текущей ветки с веткой "forum"

>git remote add origin https://github.com/evlsb/Git_command.git : подключение к репозиторию
>git remote                                                     : состояние подключения к удаленному репозиторию (если origin, то подключение успешно)
>git push -u origin main                                        : добавление ветки main в репозиторий origin
>git clone https://github.com/evlsb/web.git                     : клонирование репозитория с удаленного сервера
>git pull                                                       : обновить файлы в локальной папке из удаленного репозитория