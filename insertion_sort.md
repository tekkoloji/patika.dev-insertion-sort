# Insertion Sort

## [22,27,16,2,18,6] -> Insertion Sort

### **1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.**

[22,27,16,2,18,6]  
[22,16,27,2,18,6]  
[16,22,27,2,18,6]  
[16,22,2,27,18,6]  
[16,2,22,27,18,6]  
[2,16,22,27,18,6]  
[2,16,22,18,27,6]  
[2,16,18,22,27,6]  
[2,16,18,22,6,27]  
[2,16,18,6,22,27]  
[2,16,6,18,22,27]  
[2,6,16,18,22,27]  
___

### **2. Big-O gösterimi**

O($n^2$)
___

### **3. Time Complexity**

*Worst case:* **$n^2$**  
*Average case:* **$n^2$**  
*Best case:* **$n$**  
___

#### **4. Dizi sıralandıktan sonra 18 sayısı hangi case kapsamına girer? Yazınız.**

Cevap : **Average case**
***

#### **5. [7,3,5,8,2,9,4,15,6] dizisinin Insertion Sort'a göre ilk 4 adımını yazınız.**

[7,3,5,8,2,9,4,15,6]  
[3,7,5,8,2,9,4,15,6]  
[3,5,7,8,2,9,4,15,6]  
[3,5,7,2,8,9,4,15,6]  