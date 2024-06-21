# BringGo Ship Next Documentation

## Front Tasarım Notları

### 1 - Login Pages
- [x] [Login](https://demos.pixinvent.com/vuexy-nextjs-admin-template/demo-6/en/login)
- [x] [Register](https://demos.pixinvent.com/vuexy-nextjs-admin-template/demo-6/en/register)
- [x] [Forgot Password](https://demos.pixinvent.com/vuexy-nextjs-admin-template/demo-6/en/forgot-password)
- [ ] Google SSO

### 2 - Layout
- [x] [CRM Dashboard](https://demos.pixinvent.com/vuexy-nextjs-admin-template/demo-6/en/dashboards/crm)
  - [x] Horizontal
  - [x] Wide
  - [x] Search (navbar) -> Upcoming Development
    - [ ] Order (Drop)
      - [ ] Warehouse tracking
      - [ ] Tracking Number
      - [ ] Seller Order Id
      - [ ] Inbound Tracking
      - [ ] Product Title
      - [ ] ASIN
    - Destek talebi
      - [ ] Ticket Number
      - [ ] Title
    - Menuler
  - [ ] Dil seçeneği (tr-en-es) (navbar)
  - Bildirimler (navbar)
    - [ ] Kullanıcı özelinde mesaj
    - [ ] Inbound tracking hatırlatması
    - [ ] Etiket girildi uyarısı
    - [ ] Sistem geneli bildirim
  - [x] Light/dark mode (navbar)
  - Profile (navbar)
    - [ ] [Profilim] (https://demos.pixinvent.com/vuexy-nextjs-admin-template/demo-6/en/pages/user-profile)
    - [ ] Ayarlar (https://demos.pixinvent.com/vuexy-nextjs-admin-template/demo-6/en/pages/account-settings)
    - [ ] Bakiye (Gösterim)
    - [x] Güvenli Çıkış

### 3 - Menüler (sidebar - USER MENÜLER)
- Anasayfa
  - [x] Depo bilgileri
- Dropshipping
  - [x] Yeni Gönderi
  - [x] Gönderi Listesi
  - [x] Bekleyen Siparişler
  - [x] Sahipsiz kargolar
- İade Gönderiler
  - [x] İade talebi oluştur
  - [x] İade talep takibi
- Diğer İşlemler
  - [x] Bakiye Yönetimi (profilimdeki Billing&Plan sayfasına yönlenecek)
  - [x] Ödeme detayları
  - [x] Eğitim Videoları
  - [x] Sıkça sorulan sorular (https://demos.pixinvent.com/vuexy-nextjs-admin-template/demo-6/en/pages/faq)
  - [x] Destek talebi (https://demos.pixinvent.com/vuexy-nextjs-admin-template/demo-6/en/forms/form-layouts) [Basic with Icons]
- Kullanıcı Sözleşmeleri
  - [x] Aradepo sözleşmesi
  - [x] Mesafeli satış sözleşmesi
  - [x] Hizmet sözleşmesi

### 4 - Dashboard
- [Ecommerce Dashboard (static)](https://demos.pixinvent.com/vuexy-nextjs-admin-template/demo-6/en/dashboards/ecommerce)
- Duyuru alanı (kayar yazı)
  ![image](https://github.com/BringGo-Ship-Next/roadmap/assets/169343536/6e24ee2a-9791-44fc-b5ec-aba02a0ef711)

### 5 - DropShipping – Yeni Gönderi (form temizle denene kadar cachlenecek)
![yeni_gönderi](https://github.com/BringGo-Ship-Next/roadmap/assets/169343536/a35f8315-3e57-4c82-8fbb-16c091ff63d3)
- Amazon Ürün Arama
  - Foto
  - Ürün adı
  - ASIN + arama butonu (amazon logolu bir buton)
  - Fiyat
  - Ülke
  - Adet
  - Dimensions
  - Weight
- Gönderi Detayları
  - Alıcı adı
  - Adres1
  - Adres2
  - Şehir (fiyat için req)
  - Eyalet
  - Posta kodu (fiyat için req)
  - Telefon
  - Amazon satıcı order id
- Paket Detayları
  - Kullanıcı notu
  - Dosya ekle
- Fiyat Teklifleri
  - Logo -  Servis adı – fiyat
  - Kargo ücretleri (buton – popup açacak)
  - Ödeme yap (default ödeme yöntemi – kredi)
- Fiyat teklifleri popup (içeriği zaten mevcut)

### 6 - DropShipping - Yeni Gönderi (Sonuç sayfaları)
- Başarılı ekranları
  - [Template](https://demos.pixinvent.com/vuexy-nextjs-admin-template/demo-6/en/apps/invoice/preview/4987)
- Başarısız ekranları
  - [Template](https://demos.pixinvent.com/vuexy-nextjs-admin-template/demo-6/en/apps/invoice/preview/4987)

### 7 - DropShipping - Gönderi Listesi
- [Kitchen Sink](https://demos.pixinvent.com/vuexy-nextjs-admin-template/demo-1/en/react-table)
  - Her satırın başında chx olmalı
  - chx hücresinin altında (manuel - amazon iconu)
  - Depo Takip Numarası (Yeni Gönderi sayfasına gidecek ve gerekli değerler ile doldurulmuş olacak)
  - Ürün Fotoğrafı
  - Başlık
  - ASIN
  - Adet
  - Satıcı Hesap Order Id
  - Alıcı Hesap OrderId
  - Inbound Trackings (birden fazla olabilir)
  - Outbound Trackings (birden fazla olabilir)
  - Tutar
  - Durum
  - İşlemler
    - Ödeme Yap
    - İptal Et
    - Inbound Tracking (popup açacak)
    - Fatura İndir
    - Destek Talebi (destek talebi sayfasına yönlenecek)
    - İade Talebi (popup açacak - (Etiket satın al - Etiketim var))

### 8 - DropShipping - Bekleyen Siparişler
- [Kitchen Sink](https://demos.pixinvent.com/vuexy-nextjs-admin-template/demo-1/en/react-table)
  - Her satırın başında chx olmalı
  - Amazon Order Id
  - Ürün Fotoğrafı
  - Başlık
  - ASIN
  - Adet
  - Ülke
  - Tahmini Tutar
  - İşlemler
    - Ödeme Yap (Yeni gönderi ekranına gidecek)
    - İptal Et

### 9 - DropShipping - Sahipsiz Kargolar
![image](https://github.com/BringGo-Ship-Next/roadmap/assets/169343536/8632bea1-1542-467a-a24c-85911dd810f6)
- Inbound Tracking
- Paket içeriği
- Oluşturulma Tarihi
- Fotoğraflar
- İşlemler
  - Destek Talebi

### 10 - İade Gönderiler
- [İade Talep Listesi](https://demos.pixinvent.com/vuexy-nextjs-admin-template/demo-1/en/react-table)
  - Depo Takip Numarası
  - Ürün fotoğrafı
  - Başlık
  - ASIN
  - Kargo Firması
  - Servis Adı
  - Tracking Number
