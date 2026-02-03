# UA-5305-Big-Data-Internship

Цей репозиторій створений для практичного відпрацювання навичок роботи з **Git**, **Code Review** та мінімізації **Merge Conflicts**.

---

## Основні правила 

1.  **Заборонено пушити в `main`**: Всі зміни вносяться тільки через Pull Requests.
2.  **Правило 2-х апрувів**: PR може бути замерджений лише після того, як принаймні **2 людей** перевірять код і натиснуть `Approve`.
3.  **Branch Naming**: Використовуємо префікс `part/`.
    * *Шаблон:* `part[номер_частини]/[прізвище_або_нік]`
    * *Приклад:* `part1/ronevych`

---

## Workflow

### 0. git clone 

```
git clone https://github.com/ikapu/UA-5305-Big-Data-Internship.git
```

### 1. Підготовка
Онови локальну версію проекту, щоб уникнути застарілих конфліктів:
```bash
git checkout main
git pull origin main
```

### 2. Створення гілки (шаблон зверху)

```
git checkout -b part1/your-nickname 
```

### 3. Додавання своєї частини в part1.txt (ВАЖЛИВО: старайтесь не робити зміни не у ваших рядках)

### 4. Закидаємо на сервер зміни

```
git add part1.txt
git commit -m "add first verse of the poem"
git push origin part[номер_частини]/[прізвище_або_нік]
```

### 5. Створення PR
Відкрийте Pull Request на GitHub. Додайте колег у Reviewers та чекайте апруви.
