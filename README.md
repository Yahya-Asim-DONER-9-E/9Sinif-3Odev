# 9Sinif-3 Ödev

Aşağıdaki yönerge adımlarını lütfen uygulayın. 

## Bölüm 1 (İvmeli Hareket Yapan Cismin Konum Zaman Grafiğinin Çizimi)

1)✔️ Bu ödevi kendi hesabınıza fork edin. Sonra da kendi hesabınızdan bu repoya ait Issue kısmını açın. (Ödevleriniz hakkında size yorum bırakabilmem için gerekli.) 

2)✔️ 2.ödevinizde doğrusal bir denklemin (1.dereceden) grafiğini hem elle hem de Google Sheet ile çizdiniz. Bu sefer ikinci dereceden bir denklemi Google Sheet ile çizeceksiniz. İkinci dereceden denkleminiz *y = ax^2+b*x+c* şeklinde olacak. Burada a,b, ve c katsayılardır. 

3) ✔️[Bu Videoyu](https://www.youtube.com/watch?v=--1-cfnicJ8) izleyin ve ikinci derecede denklemin nasıl Google Sheet ile çizileceğini öğrenin. Bu videoda bir karenin kenar uzunluğu ile alanın değişme grafiği çizilmiştir. Yani bu video için denkleminiz *y = x^2* şeklinde değişmiş. Yani *a=1, b=0,c=0* dır. 

4) ✔️[Bu Video'nun](https://www.youtube.com/watch?v=fhIL18aHg8s&feature=youtu.be) 1.kısmını izliyerek (11-26 saniye arası) 1 kg'lık bir kütlenin  zaman-konum grafiğini çizecekseniz. Burada ivmeli (yavaşlayan) bir hareket olacağından konum-zaman grafiği 2.dereceden denklem olarak çıkacak. 2.dereceden bir denklemi elle çizmeyi 10.sınıf matematik dersinde öğreneceksiniz. Siz bu ödevde bilgisayardan yardım alacaksanız. Video izliyerek çıkardığım zaman-konum tablosu aşağıdaki gibidir. (Not: Video 60 FPS(frame pers second) ile çekilmiştir. O zaman her frame(çerçeve) 1/60 s'dir. Siz istediğiniz noktayı orijin olarak alabilirsiniz. Ben 7'inci frameden başladım ve kütlenin sol ucunu başlangıç noktası seçtim. (x=0, t=0) 


| Frame | Zaman(s) | Konum (m)|         
|-------|----------| ---------|         
| 7 (Başlangıç)| 0 |   0      |        
| 14    | 7/60     |   0.2    |          
| 18    | 11/60    |   0.295  |       
| 23    | 16/60    |   0.4    |        
| 25    | 18/60    |   0.44   |              
| 28    | 21/60    |   0.49   |         
| 33    | 26/60    |   0.55   |       
| 38    | 31/60    |   0.61   |       
| 45    | 38/60    |   0.65   |            
| 48    | 41/60    |   0.67   |    
| 53    | 46/60    |   0.675  |           
                                        
**_Buda Benim Tablom_**
| Frame | Zaman(s) | Konum (m)|    
|-------|----------| ---------| 
|7(Başlangıç)|  0  |    0     | 
|8      | 1/60     | 0,03| 
|10|3/60|0,09| 
|15|8/60|0,223|     
|18|11/60|0,295|     
|20|13/60|0,34| 
|27|20/60|0,42| 
|30|23/60|0,52| 
|34|27/60|0,57|   
|39|32/60|0,62|  
|43|36/60|0,65| 
|45|38/60|0,66| 
|48|41/60|0,67| 
|53|46/60|0,675| 
|53|46/60|0,675|

Yukarıdaki aldığım verilerin Google Sheet'deki çizimini [burada](https://docs.google.com/spreadsheets/d/1PFojWqpQKHUI6shl7_bbvQSjrb3AS6kleerbCbNNWVg/edit?usp=sharing) bulabilirsiniz. Bu grafiği çizmek için, grafiğin üzerine iki kere tıkladım. Açılan yan pencerede aşağıdaki değişiklikleri yaptım. 
*   Chart Editor ------> Chart type -------> Scatter chart
*   Customize ------> Trendline -------> Polynomial,  Polynnomial Degree=2, Label= Use Equation

Bulduğum ikinci dereceden denklem (x= konum, t=zaman, *x= at^2+b*t + c*) şu şekilde çıktı:
*x = -1.22*t^2 + 1.81*t + 3.92E-03* 


Yukarıdaki örneği kullanarak **kendi ölçümlerinizle** bir tablo oluşturun (hiç değilse birkaç frame benim ölçümlerinden farklı olsun.) Kullandığınız Google Sheet için [buraya mı link veriyoruz hocam?](https://docs.google.com/spreadsheets/d/1stnaSU4EwF3aGddOBZSJ0y1J8i7vpq83ODpkSmrdzlI/edit?usp=sharing)  (Google Sheet herkese açık erişimli olsun.) 

a)✔️  Denklemim: _x = Konum t = Zaman x = -1,14t^2+1,76t+3,83E-03_ . Sizce a, b, ve c'nin fiziksel anlamları ne olabilir? Sizce niçin a'nın değeri negatif? 

Bu soru için Geogebradan biraz yardım aldım bulduğum grafiği yazdım ve katsayıları değiştirerek neler olduğunu gözlemledim

* a yı arttırdıkça konum ve zaman azalıyordu ve grafik daha bükülmüüş hale geliyordu yani eğim azalıyordu
* b yi arttırdıkça konum ve zaman artıyordu
* c yi arttırdıkça grafiğin y ekseni yani konumla kesiştiği nokta değişiyordu
burdan yorumlayarak: 
--------------------------------------------------------------------------------------------
* a nın sürtünme kuvveti olduğunu ve bu yüzden negatif olduğunu söyleyebilirim.
* b nin başlangıç hızı veya başlagıç kuvveti olduğunu ve 
* c nin ilk konumu olduğunu söyleyebilirim.
![Geogebra](https://user-images.githubusercontent.com/63353356/79634342-86708f80-8172-11ea-9e11-ee6702a31b0b.png)

b)✔️ Hava sürtünmesini ihmal edersek, bu harakette ivme sabit midir? 

**Sabittir**. a = F/m olacağından ve net f kuvveti ve kütle sabit olduğundan ivmede sabittir.

c)✔️ Video'daki cismin atılış hızı farklı olsaydı (diğer herşey aynı, kütle, yüzey, vb. Hava sürtünmesini ihmal edin), sizce formülde hangi terimler değişecekti? (a, b veya c) 

Yukarıda anlattığım sebeplerden dolayı **b** değişecektir.
# Bölüm 2 (İvmeli Hareketin Ortalama Hız-Zaman Grafiği)
Bu sefer aynı cismin zaman-hız (ortalama hız) grafiğini çizeceksiniz. Bunun için *1.Bölümde* aldığımız sonuçları kullanacağız. Ortalama hızı bulmak için derste öğrendiğimiz ortalama hız formülünü (Delta x/ Delta t) kullanacağız. Google Sheet kullanarak hız-zaman grafiği nasıl çizildiğini anlamak için  [bu videoya](https://www.youtube.com/watch?v=67IsHRmcmfE&t) bakınız. Ortalama hız-zaman grafiğini çizilirken, ortalama hıza karşılık gelen zamanı nasıl belirleyeceksin? Bir andaki  ortalama hızı hesaplarken o noktadan önceki ve o noktadan sonraki (t,x) noktalarını kullanacaksın. Bu yüzden konum grafiğimde 11 veri noktam varken, hız-zaman grafiğinde veri noktam 9'a düştü. (İlk baştaki ve son baştaki noktalar için ortalama hızı hesaplayamam çünkü başlangıç noktasından önce ve bitiş noktasından sonraki (t,x) bilgilerine sahip değilim.)

Ben kendi verilerim için bir google sheet hazırladım. [Buraya](https://docs.google.com/spreadsheets/d/1fFw-F2NP9XpglTTEkqOjZETT7lD0iE9sqH3Da-srS9w/edit?usp=sharing) bakabilirsiniz. Ortalama hız grafiğini çizerken bu sefer 
*   Customize ------> Trendline -------> Linear, Label=Use Equation
kullandım. Konum-zaman grafiği 2.dereceden bir denklem iken, hız-zaman grafiği 1.dereceden (linear-doğrusal) denklem. 

1)✔️ Kendi aldığınız verileri kullanarak **ortalama hız-zaman** grafiğini Google çiziniz. [Buraya diyosunuz yani.](https://docs.google.com/spreadsheets/d/1TzUaAAHVZGl3zIjCwFg33zODJ3zuv4f35kDXKgxSO1s/edit?usp=sharing)

2)✔️ Aynı Google Sheet'i kullanarak ivme verilerini Google Sheet'inize girin. (Bu sefer 7 tane ivme veriniz olacak.) İvme-zaman grafiğini çiziniz.

3)✔️ İvme'yi ne buldunuz? Bu ivme değerini kullanarak 1kg'lık cisim ile yüzey arasındaki kinetik sürtünme katsayısını bulunuz. 

İvmeyi yaklaşık olarak -3 buldum.
* F = m . a dan F(s) = 1 . -3 olur burdan F(sürtünme) -3 bulunur.
* F(s) = k . x ten -3 = k .  0.675 gelir burdan k = -4,44 buldum.

# Bölüm 3 (Ramak Kaldı Diyebilirim)
1)❌ Bu deneyde ölçüm hatalarım var. Zamandaki ölçüm hatam sizce kaç ms (mili saniye) nedir? Konumdaki ölçüm hatam sizce kaç cm'dir?

  Hiçbir Fikrim yok.

2)❌Acaba hiç grafik çizmeden sürtünme katsayısını bulabilir miydim?  (Cevap: Sizi bilemem ama ben yapamadım). 
Yardım:
* Düzgün ivmelenen bir cisim için alınan yol formülü x = (ilk hız+ son hız)/2, burdan cismin ilk hızını bulunuz. 
* Daha sonra iş-kinetik enerji teorimini kullanarak sürtünme kuvvetini bulun. Sürtünme kuvvetinden, kinetik sürtünme katsayısını bulunuz.



3)✔️ Bu video'dan statik sürtünme katsayısını bulabilir miydim? 
  Bulamazdınız çünkü cismi harekete geçirmek için gereken kuvvvetin kaç olduğunu bilmiyorsunuz.
