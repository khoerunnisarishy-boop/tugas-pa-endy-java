#Halo Java Program

Program ini adalah contoh sederhana penggunaan Java untuk menampilkan teks dan waktu saat ini menggunakan kelas `LocalDateTime`.

#Deskripsi

Program akan menampilkan dua hal:

1. Pesan sapaan: **"Halo Rishy Cantik"**
2. Waktu saat ini, diambil menggunakan `LocalDateTime.now()`

#Kode Sumber

```java
import java.time.LocalDateTime;

public class Halo {
    public static void main(String[] args) {
        System.out.println("Halo Rishy Cantik");
        System.out.println("Waktu saat ini :" + LocalDateTime.now());
    }
}
```

#Cara Menjalankan Program

1. Pastikan Java sudah terinstall (minimal Java 8).
2. Simpan file dengan nama **Halo.java**
3. Buka terminal atau command prompt di folder tempat file disimpan.
4. Compile program:

   ```sh
   javac Halo.java
   ```
5. Jalankan program:

   ```sh
   java Halo
   ```

#Contoh Output

```
Halo Rishy Cantik
Waktu saat ini :2025-11-14T10:25:30.123
```

#Catatan

Program ini dibuat untuk demonstrasi dasar Java, khususnya:

* Cara membuat program sederhana dengan `main()`.
* Cara menggunakan `LocalDateTime` untuk mengambil waktu real-time.

---

Jika ingin dibuat versi README yang lebih formal, lengkap, atau dengan badge GitHub, tinggal bilang ya!

