  4. Создать файл “new.json”.
 plaintext
- This is gray background touch new.json 

 6. Добавить файл под гит.                                  - git add new.json

 7. Закоммитить файл.                                       - git commit -m 'new.json'

 8. Отправить файл на внешний GitHub репозиторий.           - git push

 9. Создать файлы new2.json, new2.xml, new2.txt             - touch new2.json new2.xml new2.txt

 10. Добавить файлы под гит.                                 - git add .

 11. Закоммитить файлы.                                     - git commit -m '3 files'

 12. Отправить файлы на внешний GitHub репозиторий.         - git push

 13. Отредактировать содержание файла “new2.txt” - написать 
информацию о себе (ФИО, возраст, количество домашних 
животных, будущая желаемая зарплата).                       - vim new2.txt
                                                            - нажать i
                                                            - ФИО - Червякова Надежда Александровна
                                                              возраст - 25 лет
                                                              количество домашних животных - 1
                                                              желаемая зарплата - 400 долларов
                                                            - нажать Esc
                                                            - ввести :wq
     
 14. Отредактировать содержание файла “new2.json” - написать 
информацию о себе (ФИО, возраст, количество домашних 
животных, будущая желаемая зарплата). 
Всё написать в формате JSON. - vim new2.json                - vim new2.json
                                                            - нажать i
                                                            - {"FIO" : "Chervaykova Nadezhda Aleksandrovna",
                                                               "age" : 25,
                                                               "animal" : 1,
                                                               "salary" : 400}
                                                            - нажать Esc
                                                            - ввести :wq

 15. Добавить и закоммитить “new2.txt” одной строчкой.      - git commit new2.txt -m 'txt'

 16. Добавить и закоммитить “new2.json” одной строчкой.     - git commit new2.json -m 'json'

 17. Отправить изменения на внешний репозиторий.            - git push

 18. Отредактировать содержание файла “new2.xml” - написать 
информацию о себе (ФИО, возраст, количество домашних 
животных, будущая желаемая зарплата). 
Всё написать в формате XML.                                 - vim new2.xml
                                                            - нажать i
                                                            - <info>
                                                              	<FIO>Chervaykova Nadezhda Aleksandrovna</FIO>
                                                                <age>25</age>
                                                                <animal>1</animal>
                                                                <salary>400</salary>
                                                              </info> 
                                                            - нажать Esc
                                                            - ввести :wq

 19. Добавить и закоммитить “new2.xml” одной строчкой.      - git commit new2.xml -m 'xml'


 20. Отправить изменения на внешний репозиторий.            - git push

 21. Отправить предыдущее домашнее задание по GitBush       
Terminal на внешний репозиторий.                            - git add .
                                                            - git commit -m 'linux'
                                                            - git push

 22. В веб интерфейсе GitHub создать файл new3.txt.         - Add file
							    - Create new file
							    - Commit new file

 23. Отредактировать в веб интерфейсе содержание 
файла “new3.txt” - написать информацию о своих 
предпочтениях (Любимый фильм, любимый сериал, 
любимая еда, любимое время года, страна 
которую хотели бы посетить).				    - Нажать на new3.txt
							    - Edit this file
							    - Любимый фильм - "Гарри Поттер", 
							      любимый сериал - "Сверхъестественное", 
							      любимая еда - бутеры,
							      любимое время года - весна, 
							      страна которую хотели бы посетить - Австрия, Норвегия.

 24. Сделать Commit changes (сохранить) изменения на 
веб интерфейсе.						    - Commit changes

 25. Синхронизировать внешний и локальный репозитории 
(слить изменения с внешнего репозитория).		    - git pull
 
 26. Отредактировать в веб интерфейсе содержание файла 
“new2.json” - добавить информацию о своих предпочтениях 
(Любимый фильм, любимый сериал, любимая еда, 
любимое время года, страна которую хотели бы посетить). 
Всё в формате JSON.					    - {
  								"FIO" : "Chervaykova Nadezhda Aleksandrovna",
 								"age" : 25,
  								"animal" : 1,
  								"salary" : 400,
  								"favorite movie" : "Harry Potter", 
  								"favorite TV series" : "Supernatural", 
  								"favorite food"  : "buters",
  								"favorite time of the year" : "spring", 
  								"the country you would like to visit" : ["Austria", "Norway"]
							      }

 27. Сделать Commit changes (сохранить) изменения 
на веб интерфейсе.				            - Commit changes

 28. Синхронизировать внешний и локальный репозитории 	    - git pull

 29. Отредактировать в веб интерфейсе содержание файла 
“new2.xml” - добавить информацию о своих предпочтениях 
(Любимый фильм, любимый сериал, любимая еда, 
любимое время года, страна которую хотели бы посетить). 
Всё в формате XML.					    - <info>
								<FIO>Chervaykova Nadezhda Aleksandrovna</FIO>
        							<age>25</age>
        							<animal>1</animal>    
								<salary>400</salary>	
								<favorite_movie>Harry Potter</favorite_movie>
								<favorite_TV_series>Supernatural</favorite_TV_series>
								<favorite_food>buters</favorite_food>
								<favorite_time_of_the_year>spring</favorite_time_of_the_year> 
								<the_country_you_would_like_to_visit>Austria, Norway</the_country_you_would_like_to_visit>
							      </info>

 30. Сделать Commit changes (сохранить) изменения 
на веб интерфейсе.	    			            - Commit changes

 31. Синхронизировать внешний и локальный репозитории.	 
