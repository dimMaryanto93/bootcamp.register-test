1. `10`
2. program akan menampilkan `Sekarang ada di index ke 0` secara terus menurus atau endless loop.
3. Operator `=` dan `==` yaitu
    - operator `=` digunakan untuk assignment atau memberikan nilai.
    - operator `==` digunakan untuk melakukan perbandingan.
4. querynya seperti berikut:
```sql
select 
  concat('Nama ', c.name, ' membeli ', p.nama, ' dengan harga ', t.sell) as nilai
from 
  mst_products p join trx_transactions t on t.product_id = p.id join
  mst_customers c on t.cust_id = c.id
```
5. Outputnya `Hasilnya sama`
6. Outputnya seperti berikut:
```java
index i adalah 0
j[0], index i adalah 1
j[0], j[1], index i adalah 2
j[0], j[1], j[2], index i adalah 3
j[0], j[1], j[2], j[3], index i adalah 4
j[0], j[1], j[2], j[3], j[4], index i adalah 5
```
7. Outpunya adalah `Nilai val sekarang adalah 1120`
8. Program eror, karena kita hanya mendefinisikan element 5. Sedangkan yang dimita adalah index ke `10` jadi menghasilkan `IndexOutOfBound`
