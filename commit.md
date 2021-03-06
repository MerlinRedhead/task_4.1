# ``git commit``

``git commit`` - это команда для записи индексированных изменений в репозиторий Git.
---

>## Прежде чем создавать очередной коммит, необходимо проиндексировать файлы в рабочей области с помощью команды ``git add``. Новый коммит будет включать текущие состояния индексированных файлов плюс последние сохраненные состояния неиндексированных (но отслеживаемых) файлов. Обратите внимание: коммит включает в себя не изменения (дельты, патчи) относительно предыдущего коммита, а "снимок" (англ. shapshot) текущего состояния рабочей области.
---
>>**Приведем пример: 
  Допустим мы дополнили свой проект какими-то фичами, выполнили команду ``git add ``. И после этой команды говорим что обновили наш репозиторий командой:**
    
```bash
git commit -m "update"
```
---
Перейдем к кмоанде:[git clone](clone.md)