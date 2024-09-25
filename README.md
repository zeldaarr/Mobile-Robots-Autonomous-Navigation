# Navigasi Otonom Robot Mobile

## Gambaran Umum

Proyek ini berfokus pada pengembangan algoritma navigasi otonom untuk robot mobile. Dengan memanfaatkan kombinasi **input sensor**, **perencanaan jalur**, dan **mekanisme kontrol**, robot dalam proyek ini mampu menavigasi lingkungan yang kompleks tanpa campur tangan manusia. Proyek ini juga mengintegrasikan **ROS (Robot Operating System)** dan **SLAM (Simultaneous Localization and Mapping)** serta beberapa strategi navigasi lainnya.

Repositori ini berisi implementasi dalam **Python** dan **C++**, yang dirancang untuk digunakan dalam kerangka robotik seperti ROS, sehingga cocok untuk aplikasi robotik dunia nyata.

## Fitur
- **Navigasi Otonom**: Robot mobile mampu bernavigasi di lingkungan yang sudah ditentukan atau dinamis menggunakan data sensor.
- **Deteksi Halangan**: Mengimplementasikan teknik fusi sensor untuk mendeteksi rintangan secara real-time.
- **Perencanaan Jalur**: Menggunakan algoritma seperti A*, Dijkstra, dan RRT (Rapidly-exploring Random Trees) untuk perencanaan jalur yang efisien.
- **Lokalisasi & Pemetaan**: Menggunakan teknik SLAM untuk memetakan lingkungan dan menentukan posisi robot.
- **Integrasi dengan ROS**: Dirancang untuk beroperasi dalam kerangka ROS dengan memanfaatkan node standar ROS untuk komunikasi.

## Instalasi & Setup

1. Clone repositori ini:
   ```bash
   git clone https://github.com/srnand/Mobile-Robots-Autonomous-Navigation.git
