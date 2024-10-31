<h1 align="center"> NLP With HuggingFace Transformers </h1>
<p align="center"> Berisi tentang pipeline dari HuggingFace Transformers untuk keperluan NLP (Natural Language Processing)</p>

<div align="center">

<img src="https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54">
<img src="https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white">

</div>

<h2 align="center"> TERIMA KASIH</h2>
Analisis
zero-shot-classification

bagi saya teknik ini bisa dipakai klasifikasi teks kedalam kategori baru tanpa pelatihan tambahan,untuk menghemwat waktu tanpa modelin yang lebih lanjut

text-generation Model menghasilkan teks yang relevan dengan konteks yang diberikan. Teks tersebut melanjutkan ide dari prompt dengan memberikan informasi tentang apa yang akan diajarkan dalam kursus. Kreativitas: Salah satu keunggulan dari model text generation adalah kemampuannya untuk menghasilkan teks yang kreatif dan beragam, tergantung pada input yang diberikan.

text-generation",menggunakan model="distilgpt2 bagi saya dengan menggunakan model gpt 2 sangat mudah menghasilkan teks yang bervariasi dan kreatif. Dengan kemampuannya untuk memahami dan memperluas konteks yang diberikan, model ini sangat berguna dalam berbagai aplikasi, mulai dari pembuatan konten hingga interaksi dalam chatbot. Meskipun ada tantangan dalam mengontrol keluaran, pengguna dapat memanfaatkan teknik ini untuk meningkatkan produktivitas dan inovasi dalam pengolahan bahasa alami.

penggunaan pipeline fill-mask

Pipeline fill-mask dari pustaka transformers memungkinkan pengguna untuk dengan mudah mengisi bagian yang hilang dalam kalimat dengan kata-kata yang relevan. Dengan kemampuan untuk memahami konteks, model ini sangat berguna dalam berbagai aplikasi dalam pengolahan bahasa alami. Meskipun ada beberapa keterbatasan, teknik ini memberikan cara yang efisien untuk meningkatkan pemahaman dan interaksi dengan teks

Pipeline Named Entity Recognition (NER)

digunakan untuk mengenali entitas dalam teks, seperti nama orang, organisasi, lokasi, atau istilah penting lainnya. Dengan grouped_entities=True, entitas yang berdekatan dan serupa akan dikelompokkan menjadi satu.Pipeline NER dari pustaka transformers sangat berguna untuk mengenali dan mengklasifikasikan entitas dalam teks, terutama dalam aplikasi seperti ekstraksi informasi atau analisis teks. Dengan pengelompokan

pipeline question-answering

Pipeline question-answering dari pustaka transformers memungkinkan model untuk menjawab pertanyaan dengan akurat berdasarkan konteks yang diberikan. Model ini sangat berguna dalam aplikasi berbasis teks yang membutuhkan pencarian informasi atau respons otomatis, seperti chatbot atau asisten virtual.

Pipeline sentiment-analysis dari pustaka transformers

alat yang sangat berguna untuk analisis sentimen dalam berbagai aplikasi, seperti ulasan produk, media sosial, atau survei. Meskipun model ini efektif dalam mengenali sentimen dasar, hasilnya bisa menjadi kurang akurat dalam kalimat yang kompleks atau ambigu label: Menunjukkan sentimen yang diprediksi model. Dalam contoh ini, hasilnya NEGATIVE karena kalimat tersebut menyoroti adanya kekurangan/bug, meskipun ada elemen positifnya score: Menunjukkan tingkat kepercayaan model terhadap prediksi tersebut, dalam hal ini 0.95 atau 95%, yang menunjukkan kepercayaan tinggi bahwa sentimen adalah negatif.

pipeline summarization

adalah alat efektif untuk menghasilkan ringkasan dari teks panjang. Ringkasan ini memudahkan pemahaman informasi utama, terutama ketika menganalisis artikel, laporan, atau dokumen panjang. Meskipun masih ada kekurangan dalam detail, pipeline ini sangat bermanfaat dalam aplikasi yang membutuhkan pemahaman cepat atas konten Informasi Utama: Model berhasil menangkap inti dari paragraf tentang perkembangan, kebutuhan tenaga ahli, dan perbandingan dengan negara lain. Keefektifan Ringkasan: Hasil ringkasan merangkum informasi penting tanpa menyertakan detail yang berlebihan.

pipeline translation

Pipeline translation dari pustaka transformers adalah alat yang sangat berguna untuk menerjemahkan teks antar bahasa. Dengan kemudahan dan akurasi yang ditawarkan, alat ini sangat bermanfaat dalam aplikasi yang membutuhkan terjemahan cepat

pipeline question-answering

Pipeline question-answering ini sangat berguna untuk aplikasi yang membutuhkan jawaban berdasarkan konteks tertentu, seperti chatbot atau sistem pencarian informasi. Kodenya sederhana dan mudah diterapkan, terutama untuk pertanyaan dan konteks yang jelas
