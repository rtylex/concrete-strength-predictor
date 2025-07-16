# concrete-strength-predictor

🧱 Concrete Strength Prediction with Gradient Boosting
Bu proje, beton karışım bileşenlerine göre betonun basınç dayanımını tahmin etmeyi amaçlamaktadır. Modelleme sürecinde Gradient Boosting Regressor algoritması kullanılmıştır.

🔍 Proje Özeti
Veri seti, çimento, cüruf, uçucu kül, su, süper akışkanlaştırıcı, iri ve ince agrega miktarlarını ve yaş bilgisini içerir.

Hedef değişken, Strength (basınç dayanımı) olup regresyon problemi olarak ele alınmıştır.

Model hiperparametreleri GridSearchCV ile optimize edilmiştir.

Model başarımı, R² skoru üzerinden değerlendirilmiştir.

📈 Performans
Train R²: 0.9926

Test R²: 0.9475

Bu değerler, modelin eğitim verisine yüksek uyum sağladığını ve aynı zamanda test verisinde de genellenebilir sonuçlar ürettiğini göstermektedir.

🧠 Overfitting Analizi
Eğitim ve test skorları karşılaştırılarak modelin aşırı öğrenme (overfitting) eğilimi analiz edilmiştir.

Skorlar arasındaki farkın düşük olması, modelin overfit olmadığını ve genelleme kabiliyetinin yüksek olduğunu göstermektedir.

Ek olarak, öğrenme süreci boyunca train-test ayrımı, cross-validation, ve hata metrikleri dikkate alınmıştır.

⚙️ Kullanılan Teknolojiler
Python, Pandas, NumPy

Scikit-learn

Matplotlib, Seaborn

Jupyter Notebook
