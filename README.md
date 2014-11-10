php.ini
=======

Disable_functions
Php.ini with server at Maximum security

Php.ini server'da php ile yazılan dosyaların temel aldığı php fonksiyon listesidir. Apache sunucularda maksimum güvenlik derecesinde bir php elde etmek için kullanabileceğiniz bu php.ini disable_fonksiyon listesindeki fonksiyonlar servera atılan shell gibi zararlı yazılımların bir nebze engellesede tamamen güvenlik derecesine ulaştıramaz bu nednle sadece buradan aldığınız devredışı bıraktığınız fonksiyonlarla kimseye kafa tutup benim sunucum geçilmez demeyin :)

Dikkat !! Bu disabled_fonctions yani devredışı bırakılan fonksiyon listesindeki bazı fonksiyonlar yine bazı scriptlerin çalışmasında sorun yaşatabilir malum burada devredışı bırakılan fonksiyonları kullanan bir scriptiniz varsa çalışmayacaktır.

Bu nedenle Hosting sağlayıcısı iseniz bu fonksiyonları müşterilerinizin bulunduğu server için uygulamamanız iyi olacaktır malum ki hangi müşteri hangi scripti kullanır bilemezsiniz :)
