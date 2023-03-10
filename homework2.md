Homework 3 linux terminal (GitBash) commands.

1. На локальном репозитории сделать ветки для:  
`$ cd terminalgitbash`  
`$ git checkout -b name # "name" - имя ветки которую хотите создать.`
- Postman # postman
- Jmeter # jmeter
- CheckLists # checklists
- Bag Reports # bag_reports
- SQL # sql
- Charles # charles
- Mobile testing # mobile_testing
2. Запушить все ветки на внешний репозиторий.  
`$ git push origin name # "name" - имя ветки которую хотите запушить на внешний репозиторий.`
3. В ветке Bag Reports сделать текстовый документ со структурой баг репорта.  
`$ git checkout bag_reports`  
`$ touch bag_report.txt`  
`$ vim bag_report.txt`  
`i # добавляем информацию.`  
`Esc`  
`:x`  
`Enter # выходим из редактора vim.`
4. Запушить структуру багрепорта на внешний репозиторий.  
`$ git status`  
`$ git add .`  
`$ git commit -m "New file txt"`  
`$ git push`
5. Вмержить ветку Bag Reports в Main.  
`$ git checkout main`  
`$ git merge bag_reports`
6. Запушить main на внешний репозиторий.  
`$ git status`  
`$ git add .`  
`$ git commit -m "New file txt"`  
`$ git push`
7. В ветке CheckLists набросать структуру чек листа.  
`$ git checkout checklists`  
`$ touch checklist.txt`  
`$ vim checklist.txt`  
`i # добавляем информацию.`  
`Esc`  
`:x`  
`Enter # выходим из редактора vim.`
8. Запушить структуру на внешний репозиторий.  
`$ git status`  
`$ git add .`  
`$ git commit -m "New file txt"`  
`$ git push`
9. На внешнем репозитории сделать Pull Request ветки CheckLists в main.  
`Заходим на внешний репозиторий и делаем все во вкладке Pull requests.`
10. Синхронизировать Внешнюю и Локальную ветки Main.  
`$ git pull`
