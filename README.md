## Instal Plug

```bash
sh -c 'curl -fLo "${XDG_DATA_HOME:-$HOME/.local/share}"/nvim/site/autoload/plug.vim --create-dirs \
       https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim'
```

Run command to intall all plugin
```
:PlugInstall
```

Need install:
- vim-plug - see above
- ripgrep
- rust-analyzer


## Горячие клавиши Vim

```
NerdTree
ctrl+ww - Switch to hirizontal split windows
ctrl+w + hjkl - Switch split window to side by key
ctrl+w + HJKL - Move split window to side by key
:vs - vertical split
:sp - horizontal split
i in file NERDTree open with horizontal split
s in file NERDTree open with vertical
o in file NERDTree open
R - refresh file list
Shift+i - view hidden file

i - insert mode
a - insert mode перенос на следующую букву
A - insert mode курсор на конец строки
o - insert mode создание новой строки снизу и курсор в начало
O - -/-         аналогично, но строка выше
gg - в начало файла
G - в конец файла
w - в конец слова
b - back word предыдущее слово
e - конец слова
. - repeat last action in key mode

5w - перепрыгнуть на 5 слов вперед
F3 - поиск "3"
/asd - поиск вниз по файлу
?asd - поиск вверх по файлу

mx - закладка x
'x - вернуться на закладку x

v - режим выделения
V - режим выделения с текущей строкой

x или d - удаление текста с помещением в буфер обмена

p - вставить справа от курсора
P - вставить слева от курсораa

u - отмена действия

dw - удалить слово
dd - удалить строку

2dd - удалить две строки

cw - change word
C - заменить все символы до конца строки
D - удалить до конца строки

Terminal
:term - open terminal in window
:! <command> - run one command

Макросы
q1 - записать макрос с номером 1
q - окончание записи макроса
@1 - применение макроса с номером 1
```
