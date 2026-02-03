# UA-5305-Big-Data-Internship

This repository was created for practical training in **Git**, **Code Review**.

---

## Main Rules

1. **Pushing to `main` is prohibited**: All changes must be submitted via Pull Requests only.
2. **1-Approval Rule**: A PR can only be merged after at least **1 people** have reviewed the code and clicked `Approve`.
3. **Branch Naming**: Use the `part/` prefix.
    * *Template:* `part[part_number]/[surname_or_nickname]`
    * *Example:* `part1/ronevych`

---

## Workflow

### 0. git clone

```
git clone https://github.com/ikapu/UA-5305-Big-Data-Internship.git
```

### 1. Preparation

Update local version of project to avoid conflicts.
```bash
git pull origin main
```

### 2. Branch Creating

```
git checkout -b part1/your-nickname 
```

### 3. Add your part of task to part1.txt 

### 4. Pushing your changes onto the server

```
git add part1.txt
git commit -m "add first verse of the poem"
git push origin part[номер_частини]/[прізвище_або_нік]
```

### 5. Create,review and merge PR.
