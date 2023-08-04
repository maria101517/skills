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

11. Отправить сразу 2 файла на внешний репозиторий
```git add . && git commit -m "json/xml/2" && git push

12. В веб интерфейсе GitHub создать файл и сделать Commit.

```Add file --> Create new file --> Name: Linux.txt --> Commit changes```

13. Отредактировать в веб интерфейсе содержание файла.
 			    
```Linux.txt --> Edit file --> Commit changes```					    

14. Синхронизировать внешний и локальный репозитории

```git pull```
 
 



 
