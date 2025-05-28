. Restoran Sipariş ve Fiş Sistemi
Amaç: Masalara özel yemek siparişlerinin alındığı ve fiş yazdırıldığı restoran sistemi.
OOP Kavramları:
•	Kompozisyon: Siparis içinde Yemek listesi tutulur.
•	Arayüz: IYemek, IYazdirilabilir
•	Kapsülleme: Ürün fiyatı ve toplam tutar hesaplama
Modüller:
•	Menü Yönetimi (yemek & içecek)
•	Masa ve Sipariş Takibi
•	Fiş Yazdırma (console’da veya dosyaya)
Geliştirme İpuçları:
•	Tüm siparişleri Dictionary<Masa, List<Yemek>> ile saklayabilirsiniz.
•	Fiş çıktısı StreamWriter ile dosyaya alınabilir.
