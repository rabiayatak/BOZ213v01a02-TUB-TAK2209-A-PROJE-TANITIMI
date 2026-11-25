# BOZ213-TUB-TAK-2209-A-PROJE-DOSYASI-VE-SUNUMU
BU DEPODA, TUBİTAK 2209-A PROJE DOSYAM VE VİDEOLU PROJE SUNUMUM YER ALMAKTADIR.

Proje İsmi: : Programlama Laboratuvarlarında Yardım İstemeyen Öğrencinin Sessiz Öğrenme Çıkmazı: Yapay Zekâ Destekli Yüz ve Davranış İşaretlerinin Zamansal Doğrulaması

Konusu:
Programlama laboratuvarında bazı öğrenciler takılır ama el kaldırmaz. Yetersiz görünmekten çekinir, sessizce bekler, kimse de fark etmez. Bu projede bu durumu "sessiz öğrenme çıkmazı" olarak adlandırıyoruz ve web tabanlı programlama dersinde inceliyoruz.

Amacı:
Eğitmen aynı anda herkesin ekranına bakamıyor, o yüzden çoğu zaman el kaldırana gidiyor. "Uzun süredir kodda ilerleme yok" bilgisi de tek başına yetmiyor, çünkü öğrenci takılmış olabileceği gibi sadece düşünüyor da olabilir. Projenin amacı, öğrencinin davranışlarına ve yüz hareketlerine bakarak takılan öğrenciyi düşünen öğrenciden ayırıp ayıramayacağımızı görmek.

Diğer Çalışmalardan Farkı:
Daha önceki çalışmalar takılan öğrenciyi ya yalnızca kod kayıtlarına bakarak ya da nabız sensörü gibi ek cihazlarla bulmaya çalışmış. Öğrencinin takılıp takılmadığına da genellikle dışarıdan bakan biri karar vermiş. Bu projede üç fark var:

Öğrencinin o an ne durumda olduğunu öğrencinin kendisi söylüyor.
Hiçbir ek cihaz gerekmiyor; öğrencinin kendi dizüstü bilgisayarı yeterli.
Ortaya çıkan kural daha sonraki bir derste yeniden deneniyor, yani tek seferlik bir sonuçla yetinilmiyor.

Nasıl Yapılacak?
Yaklaşık 25 gönüllü öğrenci, üç laboratuvar dersinde her zamanki etkinliklerini kendi bilgisayarlarında yapacak. Derse hiç müdahale edilmeyecek. Ders boyunca bir program kamerayı, ekranı ve klavye kullanımını kaydedecek; ses kaydedilmeyecek, basılan harfler de kaydedilmeyecek. Ders sonunda öğrenci, geri bildirim testiyle 'sessiz öğrenme çıkmazı' anlarını bildirecek, zamansal doğrulama yöntemi ile sonuçlar toplanıp netleştirilecektir.

Ardından kayıtlardan altı işaret otomatik olarak çıkarılacak: kaş çatma, ekrana eğilme, geriye yaslanma, eli yüze götürme, etrafa bakma ve aynı kodu tekrar tekrar silip yazma. Son olarak iki kural karşılaştırılacak: sadece "ne kadar süredir ilerleme yok?" sorusuna bakan kural ve bu süreye en az iki işareti de ekleyen kural.

Kullanılan Uygulamalar:
Projede kullanılan araçların hepsi ücretsiz ve Python tabanlı:

Python: Kayıt programı, verilerin düzenlenmesi ve tüm analizler Python ile yapılıyor.
MediaPipe: Google'ın yapay zekâ kütüphanesidir; kamera görüntüsünden kaş, baş ve el hareketlerini otomatik ölçüyor.
OpenCV: Videoları kare kare okuyor.
Yapay zekâ dil modeli: Öğrencilerin yazdığı yorumları "takılmış", "düşünüyor", "ilerliyor" diye sınıflandırıyor.


Hedefleri:

En az 20 öğrenciden veri toplamak.
Takılma anlarını ve yardım istenmeyen anları saymak, öğrencilerin neden yardım istemediğini öğrenmek.
İşaretlerin "sadece süre" kuralını gerçekten geliştirip geliştirmediğini ortaya koymak.
Eğitmenler için "hangi işaretleri görünce hangi öğrenciye gitmeli" sorusunu cevaplayan kısa bir gözlem rehberi hazırlamak.

İleride Neyi Hedefliyor?
Bu proje ilk adım. Sonuçlar olumlu çıkarsa ileride eğitmenin ekranında takılan öğrencileri anlık gösteren bir sistem geliştirilebilir. Ek cihaz ve ücret gerektirmediği için yöntem her okulun programlama laboratuvarında uygulanabilir. Uzun vadedeki amaç, sessizce takılan hiçbir öğrencinin fark edilmeden dersten kopmaması.
