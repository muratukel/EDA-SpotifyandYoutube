# Spotify and Youtube 🎤🎬 

## Veri Seti Hakkında

Dünya çapındaki çeşitli sanatçıların şarkılarının bulunduğu bir veri kümesi ve her şarkı için aşağıdaki bilgiler bulunmaktadır:

Spotify'daki müziğin çeşitli istatistikleri, bu istatistikler arasında akış sayısı da yer almaktadır.
Şarkının resmi müzik videosunun YouTube'daki izlenme sayısı.

* Bu açıklama, veri kümesinin içeriği hakkında genel bir bilgi vermektedir. Veri kümesi, dünya genelindeki çeşitli sanatçıların şarkılarını ve bu şarkılarla ilgili Spotify ve YouTube istatistiklerini içermektedir. Spotify'daki şarkıların akış sayıları ve YouTube'daki resmi müzik videolarının izlenme sayıları gibi veriler, müzikle ilgili çeşitli analizlerin yapılmasına olanak sağlar.*

# Veri Setinin İçeriği

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

