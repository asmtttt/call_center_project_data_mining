Merhaba iyi çalışmalar.

projenin çalışması için .ipynb dosyasının çalışması yeterlidir.

repo içerisinde paylaşılan veri kümesinin 
kendi drive hesabınıza eklenmesi yeterli olacaktır.

aşağıda belirtilen adımlarda olduğu gibi bir drive hesabına göre yazılmıştır.

çalışması için MyDrive içerisinde CallCenterAnalysis klasörü açılarak CallCenter.csv dosyası eklenmelidir.

Ben sizin için bu klasörüde repo içerisinde paylaşıyorum.

Kullanım örneği aşağıdaki gibi olacaktır.

from google.colab import drive
drive.mount('/content/drive')

dataset = pd.read_csv('/content/drive/MyDrive/CallCenterAnalysis/CallCenter.csv')







Olası çalıştırılamama durumu için colab projesini paylaşıyorum.

https://colab.research.google.com/drive/1BbjentKv8beRwFuaX-O5LOXGL7G4rdKv?usp=sharing

bu bağlantıda düzenleme yetkisine sahipsiniz.

