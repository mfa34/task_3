Iki yazilimin belirli kisitlamalar altinda birbirleriyle iletisim kurmasidir.

Ornek vermek gerekirse bir haber kanalinin son dakika haberinin gecmesi ardindan telefonuza dusen bildirim . Telefonuzun api ile baglanti kurup size bu bildirimi gostermesini ornek verebiliriz .

## Soap API

Bu API'ler, Basit Nesne Erişimi Protokolünü kullanır. İstemci ve sunucu, XML aracılığıyla mesaj alışverişi yapar. Bu, diğerlerine kıyasla pek esnek olmayan ve artık popülerliğini yitiren bir API'dir.

## Rest API

Rest, HTTP protokolünü kullanarak, URL adresleri üzerinden veri ve dosya alışverişi sağlayan bir yapıdır. Rest API ise Rest işlemini yapabilmek için kurgulanmış modüle verilen isimdir. Bu API (Modül) yardımıyla Rest işlemleri ve veri alışverişi yapılıyor.

SOAP yerine neden Rest tercih ediliyor derseniz;

Rest ile veri akışları SOAP’taki XML yerine daha hafif bir yapıdaki JSON formatı yardımıyla gerçekleşir.
SOAP’taki RPC gibi karmaşık bağlantı yapıları yerine HTTP protokolü kullanılır.
SOAP gibi sert standartlara göre daha esnek yapısı vardır.
SOAP gibi Proxy kullanımına zorlanmazsınız.
Kolay entegre edilebilen bir yapıdadır.
Rest ile oluşturulan Server – Client bağlantısı sonucunda veri alışverişi belirli istekler sayesinde gerçekleşir. Rest sırasında kullanılan HTTP istekleri ve işlevleri aşağıdaki gibidir;

GET, veri listelemek ve görüntülemek için kullanılır.
POST, veri eklemek için kullanılan bir istektir.
DELETE, veri silmek için kullanılır.
PATCH, verinin bir kısmının güncellenmesi için kullanılan bir istektir.
