# Proje-3 Binary Search Tree

## [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] --> Binary-Search Tree

## 1- Yukarıdaki dizinin Binary Search Tree'ye göre aşamalarını yazınız.

### **Aşamalar**

1- 7'yi baz alarak ilk aşamamızı başlatıyoruz.

```
           7
```

2- 7'yi yan elemanı 5 ile karşılaştırarak büyüklük küçük durumuna sağ veya sol tarafına yazıyoruz. Bu karşılaştırma işlemi her aşama için aynı olacaktır. Aşamalarımıza karşılaştırmalar yaparak devam ediyoruz. 7>**5**'ten büyük bu yüzden 5'i 7'nin sol tarafına ekliyoruz.

```
         7
        /
       5
```

3- 5>**1** 5 1 5'ten küçük olduğu için 1'i 5'in soluna ekliyoruz.

```
         7
        /
       5
      /
     1
```

4- **8**>7>5>1 Bu sefer karşılaştırma işlemimimiz 1'e göre değil ağacımızın en baş elemanı olan 7'ye göre yapıyoruz. Bunun sebebi 8 7'den de 5'ten de 1'den de büyük. Bunun sonucunda 8 7'nin sağ tarafına ekliyoruz.

```
         7
        / \
       5   8
      /
     1
```

5- 5>**3**>1 3 1'den büyük 5'ten küçük olduğu için 1'in sağına ekliyoruz.

```
         7
        / \
       5   8
      /
     1
      \
       3
```

5- **6**>3>1>5 6 3'ten büyük 1'den küçük 5'ten de büyük olduğu için 5'in sağına ekliyoruz.

```
         7
        / \
       5   8
      / \
     1   6
      \
       3
```

6- **0** sayısı bu dizinin en küçük aynı zamanda 1'den de küçük olduğu için 1'in sol tarafına ekliyoruz.

```
          7
         / \
        5   8
       / \
      1   6
     / \
    0   3

```

7- **9**>8>7>6>5>1>0 9 bu durumda 8'den büyük olduğu için 8'in sağına ekliyoruz.

```
         7
        / \
       5   8
      / \   \
     1   6   9
    / \
   0   3

```

8- **4**>3 4 3'ten büyük olduğu için 3'ün sağına ekliyoruz.

```
         7
        / \
       5   8
      / \   \
     1   6   9
    / \
   0   3
        \
         4

```

9- **2**>3 2 3'ten küçük olduğu için 3'ün soluna eklenir.

```
         7
        / \
       5   8
      / \   \
     1   6   9
    / \
   0   3
      / \
     2   4
Sonuç olarak rootumuz 7'dir solunda 5 sağında ise 8 bulunur.
```

## Patika

[Patika.Dev](www.patika.dev)  
[Patika.Dev Hesabım](https://app.patika.dev/mizrakberk)  
Patika.Dev Ekibine katkıları için teşekkür ederim.
