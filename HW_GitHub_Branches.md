## Homework GitHub Branches


| Задание | Решение |
| --- |  --- |
|1. На локальном репозитории сделать ветки для: Postman, Jmeter, CheckLists, Bug_Reports, SQL, Charles, Mobile testing |```git branch ```|
|2. Запушить все ветки на внешний репозиторий |```git push --all```|
|3. В ветке Bug Reports сделать текстовый документ со структурой баг репорта |```touch bugreport.txt```|
|4. Запушить структуру багрепорта на внешний репозиторий |```git add bugreport.txt``` -> ```git commit -m "add bugreport.txt"``` -> ```git push --set-upstream origin Bug_reports ```|
|5. Вмержить ветку Bug_Reports в Main |```git checkout main```-> ```git merge Bug_reports```|
|6. Запушить main на внешний репозиторий |```git push --all```|
|7. В ветке CheckLists набросать структуру чек листа |```git checkout Check_Lists``` -> ```touch check_lists.txt```|
|8. Запушить структуру на внешний репозиторий |```git push --set-upstream origin Check_Lists```|
|9. На внешнем репозитории сделать Pull Request ветки CheckLists в main |Pull Request branch Check_Lists|
|10. Синхронизировать Внешнюю и Локальную ветки Main |```git pull```|