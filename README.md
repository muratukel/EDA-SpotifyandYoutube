# Spotify ve Youtube Keşifsel Veri Analizi 🎤🎬 
![Image](https://i.ytimg.com/vi/sEX9xIUPfnM/maxresdefault.jpg)


## ℹ️ Veri Seti Hakkında

Dünya çapındaki çeşitli sanatçıların şarkılarının bulunduğu bir veri kümesi ve her şarkı için aşağıdaki bilgiler bulunmaktadır:

Spotify'daki müziğin çeşitli istatistikleri, bu istatistikler arasında akış sayısı da yer almaktadır.
Şarkının resmi müzik videosunun YouTube'daki izlenme sayısı.

* Bu açıklama, veri kümesinin içeriği hakkında genel bir bilgi vermektedir. Veri kümesi, dünya genelindeki çeşitli sanatçıların şarkılarını ve bu şarkılarla ilgili Spotify ve YouTube istatistiklerini içermektedir. Spotify'daki şarkıların akış sayıları ve YouTube'daki resmi müzik videolarının izlenme sayıları gibi veriler, müzikle ilgili çeşitli analizlerin yapılmasına olanak sağlar.*

# 🕵️‍♂️ Veri Setinin İçeriği

Spotify'dan toplanan her şarkı için 26 değişken içermektedir. Bu değişkenler kısaca şu şekildedir:

- **Track**: Spotify platformunda görülebilen şarkının adı.
- **Artist**: Sanatçının adı.
- **Url_spotify**: Sanatçının Spotify üzerindeki URL'si.
- **Album**: Şarkının Spotify'daki bulunduğu albüm.
- **Album_type**: Şarkının Spotify'da tek olarak mı yoksa bir albümün parçası olarak mı yayınlandığını belirtir.
- **Uri**: Şarkıyı API aracılığıyla bulmak için kullanılan bir Spotify bağlantısı.
- **Dans Edilebilirlik (Danceability)**: Tempo, ritim istikrarı, vuruş gücü ve genel düzenlilik gibi müzikal öğelerin kombinasyonuna dayalı olarak bir şarkının dans etmek için ne kadar uygun olduğunu açıklar. Değerler 0.0 en az dans edilebilirken, 1.0 en çok dans edilebilir anlamına gelir.
- **Enerji (Energy)**: 0.0 ile 1.0 arasında bir ölçüdür ve bir şarkının algılanan yoğunluğunu ve etkinliğini temsil eder.
- **Ton (Key)**: Şarkının tonu. Tamsayılar standart Pitch Class gösterimi kullanarak notalara eşlenir.
- **Yükseklik (Loudness)**: Şarkının genel ses yüksekliği desibeller (dB) cinsinden.
- **Konuşma Benzerliği (Speechiness)**: Bir şarkıdaki konuşma benzeri sözcüklerin varlığını algılar.
- **Akustiklik (Acousticness)**: Bir şarkının akustik olup olmadığına dair 0.0 ile 1.0 arasında bir güven ölçüsüdür.
- **Enstrümantallik (Instrumentalness)**: Bir şarkının vokal içerip içermediğini tahmin eder.
- **Canlılık (Liveness)**: Kayıtta bir izleyici varlığını algılar.
- **Duygu Durumu (Valence)**: Bir şarkının 0.0 ile 1.0 arasındaki bir ölçüsüdür ve bir şarkının aktardığı müzikal olumlu duygu derecesini tanımlar. Yüksek valansa sahip şarkılar daha olumlu bir his verir (örneğin, mutlu, neşeli, coşkulu), düşük valansa sahip olanlar ise daha olumsuz bir his verir (örneğin, üzgün, sıkılmış, sinirli).
- **Tempo**: Şarkının genel tahmini tempo değeri dakikadaki vuruş sayısı (BPM) cinsindendir. Müzik terimleri açısından tempo, verilen bir parçanın hızı veya temposudur ve ortalama vuruş süresinden doğrudan türetilir.

- **Süre_ms (Duration_ms)**: Şarkının süresi milisaniye cinsinden ölçülür.

- **Stream**: Şarkının Spotify'daki akış sayısı.

- **Url_youtube**: Şarkıya bağlı olan YouTube'daki video URL'si, eğer varsa.

- **Başlık (Title)**: YouTube'daki video klibin başlığı.

- **Kanal (Channel)**: Videoyu yayınlayan kanalın adı.

- **Görüntülenme Sayısı (Views)**: Görüntülenme sayısı.

- **Beğenme Sayısı (Likes)**: Beğenme sayısı.

- **Yorum Sayısı (Comments)**: Yorum sayısı.

- **Açıklama (Description)**: YouTube'daki video hakkında açıklama.

- **Lisanslı (Licensed)**: Video lisanslı içerik temsil edip etmediğini belirtir. Bu, içeriğin bir YouTube içerik ortağına bağlı bir kanala yüklenip ardından bu ortak tarafından talep edilip edilmediğini ifade eder.

- **Resmi Video (official_video)**: Şarkının resmi video olup olmadığını gösteren boolean bir değerdir.

❗ Bu veri setiyle çalışırken veya analiz ederken, verilerin 7 Şubat 2023 tarihinde toplanmasından bu yana sağlanan bilgilerin ve ölçümlerin değişmiş veya gelişmiş olabileceğini akılda tutmak önemlidir. Kullanıcılar, müzik veya video içeriğinin mevcut durumunu tam olarak temsil etmeyebileceğinden, verilere dayanarak sonuç çıkarırken veya çıkarımlarda bulunurken bu zamansal yönü göz önünde bulundurmalıdır.

*Veri Seti Linki:* 
[Spotify ve YouTube Veri Seti](https://www.kaggle.com/datasets/salvatorerastelli/spotify-and-youtube)

🎯Spotify ve Youtube veri seti ile gerçekleştirdiğim keşifsel veri analizi, müzik tüketim alışkanlıklarını daha iyi anlamak, sanatçıların ve müzik platformlarının performansını incelemek ve geliştirme fırsatlarını belirlemek amacıyla gerçekleştirdiğim bir proje oldu. Bu analizler, müziğin büyüleyici dünyasına daha derin bir bakış açısı sunmayı ve sektördeki değişen dinamikleri anlamamıza yardımcı oldu.

Jupyter Notebook'ta gerçekleştirdiğim bu projede, veri seti üzerinde detaylı analizler ve görselleştirmeler gerçekleştirdim. Analizler sonucunda ortaya çıkan iyileştirme önerilerini ve fırsatları paylaştım. Bu öneriler, müzik platformları, sanatçılar ve dinleyiciler için daha iyi bir deneyim yaratma potansiyeli taşıyor.

Bu proje, kariyerimdeki gelişimime olumlu bir katkı sağladı ve veri analizi alanında daha da ilerlemek için motive etti. Gelecekte, daha fazla veri analizi projesine katılmayı ve bu alandaki yeteneklerimi geliştirmeyi hedefliyorum.

Analizimi incelemek ve daha fazla detay öğrenmek için lütfen [Jupyter Notebook Çalışma Dosyama](https://github.com/muratukel/EDA-SpotifyandYoutube/blob/main/EDASpotifyandYoutube%20.ipynb) buradan ulaşın. Eğer analizim size ilginç veya yararlı geldiyse, lütfen yıldız vererek destek olmayı unutmayın.

Sizleri projelerim ve veri analizi yolculuğumda takip etmeye davet ediyorum.
