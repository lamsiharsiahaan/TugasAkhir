Skrip Voice Over:

- Protein adalah molekul penting dalam semua organisme hidup memainkan peran kunci dalam hampir semua proses biologis. 

- Setiap protein memiliki fungsi spesifik yang ditentukan oleh struktur 3 dimensinya dan urutan asam aminonya.

- Meskipun protein memainkan peran penting dalam kehidupan, memahami fungsi setiap protein adalah tantangan yang besar. 

- Seperti prediksi fungsi protein experimental yang membutuhkan analisis laboratorium yang rumit dan memakan waktu. 

- Dengan ribuan protein yang belum diketahui fungsinya, pendekatan tersebut ini tidak praktis dan tidak efisien.

- Untuk itu, dalam mengatasi tantangan ini peneliti mengembangkan pendekatan berbasis deep learning.

- Dengan memanfaatkan Pembelajaran Mesin diharapkan dapat memprediksi fungsi protein dengan akurasi dan efisiensi yang lebih baik.

- Pada penelitian ini, kami menggunakan metode Deep Learning yang telah kami terapkan pada model Long Short Term Memory (LSTM) melalui pendekatan yang terdiri dari 4 eksperimen,

- Yang pertama adalah Eksperimen menggunakan model LSTM dan Embedding Tf.Keras yang berfokus menggunakan teknik dasar embedding untuk memberikan representasi awal dari urutan asam amino yang akan diproses oleh model LSTM.

- Yang kedua adalah eksperimen menggunakan model LSTM dan embedding T5 yang berfokus pada menangkap konteks lebih dalam dari urutan asam amino, sehingga meningkatkan akurasi prediksi.

- Yang ketiga adalah eksperimen menggunakan model LSTM dan embedding ProtBERT. Pendekatan ini berfokus pada pemanfaatan ProtBERT, sebuah model transformasi yang telah dilatih secara khusus pada data protein.

- Yang keempat adalah eksperimen menggunakan model LSTM dan embedding ProtBERT yang dipadukan dengan Diamond Search. Pendekatan ini menggabungkan hasil representasi ProtBERT dengan Diamond Search, sebuah algoritma pencarian yang sangat efisien untuk menemukan kesamaan dalam urutan protein yang sangat besar. Diamond Search memungkinkan identifikasi fungsi protein dengan cepat dengan memanfaatkan basis data yang luas, meningkatkan kecepatan dan akurasi prediksi.


- Penerapan keempat eksperimen ini dalam prediksi fungsi protein secara statistik menunjukkan hasil yang memuaskan. Eksperimen dengan model Long Short-Term Memory yang dipadukan dengan embedding Protein Language Model dan diamond search meningkatkan akurasi prediksi fungsi protein. Sementara itu, eksperimen dengan embedding Tf.Keras juga menghasilkan akurasi yang cukup baik.