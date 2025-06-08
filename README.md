# Hamming SEC-DED Simülatörü

Bu proje, JavaScript tabanlı bir **Hamming SEC-DED (Single Error Correction, Double Error Detection)** simülatörüdür. Kullanıcılar, 8, 16 veya 32 bitlik veri girdisiyle Hamming kodunu oluşturabilir, tek veya çift bitlik hatalar ekleyebilir ve bu hataları tespit edip düzeltebilir.

## Özellikler

- ✅ 8, 16 veya 32 bitlik veriyle çalışır  
- ✅ Hamming kodu üretir (SEC-DED destekli)
- ✅ Tek veya çift hata ekleme seçenekleri
- ✅ Hata tespiti ve düzeltme (tek hata düzeltilir, çift hata tespit edilir ama düzeltilemez)
- ✅ Kullanıcı dostu arayüz

## Kullanım

1. **Veri Girişi:** `0` ve `1`'lerden oluşan 8, 16 veya 32 bitlik bir veri girin.
2. **Kodla Butonu:** Hamming kodu oluşturulur ve görüntülenir.
3. **Hata Ekle:** Belirttiğiniz bit indeksine tek hata ekleyebilirsiniz.
4. **Çift Hata Ekle:** Farklı iki bit indeksine hata ekleyerek çift hata durumu simüle edebilirsiniz.
5. **Hata Tespit & Düzelt:** Sistem, hatayı tespit eder ve gerekiyorsa düzeltmeye çalışır.

## Teknik Detaylar

- Kodlama algoritması, Hamming kodunun genişletilmiş versiyonudur ve genel parity biti içerir.
- Tüm işlem ve kontroller istemci taraflı JavaScript ile yapılmaktadır.
- Kod, modern tarayıcılarla uyumludur ve kurulum gerektirmez.

## Kullanım Gereksinimleri

Sadece modern bir tarayıcı yeterlidir. Dosyayı açmanız yeterlidir.

## Ekran Görüntüsü

![Ekran görüntüsü 2025-06-08 231315](https://github.com/user-attachments/assets/bdd23cb5-1a62-4f11-96b4-f5039a794335)
![Ekran görüntüsü 2025-06-08 231333](https://github.com/user-attachments/assets/d69fe9af-158f-4791-baa6-4b838a8be843)



## Siz de Deneyin

[Simülasyonu Denemek için tıklayınız](https://asmbrk.github.io/Hamming_Sim/)

## Simülasyon Videosu için 

[Simülasyon videosu için tıklayınız](https://www.youtube.com/watch?v=NCJMXv1PZ9o)

## Proje Dökümanına Ulaşmak için 

[Proje Dökümanı için tıklayınız](https://github.com/AsmBrk/Hamming_Sim/blob/main/BLM230_PROJE_As%C4%B1mBurak%C3%96zt%C3%BCrk_22360859063.pdf)











