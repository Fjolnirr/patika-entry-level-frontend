# Proje 2
## Questions

[16,21,11,8,12,22] -> Merge Sort

1. Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
2. Big-O gösterimini yazınız.


## Answers     

[16,21,11,8,12,22]

----------LEFT NODE -------------------------------------------------------------------- RIGHT NODE   
----------[16,21,11] ------------------------------------------------------------------------ [8,12,22]     
--------LEFT NODE --- RIGHT NODE ======================= LEFT NODE --- RIGHT NODE      
-----------[16] ------------ [21,11] =========================== [8,12] ------------ [22]        
-----------[16] ---------- [21] --- [11] ========================= [8] --- [12] ------------ [22]      
-----------[16] ------------ [11,21] =========================== [8,12] ------------ [22]      
-----------[11,16,21] ========================================== [8,12,22]     

>>>>>> [8,11,12,16,21,22]      


O(log**n**)    
