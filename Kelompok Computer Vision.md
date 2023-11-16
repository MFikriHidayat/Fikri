#### Muhammad Fikri Hidayat 5311421103
#### Nanda Aprilia Damayanti 5311421105
#### Jupriansyah 5311421107

<center><h1>Perencanaan dan Pengembangan dari Computer Vision untuk Mendeteksi Nama dan Jenis Komponen Elektronika</h1></center>

#### A. Computer Vision

Aplikasi yang direncanakan yaitu aplikasi yang menggunakan sistem AI computer vision, yang berfokus hanya untuk mendeteksi komponen-komponen elektronika yang bertujuan untuk memudahkan pengguna dalam mengetahui nama dan jenis komponen elektronika.

Computer vision adalah cabang dari kecerdasan buatan yang bertujuan untuk memberikan komputer kemampuan untuk "melihat" dan memahami dunia visual seperti manusia. Ini melibatkan pengembangan algoritma dan teknologi komputer untuk menganalisis dan memproses informasi visual dari dunia nyata. Computer vision dapat digunakan untuk berbagai tujuan, termasuk pengenalan objek, deteksi wajah, navigasi otonom, pengolahan citra medis, dan banyak lagi. Teknologi ini memungkinkan mesin untuk memahami dan merespons pada input visual, membuka berbagai aplikasi di berbagai bidang.

#### B. User Interface

Graphical User Interface (GUI) adalah jenis antarmuka pengguna yang memungkinkan pengguna berinteraksi dengan perangkat elektronik atau perangkat lunak melalui elemen-elemen grafis seperti ikon, tombol, dan jendela, daripada antarmuka berbasis teks seperti antarmuka baris perintah (command-line interfaces atau CLI). GUI menyediakan cara yang lebih ramah pengguna dan intuitif secara visual bagi pengguna untuk berinteraksi dengan komputer dan aplikasi perangkat lunak.

#### C. Inference Engine

1.	Convolutional Neural Network (CNN atau ConvNet)

Algoritma pembelajaran mendalam yang populer, umumnya digunakan untuk menganalisis citra seperti pengenalan objek, klasifikasi objek, dll. CNN merupakan arsitektur jaringan untuk pembelajaran mendalam yang belajar langsung dari data, dengan menghilangkan kebutuhan untuk melakukan ekstraksi fitur secara manual. CNN terdiri dari 3 lapisan utama:
- Convolutional Layer (+ReLU) : 
Melakukan operasi konvolusi pada citra masukan dengan sejumlah penapis. Tiap
penapis menghasilkan luaran yang disebut feature map. ReLU adalah layer tambahan yang memungkinkan pelatihan yang lebih cepat dan efektif dengan memetakan nilai negatif ke nol dan mempertahankan nilai positif.

- Pooling Layer :
Pooling layer bertanggung jawab untuk mengurangi ukuran spasial dari matriks fitur hasil konvolusi. Hal ini bertjuan untuk mengurangi daya komputasi yang diperlukan untuk memproses data melalui pengurangan dimensi. Ada dua jenis pooling: Max Pooling dan Average Pooling.

- Fully-Connected Layer :
Lapisan terakhir di dalam CNN adalah fully connected layer (FC) yang menghasilkan vektor dimensi K, dalam hal ini K adalah jumlah kelas yang dapat diprediksi oleh jaringan. Vektor ini berisi probabilitas untuk setiap kelas dari setiap gambar yang diklasifikasikan. Lapisan terakhir dari arsitektur CNN menggunakan fungsi softmax untuk menyediakan luaran klasifikasi.


2.	Natural Language Processing (NLP)

Pemrosesan bahasa alami (NLP) adalah sebuah teknologi machine learning yang memberi komputer kemampuan untuk menginterpretasikan, memanipulasi, dan memahami bahasa manusia. Pemrosesan bahasa alami (NLP) menggabungkan model linguistik komputasional, machine learning, dan deep learning untuk memproses bahasa manusia.
- Linguistik Komputasional :
Linguistik komputasional adalah ilmu memahami dan membangun model bahasa manusia dengan alat komputer dan perangkat lunak.
- Machine Learning :
Machine learning adalah teknologi yang melatih komputer dengan data sampel untuk meningkatkan efisiensinya.
- Deep Learning :
Deep learning adalah sebuah bidang machine learning spesifik yang mengajari komputer untuk belajar dan berpikir seperti manusia. Deep learning melibatkan jaringan neural yang terdiri dari simpul pemrosesan data yang terstruktur untuk menyerupai operasi otak manusia.

