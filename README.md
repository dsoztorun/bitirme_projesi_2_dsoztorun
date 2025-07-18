## MOBİL GÖRÜNÜME GETİRMEYİ UNUTMA!!!!!!!!!!!!!!!!!!!!!!!!


## VİDEO ÇEEEEKKKKK!!!!!!!!




## Bitirme_Projesi_2 Dosyası Hakkında

Proje kapsamında hazırlann Power BI raporu (`.pbix` uzantılı dosya), dosya boyutunun 29 MB'ı aşması nedeniyle GitHub'a doğrudan yüklenememektedir. Bu nedenle, dosya Google Drive üzerinden erişime açılmıştır:

👉 [Bitirme_Projesi_2 (.pbix) Dosyasını İndir](https://drive.google.com/file/d/1So6tm-UDbFs4KCFomeZYYxYXj92HUH7y/view?usp=sharing)

**NOTLAR:** 
1. Bitirme projesindeki hesaplamaların **sağlama**larının yapıldığı **SQL dosyası** github'a eklenmiştir. 
2. Bitirme projesi **mobil görünüm**e uyumludur.
3. Daha önce verilen **sql ödevi** github'a yüklenmiştir.


## Projenin Kapsamı

Bu projede **"TARİŞ"** markasının verileri incelenmiştir. Tablo formatına getirilerek POWER BI ortamına eklenen .csv uzantılı dosyalarda Veri Dönüştürme işlemleri için **Power Query** ortamına geçilmiştir. Sütunlarda **eksik değer** olup olmadığı **Veri Dönüştürme** → **Görünüm** → **Sütun Kalitesi** kutucuğu tıklanarak kontrol edilmiş ve hiçbir tabloda eksik değerin olmadığı görülmüştür. Daha sonra proje kapsamında talep edilen sütun, veri tipi gibi düzenlemeler gerçekleştirilmiştir. 

Proje talebi doğrultusunda rapor **GİRİŞ**, **ÖZET**, **MÜŞTERİ**, **KATEGORİ** ve **KATEGORİ DETAY** sayfalarından oluşmaktadır. GİRİŞ sayfasından ÖZET, MÜŞTERİ ve KATEGORİ sayfalarına sayfa gezgini ile ulaşılmaktadır. KATEGORİ DETAY sayfasına ise KATEGORİ sayfasından geçilmektedir. 

Kullandığımız tablolar arasında bağlantı sağlamak amacıyla yapılan modellemenin ardından, oluşturulan **ölçü**lerle raporun; 

**ÖZET** sayfasında 
Toplam Ciro, Toplam Satış Adedi, Toplam Sipariş Adedi, Toplam Müşteri Sayısı, Müşteri Başına Ciro, Müşteri Başına Satış Adedi ve Ortalama Sipariş Tutarı

**MÜŞTERİ** sayfasında
Toplam Müşteri Sayısı, Tekil Müşteri Sayısı, Kadın Müşteri Sayısı ve Erkek Müşteri Sayısı kartları hazırlanmıştır. 

Hazırlanan grafiklerle;

**ÖZET** sayfasında 
- Hafta içi / Hafta sonu satış tutarları
- Saatlik satış tutarları
- Bölgelere göre toplam satış adetleri

**MÜŞTERİ** sayfasında
- Bölgelere göre müşteri sayısı (harita ile de illere göre dağılım)
- İstanbul ili en yüksek cirolu ilk 10 müşteri
- Yaş gruplarına göre ciro

**Kategori** sayfasında
- İstanbul ili "Yaşlı" segmentli müşteri cirosunun ağaç haritası gösterilmiştir ("Genç" segmentte hiç müşteri olmaması nedeniyle, en yoğun müşteri yaş grubu olan "Yaşlı" filtrelenmiştir). **Kategori Detay** tablosunda ise, **Kategori** sayfasındaki verilerin detayına yer verilmiştir.

Kart ve grafiklerin olduğu sayfalarda, **Tarih**, **Bölge** ve **İl** filtreleri konulmuştur. 
