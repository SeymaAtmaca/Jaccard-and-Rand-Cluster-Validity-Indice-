# Jaccard-and-Rand-Cluster-Validity-Indice-

<br><br>Jaccard ve Rand geçerleme indisleri, bir sınıflandırma sonucu elde edilen verilerin ne derece doğru olduğunu gösteren indislerdir. Bu indisler a, b, c, ve d değerlerini kullanarak J ve R değerlerinin hesaplanmasına dayanır. <br><br> a değeri, kümeleme sonucu aynı kümeye düşen aynı sınıfa ait çift sayısını,<br> b değeri, farklı kümelerde bulunan aynı sınıfa mensup elemanların çift sayısını, <br> c değeri, aynı kümede bulunan farklı sınıfların oluşturduğu çiftlerin sayısını, <br> d değeri, farklı kümelerde bulunan farklı sınıflara mensup elemanların oluşturduğu çiftlerin sayısını ifade eder. <br><br><br>
Aşağıdaki resimde ikili kümelemeye ait bir örnek yer almaktadır. Buna göre a değeri: <br><br>
![ilk](https://github.com/SeymaAtmaca/Jaccard-and-Rand-Cluster-Validity-Indice-/blob/main/images/ilk.png) <br><br>
c2 etiketli sınıfların a için değeri a1 kümesi için --> (c2,c2) =1 ve a2 kümesi için --> (c2,c2) = 1 dir. <br><br>
![c2](https://github.com/SeymaAtmaca/Jaccard-and-Rand-Cluster-Validity-Indice-/blob/main/images/c2.png) <br><br>
c1 etiketli sınıfların a için değeri a1 kümesi için 0 ve a2 için (c1,c1)(c1,c1)(c1,c1) = 3 tür. <br><br>
![c1](https://github.com/SeymaAtmaca/Jaccard-and-Rand-Cluster-Validity-Indice-/blob/main/images/c1.png) <br><br>
c3 etiketli sınıfların a için değeri a1 kümesi için (c3,c3) = 1 ve a2 için 0 dır. <br><br>
![c3](https://github.com/SeymaAtmaca/Jaccard-and-Rand-Cluster-Validity-Indice-/blob/main/images/c3.png) <br><br><br> Bu sonuçların hepsi toplandığında a için = 1 + 1 + 0 + 3 + 1 + 0 = 6 dır. Bu örnek için b, c, d değerleri de hesaplanır. <br> J ve R, hesaplanan bu değerlerden sonra aşağıdaki formüller ile bulunur: <br><br>

![j ve R ](https://github.com/SeymaAtmaca/Jaccard-and-Rand-Cluster-Validity-Indice-/blob/main/images/J%20R.png)<br><br> J ve R değerleri, modelimizin ne kadar iyi ayrım yaptığı ve doğru sonuç verdiğinin bir göstergesidir. Yukarıdaki formüllere göre iyi bir modelin c ve b değerlerinin düşük, a ve d değerlerinin ise büyük olması beklenir. 
