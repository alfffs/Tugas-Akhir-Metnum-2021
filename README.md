# Tugas-Akhir-Metnum-2021

# Kelompok 3
Maria Amahagiani Oktabunia	          26050119140113
Aulia Rahmawati				                26050119140112
Clara Clarita			                  	26050119140110
Yohana Arum E.T				                26050119140106
Allian Alfianzah				              26050119140105
Masterina Rahmadya			              26050119140102
Shahreza Gede Ammarazkha		          26050119140100
Muhammad Zidan Alfiqri			          26050119140099
Krisna Dwi Kurniawan		              26050119140095
Alvaro Theondra Undap			            26050119140093
Hana Apriana				                  26050119140092 <!--more-->

# PENGENALAN METODE NUMERIK DAN PYTHON
Pada dasarnya metode numerik merupakan suatu teknik, yang mana dapat digunakan untuk menyelesaikan permasalahan – permasalahan yang diformulasikan secara matematis dengan melakukan suatu operasi hitungan.  Pada umumnya metode numerik digunakan untuk menyelesaikan permasalahan - permasalahan matematis yang tidak dapat diselesaikan menggunakan metode analitik. Apabila terdapat cara untuk menyelesaikan secara analitik, proses penyelesaian tersebut sangat rumit serta menghabiskan banyak waktu sehingga tidak efisien. Oleh karena itu, pada umumnya penyelesaiannya dilakukan secara numeris, yang mana memiliki hasil dari penyelesaian yang mana merupakan nilai perkiraan atau pendekatan yang diperoleh dari penyelesaian analitis. Jika dilihat berdasarkan cara kerja dari metode numeric, maka diketahui bahwa dari hasil tersebut akan diperoleh nilai kesalahan atau biasa disebut dengan nilai error. Semakin kecil nilai error yang diperoleh, maka hasil dari perhitungan akan semakin mendekati sempurna, dan begitupun sebaliknya apabila nilai erro yang diperoleh semakin besar, maka hasil perhitungan dinggap kurang akurat.
Pada dasarnya terdapat beberapa proses algortima yang dilakukan dalam menyelesaikan suatu tipe persamaan matematis. Dapat dikatakan bahwa dalam menyelesaikan perhitungan – perhitungan yang ada dilakukan dengan iterasi dalam jumlah yang sangat banyak dan berulang – ulang. Hal tersebut menyebabkan dalam melakukan perhitungan, diperlukan adanya bantuan teknologi, berupa computer untuk menyelesaikan perhitungan tersebut, yang mana hitungan numeric akan dapat terselesaikan dalam waktu yang singkat. Terdapat beberapa perbedaan antara metode numerik dan metode analitik, yaitu :
1.	Metode numerik memeiliki hasil yang selalu berbentuk angka, sedangkan pada metode analitik hasil yang diperoleh dapat berbentuk fungsi matematik yang kemudian dapat dievaluasi untuk menghasilkan nilai dalam bentuk angka.
2.	Nilai error yang diperoleh pada metode analitik adalah 0, sedangkan metode numerik ≠0≠0.
3.	Metode analitik pada umumnya digunakan untuk permasalahan dengan model terbatas dan sederhana, adapun metode numerik biasanya digunakan pada semua jenis permasalahan.
Terdapat beberapa kelebihan dan kekurangan yang dimiliki oleh penggunaan metode numeric, yang mana kelebihan nya seperti :
1.	Solusi persoalan akan selalu dapat diperoleh.
2.	Penyelesaian dari suatu perhitungan dapat dilakukan dalam waktu yang singkat dan hasil yang diperoleh mendekati nilai sebenarnya.
3.	Tampilan hasil perhitungan dapat disimulasikan.
Sedangkan kelemahannya, yaitu :
1.	Nilai yang diperoleh berupa pendekatan atau hampiran.
2.	Tanpa bantuan komputer, proses perhitungan akan berlangsung lama dan berulang-ulang.
Pada dasarnya pyton merupakan suatu bahasa pemrograman tingkat tinggi dengan interpretatif multiguna yang menggunakan filosofi perancangan yang cenderung memiliki fokus kepada tingkat keterbacaan kode supaya lebih mudah untuk memahami sintaks yang ada. Hal tersebut menjadikan bahasa pemrograman pyton sangat mudah dipelajari bagi para pemula di bidang pemrograman. Pada dasarnya Python bekerja dengan cara menggabungkan kemampuan, kapabilitas dan sintaksis kode yang kemudian dilanjutkan dengan fungsi pustaka yang berkualitas tinggi. 
Pyton merupakan bahasa pemrograman yang popoler digunakan di seluruh dunia dalam melakukan pengembangan pada situs web, algoritma, dan menyederhanakan proses otomatisasi. Pyton sendiri mampu menjadikan suatu program lebih ringkas apabila dibandingkan dengan bahasa pemrograman lain. Pada dasarnya python adalah suatu Bahasa pemrograman open-source yang memiliki banyak fungsi yang luas. Hal tersebut dapat dibuktikan melalui penyelesaian yang ada pada model numerik, metode numerik, statistik, machine learning, augmented reality, website, hingga program hardware. Seiring perkembangan zaman, pyton sudah berkembang hingga versi 8. Pada dasarnya pemrograman Python dapat dilakukan dengan menggunakan IDLE, Notepad++, Google Colaboratory, Jupyter Notebook, Visual Studio, dan lain sebagainya. Adapun Python sendiri mempunyai packages atau library yang sangat beragam. Library yang ada pada bahasa pemrograman Pyton diantaranya adalah Numpy, Matplotlib, Pandas, Basemap, Iris, dan sebagainya, yang mana banyak digunakan dalam pembuatan program di Python.

