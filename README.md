Konsol tabanlı casino oyunu

Dil: C++

Zorluk seviyesi: Orta

Konsept: Sanal para ile zar ve kart oyunları oynanan konsol tabanlı casino

Başlangıç parası: 1000 dolar

Oyunlar: – Zar atma (6 yüzlü) – Kart çekme (1–13 arası)

Kayıt sistemi: casino_scores.txt dosyasına para durumu kaydediliyor

Kapanış: Para sıfırlanınca oyun bitiyor

Teknik özellikler: 
srand(time(0))	Rastgelelik için zaman bazlı seed
rand() % 6 + 1	Zar simülasyonu
rand() % 13 + 1	Kart simülasyonu
ofstream kullanımı	Skorları dosyaya yazma
getValidInput()	Giriş doğrulama ve hata kontrolü
Menü sistemi	Kullanıcı dostu yönlendirme

