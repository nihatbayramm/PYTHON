n-Küp Grafiği Çizici Uygulaması
Bu uygulama, kullanıcının girdiği bir n değeri üzerinden n-küp grafiği oluşturan bir GUI (grafik kullanıcı arayüzü) sağlar. Kullanıcı, bir sayı girerek bir n-küp grafiğinin düğüm ve kenarlarını görsel olarak görebilir.

Kullanılan Kütüphaneler
tkinter: GUI (Grafiksel Kullanıcı Arayüzü) oluşturmak için kullanılır.
networkx: n-küp grafı oluşturmak için kullanılan bir grafik kütüphanesidir.
matplotlib: Grafiği görselleştirmek ve çizmek için kullanılır.
Özellikler
Kullanıcı, bir sayı girdikten sonra, n-küp grafiğini görsel olarak oluşturabilir.
Hatalı girişler (negatif sayı veya sayı dışında bir karakter) yapıldığında uyarı mesajı ile kullanıcı bilgilendirilir.
Kurulum
Projeyi çalıştırmak için aşağıdaki Python kütüphanelerini yüklemeniz gerekmektedir:

bash
Kodu kopyala
pip install networkx
pip install matplotlib
Not: tkinter çoğu Python kurulumunda varsayılan olarak gelir. Yine de kurulum eksikse, sudo apt-get install python3-tk komutuyla yükleyebilirsiniz (Linux için).

Kullanım
Projeyi bir Python dosyası olarak kaydedin, örneğin n_kup_grafigi.py.

Python dosyasını çalıştırmak için şu komutu kullanın:

bash
Kodu kopyala
python n_kup_grafigi.py
Çıkan pencerede, n-küp grafiği oluşturmak istediğiniz sayıyı girin ve "Grafı oluştur" butonuna tıklayın.

Girilen n sayısına göre oluşturulmuş n-küp grafiği yeni bir pencerede görünecektir.

Kod Açıklamaları
n_kupu_ciz(n): Girilen n değeri ile bir n-küp grafiği oluşturan fonksiyon.
ciz_buton_tiklama(): Butona tıklandığında, kullanıcı girdisini kontrol eden ve geçerli ise n-küp grafiği oluşturan fonksiyon.
GUI: tkinter kütüphanesi ile temel bir arayüz oluşturulmuştur. Giriş kutusu ve buton aracılığıyla kullanıcıdan giriş alınıp, çizim işlemi yapılır.
Hata Mesajları
Negatif bir sayı veya geçersiz bir giriş yapılırsa, kullanıcıya bir hata mesajı görüntülenir.
