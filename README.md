# Bootcamp Test - Algoritma Dasar

Kerjakan **tanpa menggunakan Komputer/Laptop**, **tidak boleh menggunakan alat bantu apa pun seperti kalkulator dll**, baca pertanyaan secara teliti, waktu pengerjaan 30 menit.

1. Apa yang ditampilkan dari perintah berikut:

```java
int a = 0;

if(a == 10)
System.out.print(a);
System.out.println("10");
```

2. Coba anda analisis apa yang terjadi dengan perulangan berikut:

```java
int a = 0;
while(a < 10)
System.out.println("Sekarang ada di index ke "+ a);
```

3. Apa perbedaan operator `=` dengan `==` :

4. Contohnya saya punya tabel seperti berikut:

### Product

| id              | nama            | harga           |
| :-------------  | :-------------  | :-------------  |
| 001             | Product 001     |        Rp.500   |
| 002             | Product 002     |       Rp.10.000 |
| 003             | Product 003     |       Rp.15.000 |

### Transaksi

| id     | cust_id | product_id   |           jual  |
| :------| :-----  | :----------- | :-------------  |
| 001    | 001     |         001  |        Rp.600   |
| 002    | 001     |         001  |       Rp.10.000 |
| 003    | 001     |         002  |       Rp.15.000 |

### Customer

| id              | nama            |
| :-------------  | :-------------  |
| 001             | Agus            |
| 002             | Rohman          |

buat query `sql` untuk menampilkan data seperti berikut:

```sql
Nama Agus membeli Product 001 dengan harga 600
Nama Agus membeli Product 002 dengan harga 10.000
Nama Agus membeli Product 003 dengan harga 15.000
```

5. Bagaimana output yang dihasilkan dari perintah berikut:

```java
String lang = "java";
if(lang.equalIgnoreCase("Java"))
  System.out.println("Hasilnya sama");
else if( lang == "java") {
  System.out.println("hasilnya sama dengan java");
  System.out.println("perintah ke2 yang dijalankan");
} else System.out.println("Error");
```

6. Bagaimana output yang dihasilkan dari output berikut:

```java
for(int i = 0; i < 10; i++){
  for(int j = 0; j < i; j++)
    System.out.print("j["+ j+"], ");
  System.out.println("index i adalah "+ i);
  if(i == 5) break;
}
```

7. Apa output yang dihasilkan dari perintah berikut:

```java
Integer val = 110; val+=2;
val = val * 10;
System.out.println("Nilai val sekarang adalah "+ val);
```

8. Coba anda analisis bagaimana output yang dihasilkan dari perintah berikut:

```java
List<Integer> numbers = Arrays.asList(2, 3, 4, 5, 6, 10);
String val = numbers.get(10).toString();
System.out.println("value dari variable val adalah "+ val);
```
 
