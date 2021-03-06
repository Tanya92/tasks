#  "Markdown & Git"

### Deadline: 03-03-2019 23:59

## Задание 
Вам необходимо создать markdown документ. Что такое markdown можно прочитать тут - https://guides.github.com/features/mastering-markdown/

Содержание документа - ваше резюме.  
Вот рекомендации к контенту от EPAM HR-ов:
```
Что должно содержать в себе резюме Junior разработчика?
 
! Важно: по-возможности составлять резюме на английском

1. Имя, фамилия (реальные)
2. Контакты (желательно несколько)
3. Summary (цель, пожелания, раскрыть, что важно, что хочется и почему. 
Некий вариант самопрезентации. Когда опыта минимум, джун продает свой потенциал, 
свое желание и способность быстро учиться. Не занимать позицию, что он придет, 
и все кинутся его учить. Но обратное – у джуна время все брать, отовсюду, всегда и т.д.).
4. Skills (например: языки программирования, фреймворки, методологии, системы контроля версий, тулы...)
5. Примеры кода (по возможности СВЕЖИЕ)
6. Опыт (Junior-у имеет смысл указать весь опыт: тестовые задания, проекты с курсов,
фрилансовые проекты – все, где он применял вышеупомянутые скилы. 
Круто, если это будет со ссылками на код)
7. Образование (в т.ч. курсы, семинары, лекции, онлайн-обучение)
8. Уровень английского (тут стоит указать, какая именно практика была, как долго и т.д.) 
```
**NOTE!** Рекомендуется использовать ваши реальные данные, но и фейковые тоже подойдут. 

Документ должнен быть размещен на GitHub Pages (https://pages.github.com/), это произойдет автоматически при создании `gh-pages` бранча. После чего страница будет доступна по адресу вида - https://your-githab-account.github.io/rsschool-2019Q1-cv/cv  

### Требования к репозиторию: 
1. Вам необходимо создать публичный репозиторий c названием  `rsschool-2019Q1-cv` на вашем GitHub аккаунте.
2. В `master` бранче должен быть только один файл - `readme.md` содержащий ссылку вида https://your-githab-account.github.io/rsschool-2019Q1-cv/cv. 
3. Сам документ с название `cv.md` должен находиться в бранче `gh-pages`. 
4. После выполнения задания вам необходимо создать Pull Request `gh-pages`->`master`.

### Требования к коммитам
- Минимум 3 коммита
- Названия коммитов должны быть согласно гайдлайна - https://www.conventionalcommits.org/en/v1.0.0-beta.2/ 
Основные требования:
```
  * Allowed Types:
    * docs: - *documentation only changes*
    * feat: - *a new feature*
    * fix: - *a bug fix*
    * perf: - *a code change that improves performance*
    * refactor: - *a code change that neither fixes a bug nor adds a feature*
    * style: - *сhanges that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc)*
    * ...
  * Use the present tense ("add feature" not "added feature")
  * Use the imperative mood ("move cursor to..." not "moves cursor to...")
  * Limit the first line to 72 characters or less
  * Reference issues and pull requests liberally after the first line
```

### Требования к оформлению PR (Pull Request)
1. PR name should contains **the task name** and probably additional info.
2. Changes **must not contain commented code, unnecessary files, changes from other branches and generated files** like *.bundle.js. Please review your changes before contributing. .editorconfig, .gitignore, etc. can be included.
3. Comments in the PR are good practice.
4. [How to write the perfect Pull Request](https://github.com/blog/1943-how-to-write-the-perfect-pull-request)

### Критерии оценки
- +25 баллов, если требования к заданию выполены
