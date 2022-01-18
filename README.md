# KLASIFIKASI PENYAKIT TANAMAN DENGAN CNN

## Deskripsi Dataset
Dalam pembuatan project ini, dataset yang kami gunakan merupakan dataset yang berupa daun padi yang didapatkan dari situs [kaggle.com](http://www.kaggle.com) yang berjudul [Rice Leaf Diseases Dataset](http://www.kaggle.com/vbookshelf/rice-leaf-diseases). Dataset ini berisi 120 gambar padi dan terdapat 3 kategori, yaitu Bacterial Leaf Blight, Brown Spot, dan Leaf Smut yang masing-masing terdapat 120 gambar bertipe .jpg

## Jurnal Referensi
Jurnal referensi yang digunakan dalam pembuatan project ini berjudul [Rice Leaf Diseases Prediction Using Deep Neural Networks with Transfer Learning](http://www.doi.org/10.1016/j.envres.2021.111275). Krishnamoorthy N., L.V. Narasimha Prasad, C.S. Pavan Kumar, Bharat Subedi, Haftom Baraki Abraha, Sathishkumar V.E.

## Author
Kontributor dalam pengerjaan project ini adalah
1. M. Aji Purnama Wibowo [ajipurnama25@gmail.com](http://www.gmail.com) - 201810370311122
2. Auliya Tara SL [auliyatara11@gmail.com](http://www.gmail.com) - 201810370311129

### Pre-Processing
Pre processing yang digunakan dalam project ini yaitu ekstrak file, split data, pemberian data augmentasi menggunakan image generator

### Modeling
Modeling yang digunakan dalam project ini adalah model InceptionResNetV2, augmentasi, MaxPooling2D, AveragePooling2D, Hyperparameter, GlobalAveragePooling2D, Flatten,BatchNormalization, Dropout

## Overview Dataset
Jumlah dan persentase splitting dataset :
train (persentase, jumlah data train)
validation (persentase, jumlah data validation)
test (persentase, jumlah data test)

masing-masing data pada train, validation dan tes berjumlah 40 data

## Hasil akhir project setelah di deploy ke heroku
![image](https://user-images.githubusercontent.com/92361807/149866809-03a58071-e31f-4306-99f5-73aa0f79a66c.png)
![image](https://user-images.githubusercontent.com/92361807/149866901-4e7064d1-879f-4290-9444-77812ebeb491.png)

### Link Heroku : https://mldeploys.herokuapp.com
