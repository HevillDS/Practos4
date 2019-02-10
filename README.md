Практическая №4
Вариант 1
Задание: Реализуйте миграции для таблиц: iPhone (5 полей) Shop ( 3 поля) и свяжите их между собой.

Некоторые используемые команды
Shop:
php yii migrate/create create_shop_table --fields=shop_id:primaryKey,name:string,location:string

iPhone:
php yii migrate/create create_iphone_table 
--fields=iphone_id:primaryKey,model:string,description:text,rating:integer,shop_id:foreignKey

![Image alt](https://github.com/HevillDS/Practos4/raw/master/working.png)
