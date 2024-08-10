Association Rule Learning ile Ürün Tavsiye Sistemi

Türkiye’nin en büyük online hizmet platformu olan Armut, hizmet verenler ile hizmet almak isteyenleri buluşturmaktadır. Bilgisayarın veya akıllı telefonunun üzerinden birkaç dokunuşla temizlik, tadilat, nakliyat gibi hizmetlere kolayca ulaşılmasını sağlamaktadır. Hizmet alan kullanıcıları ve bu kullanıcıların almış oldukları servis ve kategorileri içeren veri setini kullanarak Association Rule Learning ile ürün tavsiye sistemi oluşturulmak istenmektedir.

Veri Seti

Veri seti müşterilerin aldıkları servislerden ve bu servislerin kategorilerinden oluşmaktadır. Alınan her hizmetin tarih ve saat bilgisi de içermektedir.

Değişkenler

- **UserId:** Müşteri numarası. Her müşterinin eşsiz kimliği.
- **ServiceId:** Her kategoriye ait anonimleştirilmiş servisler. Örneğin, Temizlik kategorisi altında koltuk yıkama servisi olabilir. Bir ServiceId, farklı kategoriler altında bulunabilir ve farklı servisleri ifade edebilir. Örneğin, CategoryId’si 7 ve ServiceId’si 4 olan hizmet petek temizliği iken, CategoryId’si 2 ve ServiceId’si 4 olan hizmet mobilya montaj olabilir.
- **CategoryId:** Anonimleştirilmiş kategoriler. Örneğin, Temizlik, nakliyat, tadilat kategorileri.
- **CreateDate:** Hizmetin satın alındığı tarih. 

Proje Amacı

Bu projede, müşteri hizmetleri ve hizmet kategorilerini kullanarak Association Rule Learning (Kümeleme ve Bağlantı Kuralı Öğrenimi) yöntemleriyle bir ürün tavsiye sistemi oluşturulacaktır. Hedefler şunlardır:

1. **Veri Hazırlığı:** Veri setinin yüklenmesi ve temizlenmesi. Eksik veya hatalı verilerin düzeltilmesi.
2. **Kümeleme ve Analiz:** Müşteri hizmet kullanım alışkanlıklarının analiz edilmesi.
3. **Tavsiye Sistemi Oluşturma:** Association Rule Learning algoritmalarını kullanarak ürün tavsiye sisteminin geliştirilmesi.
4. **Sonuçların Görselleştirilmesi:** Tavsiye sisteminin sonuçlarının özetlenmesi ve görselleştirilmesi.
5. **Performans Ölçümü:** Tavsiye sisteminin performansının değerlendirilmesi.

Katkıda Bulunma

Bu proje üzerinde geliştirme yapmak istiyorsanız, lütfen projeyi fork'layın ve pull request gönderin. Her türlü katkı kabul edilir ve projeye katkıda bulunanlara teşekkür edilir.

Lisans

Bu proje MIT Lisansı altında lisanslanmıştır. Lisans hakkında daha fazla bilgi için LICENSE dosyasına bakabilirsiniz.
