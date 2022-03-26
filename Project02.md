www.patika.dev

### 1.soru: [16,21,11,8,12,22] -> Merge Sort

* Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
* Big-O gösterimini yazınız.


### Cevap:
* [16,21,11]  [8,12,22]
  
  [16] [21,11] [8] [12,22]
  
  [16] [21] [11] [8] [12] [22]
  
  [16,21] [8,11] [12,22]
  
  [8,11,16,21] [12,22]
  
  [8,11,12,16,21,22]
  
* O(nlogn)
