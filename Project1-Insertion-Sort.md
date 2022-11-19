# Proje-1 Insertion Sort

## [22,27,16,2,18,6] -> Insertion Sort

## 1. Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

```
Insertion Algoritmaları karşılaştırma şeklinde çalışmaktadır.Bu örneğimizde küçükten büyüğe şeklinde sıralayacağız. Bunu yaparken de algoritma şu şekilde çalışıyor. 22 27 küçük mü o zaman yerinde kal 27 16'dan küçük mü değil o zaman yer değiştirin. 16 sola 27'sağ gelsin böyle böyle listemiz küçükten büyüğe sıralanacak.
```

### **Sıralanış Şekli**

[22,**27**,**16**,2,18,6]  
[**22**,**16**,27,2,18,6]  
[16,22,**27**,**2**,18,6]  
[16,**22**,**2**,27,18,6]  
[**16**,**2**,22,27,18,6]  
[2,16,22,**27**,**18**,6]  
[2,16,**22**,**18**,27,6]  
[2,16,18,22,**27**,**6**]  
[2,16,18,**22**,**6**,27]  
[2,16,**18**,**6**,22,27]  
[2,**16**,**6**,18,22,27]  
**[2,6,16,18,22,27]**

## 2. Big-O gösterimi

```
Best Case:O(n)
Average Case: n+(n-1)+(n-2)+(n-3)+...+1=O(n^2)
Worst Case: n+(n-1)+(n-2)+(n-3)+...+1=O(n^2)
```

## 3. Time Complexity

```
Average Case: [2,6,16,18,22,27] sıralama işlemini yaptıktan sonra 18 sayısı bize verilen tanımlamaya göre orta kısıma  denk geldiği için Average Case olarak belirliyoruz. Tanımlamalar aşşağıda yer almaktadır.
```

<ol>
 <li>Average case: Aradığımız sayının ortada olması</li>
 <li>Worst case: Aradığımız sayının sonda olması</li>
 <li>Best case: Aradığımız sayının dizinin en başında olması</li>
</ol>

## 3. Selection Sort

```
[7,3,5,8,2,9,4,15,6] dizisini selection sorta göre ilk 4 adımını yazınız.
```

### **Adımlar**

Liste: [**7**,3,5,8,2,9,4,15,**6**]  
1.Adım [2,3,**5**,8,7,9,**4**,15,6]  
2.Adım [2,3,4,**8**,7,9,**5**,15,6]  
3.Adım [2,3,4,5,**7**,9,8,15,**6**]  
4.Adım [2,3,4,5,6,**9**,8,15,**7**]

## Patika

[Patika.Dev](www.patika.dev)  
[Patika.Dev Hesabım](https://app.patika.dev/mizrakberk)  
Patika.Dev Ekibine katkıları için teşekkür ederim.
