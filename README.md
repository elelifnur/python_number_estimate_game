# python_number_estimate_game
Python programlama dili ile 2 kişilik sayı tahmin etme oyunu yapmanız isteniyor. Aşağıda özellikleri verilen oyunu uygun şekilde programlayınız

Oyun 2 kişilik olacaktır. Oyun başladığında 1.oyuncu ve 2.oyuncu isimleri girilmesi istenecektir

Oyuncu isimleri girdikten sonra sorulan sorularda ilk oyuncunun ismi ile giriş bilgileri istenecektir. Örn: ilk oyuncu ismi Fehim; Fehim sayı tahiminin girer misin?


Başlangıçta her 2 kullanıcının 100 puanı olacak ve her yanlış tahminde 10 puanı silinecek, eğer kalan puanı 0 olduğu anda ilgili oyuncu için puan yerine Başarısız yazacak ve ilk oyuncu ise  yeni tahmin istenmeden 2.oyuncuya geçecek, eğer 2. oyuncuda Başarısız olursa oyun tamamlanacak ve ekrana oyuncuların puanları yada Başarısız ise karşılarına başarısız yazacak . Her 2 oyuncuda başarısız olursa, Üzgünüz ikiniz de kaybettiğiniz  mesajı kerana yazılacaktır.
Örn: Oyun Sonucu;
Fehim : 70
Kerem: 60
Kerem kazandı, tebrik ederiz
Veya
Oyun Sonucu;
Fehim : Başarısız.
Kerem: 60
Kerem kazandı, tebrik ederiz
Veya
Fehim : Başarısız.
Kerem: Başarısız.
Üzgünüz ikiniz de kaybettiğiniz


Oyun başladığında program random olarak 1 ile 81 aralığında sayı üretecek. Oyuncular bu aralıkta sayıları tahmin ederek yüksek puan almaya çalışacaklar.( Not: İnternet üzerinden pythonda random sayı üretme nasıl olduğu araştırılacak)


İlk oyuncu tahminlemeyi tamamladıktan sonra sıra ikinci oyuncuya geçecek ve oyun ikinci oyuncunun tahminleyeceği sayıyı tekrardan random olarak oluşturacak.

Oyuncuların tahmin ettiği sayı doğru değil ise, oyunun ürettiği tahmin edilecek sayının +-3 aralığında bir sayının plaka konumuna göre şehrine uzak olduğunun mesajı ekrana yazılacak.
Örn: Tahmin edilecek sayı 26 ve oyuncu 55 olarak tahmin etti, oyuncuyu doğru yönlendirmek için 26-3=23 ile 26+3=29 sayıları arasından random sayı üretim(yani 23-29 arası random sayı ama 26 olmayacak) üretilen sayın örneğin 25 olsun. Oyuncunun ekranına tahmin ettiğin yer Erzuruma Uzak Kaldı mesajı ekrana yazılacak, ve oyuncudan 10 puan silinecek, bir sonraki tahmininin girilmesi istenecek. Böylelikle oyuncu tahmin edecek sayının aralığı ile ilgili yönlendirme yapılmış olacak)
