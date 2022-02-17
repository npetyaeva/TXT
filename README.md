# TXT

21. Создать внешний репозиторий c названием TXT.

    `https://github.com/npetyaeva/TXT.git`
22. Клонировать репозиторий XML на локальный компьютер.

    `git clone https://github.com/npetyaeva/TXT.git` 

    `cd TXT`
23. Внутри локального TXT создать файл “new.txt”.

    `touch new.txt`
24. Добавить файл под гит.

    `git add new.txt`
25. Закоммитить файл.

    `git commit -m "Added new.txt"`
26. Отправить файл на внешний GitHub репозиторий.

    `git push`
27. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.
    ```
    Name: Natalia Petyaeva,
    Age: 43,
    Pets: 3,
    Salary: 1000
    ```
28. Отправить изменения на внешний репозиторий. Использую команду `commit` с двумя параметрами: `-а` - проиндексирует отслеживаемые файлы (замена `git add`) и `-m` - написание комментария через командную строку:

       `git commit -am "Modified new.txt"`
       
       `git push`
29. Создать файл preferences.xml

    `touch preferences.txt`
    
    `git add preferences.txt`
30. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.
    ```
    Favority movie: Flashbacks of a Fool,
    Favority serias: Altered Carbon,
    Favority food: steak,
    Favority season: autumn,
    Country: Japan
    ```
31. Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT

    `touch sklls.txt`
    
    `git add skills.txt`    
    
    `vim sklls.txt`
    
    ```
    6. What is JSON, XML. Their structure.
    7. API testing.
    8. How to view read logs.
    9. Postman, Fidler.
    11. Dev Tools of web browsers (Google Chrome, FireFox).
    ```

32. Сделать коммит в одну строку.

    `git commit -am "Added preferences.txt & sklls.txt"`

33. Отправить сразу 2 файла на внешний репозиторий.

    `git push`
34. На веб интерфейсе создать файл bug_report.txt.
35. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

    `https://github.com/npetyaeva/TXT/blob/main/bug_report.txt`
36. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате TXT.
    
    ```
      #0001
      Missing product images on the Product page.
      Priority: High.
      Severity: Major.
      Еxpected result: Product images are displayed on the Product page.
      Actual result": All product images are missing on the Product page.
      Steps: 
          1. Open www.storeName.com.
          2. Find and select a product on the Main page and make sure that the Product page has loaded.                   
      Enviroment:
          OS: Windows 10
          Browser: Google Chrome 98.0.4758.102, (x86_64)
      Attachments: 
          link1": https://...
          link2": https://...
    ```
36. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
37. Синхронизировать внешний и локальный репозиторий XML

    `git pull`
