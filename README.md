# Merge_Sort
**Merge Sort** algoritması, bir diziyi sıralamak için kullanılan bir böl-ve-yönet (divide and conquer) algoritmasıdır. İşte [16, 21, 11, 8, 12, 22] dizisini Merge Sort algoritması ile sıralamanın aşamaları:
## Merge Sort Aşamaları

1. **Bölme Aşaması**:
   - Diziyi ortadan ikiye böleriz.
   - [16, 21, 11] ve [8, 12, 22]

2. **Daha Küçük Parçalara Bölme**:
   - [16, 21, 11] dizisini tekrar böleriz:
     - [16] ve [21, 11]
     - [21, 11] dizisini böleriz:
       - [21] ve [11]
   - [8, 12, 22] dizisini tekrar böleriz:
     - [8] ve [12, 22]
     - [12, 22] dizisini böleriz:
       - [12] ve [22]

3. **Birleştirme Aşaması**:
   - Önceki adımda oluşturulan küçük dizileri birleştirerek sıralarız:
     - [21] ve [11] dizilerini birleştiririz: [11, 21]
     - [16] ve [11, 21] dizilerini birleştiririz: [11, 16, 21]
   - [8] ve [12] dizilerini birleştiririz: [8, 12]
   - [8, 12] ve [22] dizilerini birleştiririz: [8, 12, 22]
   - Son olarak, [11, 16, 21] ve [8, 12, 22] dizilerini birleştiririz: [8, 11, 12, 16, 21, 22]

## Big-O Notasyonu

- **Best Case**: O(n log n)
- **Average Case**: O(n log n)
- **Worst Case**: O(n log n)