# AKAR-AKAR PERSAMAAN
Bentuk persamaan-persamaan polinomial sangat sulit atau tidak mungkin diselesaikan secara eksplisit. Penyelesaian numerik dilakukan dengan perkiraan yang berurutan (iterasi), sedemikian sehingga setiap hasil adalah lebih teliti dari perkiraan sebelumnya. Akar-akar persaman dapat diselesaikan dengan berbagai metode salah satunya metode setengah interval, metode interpolasi linear, metode newtop rhapson, metode secant, motode iterasi. 
1.	Metode Setengah Interval
Metode setengah interval merupakan metode analisis numerik paling sederhana diantara metode-metode analisis lainnya. Metode ini adalah selalu berhasil dalam menentukan akar-akar (solusi) yang dicari atau dengan kata lain selalu konvergen. 
2.	Metode Interpolasi Linear
Metode interpolasi linier hampir mirip dengan metode setengah interval. Prinsip pencarian akar persamaan dari metode ini didasarkan pada penggunaan interpolasi linier. Interpolasi linier dilakukan melalui dua titik pertama dengan garis interpolasi memotong sumbu x dan dititik perpotongan tersebut didapatkan pendekatan akar yang pertama. Kemudian pendekatan tersebut dievaluasi pada fungsi nonlinier sehingga diperoleh titik pada fungsi nonlinier tersebut. Kemudian dilakukan lagi interpolasi melalui ujung sebelumnya dan diperoleh pendekatan akar berikutnya. Demikian seterusnya, hingga diperoleh harga pendekatan akar yang sudah sangat dekat dengan akar persamaan eksaknya
3.	Metode Newtop Rhapson
Metode newton-raphson merupakan metode yang paling sering digunakan diantara metode-metode pencarian akar persamaan yang lain. Metode ini sederhana dan cukup handal dalam mendapatkan akar persamaan nonlinier. Metode newton-raphson tidak memerlukan dua buah terkaan awal seperti halnya metode bagi dua dan Regula Falsi. Syarat yang harus dipenuhi adalah bahwa taksiran awal yang diberikan harus sedekat mungkin dengan harga eksaknya. 
4.	Metode Secant
Pada dasarnya metode ini sama dengan metode newton-raphson, perbedaannya hanya terletak pada pendekatan untuk turunan pertama dari f saja. Pendekatan f' pada metode Secant didekati dengan ungkapan beda hingga yang didasarkan pada taksiran akar sebelumnya (beda mundur). 
5.	Metode Iterasi 
merupakan metode yang berbasiskan terhadap aplikasi dari langkah–langkah atau algoritma sederhana yang diulang–ulang pada sistem persamaan tersebut hingga sistem persamaan mencapai keadaan konvergen yang merepresentasikan solusi dari sistem persamaan tersebut.
Berdasarkan ke lima metode diatas dapat disimpulkan penyelesaian akar-akar persamaan ketika menggunakan python menunjukkan bahwa metode secant membutuhkan iterasi yang paling sedikit. Selain itu toleransi nilai error dengan metode ini memiliki nilai yang paling kecil. Semakin kecil error yang dihasilkan maka data yang dihasilkan akurat. Metode ini efektif digunakan karena membutuhkan iterasi yang paling sedikit dari metode-metode lain.

