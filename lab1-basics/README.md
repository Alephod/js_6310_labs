## Порядок выполнения лабораторной работы 1
### Перейдите в папку лабораторной работы
cd lab1-basics
###  Создайте свою ветку
git checkout -b student-lab1-{ваш_номер}
### Создайте папку с решениями

mkdir solutions/student-{ваш_номер}

cp tasks/lab1-tasks.js solutions/student-{ваш_номер}/solution.js
### Выполните задания и тесты
cd solutions/student-{ваш_номер}
node solution.js
###  Закоммитьте и запушьте изменения
git add solutions/student-{ваш_номер}/solution.js

git commit -m "Lab 1 solution by student {номер}"

git push origin student-{ваш_номер}

### Сроки сдачи
Дата выдачи: 08.09.2025
Срок ревью: {дата + 14 дней}
Срок сдачи: ближайшая лабораторная работа, после прохождения ревью.

Важно: За работы сданные после дедлайна, за каждую неделю просрочки снимается 1 балл.

Удачи в выполнении! 🚀