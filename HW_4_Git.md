1. На локальном репозитории сделать ветки для:
- Postman
```git branch Postman```
- Jmeter
```git branch Jmeter```
- CheckLists
```git branch CheckList```
- Bug_Reports
```git branch Bug_Reports``` 
- SQL
```git branch SQL```
- Charles
```git branch Charles```
- Mobile_testing
```git branch Mobile_testing```

2. Запушить все ветки на внешний репозиторий
- ```git push -u origin Postman```
- ```git push -u origin Jmeter```
- ```git push -u origin Checklists```
- ```git push -u origin Bug_Reports```
- ```git push -u origin SQL```
- ```git push -u orugun Charles```
- ```git push -u origin Mobile_testing```

3. В ветке Bug_Reports сделать текстовый документ со структурой баг репорта
```
git checkout Bug_Reports
touch bug_report.md
vim bug_report.md
i
#ввести структуру баг репорта
ESC :wq ENTER
```
4. Запушить структуру багрепорта на внешний репозиторий
```
git add bug_report.md
git commit -m "Add file bug_report.md to Bug_Reports branch"
git push
```
5. Вмержить ветку Bug_Reports в Main
```
git checkout master
git merge Bug_Reports
```

6. Запушить main на внешний репозиторий
```git push```

7. В ветке CheckLists набросать структуру чек листа.
```
git checkout Checklists
touch checklist.md
vim checklist.md
i
#ввести структуру чек-листа
ESC :wq ENTER
```
8. Запушить структуру на внешний репозиторий
```
git add checklist.md
git commit -m "Add file checklist.md to Checklists branch"
git push
```
9. На внешнем репозитории сделать Pull Request ветки CheckLists в main

Зайти на свой [github](https://github.com/OlesyaMashuk)

Выбрать репозиторий [Course_VK](https://github.com/OlesyaMashuk/Course_VK)
![Screenshot_13](https://user-images.githubusercontent.com/91422609/174664793-9215a434-7240-46e4-954e-0f58540b2919.png)

Нажать на кнопку 

![Screenshot_14](https://user-images.githubusercontent.com/91422609/174664994-78d8dc80-52ff-4de7-a819-9d4aa113ce6e.png)

Под заголовком Open a pull request должно быть указано см.скриншот, написать Add file checklist.md to Checklists branch
![Screenshot_15](https://user-images.githubusercontent.com/91422609/174665047-5a8b1bc1-281a-454d-b847-7d53f45f2436.png)

Нажать на кнопку 

![Screenshot_16](https://user-images.githubusercontent.com/91422609/174665207-e7e2a253-40aa-4be0-ae60-2f6c5ebc0f7d.png)

После проверки возможности слияния веток есть сообщение
![Screenshot_17](https://user-images.githubusercontent.com/91422609/174665295-dbb00c08-4d70-4133-82a2-0ac6e8c17622.png)

Нажать на кнопку

![Screenshot_18](https://user-images.githubusercontent.com/91422609/174665340-8951b37c-05c7-4fac-bc44-0041f4cdb858.png)

После слияния веток есть сообщение
![Screenshot_19](https://user-images.githubusercontent.com/91422609/174665463-272a28b6-b073-4074-9c99-61a0b5fbcd25.png)

10. Синхронизировать Внешнюю и Локальную ветки Main
```
git checkout master
git pull
```
**main = master**
