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
```git push
```
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
Зайти на свой github -->

Выбрать репозиторий Course_VK

Нажать на кнопку

10. Синхронизировать Внешнюю и Локальную ветки Main
