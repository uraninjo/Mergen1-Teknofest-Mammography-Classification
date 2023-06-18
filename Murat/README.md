# Mergen1-Teknofest-Murat

Dosya sisteminde,
* KadranÖzel: Sadece kadranı belirleme üzerine yapılan çalışmalar yer alıyor.
* MemeUcu: Kadranın bir parçasıdır fakat KadranÖzel içerisinde kullanılmayan bir parçadır. Bu yüzden dışarıda tutuluyor.
* TestPipeline: Yarışma anı için kullanılacak kodların sıralanıp tutulduğu dosyadır.
* biradsclassificationmodifon.ipynb: Sıradan pytorch sınıflandırma kodunu kendi verimiz için uyarlanmış halidir. Bu kısımdaki önemli olan değişiklikler; 
	- Veri overfit olmaya yatkın olduğu için en iyi val_acc'de confusion matrixin çizdirilmesi
	- Dengesiz verinin kod içinde dengeli hale getirilmesi veya dengesiz verinin dengeli olması için kodun her epochta değiştirilen dengeli veri görmesi(Bu deneyin farklı varyasyonda veriler görmesi için kullanılabileceği düşünüldü.)
* birads_split.ipynb: BIRADS kategorisine göre verinin ayrılması işlemini yapar.
* kompozisyon_split.ipynb: Kompozisyon kategorisine göre verinin ayrılması işlemini yapar.
* resize_output.ipynb: Verinin boyutlarını tekrardan belirlemek için kullanılır.
* segmentasyon.ipynb: Segmentasyon mimarisi hazırlanır.
* test_segmentasyon.ipynb: Segmentasyon mimarisi test edilmek üzere hazırlanır.
