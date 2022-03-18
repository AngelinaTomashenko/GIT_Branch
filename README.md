## GIT_Branch
# work with branches
**1. На локальном репозитории сделать ветки для:**
- Postman
- Jmeter
- Check_Lists
- Bug_Reports
- SQL
- Charles
- Mobile_testing

> Git Branch "branch name"

**2. Запушить все ветки на внешний репозиторий**
> git push -u origin --all

**3. В ветке Bag Reports сделать текстовый документ со структурой баг репорта**
> checkout bug_reports -> touch bug_report.txt -> nano bug_report.txt

**4. Запушить структуру багрепорта на внешний репозиторий**
> git add . -> git commit -m "bug_rep" -> git push

**5. Вмержить ветку Bag Reports в Main**
> git checkout main -> git merge bug_reports

**6. Запушить main на внешний репозиторий**
> git push

**7. В ветке CheckLists набросать структуру чек листа**
> git checkout check_lists -> touch check_list.txt -> nano check_list.txt

**8. Запушить структуру на внешний репозиторий**
> git commit -m "check_list" -> git push

**9. На внешнем репозитории сделать Pull Request ветки CheckLists в main**
> GitHub -> go to pull requests -> press button "new pull request" -> select base branch "main" & select compare branch "check_lists" -> pull request

**10. Синхронизировать Внешнюю и Локальную ветки Main**
> git pull
