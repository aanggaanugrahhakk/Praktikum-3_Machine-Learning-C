
# Decision Tree

Decision Tree adalah struktur seperti diagram alur yang mewakili model hirarki keputusan dan kemungkinan konsekuensinya, termasuk hasil kejadian peluang, biaya sumber daya, dan utilitas.

Library yang digunakan:

- panda: Pustaka yang digunakan untuk manipulasi dan analisis data. Library ini menyediakan struktur data untuk menyimpan dan memanipulasi kumpulan data yang besar secara efisien.
- LabelEncoder: Sebuah kelas dari pustaka scikit-learn yang digunakan untuk mengkodekan fitur kategorikal menjadi nilai numerik.
- train_test_split: Sebuah fungsi dari pustaka scikit-learn yang digunakan untuk membagi dataset menjadi set pelatihan dan pengujian.
- accuracy_score: Fungsi dari pustaka scikit-learn yang digunakan untuk menghitung akurasi pengklasifikasi.
- DecisionTreeClassifier: Sebuah kelas dari pustaka scikit-learn yang digunakan untuk mengimplementasikan pengklasifikasi pohon keputusan.
- plot_tree: Sebuah fungsi dari pustaka scikit-learn yang digunakan untuk memvisualisasikan pohon keputusan.
- matplotlib.pyplot: Sebuah pustaka yang digunakan untuk membuat visualisasi dalam Python.

Penjelasan penyelesaian Decision Tree yang digunakan di skrip:

- Pustaka pandas diimpor, dan set data karyawan dimuat ke dalam dataframe pandas menggunakan fungsi read_csv().
- Fungsi info() digunakan untuk menampilkan informasi tentang dataframe, termasuk jumlah baris, kolom, dan tipe data.
- Fungsi unique() digunakan untuk menampilkan nilai unik dari beberapa kolom kategorikal dalam dataframe, termasuk Education, JoiningYear, City, Gender, EverBenched, ExperienceInCurrentDomain, dan LeaveOrNot.
- Fungsi describe() digunakan untuk menampilkan ringkasan statistik dari kolom numerik dalam dataframe.
- Kelas LabelEncoder dari pustaka scikit-learn diimpor, dan perulangan for digunakan untuk mengkodekan kolom kategorikal dalam dataframe ke dalam nilai numerik.
- Fungsi drop() digunakan untuk menghapus kolom Gender, EverBenched, dan LeaveOrNot dari dataframe, dan dataframe yang dihasilkan ditugaskan ke variabel x. Kolom Gender, EverBenched, dan LeaveOrNot ditugaskan ke variabel y1, y2, dan y3, masing-masing.
- Fungsi train_test_split() dari pustaka scikit-learn digunakan untuk membagi dataset menjadi set pelatihan dan pengujian.
- Atribut shape digunakan untuk menampilkan jumlah baris dan kolom dalam set pelatihan dan pengujian.
- Kelas DecisionTreeClassifier dari pustaka scikit-learn diimpor, dan pengklasifikasi pohon keputusan dibuat dengan kedalaman maksimum 5.
- Fungsi fit() digunakan untuk melatih pengklasifikasi pohon keputusan pada set pelatihan.
- Fungsi predict() digunakan untuk membuat prediksi pada set pengujian, dan fungsi accuracy_score() digunakan untuk menghitung akurasi pengklasifikasi.
- Fungsi plot_tree() dari pustaka scikit-learn digunakan untuk memvisualisasikan pohon keputusan.

Berikut alur penjelasan skrip tersebut:

- Pustaka pandas diimpor, dan set data karyawan dimuat ke dalam dataframe pandas menggunakan fungsi read_csv().
- info() digunakan untuk menampilkan informasi tentang dataframe, termasuk jumlah baris, kolom, dan tipe data.
- Fungsi unique() digunakan untuk menampilkan nilai unik dari beberapa kolom kategorikal dalam dataframe, termasuk Education, JoiningYear, City, Gender, EverBenched, ExperienceInCurrentDomain, dan LeaveOrNot.
- Fungsi describe() digunakan untuk menampilkan ringkasan statistik dari kolom numerik dalam dataframe.
- Kelas LabelEncoder dari pustaka scikit-learn diimpor, dan perulangan for digunakan untuk mengkodekan kolom kategorikal dalam dataframe ke dalam nilai numerik.
- Fungsi drop() digunakan untuk menghapus kolom Gender, EverBenched, dan LeaveOrNot dari dataframe, dan dataframe yang dihasilkan ditugaskan ke variabel x. Kolom Gender, EverBenched, dan LeaveOrNot ditugaskan ke variabel y1, y2, dan y3, masing-masing.
- Fungsi drop() digunakan untuk menghapus kolom Gender, EverBenched, dan LeaveOrNot dari dataframe, dan dataframe yang dihasilkan ditugaskan ke variabel x. Kolom Gender, EverBenched, dan LeaveOrNot ditugaskan ke variabel y1, y2, dan y3, masing-masing.
- Fungsi train_test_split() dari pustaka scikit-learn digunakan untuk membagi dataset ke dalam set pelatihan dan pengujian.
- Atribut shape digunakan untuk menampilkan jumlah baris dan kolom dalam set pelatihan dan pengujian.
- Kelas DecisionTreeClassifier dari pustaka scikit-learn diimpor, dan pengklasifikasi pohon keputusan dibuat dengan kedalaman maksimum 5.
- Fungsi fit() digunakan untuk melatih pengklasifikasi pohon keputusan pada set pelatihan.
- Fungsi predict() digunakan untuk membuat prediksi pada set pengujian, dan fungsi accuracy_score() digunakan untuk menghitung akurasi pengklasifikasi.
- Fungsi plot_tree() dari pustaka scikit-learn digunakan untuk memvisualisasikan pohon keputusan.

Sitasi:
- [1] https://en.wikipedia.org/wiki/Decision_tree
- [2] https://www.simplilearn.com/tutorials/scikit-learn-tutorial/sklearn-decision-trees
- [3] https://stackoverflow.com/questions/3127922/what-is-a-good-python-library-for-decision-trees
- [4] https://www.datacamp.com/tutorial/decision-tree-classification-python
- [5] https://revou.co/kosakata/decision-tree
- [6] https://pypi.org/project/DecisionTree/
- [7] https://www.ocbcnisp.com/id/article/2023/06/20/decision-tree-adalah
- [8] https://dqlab.id/pahami-metode-decision-tree-sebagai-algoritma-data-science
- [9] https://pypi.org/project/DecisionTree/
- [10] https://www.ocbcnisp.com/id/article/2023/06/20/decision-tree-adalah
- [11] https://revou.co/kosakata/decision-tree
- [12] https://glints.com/id/lowongan/decision-tree-adalah/
- [13] https://stackoverflow.com/questions/32506951/how-to-explore-a-decision-tree-built-using-scikit-learn
- [14] https://gist.github.com/chalg/c1a7d707c10d496bb3139719b6aff258
- [15] https://dqlab.id/pahami-metode-decision-tree-sebagai-algoritma-data-science
- [16] https://pypi.org/project/DecisionTree/
- [17] https://www.ocbcnisp.com/id/article/2023/06/20/decision-tree-adalah
- [18] https://revou.co/kosakata/decision-tree
- [19] https://glints.com/id/lowongan/decision-tree-adalah/
## 🔗 Link Data Diri
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/anugrahak)

## Authors

- Anugrah AK. [@aanggaanugrahhakk](https://www.github.com/aanggaanugrahhakk)


## Identitas Authors

Nama: Anugrah AK.

NIM: 202131037

Kelas: C