3.	Teknologi Augmented Reality (AR)

Bixby vision dapat memberikan pengalaman augmented reality dengan menampilkan informasi tambahan atau tindakan yang dapat dilakukan ketika Anda mengarahkan kamera ke objek tertentu.

Augmented Reality (AR) adalah teknologi yang menggabungkan dunia fisik dengan unsur-unsur digital, menciptakan pengalaman gabungan antara dunia nyata dan dunia maya. Beberapa karakteristik utama dari teknologi Augmented Reality melibatkan penambahan atau penyisipan informasi, objek, atau elemen virtual ke dalam lingkungan fisik secara real-time.

Berikut beberapa poin terkait Teknologi Augmented Reality:
- Overlay Informasi :
AR memungkinkan pengguna melihat informasi tambahan yang "diterapkan" atau disisipkan ke dalam pandangan mereka. Contohnya, menampilkan informasi cuaca saat melihat langit biru melalui perangkat AR.
- Interaksi Realtime :
AR memungkinkan interaksi langsung dengan elemen-elemen digital yang ditambahkan ke lingkungan fisik. Pengguna dapat berinteraksi dengan objek virtual menggunakan perangkat seperti smartphone, kacamata AR, atau headset AR.
- Marker-based dan Markerless AR :
AR dapat dibagi menjadi dua kategori utama. Marker-based AR menggunakan marker fisik (contohnya kode QR) sebagai titik referensi untuk menempatkan objek virtual. Sedangkan markerless AR menggunakan fitur lingkungan fisik, seperti tembok atau objek, tanpa memerlukan marker tambahan.

4. Algoritma Deteksi Objek

Algoritma deteksi objek adalah serangkaian langkah dan prosedur yang dirancang untuk secara otomatis mengidentifikasi dan menemukan objek-objek tertentu dalam gambar atau video. Tujuan utama dari algoritma ini adalah untuk menentukan lokasi dan kelas (jenis) dari objek-objek tersebut dalam suatu konteks visual.

- Faster R-CNN (Region-based Convolutional Neural Network):
adalah sebuah arsitektur dalam bidang pengolahan citra dan deteksi objek. Faster R-CNN mendemonstrasikan keunggulan dalam kecepatan dan akurasi deteksi objek dibandingkan dengan pendahulunya. Ini telah menjadi landasan untuk banyak pengembangan selanjutnya dalam bidang deteksi objek dengan menggunakan deep learning.

- SSD (Single Shot Multibox Detector) :
adalah jenis algoritma deteksi objek yang digunakan dalam visi komputer dan pemrosesan gambar. Algoritma ini dirancang untuk mengidentifikasi dan menemukan objek dalam sebuah gambar secara real-time. SSD sangat populer karena efisiensinya dan akurasinya dalam mendeteksi objek pada skala yang berbeda dalam suatu gambar.

- YOLO (You Only Look Once) :
adalah sebuah algoritma deteksi objek yang terkenal dalam bidang computer vision. Dikembangkan oleh Joseph Redmon, YOLO membedakan dirinya dengan kemampuan untuk melakukan deteksi objek secara real-time dengan tingkat akurasi yang tinggi.

5. VPU (Vision Processing Unit) :
adalah jenis unit pemrosesan khusus yang dirancang untuk menangani tugas-tugas terkait pengolahan citra dan pengenalan pola visual dengan efisien. VPU secara khusus dioptimalkan untuk bekerja dengan data visual dan dapat memproses informasi gambar atau video dengan kecepatan tinggi dan efisiensi daya yang baik.

#### D. Knowledge Base

Knowledge base yang digunakan merupakan jenis komponen elektronika seperti :
- Resistor 
- Kondensator 
- Induktor 
- Dioda 
- Transistor 
- IC 
- Potensiometer 
- Kapasitor 
- Transformator 
- Sensor 
- LED 
- Buzzer 
- Relay 
- Fuse 
- Mosfet 
- Thyristor 
- SCR 
- OP AMP 
- LCD 
- Baterai 
- Akumulator 
- Regulator Tegangan dan Catu Daya 
- Resistor pull down dan pull up 
- Transceiver 
- Motor servo 
- Speaker

#### E. Kesimpulan

Dari perencanaan dan pengembangan aplikasi yang kita buat menggunakan Graphical User Interface (GUI) sebagai user interface, kemudian menggunakan CNN, NLP, AR, Algoritma Deteksi Objek (YOLO, SSD, dan Faster R-CNN), dan VPU (Vision Processing Unit). Sedangkan knowledge base yang digunakan, yaitu nama dan jenis komponen elektronika.
