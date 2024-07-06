### README.md

# Packet Tracer Uygulaması: İki Şirket Ağını Birleştirme

Bu proje, Cisco Packet Tracer kullanılarak iki şirket ağını birbirine bağlayan bir ağ topolojisini içermektedir. Bu topoloji, çeşitli departmanları ve cihazları içeren bir ağ yapısını temsil eder.

## Proje Özeti

Ağ topolojisi, aşağıdaki bileşenleri ve bağlantıları içermektedir:

- **Çeşitli Departmanlar:** Güvenlik, Yazılım, İnsan Kaynakları (HR) ve diğerleri.
- **Yönlendiriciler (Routerlar):** İki ana yönlendirici (Router0 ve Router1) kullanılarak iki farklı ağ segmenti birbirine bağlanmıştır.
- **Anahtarlar (Switchler):** Her departmanda, cihazları birbirine bağlamak için kullanılan anahtarlar bulunmaktadır.
- **Bilgisayarlar (PC'ler):** Her departmanda belirli sayıda bilgisayar bulunmaktadır ve bunlar kendi yerel ağlarında yer almaktadır.
- **IP Adresleri:** Her cihaz için atanmış belirli IP adresleri bulunmaktadır.

## Topoloji Detayları

- **Güvenlik Departmanı (Guvenlik):**
  - **Bilgisayarlar:** PC11, PC13
  - **Anahtar:** dep1SW
  - **IP Adresleri:** Otomatik veya manuel atanmış IP adresleri.

- **Yazılım Departmanı (Yazılım):**
  - **Bilgisayarlar:** PC8, PC9, PC0, PC1
  - **Anahtar:** deptSW
  - **IP Adresleri:** 192.168.1.2, 192.168.1.3
  
- **İnsan Kaynakları Departmanı (HR):**
  - **Bilgisayarlar:** PC4, PC5
  - **Anahtar:** dep3SW
  - **IP Adresleri:** Otomatik veya manuel atanmış IP adresleri.

- **Diğer Şirket Ağı:**
  - **Bilgisayarlar:** PC2, PC3
  - **Anahtar:** ruzumsW1
  - **IP Adresleri:** 192.168.2.2, 192.168.2.3

- **Yönlendiriciler:**
  - **Router0:** 192.168.1.1 (yerel ağ), 10.0.0.1 (harici ağ)
  - **Router1:** 10.0.0.2 (harici ağ), 192.168.2.1 (yerel ağ)

## Bağlantılar

- **Router0** ve **Router1** arasındaki bağlantı, her iki yönlendiricinin harici ağ portları (10.0.0.1 ve 10.0.0.2) üzerinden sağlanmıştır.
- Her departmandaki anahtarlar, ilgili bilgisayarları kendi yerel ağlarına bağlamak için kullanılır.
- Her yönlendirici, kendi yerel ağındaki anahtara bağlıdır ve bu bağlantılar üzerinden cihazlarla iletişim kurar.

## Kurulum ve Çalıştırma

1. **Packet Tracer'ı Açın:** Cisco Packet Tracer uygulamasını açın.
2. **Dosyayı Yükleyin:** Proje dosyasını Packet Tracer içine yükleyin.
3. **Ağ Konfigürasyonlarını Kontrol Edin:** Tüm bağlantıların ve IP adreslerinin doğru yapılandırıldığından emin olun.
4. **Test Edin:** Cihazlar arasında pingi kullanarak bağlantıları ve iletişimi test edin.

## Kullanım

Bu topoloji, iki farklı şirket ağını birbirine bağlamak için kullanılabilir. Ağ yapılandırmalarını ve bağlantılarını test etmek için kullanılabilir ve eğitim amaçlı olarak ağ yönetimi ve yapılandırma becerilerini geliştirmek için idealdir.

![packettracertest](https://github.com/Hamzaakl/Basit-Ag-Kurma/assets/163044736/f6a82bb6-63bf-4c60-b799-dd382f9cda95)

