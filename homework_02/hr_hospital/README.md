## Homework 02
### Ціль
Розробити модуль для автоматизації лікарні: ведення обліку лікарів та пацієнтів.
### Дані
Назва модуля "hr_hospital"
Перелік сутностей, для котрих потрібно створити нові моделі:
- Лікар 
- Пацієнт
- Види захворювань (хвороби)
- Візити пацієнтів
### Вимоги
- Створити нові моделі для кожної сутності.

- Створити власне меню для модуля, додати пункти підменю: "Пацієнти", "Лікарі".

- Додати до кожної моделі представлення: form та tree.

- Надати повні права доступу до записів нових моделей для групи користувачів "base.group_user".

* Додати наступні "майстер" дані:
* - створити три записи для моделі "Види захворювань"

- Додати наступні "демо" дані:
- - створити три записи для моделі "Лікар" (вказати лікаря, що спостерігає)
- - створити три записи для моделі "Пацієнт"


 - Завантажити модуль у власний (відкритий) репозиторій на GitHub.

-----------
Installation
-----------

To install this module, you need to:

1. Clone repository.
2. Add the repository path to the config file.
3. Update the app list.
4. Install the module.

'Don't forget to update `Apps List` by clicking on `Update Apps List` menu or use ` odoo-helper addons update-list
` in your terminal.'
