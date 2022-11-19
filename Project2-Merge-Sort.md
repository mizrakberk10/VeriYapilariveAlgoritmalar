# Proje-2 Merge Sort

## [16,21,11,8,12,22] -> Merge Sort

## 1-Yukarıdaki listenin Merge Sort şeklinde sıralayınız.

```
Merge Sort için öncelikle listemizi parçalıyoruz. Daha sonra parçaladığımız liste elemanlarını toparlarken kendi aralarında sıralayıp en son halini çıktı olarak görüyoruz.
```

### **Sıralanış Şekli**

[16,21,11,8,12,22]  
[16,21,11] [8,12,22]  
[16,21] [11] [8] [12,22]  
[16] [21] [11] [8] [12] [22]
[16,21] [8,11] [12,22]  
[8,11,16,21] [12,22]  
**[8,11,12,16,21,22]**

## 2- Big-O Gösterimini yazınız.

### **Big-O**

```
n+n/2+n/4+....+1= 2^x=n
x=log(n)
O(nlogn)
Bizim n adımımız 6 olduğu için
O(6log6)
```

## Patika

[Patika.Dev](www.patika.dev)  
[Patika.Dev Hesabım](https://app.patika.dev/mizrakberk)  
Patika.Dev Ekibine katkıları için teşekkür ederim.
