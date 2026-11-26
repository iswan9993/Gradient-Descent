#### Gradient-Descent
---
<p align="justify" style="text-indent:1.27cm">Dalam optimasi matematika dan pemodelan data, Gradient Descent adalah algoritma optimasi yang digunakan untuk mencari nilai minimum suatu fungsi kerugian (loss function). Algoritma ini bekerja secara bertahap dengan memulai dari suatu titik awal, menghitung gradien pada titik tersebut, kemudian memperbarui posisi berdasarkan arah gradien agar nilai fungsi semakin mendekati minimum.</p>

<p align="justify" style="text-indent:1.27cm">Untuk memahami cara kerja Gradient Descent, kita dapat menggunakan analogi seseorang yang sedang menuruni gunung. Bayangkan kita berada di atas gunung yang diselimuti kabut tebal sehingga tidak dapat melihat seluruh permukaan gunung maupun lokasi lembah yang menjadi tujuan. Kita hanya dapat merasakan kemiringan tanah di sekitar tempat kita berdiri untuk menentukan arah pergerakan berikutnya.</p>  

<p align="justify" style="text-indent:1.27cm">Jika permukaan tanah menurun ke arah kiri, kita dapat bergerak ke kiri. Setelah berpindah ke posisi baru, kita kembali mengamati kemiringan tanah untuk menentukan langkah selanjutnya. Proses tersebut dilakukan berulang kali hingga kita mendekati titik terendah. Ketika permukaan semakin landai, langkah yang diambil juga perlu diperhatikan agar kita tidak melewati titik minimum yang sedang dicari.</p>  

<p align="justify" style="text-indent:1.27cm">Analogi tersebut menggambarkan prinsip dasar Gradient Descent, yaitu menggunakan informasi kemiringan pada posisi saat ini untuk menentukan arah perubahan berikutnya. Dalam matematika, kemiringan tersebut dinyatakan sebagai gradien f(x)=x<sup>2</sup>+3 </p>  

$m=\frac{\Delta y}{\Delta x} =\frac{y_2 - y_1}{x_2 - x_1}$

<table border="0">
  <tr>
    <td>m  </td>
    <td>Gradient</td>
  </tr>
  <tr>
    <td>$\Delta y$</td>
    <td>Selisih perubahan tinggi vertikal </td>
  </tr>
  <tr>
    <td>$\Delta x$</td>
    <td>Selisih perubahan tinggi Horizontal </td>
  </tr>
</table>
<p>Titik awal posisi kita berada pada koordinat horizontal f(x), sehingga ketinggian gunung di titik ini adalah y<sub>1</sub> = f(x). Titik kedua atau titik bantu yang kita gunakan di depan posisi kita secara horizontal sejauh h. Maka, koordinat horizontal barunya menjadi x<sub>2</sub> = x+h, dan ketinggian bukit di depan kita otomatis menjadi y<sub>2</sub> = f(x+h). Sehingga jika kita substitusikan notasi fungsi ke dalam rumus gradient akan menjadi, </p>