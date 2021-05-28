```python
# PROJE 1
    # Bir listeyi düzleştiren (flatten) fonksiyon yazın. 
    #Elemanları birden çok katmanlı listtlerden ([[3],2] gibi) oluşabileceği gibi, non-scalar verilerden de oluşabilir.

```


```python
List = [l for l in range (50,100,5)]
print (List)
```

    [50, 55, 60, 65, 70, 75, 80, 85, 90, 95]



```python
# PROJE 2
    #Verilen listenin içindeki elemanları tersine döndüren bir fonksiyon yazın. 
    #Eğer listenin içindeki elemanlar da liste içeriyorsa onların elemanlarını da tersine döndürün. 
```


```python
List2 = [[40,50],[80,70],[3,5,7]]
List2 [::-1]
```




    [[3, 5, 7], [80, 70], [40, 50]]


