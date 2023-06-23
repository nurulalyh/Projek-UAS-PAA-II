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
