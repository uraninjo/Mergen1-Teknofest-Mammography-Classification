# Mergen1-Teknofest-Murat

**CC görüntüsü memenin üstten görüntülenmiş halidir.**

**MLO görüntüsü memenin yanlardan görüntülenmiş halidir**

Dosya sisteminde,
* CC_Ortanokta.ipynb: CC görüntülerine özel kadran belirleme üzerine yapılan bir koddur.
	- CC görüntülerinde meme görüntülerinde orta başlangıç noktası bulunur ve meme ucuna çizgi çizilir.
	- Meme ucu olmadığı durumda ise segmentasyondan çıkan fotoğrafta memenin en uç noktaya değen noktası bulunur ve meme ucu kabul edilir.
	
* MLO_Ortanokta.ipynb: MLO görüntülerine özel kadran belirleme üzerine yapılan bir koddur.
	- Pektoral kastan meme ucuna çizgi çizilir.
	- Meme ucu olmadığı durumda ise segmentasyondan çıkan fotoğrafta memenin en uç noktaya değen noktası bulunur ve meme ucu kabul edilir.
