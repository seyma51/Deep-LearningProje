# Deep-LearningProje
CNN ve EfficientNetB0 ile geliştirilen bu AI modeli, bitki yapraklarını analiz ederek hastalıkları %98.5 doğrulukla tespit eder. PlantVillage veri setinde eğitilmiş olup 38 farklı hastalık sınıfını tanıyabilir. Çiftçiler ve tarım uzmanları için erken teşhis imkanı sunarak tarımsal verimliliği artırmayı hedefler.

# Giriş
Bu proje kapsamında, PlantVillage veri setindeki 54.000'den fazla görüntü üzerinde derin öğrenme teknikleri kullanılarak bitki hastalık tespit modeli geliştirilmiştir. CNN ve EfficientNetB0 Transfer Learning mimarileriyle oluşturulan model, 38 farklı bitki hastalığı sınıfını %98.5 doğruluk oranıyla sınıflandırabilmektedir. TensorFlow/Keras framework'ü kullanılarak geliştirilen sistemde, Adam Optimizer ile optimize edilen modelin eğitim süreci Early Stopping ve Learning Rate Scheduling teknikleriyle desteklenmiştir. Proje kapsamında veri ön işleme, model eğitimi ve performans değerlendirme aşamaları detaylı şekilde incelenerek robust bir çözüm sunulmuştur.

# Metrikler
Model %98.5 accuracy ile çok iyi sonuç verdi. F1-Score 0.984 çıkması, hem yanlış alarmları hem de kaçırdığımız hastalıkları minimize ettiğimizi gösteriyor. Ancak bu sonuçlar laboratuvar verilerinde elde edildi - gerçek tarla koşullarında test etmem gerekecek. Model güvenilir görünüyor ama daha fazla gerçek dünya verisiyle geliştirilmeli. 

# Sonuç ve Gelecek Çalışmalar
Gelecek çalışmamda, Türkiye'nin tarımsal ihtiyaçlarına özel bir veri seti oluşturmayı planlıyorum. Şu an kullandığımız PlantVillage veri seti genel bitki hastalıklarını kapsıyor ancak Türkiye'de yetişen özel ürünler ve bölgesel hastalıklar yeterince temsil edilmiyor. Özellikle Ege'de zeytin, Karadeniz'de fındık, İç Anadolu'da buğday gibi bölgesel ürünlerde görülen hastalıkları içeren bir veri setine ihtiyaç var.

Bu proje kapsamında çiftçilerle işbirliği yaparak gerçek tarla koşullarında fotoğraflar çekeceğim. Tarım Bakanlığı'nın yayınladığı hastalık rehberlerinden faydalanarak etiketleme yapmayı düşünüyorum. Ayrıca mevsimsel değişiklikleri de dikkate alarak, aynı hastalığın farklı gelişim evrelerini kaydetmek istiyorum.

Amacım, Türk çiftçisinin gerçek ihtiyaçlarına yönelik daha doğru teşhisler yapabilen bir model geliştirmek. Bu sayede yerel tarım ekonomisine katkı sağlayabileceğimize inanıyorum. Veri setini oluşturduktan sonra açık kaynak olarak paylaşmayı da planlıyorum ki diğer araştırmacılar da faydalanabilsin.

# Linkler
https://www.kaggle.com/code/seymaonerli/bitkihastaliklarinitanima-ipynb/edit/run/264039474
