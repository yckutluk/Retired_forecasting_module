# Retired_forecasting_module


Bu proje, emeklilik planlaması üzerine bir simülasyon yapmayı amaçlayan bir analiz çalışmasıdır. İlk adımda, kullanıcıdan başlangıç maaşı, terfi sıklığı, yaşam maliyeti artışı, terfi zam oranı, biriktirme oranı ve faiz oranı gibi girdi verileri alınır.

Sonra, bu girdi verileri kullanılarak Monte Carlo simülasyonu yöntemiyle emeklilik yılı tahmin edilir. Simülasyon, girdi verilerinin rastgele örneklemlemesiyle birden fazla senaryo oluşturur ve her bir senaryoda emeklilik için geçecek yıl sayısını hesaplar.

Simülasyon sonuçları bir DataFrame olarak kaydedilir ve isteğe bağlı olarak stilize edilerek daha okunabilir hale getirilir. Ayrıca, girdi verilerinin emeklilik yılı üzerindeki etkisini analiz etmek için saçılım (scatter) grafikleri oluşturulur.

Son olarak, regresyon analizi kullanılarak girdi verilerinin emeklilik yılı üzerindeki etkisi istatistiksel olarak değerlendirilir. Bu analiz, her bir girdi değişkeninin emeklilik yılı üzerindeki katsayılarını ve istatistiksel anlamlılığını sağlar.

Proje, emeklilik planlamasında farklı senaryoların incelenmesine ve girdi verilerinin emeklilik yılı üzerindeki etkisini anlamaya yönelik bir araç sunar. Kullanıcılar, farklı parametrelerle oynayarak emeklilik planlarını optimize etmek için veriye dayalı kararlar alabilirler.





