Metro Simülasyonu Projesi🚇

Bu proje, bir metro ağında en az aktarmalı ve en hızlı rotayı bulmak için BFS ve A* algoritmalarını kullanır.

📌 Kullanılan Teknolojiler ve Kütüphaneler

Python 3

collections: BFS için kuyruk (deque) yapısı oluşturmak için kullanıldı.

heapq: A* algoritması için öncelik kuyruğu yapısında kullanıldı.

defaultdict: Metro hattının graf veri yapısında tutulmasını sağladı.

📌 Özellikler

En Az Aktarmalı Rota: BFS kullanarak en kısa durak sayısını hesaplar.

En Hızlı Rota: A* algoritmasıyla en kısa süreyi hesaplar.

Test Senaryoları: Farklı girişler için test edilebilir.

🚀 Kurulum

Python 3 yüklü olmalıdır.

Terminal veya komut satırında aşağıdaki komutu çalıştırarak dosyayı çalıştırabilirsiniz:

python YusufDuman_metro_simulation.py

📊 Algoritmaların Çalışma Mantığı

🔹 BFS (En Az Aktarmalı Rota)

Başlangıç istasyonu kuyruğa eklenir.

Komşu istasyonlar ziyaret edilir.

En kısa durak sayısıyla hedefe ulaşılır.

Neden BFS? Çünkü en kısa durak sayısını bulmada etkilidir.

🔹 A* (En Hızlı Rota)

Öncelik kuyruğu (heapq) ile en hızlı rota hesaplanır.

Her istasyon için toplam süre belirlenir.

En düşük süreli yol işlenerek hedefe ulaşılır.

Neden A?* Çünkü en kısa sürede ulaşımı garanti eden bir yol bulur.

🛠 Test Senaryoları

Kod içerisinde aşağıdaki test senaryoları uygulanmıştır:

AŞTİ → OSB

Batıkent → Keçiören

Keçiören → AŞTİ

Kızılay → Kızılay (aynı istasyon testi)

X1 → Kızılay (geçersiz istasyon testi)

💡 Geliştirme Fikirleri

Daha büyük bir metro ağı eklenebilir.

Rotalar görselleştirilebilir.

Kullanıcıdan giriş alarak dinamik yapı oluşturulabilir.
