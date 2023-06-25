# Projek-UAS-PAA-II
## Nurul Aliyah Dyah Sakhinah - F55121069 - B

## **Analisa Algoritma Bubble Sort dan Insertion Sort**
Analisis hasil dari algoritma Bubble Sort dan Insertion Sort untuk evaluasi best case, average case, dan worst case dapat dilakukan dengan mempertimbangkan jumlah elemen dalam array yang diurutkan.

**1. Bubble Sort:**

a. Best case: Jika array sudah terurut secara ascending, maka algoritma Bubble Sort akan memiliki kinerja terbaik. Pada kasus ini, algoritma hanya memerlukan satu iterasi untuk membandingkan seluruh elemen dan tidak ada pertukaran yang dilakukan. Namun, pada implementasi Bubble Sort yang diberikan, iterasi terakhir tetap dilakukan walaupun array sudah terurut, sehingga tidak ada keuntungan nyata dalam hal waktu eksekusi. Karena itu, best case time complexity dari Bubble Sort tetap O(n^2).

b. Average case: Pada average case, waktu eksekusi Bubble Sort memiliki kompleksitas O(n^2), di mana n adalah jumlah elemen dalam array. Algoritma melakukan iterasi sebanyak n kali dan pada setiap iterasi, membandingkan dan menukar elemen-elemen yang tidak terurut.

c. Worst case: Pada worst case, waktu eksekusi Bubble Sort juga memiliki kompleksitas O(n^2). Hal ini terjadi ketika array diurutkan secara descending. Pada setiap iterasi, algoritma harus membandingkan dan menukar elemen-elemen yang semakin besar nilainya.

**2. Insertion Sort:**

a. Best case: Jika array sudah terurut secara ascending, maka algoritma Insertion Sort akan memiliki kinerja terbaik. Pada kasus ini, algoritma hanya memerlukan satu iterasi untuk membandingkan seluruh elemen dan tidak ada pergeseran elemen yang dilakukan. Waktu eksekusi pada best case adalah O(n), di mana n adalah jumlah elemen dalam array.

b. Average case: Pada average case, waktu eksekusi Insertion Sort memiliki kompleksitas O(n^2). Algoritma melakukan iterasi sebanyak n kali dan pada setiap iterasi, membandingkan dan menggeser elemen-elemen yang tidak terurut.

c. Worst case: Pada worst case, waktu eksekusi Insertion Sort juga memiliki kompleksitas O(n^2). Hal ini terjadi ketika array diurutkan secara descending. Pada setiap iterasi, algoritma harus membandingkan dan menggeser seluruh elemen sebelum elemen yang sedang diiterasi.

Dari hasil yang diberikan, terlihat bahwa algoritma Bubble Sort dan Insertion Sort menghasilkan hasil pengurutan yang sama untuk array yang diberikan. Namun, Bubble Sort membutuhkan waktu eksekusi yang lebih lama dibandingkan dengan Insertion Sort.



## **Analisa Algoritma TSP dan Dijkstra**
Berikut adalah analisis untuk best case, average case, dan worst case dari kedua algoritma

**1. Algoritma TSP**

a. Best Case: Best case terjadi ketika grafik memiliki sedikit simpul dan jarak antara simpul-simpulnya relatif sama. Dalam kasus ini, kompleksitas waktu algoritma TSP akan cenderung lebih baik. Pada contoh grafik yang diberikan, best case terjadi ketika simpul-simpul yang dikunjungi sedikit dan jarak antara simpul-simpulnya relatif sama. Hasil yang didapatkan adalah shortest path a -> c -> e -> f dengan jarak terpendek 19. Waktu komputasi yang sangat kecil menunjukkan best case.

b. Average Case: Average case terjadi ketika grafik memiliki jumlah simpul yang sedang dan distribusi jarak antara simpul-simpulnya merata. Pada contoh grafik yang diberikan, average case terjadi ketika jumlah simpul yang dikunjungi sedang dan distribusi jarak antara simpul-simpulnya merata. Hasil yang didapatkan adalah shortest path a -> c -> e -> f dengan jarak terpendek 19. Waktu komputasi yang sangat kecil menunjukkan average case.

c. Worst Case: Worst case terjadi ketika grafik memiliki banyak simpul dan jarak antara simpul-simpulnya berbeda-beda. Algoritma TSP menggunakan pendekatan brute force untuk mencari jalur terpendek, sehingga kompleksitasnya eksponensial terhadap jumlah simpul. Oleh karena itu, semakin banyak simpul, semakin lama waktu yang dibutuhkan untuk mencari jalur terpendek. Pada contoh grafik yang diberikan, tidak ada simpul yang dikunjungi lebih dari satu kali, sehingga waktu komputasi yang sangat kecil menunjukkan worst case yang efisien.

**2. Algoritma Dijkstra**

a. Best Case: Best case terjadi ketika simpul tujuan langsung terhubung dengan simpul awal dan jaraknya relatif lebih kecil dibandingkan simpul lainnya. Dalam kasus ini, algoritma Dijkstra akan langsung menemukan jalur terpendek tanpa perlu melakukan iterasi yang banyak. Pada contoh grafik yang diberikan, best case terjadi ketika simpul tujuan 'f' langsung terhubung dengan simpul awal 'a' dengan jarak 19. Waktu komputasi yang sangat kecil menunjukkan best case.

b. Average Case: Average case terjadi ketika grafik memiliki jumlah simpul yang sedang dan jarak antara simpul-simpulnya beragam. Pada contoh grafik yang diberikan, average case terjadi ketika jumlah simpul yang dikunjungi sedang dan jarak antara simpul-simpulnya beragam. Hasil yang didapatkan adalah shortest path a -> c -> e -> f dengan jarak terpendek 19. Waktu komputasi yang sangat kecil menunjukkan average case.

c. Worst Case: Worst case terjadi ketika grafik memiliki banyak simpul dan jarak antara simpul-simpulnya berbeda-beda. Algoritma Dijkstra menggunakan pendekatan greedy dengan mempertimbangkan jarak terpendek saat ini, sehingga kompleksitasnya bergantung pada jumlah simpul dan jarak antara simpul-simpulnya. Pada contoh grafik yang diberikan, tidak ada simpul yang dikunjungi lebih dari satu kali, sehingga waktu komputasi yang sangat kecil menunjukkan worst case yang efisien.
