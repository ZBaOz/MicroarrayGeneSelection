# MicroarrayGeneSelection
PrBABC: Özellik seçiminde kullanılmak üzere EDA tabanlı binary bir Artificial Bee Colony Algoritmasıdır.
Algoritma 'Run' fonksiyonu ile çalıştırılır.

Performans karşılaştırma yapmak için aynı verisetlerine binPSO, binDE ve GA algoritmaları da uygulanmıştır.
Fitness, train2testbolme ve filter tüm algoritmaların ortak kullandığı fonksiyonlardır.
Farklı olarak binABC için 'yeniKaynakEDA', binPSO için binPSObinaruDonustur, ve binDE için binDEbinaryDonustur fonksiyonları vardır.
Tüm yöntemler 'run' fonksiyonu ile çalıştırılır ancak çalıştırılacak algoritmanın fonksiyonu 'run' fonksiyonu içinde çağrılmalıdır.