# SISTEM PERSAMAAN LINEAR dan MATRIKS
1. Metode Gauss
Metode Gauss merupakan salah satu penyelesaian system persamaan linear dengan menggunakan metode langsung. Metode eliminasi Gauss ini mengubah persamaan linear ke dalam bentuk matriks dan menyederhanakan matriks ini ke dalam bentuk segitiga atas. Algoritma eliminasi Gauss mengubah matriks menjadi matriks dengan sifat-sifat, Jika satu baris tidak seluruhnya nol maka bilangan selain nol pertama pada baris tersebut adalah 1, bilangan ini disebut bilangan satu utama, Jika terdapat baris yang seluruhnya terdiri dari nol, maka baris-baris ini akan dikelompokkan bersama-sama pada bagian paling bawah dari matriks, Jika terdapat dua baris berurutan yang tidak nol seluruhnya, maka 1 utama pada baris lebih rendah diletakkan pada kolom yang lebih kanan dari 1 utama di baris atasnya.
Metode Gauss dilakukan dengan mengkonversi persamaan linear yang ada kemudian dikonversi menjadi dalam bentuk matriks (Ibnu, 2016). 
Metode Gauss juga dapat dilakukan dalam pemograman seperti pada phyton dengan menggunakan script secara algoritma dapat dicontohkan sebagai berikut,
2. Metode Gauss-Jordan
Menurut Hasanudin et.al., (2019), metode eliminasi Gauss-Jordan merupakan metode penerapan dari metode eliminasi Gauss. Perbedaan antara kedua metode ini terletak pada matriks identitasnya dimana pada metode Gauss-Jordan matriks identitas pada sebelah kiri dikonversai menjadi matriks diagonal. 
Proses eliminasi gauss-Jordan ini dilakukan dengan mengubah system dari peramaan linear menjadi ke dalam bentuk matriks dan menyelesaikannya. Dalam penyelesaiannya secara algoritma, eliminasi Gauss-Jordan dilakukan dengan menghitung matriks kuadrat dengan menambah matriks dengan matriks identitasnya dari dimensi yang sama. Penggunaan metode eliminasi Gauss Jordan secara algoritma dapat dicontohkan sebagai berikut,
3. Metode Gauss-Seidel
Metode Gauss-Seidel termasuk kedalam metode penyelesaian system persamaan linier secara tidak langsung. Metode ini memiliki kemiripan dengan metode iterasi Jacobi. Perbedaan antara keduanya terletak pada hasil nilai x di metode Gauss-Seidel yang telah dihitung dan digunakan untuk menghitung nilai x lain dilakukan tanpa harus menunggu iterasi seleasi. Perhitungan metode Gauss-Seidel dilakukan seperti pada contoh,
Pada metode Gauss-Seidel ini, proses iterasi lebih cepat dilakukan daripada pada metode iterasi Jacobi (Sasongko, 2010).
Metode Gauss-Seidel dapat dilakukan dalam bentuk algoritma dengan contoh sebagai berikut,
4. Metode Iterasi Jacobi
Metode Iterasi Jacobi merupakan salah satu penyelesaian yang digunakan dalam menyelesaikan system persamaan linier dengan metode tidak langsung seperti pada metode gauss-seidel. Metode iterasi ini menjadi metode alternative dalam penyelesaian system persamaan liniear karena dengan menggunakan metode eliminasi masih terasa cukup sulit untuk menyelesaikan system persamaan linier yang terdiri dari n persamaan dengan n > 3. Metode iterasi Jacobi menggunakan nilai awal pada caranya sehingga nilai yang diperoleh memliki kesalahan yang relative kecil dengan syarat persamaan harus dominan secara diagonal. Konsep dari metode ini adalah melakukan perubahan nilai x yang diperoleh tiap iterasi. Iterasi dilakukan hingga mencapai nilai yang konvergen dengan toleransi yang diberikan. Metode iterasi Jacobi memiliki hasil ketelitian yang baik dan waktu komputasi yang lebih cepat daripada metode Eliminasi Gauss. Teknik iterasi metode Jacobi ini menyelesaikan system persamaan linear dengan ukuran n x n atau AX = b. 
Menurut Nisa dan Asih (2020), iterasi Jacobi dapat dilakukan dengan menggunakan Ms Excel ataupun dengan pemrogaman agar tidak menghitung secara manual.

