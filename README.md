﻿# MergeSortProject
Merge Sort algoritması, bir diziyi sıralamak için kullanılan bir böl ve fethet (divide and conquer) yöntemidir. İşlem, diziyi sürekli olarak ikiye bölüp, her iki yarıyı sıralayıp, son olarak sıralı yarıları birleştirerek devam eder.

Dizi: [16,21,11,8,12,22]

Merge Sort Aşamaları
Bölme (Divide):

Dizi ikiye bölünür:
Sol: [16, 21, 11]
Sağ: [8, 12, 22]
Daha Küçük Parçalara Ayırma:

Sol dizi [16, 21, 11] ikiye bölünür:
Sol: [16]
Sağ: [21, 11]
Sağ dizi [8, 12, 22] ikiye bölünür:
Sol: [8]
Sağ: [12, 22]
Tek Elemanlı Diziler:

[16] ve [21, 11]
[8] ve [12, 22]
Daha Küçük Parçaları Bölme:

[21, 11] ikiye bölünür:
Sol: [21]
Sağ: [11]
[12, 22] ikiye bölünür:
Sol: [12]
Sağ: [22]
Birleştirme (Merge):

[21] ve [11] birleştirilir ve sıralanır:
Sonuç: [11, 21]
[12] ve [22] birleştirilir ve sıralanır:
Sonuç: [12, 22]
Birleştirme:

[16] ve [11, 21] birleştirilir ve sıralanır:
Sol: [11, 16, 21]
[8] ve [12, 22] birleştirilir ve sıralanır:
Sonuç: [8, 12, 22]
Son Birleştirme:

[11, 16, 21] ve [8, 12, 22] birleştirilir ve sıralanır:
Sonuç: [8, 11, 12, 16, 21, 22]
Big-O Gösterimi
Worst Case (En Kötü Durum): O(n log n) - Her ikiye bölme işlemi ve her birleştirme işlemi log(n) derinliğe sahip olduğu için, toplam işlem süresi n log n olur.
Best Case (En İyi Durum): O(n log n) - Merge Sort her durumda aynı adımları izlediği için, en iyi durumda bile zaman karmaşıklığı O(n log n)'dir.
Average Case (Ortalama Durum): O(n log n) - Ortalama durumda da zaman karmaşıklığı O(n log n)'dir.
Özetle, Merge Sort'un Big-O gösterimi tüm durumlar için O(n log n) şeklindedir.
