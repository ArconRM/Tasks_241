1. **Перемещение между директориями**
``` 
cd <путь_к_директории> 
```
Описание: Используется для смены текущей директории.

---

2. **Вывод списка файлов в директории**
```
ls
```
Описание: Выводит имена файлов и папок в текущей директории.  

---

3. **Вывод списка всех файлов в директории**
```
ls -a  
```
Описание: Выводит файлы, включая скрытые (начинающиеся с .), в текущей директории. Еще часто используемые флаги: ```-l``` (длинный вывод) и ```-h``` (вывод с размерами файлов)

4. **Создание папки с подпапками**
```
mkdir -p <папка>/<подпапка>/<подпапка подпапки>/...
```
Описание: Создает саму папку и все указанные через слеш до нее  

---

5. **Внутри папки создать файлик и записать в него что-нибудь**
```
echo "текст" > <имя файла>
```
Описание: Создает файл с указанным текстом.  

---

6. **Перемещение файла из одной директории в другую**
```
mv <путь_к_файлу> <путь_к_директории>  
```
Описание: Перемещает файл в указанную директорию.  

---

7. **Копирование файла из одной директории в другую**
```
cp <путь_к_файлу> <путь_к_директории>  
```
Описание: Копирует файл в указанную директорию. Чтобы скопировать рекурсивно - ```-r```  

---

8. **Переименование файла**
```
mv <старое_имя> <новое_имя>
```
Описание: Переименовывает файл.  

---

9. **Сравнение содержимого файла**
```
diff <файл1> <файл2>
```
Описание: Сравнивает содержимое двух файлов и выводит различия между ними.    

---

10. **Сортировка содержимого файла по возрастанию и убыванию**
```
Возрастание: sort <файл>

Убывание: sort -r <файл>
```  

---

11. **Удаление файлов и папок**
```
rm -r <директория>
```
Описание: Удаляет указанную директорию и все её содержимое. Самое интересное применение: rm -rf /