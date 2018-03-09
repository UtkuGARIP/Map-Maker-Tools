Harita Üreticisi Aracı


Hinterland Studio, Inc. **The Long Dark** için bir moddur.


Yer haritalandırılmasına yardımcı olan [Geliştirici Konsolu](https://github.com/FINDarkside/TLD-Developer-Console)'na komutlar ekler.

Eklenen komutlar:

* `MapMaking-NoTerrainError` - En yüksek piksel hatası yanı sıra çok yüksek bir LOD yanlılığı ve baz harita mesafesini zorlayarak en doğru arazi render'ini üretin. (LOD yanlılığı tüm nesneleri etkileyecektir)
* `MapMaking-NoGrass` - Tüm çimleri gizler
* `MapMaking-FullGrass` - Maksimum çim yoğunluğunu ayarla
* `MapMaking-NoTrees` - Kuşburnu veya ağaç kütüğü haricinde tüm ağaçları ve çalıları gizler.
* `MapMaking-FullTrees` - Ağaç çizim mesafesini maksimum seviyeye çıkart ve asla reklam panolarını render etme.
* `MapMaking-ToggleBloom` - AmplifyBloom efektini aç/kapat (Çimlerin büyümesi, gün döngüsü veya lamba parıltısı)
* `MapMaking-ToggleContrast` - Kontrast İyileştirme efektini aç/kapat
* `MapMaking-ToggleVignette` - VignetteAndChromaticAberration efektini aç/kapat
* `MapMaking-NoShadows` - Gölgeleri tamamen devre dışı bırak
* `MapMaking-ShadowDistance` - Verilen parametreye gölge çizim mesafesini ayarlayın. Bu oldukça deneyseldir, çünkü çizim mesafesini arttırırken gölgeler hızlı bir şekilde parçalanmaya başlar.
* `MapMaking-None` - Do `MapMaking-NoTerrainError` + `MapMaking-NoGrass` + `MapMaking-NoTrees`
* `MapMaking-Full` - Do `MapMaking-NoTerrainError` + `MapMaking-FullGrass` + `MapMaking-FullTrees`
* `MapMaking-Reset` - Tüm ayarları daha önce seçilen kalite ayarlarına geri döndür.

* `FaithfulCartographer-ShowIncompleteRegions` - List regions that are still considered incomplete for the 'Faithful Cartographer' achievement
* `FaithfulCartographer-ShowMissingPlacesInCurrentRegion` - Faithful Cartographer başarısı için eksik olan bölgeleri listele


Ayarların hiçbiri kalıcı olmayacak ve sahneleri değiştirirken ya da oyunu kapatırken daha önce seçilen kalite ayarlarına geri dönecektir.


Modun kurulumu için [Mod Yükleyici](https://github.com/zeobviouslyfakeacc/ModLoaderInstaller) gereklidir.
