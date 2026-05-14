# WSC Tarzı Futbol Kariyeri v0.2

Bu v0.2 prototipidir. v0.1 temelinin üstüne ilk 11, istatistik ekranları, kart/sakatlık haberleri ve sezon sonu özeti eklendi.

## Çalıştırma

`index.html` dosyasını açın. Bazı tarayıcılarda ES module dosya erişimi için küçük bir yerel sunucu gerekebilir:

```bash
cd football-manager-game
python3 -m http.server 8000
```

Sonra `http://localhost:8000` adresini açın.

## v0.1 İçerik

- 10 takımlı kurgusal test ligi
- Her takımda 18 oyuncu
- Oyuncu reytingleri: hız, fizik, şut, pas, dribling, potansiyel, durability, enerji
- Gizli maç içi dinamik reyting
- Az baskı / dengeli / çok baskılı taktik seçimi
- Dakika dakika yazılı maç anlatımı
- Lig fikstürü ve puan durumu
- Hafta sistemi
- 3 kayıt slotu
- Tarayıcı localStorage kayıt sistemi
- Haftalık enerji yenilenmesi
- Basit dinamik potansiyel/gelişim

## Sonraki Sürümler İçin Plan

- v0.2: Süper Lig datası, daha gelişmiş kadro/ilk 11 ekranı, kart/sakatlık detayları
- v0.3: 5 büyük lig, kupa sistemi, veri import editörü
- v0.4: UCL/UEL/UECL yeni lig formatı, ülke puanı ve Avrupa fikstürleri


## v0.2 Eklenenler

- İlk 11 seçim ekranı
- Kullanıcı takımının maç motorunda seçilen ilk 11 ile oynaması
- Otomatik en iyi ilk 11 oluşturma
- Gol krallığı ve asist krallığı ekranı
- Kart olayları ve oyuncu kart istatistikleri
- Daha belirgin sakatlık haberleri
- Sezon bittiğinde şampiyon duyurusu
- Eski kayıtlar için basit migration/uyumluluk
