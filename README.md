# SQL_odev8
## *1. test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.*

### **SELECT AVG(rental_rate) from film;**

## *2. Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.*

### **insert into employee (id, name, birthday, email) values (1, 'Ford Sporner', '1977-03-28', 'fsporner0@qq.com');**
...

## *3. Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.*

### **UPDATE employee SET name = 'Ali Aliyev' WHERE id = 10;**
...

## *4. Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.*

### **DELETE FROM employee WHERE id = 10;**
...
