# Akbank-Derin-Ogrenme-Bootcamp-
🚀 Akbank Deep Learning Bootcamp Projesi  
Bu proje, veri ön hazırlığı, Custom CNN ve Transfer Learning (MobileNetV2) modellerini kullanarak bir sınıflandırma probleminde eğitim süreci ve performans analizi yapmayı amaçlamaktadır. Bootcamp kapsamında **eğitimler kısa tutulmuş**, amacımız veri hazırlığı, model oluşturma, eğitim ve transfer learning mantığını öğrenmek olmuştur. LLM modelleri proje planlaması, analiz ve rehberlik süreçlerinde kullanılmıştır.

![Lisans](https://img.shields.io/badge/lisans-MIT-mavi)  
![Versiyon](https://img.shields.io/badge/versiyon-1.0.0-turuncu)  

## 📋 İçindekiler  
- [Kaggle Notbook](#kaggle-notbook)  
- [Kullanım](#kullanım)  
- [Özellikler](#özellikler)  
- [Test Sonuçları](#test-sonuçları)  
- [Grad-CAM Görselleştirme](#grad-cam-görselleştirme)  
- [Lisans](#lisans)  
- [Teşekkür](#teşekkür)  

## 📝 Kaggle Notbook  
Projeyi çalıştırmak ve incelemek için Kaggle notbook:  
[Kaggle Linki](https://www.kaggle.com/code/yusufmertyrek/akbank-derin-renme-bootcamp)

## 🚀 Kullanım  
Notbook Kaggle ortamında hazır dataset ve bağımlılıklarla çalışacak şekilde tasarlanmıştır.  
Linkten açıp çalıştırmanız yeterlidir. Eğitim süresi kısa tutulmuştur (epoch sayısı sınırlı), amaç **öğrenme ve kavrama**dır.

## ✨ Özellikler  
- ✅ **Custom CNN**: Özel CNN modeli ile sınıflandırma.  
- ✅ **Transfer Learning**: MobileNetV2 ile daha hızlı ve etkili eğitim.  
- ✅ **Performans Karşılaştırması**: Custom CNN vs Transfer Learning sonuçları (loss, accuracy, top-3 accuracy).  
- ✅ **Grad-CAM Görselleştirme**: Modelin hangi bölgeleri dikkate aldığını görselleştirme.  
- ✅ **Veri Ön Hazırlığı**: Dataset'in boyutlandırılması, normalizasyonu, tf.data.Dataset kullanımı.  
- ✅ **Eğitim ve Analiz**: Train/validation adım sayıları, class weight kullanımı, learning rate schedule.  
- ✅ **LLM Kullanımı**: Proje planlama, teknik rehberlik ve model yorumlamasında.

## 🧪 Test Sonuçları
**Custom CNN (5 epoch)**:  
- Loss: 3.5645  
- Accuracy: 0.0416  
- Top-3 Accuracy: 0.2089  

**Transfer CNN (MobileNetV2, 5 epoch)**:  
- Loss: 2.7760  
- Accuracy: 0.2259  
- Top-3 Accuracy: 0.5390  

> Transfer Learning modeli, kısa eğitim süresine rağmen Custom CNN’e göre belirgin şekilde daha yüksek performans göstermiştir.

## 🌡️ Grad-CAM Görselleştirme
- Custom CNN ve Transfer CNN modelleri için Grad-CAM kullanılarak modelin odaklandığı bölgeler görselleştirilmiştir.  
- Bu sayede, hangi özelliklerin sınıflandırmaya katkıda bulunduğu anlaşılmıştır.  

## 📄 Lisans  
Bu proje [MIT Lisansı](LICENSE) altında lisanslanmıştır. Dilediğiniz gibi kullanabilirsiniz.

## 🙏 Teşekkür  
Bu projede sağladıkları eğitim ve rehberlik için **Turkish AI Hub ekibine teşekkürler**.
