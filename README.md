# Proje 1: Insertion Sort

## [22,27,16,2,18,6] -> Insertion Sort

## Soru 1: Yukarıda verilen dizinin sort türüne göre aşamalarını yazınız.
Insertion Sort Aşamaları;
[22,27,16,2,18,6]
[16,22,27,2,18,6]
[2,16,22,27,18,6]
[2,16,18,22,27,6]
[2,6,16,18,22,27]

## Soru 2: Dizinin Big-O gösterimini yazınız.
• Best Case: O(n) — Sıralıysa, elemanlar sadece bir kez kontrol edilir.
• Average Case: O(n²)
• Worst Case: O(n²) — Tersten sıralıysa, her eleman için sıralı kısmın tamamını kontrol etmek gerekir.

 ## Soru 3: Time Complexity, Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer?
Dizi sıralandıktan sonra 18 sayısı dizinin ortalarına gelmiş oluyor bu nedenle Average Case uygun oluyor.

## Soru 4: [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.
Selection Sort'a göre ilk 4 Adım:
[7, 3, 5, 8, 2, 9, 4, 15, 6]
[2, 3, 5, 8, 7, 9, 4, 15, 6] -> 1
[2, 3, 5, 8, 7, 9, 4, 15, 6] -> 2
[2, 3, 4, 8, 7, 9, 5, 15, 6] -> 3
[2, 3, 4, 5, 7, 9, 8, 15, 6] -> 4
