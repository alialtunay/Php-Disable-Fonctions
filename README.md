Php Disabled functions olarak anlatacağım kısım, Sunucudaki php’nin güvenlik amacı ile devredışı bırakılan fonksiyon listesidir.

Bu listedeki fonksiyonlar genel olarak güvenlik açığı oluşturma riski olduğu için bu fonksiyonların sunucuda kullanılması sunucu güvenliğini riske edeceği için bu fonksiyonları devre dışı bırakmak (Güvenli sunucu isteyenler için gereklidir.)

Tabi bu fonksiyonların devre dışı bırakılması; bu fonksiyonları kullanan tema eklenti, script, vs ne varsa bunların artık çalışmamasına neden olacaktır bunu önlemek için buradaki listede birçok fonksiyonu devre dışı bırakmadan önce kendi sunucunuzda var olup olmadığını kontrol etmenizi öneririm.

Aynı şekilde bu fonksiyonlar güvenlik amacı ile devre dışı bırakılsada sunucuda varsayılan php olarak php.ini kullanmaya zorlamamışsanız bunun hiçbir önemi yoktur. bir saldırgan php.ini içinde disable fonksiyon olarak kendi betiğindeki fonksiyonun çalışmadığını gördüğü anda kendisi yeni bir php.ini oluşturarak betiğine uygun fonksiyonları dahil ederbilir. bu yüzden bu sistemin sağlıklı çalışması için önelikle sunucuda varsayılan php.ini kullanmaya zorlamak gerekir.

Ardından bu php disable fonksiyon listesini eklediğinizde istediğiniz güvenliği elde edersiniz, Ancak bu demek olmuyor ki sunucunuz artık kapalı kutu 🙁 malesef öyle bir durum yok buradaki fonksiyonlar ile sunucuya maksimum güvenlik çekemezsiniz.

Read more / Devamını oku  =>https://alicomez.com/php-disable_functions.slw
