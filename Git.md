1. Создать внешний репозиторий c названием skills 

``` New --> Repository name ... --> Check "Add a README file" --> "Create repository" ```

2. Клонировать репозиторий skills на локальный компьютер

```git clone https://github.com/maria101517/skills.git```

3. Зайти в папку

```cd skills```

4. Локально создать 2 файла
 
```touch XML.xml JSON.json ```

5. Добавить файл под гит.                                  
 
```git add XML.xml JSON.json```

6. Закоммитить файл.                                       

```git commit -m 'xml/json'```

7. Отправить файлы на внешний GitHub репозиторий.         

```git push```

8. Отредактировать содержание файла.                    

```vim JSON.json```

нажать i

```
{
   "name": "Maria",
   "the country you would like to visit": ["Japan", "Australia"],
   "pets": [
      {
         "name": "Steve",
         "species": "dog",
         "age": 1
      },
      {
         "name": "Asyka",
         "species": "cat",
         "age": 8
      }
   ]
}
```

нажать Esc
ввести :wq
     
9. Отредактировать содержание файла.

```cat >> XML.xml```

```
<info>
      <favorite_movies>
         <movie>Perfume</movie>
         <movie>In Time</movie>
         <movie>Inception</movie>
      </favorite_movies>
      <season>Spring</season>
   <hobbies>
      <hobby>movies</hobby>
      <hobby>books</hobby>
      <hobby>creating paintings from epoxy resin</hobby>
   </hobbies>
</info>
```
ввести ctrl+c

10. Посмотреть состояние рабочего каталога.
    
```git status```

11. Отправить сразу 2 файла на внешний репозиторий.
    
```git add . && git commit -m "json/xml/2" && git push```

12. В веб интерфейсе GitHub создать файл и сделать Commit.

```Add file --> Create new file --> Name: Linux.txt --> Commit changes```

13. Отредактировать в веб интерфейсе содержание файла.
 			    
```Linux.txt --> Edit file --> Commit changes```					    

14. Синхронизировать внешний и локальный репозитории

```git pull```

15. На локальном репозитории создать веткую

```git branch Mobile_testing```

```git branch Charles```

16. Запушить ветки на внешний репозиторий.
 
```git push -u origin --all```

17. В ветке Mobile_testing создать текстовый документ.

```git checkout Mobile_testing``` 

```vim Mobile_testing.txt```

18. Запушить структуру файла Mobile_testing на внешний репозиторий.

```git add Mobile_testing.txt```

```git commit -m "comment"```

```git push origin Mobile_testing```

19. Вмержить ветку Mobile_testing в Main.

```git checkout main``` 

```git merge Mobile_testing```

20. Запушить main на внешний репозиторий.

```git push origin main```.

21. В ветке Charles создать файл.

```git checkout Charles```

```vim Charles.txt```

23. Запушить структуру на внешний репозиторий.

```git add Charles.txt```
 
```git commit -m "comment"```

```git push origin Charles```

24. На внешнем репозитории сделать Pull Request ветки Charles в main

```Compare & pull request --> Create pull request --> Merge pull request --> Confirm merge```

25. Синхронизировать Внешнюю и Локальную ветки Main.

```git checkout main```

```git pull origin main```




 
