Hi, my name is Carlo Abimanyu. These are my Data Science portfolios.

### [Indonesia Mobility Changes due to COVID-19 -  Data Visualization with Tableau](https://public.tableau.com/views/IndonesiamobilitychangesduetoCOVID-19/Dashboard?:language=en&:display_count=y&:origin=viz_share_link)
Saya membuat dashboard menggunakan Tableau Public untuk memvisualisasikan perubahan mobilitas di Indonesia akibat pandemi COVID-19. Pada project ini saya belajar membuat scatter plot, filter, map, dan beberapa fitur-fitur lainnya dari Tableau Public. <br>

![](images/id-mobility-changes-tableau.png)

### [Predict Molecular Atomization Energy using XGBoost Regression Tree and Neural Network](https://github.com/carloabimanyu/predict-molecular-energy)
Dataset diperoleh dari *database* PubChem yang memuat informasi mengenai posisi dan muatan atom dalam molekul serta bentuk multipole molekul. Informasi tersebut digunakan untuk membangun fitur berdasarkan definisi Matriks Coulomb ([Rupp dkk, 2012](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.108.058301)). Kemudian dengan menggunakan fitur tersebut, saya membangun model *machine learning* untuk memprediksi energi atomisasi molekul sebagai alternatif lain jika penyelesaian persamaan Schrodinger secara analitik maupun simulasi numerik mengalami kebuntuan. 
* Model XGB memiliki MAE 16.69 kcal/mol dengan durasi training 86.7 detik dan durasi prediksi 0.18 detik.
* Model Neural Network memiliki MAE 77.14 kcal/mol dengan durasi training 195.0 detik dan durasi prediksi 0.77 detik. <br>

![](images/predictall.png)

### [Hate Speech Tweet Classification using Bi-LSTM](https://github.com/carloabimanyu/NLP/tree/main/hate-speech-tweet)
* Membangun model machine learning untuk klasifikasi tweet apakah termasuk hate speech atau bukan.
* Dataset yang digunakan merupakan tweet berbahasa Indonesia.
* Menerapkan stemming dengan library Sastrawi.
* Menerapkan Tokenisasi, Embedding Layer, dan Bi-LSTM dari TensorFlow dan menghasilkan akurasi 83%.

### [Animal Image Classifier with Transer Learning and TF-Lite Deployment](https://github.com/carloabimanyu/CNN/tree/main/animal-vgg19)
* Dataset berisi lebih dari 15 ribu gambar hewan dengan 3 kelas.
* Menggunakan transfer learning dengan VGG19.
* Akurasi yang dihasilkan 92%.
* Model dikonversi menjadi format TF-Lite untuk deployment ke mobile.

![](images/animal-vgg19.png)

### [Appliances Time Series Energy Prediction](https://github.com/carloabimanyu/Time-Series/tree/main/energy_appliances)
Saya membuat model machine learning untuk permasalahan time series untuk memprediksi konsumsi energi dengan agregasi 10 menit. Dataset diperoleh dari UCI Machine Learning. Model dibangun dengan TensorFlow menggunakan layer LSTM. Dihasilkan model dengan MAE < 10% skala data. <br>

![](images/energy-appliances1.png)

### [Google Play Store Reviews - Multiclass Sentiment Analysis](https://github.com/carloabimanyu/NLP/tree/main/play_store_reviews)
* Membuat model klasifikasi 3 kelas untuk permasalahan NLP, khususnya sentiment analysis.
* Dataset terdiri dari 37 ribu review.
* Arsitektur model terdiri dari layer Embedding dan Bi-LSTM.
* Diperoleh akurasi 92%.

![](images/play-store-nlp.png)

### [In depth EDA for Used Car Price Predictions Dataset](https://github.com/carloabimanyu/EDA/tree/main/used_car_data)
Saya melakukan eksplorasi secara mendalam pada dataset dengan manipulasi DataFrame dengan pandas serta visualisasi dengan matplotlib dan seaborn.

![](images/used-car-dsa.png)

### [Simulate Forced Oscillation with Euler, Runge-Kutta, and Exponential Time Differencing (ETD) Method](https://github.com/carloabimanyu/forced-oscillation)
Sistem osilasi terpaksa dalam mekanika klasik memiliki persamaan gerak yang merupakan persamaan diferensial stiff. Permasalahan syarat awal ini dapat diselesaikan dengan pendekatan numerik dari beberapa metode, yakni Metode Euler, Metode Runge-Kutta, dan Metode ETD. Hasil simulasi divisualiasikan dalam plot simpangan sebagai fungsi waktu dan kecepatan sudut sebagai fungsi waktu. Hasil simulasi menunjukkan bahwa pada kasus stiff differential equation, Metode ETD lebih akurat dibandingkan Metode Euler dan Runge-Kutta.

![](images/forced-oscillations.png)
