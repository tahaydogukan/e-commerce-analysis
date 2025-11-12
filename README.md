E-Ticaret Analizi

Bu proje, bir e-ticaret firmasının müşteri verilerini analiz ederek yıllık harcama miktarını tahmin etmeyi amaçlar.

## Proje Amacı

Müşterilerin uygulamada ve web sitesinde geçirdikleri zaman, oturum uzunluğu ve üyelik süresi gibi değişkenlerin, yıllık harcama tutarı üzerindeki etkisini incelemek ve gelecekteki harcamaları tahmin edebilen bir model geliştirmektir.

## Kullanılan Teknolojiler

* Python 3
* Pandas
* Matplotlib & Seaborn
* Scikit-learn
* LinearRegression 

## Model Süreci

1. Veri Keşfi (EDA)
   
3. Model Eğitimi:
   * Bağımsız değişkenler: Avg. Session Length, Time on App, Time on Website, Length of Membership
   * Bağımlı değişken: Yearly Amount Spent
   * Veriler %80 eğitim, %20 test olarak ayrıldı.
     
4. Model Performansı:
   MAE: 7.20
   MSE: 84.25
   RMSE: 9.17
