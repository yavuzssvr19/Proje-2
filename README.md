# Patika.dev Veri Yapıları ve Algoritmalar Kursu

   # Merge Sort Projesi:
   
   [16, 21, 11, 8, 12, 22] dizisinin Merge Sort'a göre adımları;

* İlk olarak diziyi tek elemanlar kalana kadar parçalayacğız ve her adımda ortadan böleceğiz:

    1.[16, 21, 11] -------- [8, 12, 22]
    
    2.[16, 21]--- [11] __________ [8, 12]----[22]
    
    3.[16]---[21]---[11]__________[8]----[12]----[22]
    
 *İkinci olarak ayırdığımız dizi elemanlarında en küçükleri kendi aralrında sıralayarak tekrar birleştireceğiz:
 
    1.[16] --- [11, 21] --- [8] --- [12, 22]
    
    2.[11, 16, 21] --- [8, 12, 22]
    
    3.[8, 11, 12, 16, 21, 22]
    
*Big O gösterimi;

   O(nlogn)
  