# INTEGRASI NUMERIK
Integrasi numerik merupakan cara alternatif untuk mengintegrasikan suatu persamaan, di samping integrasi analitis. Integrasi analitis terkadang merupakan cara integrasi yang sulit, khususnya pada persamaan-persamaan kompleks dan juga rumit. Untuk metode yang digunakan adalah metode Trapesium Banyak Pias dan metode Simpson 1/3. Untuk metode Trapesium Banyak Pias, semakin banyak pias atau sekat yang digunakan, nilai yang dihasilkan akan menjadi lebih teliti. Metode Simpson 1/3 biasanya lebih disukai karena mencapai ketelitian orde ketiga dan hanya memerlukan tiga titik.

# PERSAMAAN DIFFERENSIAL BIASA
Persamaan Diferensial Biasa
Persamaan diferensial biasa adalah persamaan diferensial dimana fungsi yang tidak diketahui (variabel terikat) adalah fungsi dari variabel bebas tunggal. Dalam bentuk paling sederhana fungsi yang tidak diketahui ini adalah fungsi riil atau fungsi kompleks namun secara umum bisa juga berupa fungsi vektor maupun matriks. Lebih jauh lagi, persamaan diferensial biasa digolongkan berdasarkan irde tertinggi dari turunan terhadao variabel terikat yang muncul dalam persamaan tersebut
1. Persamaan Diferensial Biasa Metode Euler
Persamaan diferensil biasa orde satu dapat diselesaikan dengan berbagai macam metode numerik. Salah satu metode yang cukup terkenal adalah metode Euler. Metode ini ditemukan oleh Leonhard Euler pada tahun 1770.  Anggap ada sebuah persamaan diferential biasa orde satu dan kondisi awal dengan persamaan sebagai berikut
 
Dengan “Langkah” h didefinisikan sebagai
 
Persamaan Euler untuk menyelesaikan persamaan diferensial biasa orde 1 dapat ditulis
 
sebagai contoh, kita akan menyelesaikan persamaan hukum pendinginan Newton. Hukum tersebut menyatakan bahwa perubahan suhu suatu benda yang memiliki suhu lebih tinggi dari lingkungannya berbanding lurus dengan selisih suhu benda dengan lingkungannya. Dalam bahasa matematika dapat ditulis menjadi
 
Kita akan menyelesaikan persamaan di atas dengan menggunakan metode Euler, namun sebagai perbandingan kita bisa dengan mudah mendapatkan solusi analitis hanya dengan mengintegralkan persamaan tersebut
 
Kode python yang digunakan untuk mengetahui nilai Persamaan diferensial biasa metode euler dan galatnya serta grafiknya adalah 
 
# PENDEKATAN PERSAMAAN DIFFERENSIAL BIASA DENGAN METODE EULER
Nama = input("Masukkan Nama: ")
NIM = (input("Masukkan NIM: "))
Kelas = input("Masukkan Kelas: ")

#=== Import Library ===#
import numpy as np
import matplotlib.pyplot as plt
from IPython import get_ipython

plt.style.use('seaborn-poster')
ipy = get_ipython()
if ipy is not None: 
    ipy.run_line_magic('matplotlib', 'inline')

#==== Mendefinisikan parameter dan fungsi ===#
h = float(input("Masukkan nilai h: ")) # Step size
x0 = float(input("Masukkan nilai x awal: "))
xn = float(input("Masukkan nilai x akhir: "))
x = np.arange(x0, xn + h, h) # Numerical grid
y0 = float(input("Masukkan nilai y awal: ")) # Initial Condition
G = (2*x**3)+(9*x**2)+(4*x)+12
f = lambda x, y: (2*x**3)+(9*x**2)+(4*x)+12 # Persamaan Differensial Biasa

#=== Metode Euler Eksplisit ===#
y = np.zeros(len(x))
y[0] = y0
for i in range(0, len(x) - 1):
    y[i + 1] = y[i] + h*f(x[i], y[i])

#=== Menghitung Error ===#
Galat = G-y
print (Galat)

#=== Menampilkan Grafik ===#
Judul = ("\n Grafik Pendekatan Persamaan Differensial Biasa Dengan Metode Euler \n\n %s_%s_%s \n" % (Nama,NIM,Kelas))
plt.figure(figsize = (12, 12))
plt.plot(x, y, 'b--', label='Hasil Pendekatan') 
plt.plot(x, G, '-g', label='Hasil Analitik')
plt.title(Judul) # Judul plot
plt.xlabel('x') # Label sumbu x
plt.ylabel('F(x)') # Label sumbu y
plt.grid() # Menampilkan grid
plt.legend(loc='lower right')
#plt.savefig('image\euler.png')

