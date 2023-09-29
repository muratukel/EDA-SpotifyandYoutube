# Spotify and Youtube 🎤🎬 

## Veri Seti Hakkında

Dünya çapındaki çeşitli sanatçıların şarkılarının bulunduğu bir veri kümesi ve her şarkı için aşağıdaki bilgiler bulunmaktadır:

Spotify'daki müziğin çeşitli istatistikleri, bu istatistikler arasında akış sayısı da yer almaktadır.
Şarkının resmi müzik videosunun YouTube'daki izlenme sayısı.

* Bu açıklama, veri kümesinin içeriği hakkında genel bir bilgi vermektedir. Veri kümesi, dünya genelindeki çeşitli sanatçıların şarkılarını ve bu şarkılarla ilgili Spotify ve YouTube istatistiklerini içermektedir. Spotify'daki şarkıların akış sayıları ve YouTube'daki resmi müzik videolarının izlenme sayıları gibi veriler, müzikle ilgili çeşitli analizlerin yapılmasına olanak sağlar.*

# Veri Setinin İçeriği

Spotify'dan toplanan her şarkı için 26 değişken içermektedir. Bu değişkenler kısaca şu şekildedir:

Track: Spotify platformunda görülebilen şarkının adı.
Artist: sanatçının adı.
Url_spotify: sanatçının Spotify üzerindeki URL'si.
Album: şarkının Spotify'daki bulunduğu albüm.
Album_type: şarkının Spotify'da tek olarak mı yoksa bir albümün parçası olarak mı yayınlandığını belirtir.
Uri: şarkıyı API aracılığıyla bulmak için kullanılan bir Spotify bağlantısı.
Dans Edilebilirlik (Danceability): tempo, ritim istikrarı, vuruş gücü ve genel düzenlilik gibi müzikal öğelerin kombinasyonuna dayalı olarak bir şarkının dans etmek için ne kadar uygun olduğunu açıklar. Değerler 0.0 en az dans edilebilirken, 1.0 en çok dans edilebilir anlamına gelir.
Enerji (Energy): 0.0 ile 1.0 arasında bir ölçüdür ve bir şarkının algılanan yoğunluğunu ve etkinliğini temsil eder. Genellikle enerjik şarkılar hızlı, yüksek sesli ve gürültülü hissettirir. Örneğin, death metal yüksek enerjiye sahiptir, ancak bir Bach prelüdü ölçekte düşük bir puan alır. Bu özellikle ilgili olarak algılanan ses şiddeti, tonal renk, başlangıç hızı ve genel entropiyi içerir.
Ton (Key): şarkının tonu. Tamsayılar standart Pitch Class gösterimi kullanarak notalara eşlenir. Örneğin, 0 = C, 1 = C♯/D♭, 2 = D vb. Bir ton algılanmadıysa, değer -1'dir.
Yükseklik (Loudness): şarkının genel ses yüksekliği desibeller (dB) cinsinden. Ses yüksekliği değerleri şarkının tamamı boyunca ortalamaları alınır ve şarkıların göreceli ses yüksekliğini karşılaştırmak için kullanışlıdır. Ses yüksekliği, bir sesin fiziksel güç (genlik) ile ilgili psikolojik bir özelliktir. Değerler genellikle -60 ile 0 dB arasında değişir.
Konuşma Benzerliği (Speechiness): bir şarkıdaki konuşma benzeri sözcüklerin varlığını algılar. Kayıt ne kadar çok konuşma gibi ise (örneğin, talk show, sesli kitap, şiir), bu özelliğin değeri o kadar yaklaşık olarak 1.0'a olur. 0.66'dan yüksek değerler muhtemelen tamamen konuşma içeren şarkıları tanımlar. 0.33 ile 0.66 arasındaki değerler, müzik ve konuşma içeren şarkıları tanımlar, ya bölümlerde veya katmanlı olarak, rap müziği gibi örnekler de dahil. 0.33'ten düşük değerler muhtemelen müziği ve diğer konuşma olmayan şarkıları temsil eder.
Akustiklik (Acousticness): bir şarkının akustik olup olmadığına dair 0.0 ile 1.0 arasında bir güven ölçüsüdür. 1.0, şarkının kesinlikle akustik olduğu yüksek güveni temsil eder.
Enstrümantallik (Instrumentalness): bir şarkının vokal içerip içermediğini tahmin eder. "Ooh" ve "aah" sesleri bu bağlamda enstrümantal olarak kabul edilir. Rap veya konuşma içeren şarkılar açıkça "vokal" olarak kabul edilir. Enstrümantal olasılığı değeri 1.0'a yaklaştıkça, şarkının vokal içermeme olasılığı o kadar yüksektir. 0.5'in üzerindeki değerler enstrümantal şarkıları temsil etmeyi amaçlar, ancak değer 1.0'e yaklaştıkça güven de artar.
Canlılık (Liveness): kayıtta bir izleyici varlığını algılar. Daha yüksek canlılık değerleri, şarkının canlı performe edilme olasılığını artırır. 0.8'in üzerinde bir değer, şarkının canlı performans olduğu yüksek bir olasılık sağlar.
