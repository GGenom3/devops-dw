**JAWABAN**
<br>
Untuk mencari file dengan hanya isinya saja yang diketahui bisa menggunakan command grep dengan optionnya
<br>
Perintahnya dengan mengetikan grep -rnw '/pathnya/misal/home/' -e 'isi kalimatnya yang dicari'
<br>
<br>
-r rekursif yang berati akan mencari di lokasi itu berulang
<br>
-n menunjukan pada line number berapa di file tersebut ditemukan
<br>
-w yang menunjukan seluruh kalimatnya atau word nya
<br>
lalu masukan path direktorinya yang akan dicari
<br>
-e untuk penggunaan pattern untuk matching kalimatnya
<br>
berikut hasil screenshootnya untuk mencari file yang berisi print
<br>
![hasil](./Images/Images1.png)
