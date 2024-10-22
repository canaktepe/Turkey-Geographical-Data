# Turkey-Geographical-Data

Bu repository, Türkiye'nin il, ilçe ve mahalle-köy verilerini içeren üç CSV dosyasını barındırır. Bu veriler, coğrafi analizler yapmak veya yazılım projelerinde Türkiye'nin yerel düzeyde verilerine erişim sağlamak isteyenler için kullanılabilir.

## Kullanım Kılavuzu

1. **Veri Setlerini İndirme**: İlgili CSV dosyalarını bu repository'den indirebilirsiniz.
2. **CSV Dosyalarını Açma**: CSV dosyalarını tercih ettiğiniz bir veri analizi veya programlama aracıyla açabilirsiniz.
3. **Veri Setlerini İnceleme**: CSV dosyalarındaki sütun başlıkları ve içeriklerini inceleyerek istediğiniz analizi yapabilirsiniz.
4. **Veri Analizi ve Proje Geliştirme**: Veri setlerini kullanarak coğrafi analizler yapabilir veya yazılım projelerinizde Türkiye'nin yerel verilerini entegre edebilirsiniz.

## Örnek Kodlar

Python kullanarak veri setlerini yükleme ve temel analiz yapma örnekleri aşağıdaki gibidir:

```python
import pandas as pd

# CSV dosyalarını yükleme
il_data = pd.read_csv("iller.csv")
ilce_data = pd.read_csv("ilceler.csv")
mahalle_koy_data = pd.read_csv("mahalleler_ve_koyler.csv")

# Veri setlerini inceleme
print("İl Veri Seti Örneği:")
print(il_data.head())

print("İlçe Veri Seti Örneği:")
print(ilce_data.head())

print("Mahalle/Köy Veri Seti Örneği:")
print(mahalle_koy_data.head())
