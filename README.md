# Tas-Kagit-Makas_Mobil--Oyun
  - Taş-Kağıt-Makas, genellikle iki oyuncuyla ve üç durumdan birinin seçilmesiyle oynanan bir el oyunudur. 

  - Taş makası, Makas kağıdı, Kağıt da taşı yener. Eğer oyuncular aynı durumu seçerlerse oyun berabere biter. 

  - Kullanım alanları Yazı-Tura çöp çekme gibi oyunların yerine seçilebilir.


## Gereksinimler
   - Android Studio

   - JDK 11
  
  
## Kurulum
   - Kaynak kod, Android Studio IDE'ye import ederek aktarılır.

   - Proje Android Studio IDE ile açılıp build yapılıp çalıştırılır.

   - Açılan Emulator ekranı ya da uygulamaya dışarıdan bağlanan Android cihaz ile run edilir.
  
## Kazanma Durumları
   • Taş makası kırarak yener.
   
   • Kağıt taşı sararak yener.
   
   • Makas kağıdı keserek yener.
     Belirlenen skora ilk ulaşan kazanır. İstenirse tek seferli oyunlar da oynanabilir.
  
  
## Taş
   • El yumruk şeklindedir.
   
![rock](https://user-images.githubusercontent.com/81168263/154966487-5f68dde0-79e7-4c19-bf4f-8f53c1b41bc3.png)
  
## Kağıt
   • El tamamen açık parmaklar birbirine yapışıktır.
   
![paper](https://user-images.githubusercontent.com/81168263/154966997-896f47d4-18bc-44d7-ae0b-2ff7d88c3d2f.png)  

## Makas
   • Elin işaret parmağı ve orta parmağı hariç bütün parmaklar avuç içine kıvrılmıştır, işaret
   parmağı ve orta parmak birbirinden ayrıktır.
   
![scissors](https://user-images.githubusercontent.com/81168263/154967009-f3382e20-e0b3-4600-870c-f38d46d5b9b3.png)  

## Uygulamanın yüklenmesi ve çalıştırılması işlemi  
   Bu uygulama Playstore’dan Telefon|Tablet|Bilgisayar’ dan indirilip cihaza yüklendiğinde
   aşağıdaki resimde okların gösterildiği gibi bir simge ile cihaza yüklenmiş olur.
   Uygulama çalışır vaziyette cihazda yüklenmiştir. Şekilde gösterildiği gibi uygulamaya çift tıklanır ve oyun açılır.
<p align="center">
  <img width="300" height="600" src="https://user-images.githubusercontent.com/81168263/154969977-ff0c41f9-0f30-4e7d-9546-947c6fe00213.jpg">
</p>     

## Açılış Ekranı
   Uygulamaya çift tıkladıktan sonra oyun açılır görünüm aşağıdaki gibidir. Oyun açıldığında Kullanıcı aşağıdaki ekran görüntüsüne erişecektir. 
   Oyun kullanıcının bilgisayara karşı oynama durumu aşağıdaki gibi ekranda belirir, oyunda aşağıda görüldüğü gibi 3 adet buton bulunmaktadır. 
   Oyuncu kendi isteğine bağlı olarak bu butonlardan birini seçip butona tıklar ve aynı anda bilgisayarda rasgele olarak bir seçim yapar. 
   Oyuncunun seçimi ile Bilgisayarın seçimine bağlı olarak oyunun kazanma durumu ekranda bildiri olarak ve sonuç tablosunda belirir.
    
<p align="center">
  <img width="300" height="600" src="https://user-images.githubusercontent.com/81168263/154970537-a1de0cf1-d643-41cf-af35-c57f87f67af1.jpg">
</p>     

#### 1
     Bu programda Oyuncunun Bilgisayara karşı oynanması durumda oyuncunun aşağıdaki butonlardan istediğinden birini(Taş|Kağıt|Makas)
     seçerek oyun içindeki seçimini yapmış olur. Oyun içerisinde Oyuncu Seçiminden Makası seçtiğimde bilgisayar ise rastgele olarak 
     Kağıdı seçmiş oldu ve bu durumda oyunun kuralları gereği bilindiği üzere Makas keser Kağıdı ve Oyuncu Bilgisayar’a karşı bu eli
     kazanmış olur. Aşağıda gösterildiği gibi Sonuç tablosunda Oyuncunun Puanı 1 Bilgisayarın Puanı ise 0 olur.    
<p align="center">
  <img width="300" height="600" src="https://user-images.githubusercontent.com/81168263/154970710-91596dc9-0c90-48b0-b808-e4b7355b375d.jpg">
</p>     


#### 2
     Oyuna devam ettiğimde ve ben bu sefer butonlardan Taş’ ı seçtiğimde bilgisayar rasgele olarak Kağıt’ ı seçer ve oyun kuralları gereği 
     bilindiği üzere Kağıt sarar Taşı ve bu durumda bilgisayar kazanmış olur ve bilgisayarın sonucuna 1 Puan eklenir ve bu durumda Oyuncu
     1 Bilgisayar 1 olur. Berabere durum söz konusu olur.
<p align="center">
  <img width="300" height="600" src="https://user-images.githubusercontent.com/81168263/154970728-0fd52364-a098-4e3c-9b11-1e21f17d9f65.jpg">
</p>       
     


#### 3
     Oyuna kaldığı yerden devam ettiğimde ve ben bu sefer butonlardan yine Taş’ ı seçtiğimde bilgisayar rasgele olarak Makas’ ı seçer ve
     oyun kuralları gereği bilindiği üzere Taş kırar Makası ve Aşağıda gösterildiği gibi Sonuç tablosunda Oyuncunun Puanına +1 puan daha
     eklenir ve Oyuncu 2 Bilgisayar 1 oyuncu kazanmış olur sonuç tablosu güncellenir ve bu durumda görüldüğü üzere oyuncu bilgisayara
     karşı puan olarak daha önde olur. 
<p align="center">
  <img width="300" height="600" src="https://user-images.githubusercontent.com/81168263/154970739-2017fab2-5479-40e8-923c-0449eb22c145.jpg">
</p>      


#### 4
     Oyuna kaldığı yerden devam ettiğimde ve ben bu sefer butonlardan Aşağıda görüldüğü gibi Kağıt’ ı seçtiğimde bilgisayar rasgele olarak
     Taş’ ı seçer ve oyun kuralları gereği bilindiği üzere Kağıt sarar Taşı ve bu durumda yine Oyuncu kazanmış olur ve aşağıda gösterildiği
     gibi Sonuç tablosunda Oyuncunun Puanına +1 puan daha eklenir. Oyuncu 3 Bilgisayar 1 puan olarak sonuç tablosu güncellenir ve bu durumda
     görüldüğü üzere oyuncu bilgisayara karşı puan olarak daha önde olur.
<p align="center">
  <img width="300" height="600" src="https://user-images.githubusercontent.com/81168263/154970752-3280c519-a9a0-4799-b14a-8f0764bcfba0.jpg">
</p>      


    
    
#### 5
     Oyuna kaldığı yerden devam ettiğimde ve ben bu sefer butonlardan Aşağıda görüldüğü gibi Oyuncu Seçimi olarak Makas’ ı seçtiğimde
     bilgisayar rasgele olarak Kağıt’ ı seçer ve oyun kuralları gereği bilindiği üzere Makas keser Kağıdı ve bu durumda yine Oyuncu
     kazanmış olur ve aşağıda gösterildiği gibi Sonuç tablosunda Oyuncunun Puanına +1 puan daha eklenir. Oyuncu 4 Bilgisayar 1 puan 
     olarak sonuç tablosu güncellenir ve bu durumda görüldüğü üzere oyuncu bilgisayara karşı puan olarak daha önde olur.
<p align="center">
  <img width="300" height="600" src="https://user-images.githubusercontent.com/81168263/154970767-84b34721-b06b-4689-824b-6d3337cfb410.jpg">
</p>     


#### 6
     Oyuna kaldığı yerden devam ettiğimde ve ben bu sefer butonlardan Aşağıda görüldüğü gibi Oyuncu Seçimi olarak Taş’ ı seçtiğimde 
     bilgisayar rasgele olarak Kağıt’ ı seçer ve oyun kuralları gereği bilindiği üzere Kağıt sarar Taşı ve bu durumda Bilgisayar
     kazanmış olur ve aşağıda gösterildiği gibi Sonuç tablosunda Bilgisayarın Puanına +1 puan daha eklenir. Oyuncu 4 Bilgisayar
     2 puan olarak sonuç tablosu güncellenir ve bu durumda görüldüğü üzere oyuncu bilgisayara karşı puan olarak daha önde olur.
 <p align="center">
  <img width="300" height="600" src="https://user-images.githubusercontent.com/81168263/154970786-3f8993e4-7f34-44f9-82e4-aed4ce8813d7.jpg">
</p>     


## Dipnot
   Uygulamanın Kaynak kodununun içerisinde Apk(Çalışır) hali klasörde mevcut.
