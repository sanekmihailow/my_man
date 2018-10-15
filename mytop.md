### Synopsys
```bash
mytop [options] [args]
```
### опции для запуска утилиты
<d>
  <details>
  
| ***option short*** | ***option long*** | ***<arguments> and Description*** |
|---|---|---|
| <b>-b</b> | <b>--batch</b> or<br> <b>--batchmode</b> |одноразово рисует показ монитора, как выполниить top через screen|
|  | <b>--color</b> or<br> <b>--nocolor</b> |highlight вывод или нет  |
| <b>-d</b> | <b>--db</b> or<br> <b>--database</b> |<database> - выбор базы данных|
| <b>-h</b> | <b>--host</b> |<hostname> - испольовать Hostname, `default - localhost`  |
| <b>-i</b> | <b>--idle</b> or<br> <b>--noi</b> or<br> <b>--noidle</b> |Показывать спящие(idle) потоки в выводе|
|  | <b>--long</b> or<br> <b>--nolong</b> |не использовать сокращение чисел или использовать   |
| <b>-m</b> | <b>--mode</b> |$mode$ - variables:  qps(queries/second), top(overview), cmd(command summary), innodb(InnoDB status) or status()  |
| <b>-P</b> | <b>--port</b> |<port> - использовать порт , `default - 3306`  |
|  | <b>--resolve</b> | If you have skip-resolve set on MySQL (to keep it from doing a reverse DNS lookup on each inbound connection), mytop can replace IP addresses with hostnames |
| <b>-s</b> | <b>--delay</b> |<seconds> - устанавливает время обновления картинки на экране , `default - 5`  |
| <b>-S</b> | <b>--socket</b> |<path/to/socket> - возможность использовать вместо <hostname>:<port>  |
|  | <b>--sort</b> or<br> <b>--nosort</b> |Сортиировка по возврастанию или убыванию , `default - nosort`  |
| <b>-u</b> | <b>--user</b> |$username$ - использовать пользователя , `default - root` |
  
  </details>
</d>  

### hotkeys внутри утилиты
| ***key*** | ***Description*** |
|---|---|
| <kbd>?</kbd> | показать справку | 
| <kbd>#</kbd> | Вкл/Выкл показ не сокращенных чисел |  
| <kbd>:</kbd> | ввести команду (не работает) |  
| <kbd>!</kbd> | Пропустить ошибки останавливающие репликацию (на свой страх и риск)
| <kbd>c</kbd> | отобразить счетчики команд (основываясь на Com_* counters)  выйти обратно только через "t" |  
| <kbd>C</kbd> | Вкл/Выкл подцветку |  
| <kbd>d</kbd> | показать другую БД |
| <kbd>e</kbd> | показать запрос который запущен в потоке |  
| <kbd>E</kbd> | показать текущие ошибки репликации |  
| <kbd>f</kbd> | показать все инфу о запросах в выбранном потоке |  
| <kbd>F</kbd> | снять все фильтры |
| <kbd>h</kbd> | показывать информацию только о выбранном хосте |  
| <kbd>H</kbd> | Вкл/Выкл показ только потоков |
| <kbd>i</kbd> | Вкл/Выкл показ idle(спящик) потоков |  
| <kbd>I</kbd> | показать InnoDB статус |  
| <kbd>k</kbd> | убить выбранный поток |  
| <kbd>l</kbd> | изменить продолжительность длинных запросов| 
| <kbd>m</kbd> | переключить вид на запросы qps (queries/sec) с возможность скроллинга |  
| <kbd>o</kbd> | Вкл/Выкл обратную сортировку (снизу вверх) |  
| <kbd>p</kbd> | запаузить экран |  
| <kbd>q</kbd> | выйти|
| <kbd>r</kbd> | сбросить статусы счетчиков (via FLUSH STATUS on your server) |  
| <kbd>R</kbd> | change reverse IP lookup  |  
| <kbd>s</kbd> | задать задержку между обновление данных на экране |  
| <kbd>S</kbd> | задать задержку для медленных запросов| 
| <kbd>t</kbd> | вернуть в первоначальное состояние экрана (default) |  
| <kbd>u</kbd> | показать потоки только для выбранного пользователя |  
|  |  |
