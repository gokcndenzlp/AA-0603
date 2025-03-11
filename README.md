# AA-0603
 🔢 MatrixSum & FindMax  

Bu proje, **FindMax** ve **MatrixSum** algoritmalarını içerir.  
- **FindMax**: Bir dizideki en büyük elemanı bulan algoritma.  
- **MatrixSum**: Bir matris içindeki tüm elemanların toplamını hesaplayan algoritma.  

Ayrıca, **Big-O zaman karmaşıklıkları**, **arama ve sıralama algoritmaları**, **rekürsif fonksiyonlar** ve **verimlilik analizleri** hakkında özet bilgiler içermektedir.

---

## 📌 Algoritma Açıklamaları  

### **FindMax Algoritması**  
**Amaç**: Bir dizideki en büyük elemanı bulmak.  
Zaman Karmaşıklığı:
Algoritma diziyi O(n) zaman karmaşıklığında tarar.
Best case (En iyi durum): İlk eleman en büyükse O(n)
Worst case (En kötü durum): Son eleman en büyükse O(n)
MatrixSum Algoritması
Amaç: Bir matrisin tüm elemanlarının toplamını bulmak.
Zaman Karmaşıklığı:
Matrisin tüm elemanlarını tek tek topladığı için O(n × m)
Best case / Worst case değişmez, her zaman O(n × m) olur.
📈 Big-O Analizi ve Notlar
Arama Algoritmaları
Doğrusal arama (Linear Search): O(n)
Binary Search (İkili Arama - Sıralı diziler için):
Best case: O(1) (İlk denemede bulunursa)
Worst case: O(log n)
Sıralama Algoritmaları
Bubble Sort: O(n²)
Selection Sort: O(n²)
Insertion Sort: Ortalama O(n²), En iyi durumda O(n)
Quick Sort: Ortalama O(n log n), En kötü durumda O(n²)
Merge Sort: O(n log n)
Rekürsif Algoritmalar ve T(n) Çözümlemesi
Birçok rekürsif algoritmanın karmaşıklığını analiz etmek için T(n) denklemleri kullanılır:

Divide & Conquer (Böl ve Fethet) yöntemleri genellikle O(n log n) karmaşıklığa sahiptir.
Örneğin, Maximum Subarray Problem için rekürsif çözüm:
T(n) = 2T(n/2) + O(n)
Master Teoremi ile çözüldüğünde O(n log n) sonucuna ulaşılır.
Üstel ve Logaritmik Fonksiyonlar
Power (aⁿ) hesaplama:
Naive yöntem: O(n)
Recursive yöntemi: O(log n)
aⁿ = (a^(n/2) * a^(n/2)) kullanımı logaritmik zaman kazandırır.