Dengan nilai H adalah 0.04, x awal adalah 0, x akhir adalah 2.1 dan y awal adalah 0, berikut hasil dari running nya
 
 
2. PERSAMAAN DIFERENSIAL BIASA METODE HEUN
Metode Heun merupakan metode predictor-corrector karena dalam penyelesaiannya metode ini tidak perlu turunan fungsi terlebih dahulu tetapi dengan memprediksi solusi menggunakan persamaan predictor kemudian dikoreksi dengan menggunakan persamaan corrector. Metode Heun adalah salah satu metode numerik yang dapat digunakan untuk menyelesaikan berbagai persoalan matematika yang mempunyai masalah nilai awal. Masalah nilai awal merupakan masalah penyelesaian suatu persamaan diferensial dengan syarat awal yang telah diketahui. Metode Heun juga merupakan salah satu metode satu langkah di dalam metode numerik. Metode numerik adalah suatu metode penyelesaian persamaan matematis secara pendekatan karena penyelesaian secara analitis sulit untuk diperoleh. Penyelesaian persamaan matematis dengan menggunakan metode numerik menghasilkan angka (numerik) yang bukan suatu fungsi [4]. Metode Heun merupakan metode satu langkah (one-step) karena untuk menaksir nilai y t n1  dibutuhkan satu buah taksiran nilai sebelumnya yaitu y t n 
Kode python yang digunakan untuk mengetahui nilai Persamaan diferensial biasa metode heun dan galatnya serta grafiknya adalah 

# PENDEKATAN PERSAMAAN DIFFERENSIAL BIASA DENGAN METODE HEUN
Nama = input("Masukkan Nama: ")
NIM = (input("Masukkan NIM: "))
Kelas = input("Masukkan Kelas: ")

#=== Import Library ===#
import numpy as np
import matplotlib.pyplot as plt
from IPython import get_ipython

plt.style.use('seaborn-poster')
ipy = get_ipython()
if ipy is not None:
    ipy.run_line_magic('matplotlib', 'inline')

#==== Mendefinisikan parameter dan fungsi ===#
h = float(input("Masukkan nilai h: ")) # Step size
x0 = float(input("Masukkan nilai x awal: "))
xn = float(input("Masukkan nilai x akhir: "))
x = np.arange(x0, xn + h, h) # Numerical grid
y0 = float(input("Masukkan nilai y awal: ")) # Initial Condition
G = (2*x**3)+(9*x**2)+(4*x)+12
f = lambda x, y: (2*x**3)+(9*x**2)+(4*x)+12 # Persamaan Differensial Biasa

#=== Metode Heun / Runge Kutta Orde 2 ===#
y = np.zeros(len(x))
y[0] = y0
for i in range(0, len(x) - 1):
    k1 = f(x[i], y[i])
    k2 = f((x[i]+h), (y[i]+(h*k1)))
    y[i+1] = y[i]+(0.5*h*(k1+k2))

#=== Menghitung Error ===#
Galat = G-y
print (Galat)

#=== Menampilkan Grafik ===#
Judul = ("\n Grafik Pendekatan Persamaan Differensial Biasa Dengan Metode Heun \n\n %s_%s_%s \n" % (Nama,NIM,Kelas))
plt.figure(figsize = (12, 12))
plt.plot(x, y, 'b--', label='Hasil Pendekatan') 
plt.plot(x, G, '-g', label='Hasil Analitik')
plt.title(Judul) # Judul plot
plt.xlabel('x') # Label sumbu x
plt.ylabel('F(x)') # Label sumbu y
plt.grid() # Menampilkan grid
plt.legend(loc='lower right')
#plt.savefig('image\heun.png') 
Dengan nilai H adalah 0.04, x awal adalah 0, x akhir adalah 2.1 dan y awal adalah 0, berikut hasil dari running nya
 
# MACAM MACAM LIBRARY PYTHON

