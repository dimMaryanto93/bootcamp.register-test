# Bootcamp Test - Algoritma Dasar

Kerjakan **tanpa menggunakan Komputer/Laptop**, **tidak boleh menggunakan alat bantu apa pun seperti kalkulator dll**, baca pertanyaan secara teliti, waktu pengerjaan 60 menit.

1. Apa perbedaan operator `=` dengan `==` ?

2. Coba anda jelaskan apa yang anda ketahui tentang _object oriented programming_ ?

3. Bagimana dan apa output yang ditampilkan dari perintah berikut:

```java
int a = 0;

if(10 >= 10) {
  a = 100;
  System.out.println(a);
}
System.out.println("10");
```

4. Bagimana dan apa output yang ditampilkan dari perintah berikut:

```java
int a = 0;

while(a < 10){
  a++;
  
  int b = 1;
  do {  
    System.out.print(a);
    b++;
  while( b < 5 );
  System.out.println();
}
```

5. Contohnya saya punya tabel seperti berikut:

### table mst_products

| id              | name            | price           |
| :-------------  | :-------------  | :-------------  |
| 001             | Product 001     |        Rp.500   |
| 002             | Product 002     |       Rp.10.000 |
| 003             | Product 003     |       Rp.15.000 |

### table trx_transactions

| id     | cust_id | product_id   |           sell  |
| :------| :-----  | :----------- | :-------------  |
| 001    | 001     |         001  |        Rp.600   |
| 002    | 001     |         001  |       Rp.10.000 |
| 003    | 001     |         002  |       Rp.15.000 |

### table mst_customers

| id              | name            |
| :-------------  | :-------------  |
| 001             | Agus            |
| 002             | Rohman          |

buat query `sql` untuk menampilkan data seperti berikut:

```sql
Nama Agus membeli Product 001 dengan harga 600
Nama Agus membeli Product 002 dengan harga 10.000
Nama Agus membeli Product 003 dengan harga 15.000
```

6. Bagaimana output yang dihasilkan dari perintah berikut:

```java
String lang = "java";

if(lang.equalsIgnoreCase("Java"))
  System.out.println("Hasilnya sama");
else if( lang == "java") {
  System.out.println("hasilnya sama dengan java");
  System.out.println("perintah ke2 yang dijalankan");
} else { 
  System.out.println("Error");
}
```

7. Bagaimana output yang dihasilkan dari output berikut:

```java
for(int i = 0; i < 10; i++){

  for(int j = 0; j < i; j++) {
    System.out.print("j["+ j+"], ");
  }
  
  System.out.println("index i adalah "+ i);
  if(i == 5) break;
}
```

8. Apa output yang dihasilkan dari perintah berikut:

```java
Integer val = 110; 

val = (val + 2) * 0;
System.out.println("Nilai val sekarang adalah "+ val);

val = val + 10;
val++;
System.out.println("Nilai val sekarang adalah "+ val);
```

9. Coba anda analisis bagaimana output yang dihasilkan dari perintah berikut:

```java
int[] numbers = [5, 3, 6, 10, 20, 100, 20];
int val = numbers[4];
System.out.println("value dari variable val adalah "+ val);
```

10. Coba jelaskan apa perbedaan nilai `null` dengan `0`?
 
