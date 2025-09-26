Chest X-ray Pneumonia Detection with Deep Learning

Projenin Amacı
Bu projenin amacı, göğüs röntgeni (Chest X-ray) görüntülerini kullanarak zatürre (pneumonia) hastalığını derin öğrenme yöntemleriyle tespit etmektir.
Model, normal ve zatürre sınıflarını ayırt ederek hekimlere karar desteği sağlamayı hedefler.

Veri Seti Hakkında Bilgi
Veri seti: Chest X-Ray Images (Pneumonia)
Kaynak: https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia
İçerik:
Train: Normal ve Pneumonia görüntüleri
Validation: Normal ve Pneumonia görüntüleri
Test: Normal ve Pneumonia görüntüleri

Kullanılan Yöntemler
Convolutional Neural Networks (CNN) tabanlı model geliştirilmiştir.
ImageDataGenerator ile veri artırma (data augmentation) uygulanmıştır.
Aşırı öğrenmeyi önlemek için:
Dropout katmanları
EarlyStopping
Batch Normalization
Optimizasyon: Adam optimizer
Kaybı ölçmek için: Binary Crossentropy
Aktivasyon fonksiyonları: ReLU ve Sigmoid

Elde Edilen Sonuçlar
Eğitim ve doğrulama seti üzerinde belirli bir doğruluk (accuracy) elde edilmiştir.
Precision, Recall, F1-Score metrikleri hesaplanmıştır.
Grad-CAM yöntemiyle modelin hangi bölgelerde odaklandığı görselleştirilmiştir.

Kaggle proje linki : https://www.kaggle.com/code/zeynepsyler/chestxraydataset-deeplearning-zynpsylr

