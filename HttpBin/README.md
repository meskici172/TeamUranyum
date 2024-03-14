# HTTPBin API TEST

Bu proje <HttpBin> Api Testi
Bu proje Maven ile geliştirilmiştir ve test edilirken `newman` ve `allure` raporları kullanılmaktadır.

## Proje için Gerekli Teknolojiler
Projenin düzgün bir şekilde çalışabilmesi için öncelikle `newman` ve `allure`'ı yüklemeniz gerekmektedir.

1. Newman'ı [buradan](https://github.com/postmanlabs/newman#installation) yükleyin.
2. Allure raporlarını [buradan](https://docs.qameta.io/allure/#_installing_a_commandline) yükleyin.

## Nasıl Çalıştırılır?

Bu projeyi newman ile çalıştırmak için aşağıdaki adımları izleyin:

1. Projeyi bilgisayarınıza klonlayın: https://github.com/meskici172/TeamUranyum.git
2. Klonladığınız dosyayı cmd prompt ile açıp cd "your/path/to" şeklinde yazınız.
3. daha sonrasında " newman run httpbin.json -e HttpBinenvironment.json --reporters cli,json --reporter-json-export report.json " yazınız.

## Nasıl Çalıştırılır 2?
1. Projeyi bilgisayarınıza klonlayın: https://github.com/meskici172/TeamUranyum.git
2. Klonladığınız dosyayı cmd prompt ile açıp cd "your/path/to" şeklinde yazınız.
3. daha sonrasında mvn test yazınız.
