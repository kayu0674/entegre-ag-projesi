# entegre-ag-projesi

## Projenin Amacı
Bu proje, iki katlı ve toplam 12 ofisten oluşan bir işletmenin kablolu (LAN) ve kablosuz (WLAN) ağ altyapısının sıfırdan planlanmasını, ağ segmentasyonunu ve güvenliğinin sağlanmasını amaçlamaktadır[cite: 1]. İnternet servis sağlayıcısının donanımsal kısıtlamalarını aşmak için özel bir yazılımsal router/firewall katmanı inşa edilmiştir
[entegre-ag-projesi.docx].

## Kullanılan Teknolojiler ve Servisler
* **Güvenlik Duvarı ve Yönlendirme:** Debian Linux, iptables/nftables, Suricata IDS
  [entegre-ag-projesi.docx].
* **Ağ Yönetimi:** BIND9 (DNS), isc-dhcp-server (DHCP)[entegre-ag-projesi.docx].
* **Kimlik Doğrulama:** FreeRADIUS[entegre-ag-projesi.docx].
* **Depolama ve Yedekleme:** Samba Dosya Sunucusu, Rsync Otomasyonu, RAID 1(Aynalama)
  [entegre-ag-projesi.docx].
* **Yazıcı Sunucusu:** CUPS (Sanal Sunucu Katmanı)[entegre-ag-projesi.docx].

## Proje Belgeleri
* `entegre-ag-projesi.docx`: Proje kimliği, IP/Subnet planlaması, sunucu konfigürasyon dosyaları, MAC/ARP tabloları ve Erişim Kontrol Listesi (ACL) matrisini içeren detaylı teknik rapor[entegre-ag-projesi.docx].
* `Ofis Planı.jpg`: Zemin ve birinci kat priz dönüşümlerini, kabinet konumunu ve tavan bağlantılarını gösteren yapısal yerleşim planı[Ofis Planı.jpg].

## Proje Ekibi
* **Geliştiriciler:**Yusuf Kayra GÜLEÇ
