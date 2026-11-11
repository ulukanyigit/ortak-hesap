# Ortak Hesap

İki kişinin ortak harcamalarını tutan küçük bir web uygulaması.

- Her kişi aldığını anında girer: siteden ya da iPhone kestirmesinden.
- Ay sonunda kimin kime ne kadar göndereceğini hesaplar. Önceki aylardan devreden farkı da sonuca katar.
- Taksitli alımlar için ödeme planı çıkarır: hangi ay ne kadar ödeneceği ve son taksitin ayı.

## Nasıl çalışır

Bu depo yalnızca arayüzü (`index.html`) içerir ve GitHub Pages'te yayınlanır. Kayıtlar burada tutulmaz.

Kayıtlar kullanıcının kendi Google E-Tablosu'nda durur. Tablonun içine eklenen küçük bir Apps Script, site ile kestirmeye kapı görevi görür ve her isteği gizli bir anahtarla doğrular.

Bir cihaz ilk kez bağlanırken script adresini ve anahtarı alır; bunu bir kez girilen bilgilerle ya da bağlantı linkiyle yapar. Bu bilgiler yalnızca o cihazın tarayıcısında saklanır.
