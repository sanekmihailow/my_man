
ls command is used to list files and directories. By default, it will be list the content of current directory.


| ***option short*** | ***option long*** | ***<arguments> and Descriptiqon*** |
|---|---|---|
| <b>-a</b> | <b>--all</b> |показывать скрытые файлы, начинающиеся с `.` |
| <b>-A</b> | <b>--almost-all</b> |показывать скрытые файлы, без начальный `.` and `..`|
| <b>-b</b> | <b>--escape</b> |print octal escapes for nongraphic characters |
| <b></b> | <b>--block-size=</b> |`G` or <br> `M` or <br> `K` - при показе, использовать соответствующий размер |
| <b>-B</b> | <b>--ignore-backups</b> |do not list implied entries ending with `~` |
| <b>-c</b> | <b></b> |with -lt: sort by, and show, ctime (time of last modification of file status information) with -l: show ctime and sort by name otherwise: sort by ctime |
| <b>-C</b> | <b></b> |показывать спсок в несколько разделяя на несколько столбцов |
| <b></b> | <b>--color=</b> |`auto` or <br> `always` or <br> `never` - показывать подцветку или нет |
| <b>-d</b> | <b>--directory</b> |list directory entries instead of contents, and do not dereference symbolic links |
| <b>-D</b> | <b>--dired</b> |генерирует вывод в стиле EMACS dired mode (показывает полный путь у симлинка) |
| <b>-f</b> | <b></b> |отключет сортировку и подцветку |
| <b>-F</b> | <b>--classify</b> |дабавляет в конец `*` `/` `=` `>` `@` `\|` |
| <b></b> | <b>--file-type</b> |дабавляет в конец  `/` `=` `>` `@` `\|` , без `*`  |
| <b></b> | <b>--format=</b> |`verbose` or <br> `long` or <br> `horizontal` or <br> `across` or <br> `vertical` or <br> `single-column` - как показывать список |
| <b></b> | <b>--full-time</b> |показывать полную дату и время , сочетать с `ls -l` |
| <b>-g</b> | <b></b> |в выводе не показывать владельца |
| <b></b> | <b>--group-directories-first</b> |в выводе сортировать сначала по каталогам |
| <b>-G</b> | <b>--no-group</b> |в вывод ене показывать группу |
| <b>-h</b> | <b>--human-readable</b> |показыать в человеческом виде размер файла,директории (не байты а килобайты и т.д.) |
| <b></b> | <b>--si</b> |в выводе показывать размер как в математике (через запятую) |
| <b>-H</b> | <b>--dereference-command-line</b> |follow symbolic links listed on the command line |
| <b></b> | <b>--dereference-command-line-symlink-to-dir</b> |follow each command line symbolic link that points to a directory |
| <b></b> | <b>--hide=</b> |`<word with regex or no>` скрывает выбрйнный символ, слово и т.д. |
| <b></b> | <b>--indicator-style=</b> |`none` or <br> `slash` or <br> `file-type` or <br> `classify` - добавлять в конец соответствующий индикатор|
| <b>-i</b> | <b>--inode</b> |показывать индексный номер для каждого файла |
| <b>-I</b> | <b>--ignore</b> |1)если использовать regex выдает список соответствующий regex (удобно для поиска файлв) <br> 2)если использовать полное слово то просто исключает из вывода |
| <b>-k</b> | <b></b> |показывает размер в килобайтах |
| <b>-l</b> | <b></b> |показывать длинный список с  параметров c 9 столбцами |
| <b>-L</b> | <b>--dereference</b> |when showing file information for a symbolic link, show information for the file the link references rather than for the link itself |
| <b>-m</b> | <b></b> |показывать список в строчку через запятую |
| <b>-n</b> | <b>--numeric-uid-gid</b> |показывать номер uid gid вместо названия |
| <b>-N</b> | <b>--literal</b> |print raw entry names (don't treat e.g. control characters specially) |
| <b>-o</b> | <b></b> |не позывать инфу о группе сочетать с `ls -l` |
| <b>-p</b> | <b>--indicator-style=slash</b> |добавлять slash к каталогам |
| <b>-q</b> | <b>--hide-control-chars</b> |print `?` instead of non graphic characters |
| <b>-Q</b> | <b>--quote-name</b> |заключить вывод пути в кавычки |
| <b></b> | <b>--quoting-style</b> |`literal` or <br> `shell` or <br> `shell-aways` or <br> `shell-escape` or <br> `shell-escape-always` or <br> `c` or <br> `c-maybe` or <br> `escape` or <br> `locale` or <br> `clocale` - show non graphic characters as-is (default unless program is 'ls' and output is a terminal) |
| <b>-r</b> | <b>--reverse</b> |сортировка с конца до начала |
| <b>-R</b> | <b>--recursive</b> |показывать полный список файлов , находящихся в каталогах и дочерних каталогах |
| <b>-s</b> | <b>--size</b> |print the allocated size of each file, in blocks |
| <b>-S</b> | <b></b> |сортировать по размеру |
| <b></b> | <b>--sort=</b> | |
| <b></b> | <b>--time=</b> | |
| <b></b> | <b>--time-style=</b> | |
| <b>-t</b> | <b></b> | |
| <b>-T</b> | <b>--tabsize=</b> | |
| <b>-u</b> | <b></b> | |
| <b>-U</b> | <b></b> | |
| <b>-v</b> | <b></b> | |
| <b>-w</b> | <b>--width=</b> | |
| <b>-x</b> | <b></b> | |
| <b>-X</b> | <b></b> | |
| <b>-1</b> | <b></b> | |
| <b>WHERE</b> | ------------<b>IT</b>----------- | <b>IS SELinux</b> |
| <b></b> | <b>--lcontext</b> | |
| <b>-Z</b> | <b>--context</b> | |
| <b></b> | <b>--scontext</b> | |
| <b></b> | <b>--help</b> | |
| <b></b> | <b>--version</b> | |

