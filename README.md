# Final thesis from Web technologies

## TODO

- [x] Add to [Installation](#installation), step to import database
  - [x] Export table and add into repository
  - [x] Create import command
  - [ ] Delete .env files
- [ ] Make the project more user friendly

## Menu

- [About](#about)
- [Installation](#installation)

## About

Create a web application using advanced programming methods. Ideally using a framework (symfony, nette,...) and using a database. The topic needs to be consulted and approved by the tutor. Sample work will be available by appointment.

## 🖥️ Installation

1. Download all project files

```bash
git clone https://github.com/Lynder063/WT_final_thesis.git &&
cd WT_final_thesis/
```

2. Make Composer install the project's dependencies into vendor/

```bash
composer install
```

3. Import `malinda.sql` to your database

```sql
mysql -u [username] -p [database_name] < malinda.sql
```

4. Running web app

```bash
symfony server:start -d
```
