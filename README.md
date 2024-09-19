# Machine-Learning-with-Bank-Churn-Prediction-Dataset-Supervised-and-Unsupervised-Models
#kaggle link
https://www.kaggle.com/code/ahmetfurkankaya/first-machine-learning-project
# Proje Amacı
Bu proje, bir bankanın müşterilerinin terk edip etmeyeceğini tahmin etmek ve müşteri davranışlarını segmentlere ayırmak amacıyla hazırlanmıştır. Gözetimli 
öğrenme ile müşteri terkini tahmin etmeye, gözetimsiz öğrenme ile ise müşterileri ortak özelliklerine göre kümelere ayırmaya çalıştık. Veri seti, müşteri özelliklerini, 
davranışlarını ve finansal metrikleri içermektedir.
# Veri Seti Açıklaması
-Veri seti, 10.000 müşteri gözleminden oluşmakta ve aşağıdaki özellikleri içermektedir:

-CreditScore: Müşterinin kredi değerliliğini sayısal olarak temsil eden bir değişken.

-Geography: Müşterinin yaşadığı ülke (Fransa, Almanya, İspanya) için one-hot encoding yöntemiyle kodlanmıştır.

-Gender: Müşterinin cinsiyeti (Erkek, Kadın) için one-hot encoding kullanılmıştır.

-Age: Müşterinin yaşı.

-Tenure: Müşterinin bankada kaç yıl kaldığını gösterir.

-Balance: Müşterinin hesap bakiyesi.

-NumOfProducts: Müşterinin bankadan kullandığı ürün sayısı.

-HasCrCard: Müşterinin kredi kartı olup olmadığını gösterir (0 veya 1).

-IsActiveMember: Müşterinin aktif üye olup olmadığını gösterir (0 veya 1).

-EstimatedSalary: Müşterinin tahmini yıllık geliri.

# Hedef Değişken

Exited: Müşterinin bankadan ayrılıp ayrılmadığını gösteren ikili değişken. "1" müşterinin ayrıldığını, "0" ise bankada kaldığını ifade eder.

# Gözetimli Öğrenme (Supervised Learning)
Proje kapsamında müşteri terkini tahmin etmek için çeşitli sınıflandırma ve regresyon algoritmaları kullanılmıştır. 

Sınıflandırma modelleri şunlardır:

-Random Forest Classification (Random Forest Sınıflandırması): RandomForestClassifier()

-Logistic Regression (Lojistik Regresyon): LogisticRegression()

-KNN Classification (K-En Yakın Komşu Sınıflandırması): KNeighborsClassifier()

-Decision Tree Classification (Karar Ağaçları Sınıflandırması): DecisionTreeClassifier()

-AdaBoost Classification (AdaBoost Sınıflandırması): AdaBoostClassifier()

Regresyon Modelleri

Müşteri terkini tahmin etmek için kullanılan regresyon modelleri:

-Linear Regression (Doğrusal Regresyon): LinearRegression()

-Ridge Regression (Ridge Regresyon): Ridge()

-Lasso Regression (Lasso Regresyon): Lasso()

-Elastic Net Regression (Elastic Net Regresyon): ElasticNet()

-Decision Tree Regression (Karar Ağaçları Regresyonu): DecisionTreeRegressor()

-KNN Regression (K-En Yakın Komşu Regresyonu): KNeighborsRegressor()

-XGBoost Regression (XGBoost Regresyonu): XGBRegressor()


# Gözetimsiz Öğrenme (Unsupervised Learning)
Müşteri segmentasyonu için aşağıdaki gözetimsiz öğrenme algoritmaları kullanılmıştır:

-KMeans Kümeleme

-Principal Component Analysis (PCA): Veri boyutunu düşürmek ve daha anlamlı bileşenler elde etmek için kullanılmıştır.

# Gözetimsiz Model Sonuçları
Müşteriler belirli özelliklerine göre kümelere ayrılmıştır. Bu segmentasyon, bankanın hangi müşteri gruplarının daha fazla risk taşıdığı veya hangi grupların daha yüksek potansiyele sahip olduğunu anlamalarına yardımcı olabilir.

# Değerlendirme Metrikleri
Model performansını değerlendirmek için aşağıdaki metrikler kullanılmıştır:

-Accuracy (Doğruluk Oranı)

-Precision (Kesinlik)

-Recall (Duyarlılık)

-F1 Score

-R-squared (R²)

-Cross Validation

-Silhouette Score
# Sonuç
Bu proje, gözetimli öğrenme yöntemleriyle müşteri terkini tahmin etmek ve gözetimsiz öğrenme ile müşterileri gruplara ayırarak daha iyi bir müşteri yönetimi stratejisi geliştirmeyi amaçlamaktadır. Müşteri kaybını önleyebilecek stratejik kararlar alabilmek için kapsamlı veri analizi yapılmıştır.


