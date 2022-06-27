 1. Создать внешний репозиторий c названием JSON. - new 
 2. Клонировать репозиторий JSON на локальный компьютер. – git clone 
 3. Внутри локального JSON создать файл “new.json”. – touch new.json
 4. Добавить файл под гит. – git add new.json
 5. Закоммитить файл. git commit -m "add file .json"
 6. Отправить файл на внешний GitHub репозиторий. – git push
 7. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON. – vim new.json – I (режим заполнения) – esc, :wq (выход из режима заполнения, выход с сохранением) 
 8. Отправить изменения на внешний репозиторий. – git add new.json, git commit -m “add new information”, git push 
 9. Создать файл preferences.json - touch preferences.json
 10. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON. vim preferences.json – I (режим заполнения) – esc, :wq (выход из режима заполнения, выход с сохранением) 
 11. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON touch skills.json, vim skills.json – I (режим заполнения) – esc, :wq (выход из режима заполнения, выход с сохранением) 
 12. Отправить сразу 2 файла на внешний репозиторий. 
git add preferences.json skills.json
git commit -m "add information about preferences and skills"
git push
 13. На веб интерфейсе создать файл bug_report.json. add file 
 14. Сделать Commit changes (сохранить) изменения на веб интерфейсе. commit new file 
 15. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON. Edite this file
 16. Сделать Commit changes (сохранить) изменения на веб интерфейсе. Commite changes 
 17. Синхронизировать внешний и локальный репозиторий JSON - git pull 
