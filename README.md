# Dogus-zingat-real-estate-forecasting

![image](https://user-images.githubusercontent.com/64266044/212747702-c60b7628-187c-4bf9-84f8-06b2aae7b0a5.png)



### Dataset Description
Veri setinde pandemi etkisi göz önünde bulundurulduğu için Ocak 2019 tarihinden itibaren ev tipi ve fiyatını etkileyen diğer değişkenlerle birlikte güncel fiyat tahminlemesi yapıldı.

  |─ Veriseti toplam 99700 row ve 20 değişkenden oluşmaktadır.



# Veriseti aşağıdaki Özniteliklerden oluşmaktadır:

  `Ilan_ID`:  Her bir ilana ait ID numaralarını içeren değişkendir.
  `Tarih` : 01.01.2019 Tarihinden itibaren başlayan zaman değişkenidir.
  `Path` : "IL/Ilce/Mahalle" formatında İstanbul'daki 5 ilçeyi barındıran object türündeki değişkendir.
  `Güncel_fiyat`: TRY biriminde tahminlenmesi beklenen hedef değişkenimizdir.
  `Odasayısı`: Evin sahip olduğu oda sayısını "2+1" veya "3+1" gibi çeşitli yapılarda barındıran değişkenimizdir.
  `brütm² `:  Söz konusu evin brüt olarak kapladığı alana ait bilgi içeren değişkendir.
  `netm²` :   Söz konusu evin net olarak kapladığı alan bilgisini içeren değişkendir.
  `Emlaktipi` : Daire, rezidans, villa, müstakil ev, Prefabrik Ev, Yalı Dairesi, Köşk / Konak / Yalı, Çiftlik Evi veya Yazlık olup olmadığını içeren değişkenlerdir.
  `Binayaşı` : Bina yaşının hangi aralıklarda olduğu bilgisini veren değişkendir.
  `Bulunduğukat`:  Evin binanın kaçıncı katında yer aldığı bilgisini verir.
  `Manzara` : Cadde,Deniz,Göl, Şehir, Doğa,Dağ, Park,Boğaz,, Yeşil Alan vb. Çeşitli kombinasyonlarından oluşan ve birden fazla manzaraya da sahip olabilen değişkendir.
  `Binadakikatsayısı` : 1den 20ye kadar veya 10-20 arası değerlerden oluşmaktadır.
  `Isıtmatipi` : Kombi (Doğalgaz), Merkezi Sistem (Isı Payı Ölçer), Merkezi Sistem, Kalorifer (Doğalgaz),Klima,Yerden Isıtma,Kat Kaloriferi,Kalorifer(Kömür), Yok,Fancoil, Kombi (Elektrikli), Soba (Doğalgaz),Soba (Kömür),Kalorifer (Akaryakıt), Güneş Enerjisi, veya Jeotermal değerlerinden oluşmaktadır.
  `Banyosayisi` : 1den 6ya kadar değerlerden oluşmaktadır.
  `Otopark`: Var (Ücretsiz, Kapalı), Yok, Var (Ücretsiz, Açık), Var, -, Var (Açık,Kapalı), Var (Ücretli, Açık) ve Var (Ücretli, Kapalı) değerlerinden oluşmaktadır.
  `Id`: Ilan_ID

  `Expected`: Güncel_fiyat (TRY cinsinden)
