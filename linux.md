1) Посмотреть где я
   
```pwd```

2) Создать папку

```mkdir linux```

3) Зайти в папку
   
```cd linux```

4) Создать 3 папки
    
```mkdir fol_1 fol_2 fol_3```

5) Зайти в любоую папку
   
```cd fol_1```

6) Создать 5 файлов (3 txt, 2 json)
     
```touch 1.txt 2.txt 3.txt 4.json 5.json```

7) Вывести список содержимого папки
     
```ls -la```

8) Создать и редактировать файл через cat
     
```cat > 4.txt``` выход ctrl+c

9) Открыть любой txt файл
       
```vim 1.txt```

Написать туда что-нибудь, любой текст 

```i ввод текста```

Сохранить и выйти 

```esc : x ```

10) Выйти из папки на уровень выше
     
```cd ..```

11) переместить любые 2 файла в любую другую папку
    
```mv fol_1/{1,2}.txt fol_2```

12) скопировать и переименовать 2 файла в другую папку
     
```cp fol_1/3.txt fol_3/a.txt```

```cp fol_1/4.json fol_3/b.json```

13) Найти файл по имени
    
```find . -name 1.txt```

14) Просмотреть содержимое в реальном времени
     
```tail -f fol_2/1.txt``` выход ctrl+c

15) вывести несколько первых строк из текстового файла
    
```head -n5 fol_2/1.txt```

16) вывести несколько последних строк из текстового файла
      
```tail -n5 fol_2/1.txt```

17) просмотреть содержимое длинного файла
    
```less fol_2/1.txt```
выход q

18) Найти инфо по тексту в файле
    
```grep text linux *```

19) вывести дату и время
     
```date```
или 

```date +"%d.%m.%y"```

history