Macam-macam library yang dipakai dalam Praktikum
1. Matplotlib
Matplotlib adalah library plotting 2D python yang menghasilkan gambar publikasi bermutu di dalam berbagai format hardcopy dan lingkungan interaktif sepanjang platform. Matplotlib dapat digunakan di dalam script Python, shell Python dan ipython, server aplikasi web dan enam gui toolkit. Biasanya untuk mempermudah secara umum matplotlib.pyplot disingkat menjadi plt.
Untuk menginstal librari ini cukup mudah dengan mengetik 
Pip install matplotlib
Berikut adalah contoh dalam membuat visualisasi dengan Matplotlib
Mari memulainya dengan mengimport library
from matplotlib import pyplot as plt
Mari hasilkan nilai untuk sumbu x dan sumbu y.
x = [2, 4, 6, 8, 10]
y = [10, 11, 6, 7, 4]
Mari kita sebut fungsi untuk mem-plot diagram batang.
plt.bar(x,y)
Selanjutnya kita tampilkan plot nya.
plt.show()
Berikut adalah tampilan chart bar:
 
2. Numpy
NumPy (kependekan dari Numerical Python) adalah salah satu library teratas yang dilengkapi dengan sumber daya yang berguna untuk membantu para data scientist mengubah Python menjadi alat analisis dan pemodelan ilmiah yang kuat. Libary Open source terpopuler ini tersedia di bawah lisensi BSD. Ini adalah pustaka Python dasar untuk melakukan tugas dalam komputasi ilmiah. NumPy adalah bagian dari ekosistem berbasis Python yang lebih besar dari tool open source yang disebut SciPy.
Untuk menginstalnya cukup mengetik
Pip install numpy
Mari memulainya dengan meng-import library ini terlebih dahulu
import numpy as np
Selanjutnya, kita akan menggunakan fungsi eye() untuk menghasilkan matriks identitas dengan dimensi yang ditetapkan.
matrix_one = np.eye(3)
matrix_one
Outputnya akan seperti dibawah ini :
array([[1., 0., 0.],
       [0., 1., 0.],
       [0., 0., 1.]])

3. Pandas
Pandas adalah library hebat lain yang dapat meningkatkan keterampilan Python Anda untuk data science. Sama seperti NumPy, Pandas milik keluarga perangkat lunak open source SciPy dan tersedia di bawah lisensi perangkat lunak bebas BSD. Pandas menawarkan alat serbaguna dan kuat untuk struktur data dan melakukan analisis data yang luas. Library ini berfungsi dengan baik dengan data dunia nyata yang tidak lengkap, tidak terstruktur, dan tidak teratur — dan dilengkapi dengan tool untuk membentuk, menggabungkan, menganalisis, dan memvisualisasikan datasets.
Ada tiga jenis struktur data di library ini:
•	Series: single-dimensional, array homogen
•	DataFrame: two-dimensional dengan kolom yang diketik secara heterogen
•	Panel: three-dimensional, array size-mutable
Sebagai contoh, mari kita lihat bagaimana library Panda Python (disingkat pd) dapat digunakan untuk melakukan beberapa perhitungan statistik deskriptif.
Mari mulai dengan mengimport library pandas ini.
import pandas as pd
Selanjutnya kita buat dictionary yang seri.
d = {'Name':pd.Series(['Alfrick','Michael','Wendy','Paul','Dusan','George','Andreas',
   'Irene','Sagar','Simon','James','Rose']),
   'Years of Experience':pd.Series([5,9,1,4,3,4,7,9,6,8,3,1]),
   'Programming Language':pd.Series(['Python','JavaScript','PHP','C++','Java','Scala','React','Ruby','Angular','PHP','Python','JavaScript'])
    }
Selanjutnya buat Data Frame.
df = pd.DataFrame(d)
Output nya akan seperti dibawah ini :
      Name Programming Language  Years of Experience
0   Alfrick               Python                    5
1   Michael           JavaScript                    9
2     Wendy                  PHP                    1
3      Paul                  C++                    4
4     Dusan                 Java                    3
5    George                Scala                    4
6   Andreas                React                    7
7     Irene                 Ruby                    9
8     Sagar              Angular                    6
9     Simon                  PHP                    8
10    James               Python                    3
11     Rose           JavaScript                    1

# SARAN PENGEMBANGAN
Sebaiknya praktikum selanjutnya, rincian terkait materi dan tugas lebih dijelaskan secara detail dan script yang dijelaskan saat praktikum dijelaskan rinci terkait fungsi dan manfaatnya per kata dan angka. Dan pada saat memberikan tugas praktikum, lebih baik diberikan video tutorial agar lebih mudah dipahami dan dipelajari.

Terima kasih kakak-kakak asisten yang sudah menyalurkan dan memberikan ilmu-ilmu kepada kami. Semoga kami bisa mengaplikasikan nya di masa depan🙇‍♀‍



