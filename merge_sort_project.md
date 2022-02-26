# Proje 2

## [16,21,11,8,12,22] -> Merge Sort

### 1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.  
[16,21,11]&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;[8,12,22]  
[16] &nbsp; &nbsp;[21,11] &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; 
[8,12] &nbsp; &nbsp; [22]  
[16] &nbsp; &nbsp; [21] &nbsp;[11] &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;&nbsp; [8] &nbsp;[12] &nbsp; &nbsp; [22]  
[16]&nbsp; &nbsp; [11,21] &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; [8,12] &nbsp; &nbsp; [22]  
[11,16,21] &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; [8,12,22]  
&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; [8,11,12,16,21,22]

### 2. Big-O gösterimini yazınız.  
O (nlogn)