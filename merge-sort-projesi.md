# Merge Sort Projesi
## [16,21,11,8,12,22] -> Merge Sort
## Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
###               [16,21,11,8,12,22]     =>diziyi parçalamaya başlayalım
### 1.Aşama:     [16,21,11] [8,12,22]    =>2 ye böldük ve 3 erli 2 grup oluştu  
### 2.Aşama:   [16,21] [11] [8,12] [22]  =>2 ye böldük ve 2 adet 2 şerli 2 adet tekli grup oluştu  
### 3.Aşama: [16] [21] [11] [8] [12] [22]=>2 li grupları 2 ye böldük ve 6 adet tekli grup oluştu
### 4.Aşama:   [16] [11,21] [8,12] [22]  =>gruplar 2 li gruplara dönüşür ve küçük olan başa alınır
### 5.Aşama:     [11,16,21] [8,12,22]    =>gruplar 3 lü sıralı gruplara dönüşür    
### 6.Aşama:      [8,11,12,16,21,22]     =>gruplar birleşir ve 6 lı sıralı gruba dönüşür     
## Big-O gösterimini yazınız.
### O(nlogn)