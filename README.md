Практическая №4 <br>
Вариант 1<br>
Задание: Реализуйте миграции для таблиц: iPhone (5 полей) Shop ( 3 поля) и свяжите их между собой.<br>

Некоторые используемые команды<br>
Shop:<br>
php yii migrate/create create_shop_table --fields=shop_id:primaryKey,name:string,location:string<br>
<br>
iPhone:<br>
php yii migrate/create create_iphone_table 
--fields=iphone_id:primaryKey,model:string,description:text,rating:integer,shop_id:foreignKey<br>

![Image alt](https://github.com/HevillDS/Practos4/raw/master/working.png)
