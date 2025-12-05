# NumPy Dizi Öznitelikleri (Array Attributes)

Bu script, oluşturulan NumPy dizilerinin yapısal özelliklerini sorgulamak için kullanılan temel komutları içerir. Veri analizi öncesinde veriyi tanımak (data exploration) için bu komutlar hayati önem taşır.

## İncelenen Özellikler
Kod içerisinde `vector` (1D) ve `matris` (2D) yapıları üzerinde şu sorgular yapılmıştır:
* **`.size`:** Dizideki toplam eleman sayısını döndürür.
* **`.shape`:** Dizinin boyut yapısını (satır, sütun) tuple formatında verir.
* **`.ndim`:** Dizinin kaç boyutlu olduğunu (Rank) verir (Vektör=1, Matris=2).
* **`.dtype`:** Dizinin içindeki verilerin türünü (örneğin: `int32`, `float64`) gösterir.
