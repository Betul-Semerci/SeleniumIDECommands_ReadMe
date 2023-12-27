# Selenium IDE Commands

"Selenium IDE command" ifadesi, Selenium Integrated Development Environment (IDE) adlı bir araçta kullanılan komutları ifade eder. Selenium IDE, web uygulamalarını otomatik olarak test etmek için kullanılan bir test aracıdır ve bu komutlar, test senaryolarını oluşturmak için kullanılır.

Selenium IDE'nin komutları, kullanıcıların bir web tarayıcısında etkileşimli olarak kaydedilen aksiyonları (tıklama, yazma, seçim yapma vb.) otomatikleştirmelerine ve bu etkileşimleri test senaryolarına dönüştürmelerine izin verir. Bu komutlar, testin adımlarını belirtir ve Selenium WebDriver gibi diğer Selenium araçlarına benzer şekilde çalışırlar.

Selenium IDE kullanıcılara kaydedilmiş bir test senaryosunu düzenleme, tekrar etme ve yeniden kullanma olanağı sağlar. Bu şekilde, web uygulamalarındaki değişikliklere karşı test senaryolarını güncel tutmak ve uygulamanın doğru çalıştığından emin olmak mümkün olur.

## Verification Commands(Doğrulama Komutları):

assert: Belirli bir koşulun doğru olduğunu doğrular.

verify: Assert'e benzer, ancak doğrulama başarısız olsa bile test yürütmesine devam eder.

verify title: Sayfa başlığını doğrular.

verify selected label: Seçili bir açılır menü etiketini doğrular.

verify checked: Bir onay kutusunun veya radyo düğmesinin seçili olduğunu doğrular.

verify not checked: Bir onay kutusunun veya radyo düğmesinin seçili olmadığını doğrular.

verify editable: Bir elementin düzenlenebilir olduğunu doğrular.

verify not editable: Bir elementin düzenlenebilir olmadığını doğrular.

verify element present: Bir elementin varlığını doğrular.

verify element not present: Bir elementin var olmadığını doğrular.

verify value: Bir elementin değerini doğrular.

verify selected value: Bir açılır menüde belirli bir değerin seçildiğini doğrular.

verify not selected value: Bir açılır menüde belirli bir değerin seçilmediğini doğrular.

verify text: Bir elementin metnini doğrular.

verify not text: Bir elementin metninin belirli bir değer olmadığını doğrular.

## Assertions(Doğrulamalar):

assert alert: Bir uyarının varlığını doğrular.

assert confirmation: Bir onay iletişim kutusunun varlığını doğrular.

assert prompt: Bir giriş iletişim kutusunun varlığını doğrular.

assert selected label: Bir açılır menüde belirli bir seçeneğin etiketle seçildiğini doğrular.

assert title: Geçerli sayfanın başlığını doğrular.

assert value: Bir elementin değerini doğrular.

assert selected value: Bir açılır menüde belirli bir değerin seçildiğini doğrular.

assert not selected value: Bir açılır menüde belirli bir değerin seçilmediğini doğrular.

assert checked: Bir onay kutusunun veya radyo düğmesinin seçili olduğunu doğrular.

assert not checked: Bir onay kutusunun veya radyo düğmesinin seçili olmadığını doğrular.

assert editable: Bir elementin düzenlenebilir olduğunu doğrular.

assert not editable: Bir elementin düzenlenebilir olmadığını doğrular.

assert element present: Bir elementin varlığını doğrular.

assert element not present: Bir elementin var olmadığını doğrular.

assert text: Bir elementin metnini doğrular.

assert not text: Bir elementin metninin belirli bir değer olmadığını doğrular.


## Action Commands(Eylem Komutları):

click: Bir elemente fare tıklamasını simüle eder.

click at: Belirli bir konumda fare tıklamasını simüle eder.

close: Geçerli pencereyi kapatır.

check: Bir onay kutusunu işaretler.

uncheck: Bir onay kutusunun işaretini kaldırır.

choose ok on next confirmation: Bir sonraki onay iletişim kutusunu kabul eder.

choose cancel on next confirmation: Bir sonraki onay iletişim kutusunu iptal eder.

choose cancel on next prompt: Bir sonraki giriş iletişim kutusunu iptal eder.

double click: Bir elemente çift tıklamayı simüle eder.

double click at: Belirli bir konumda çift tıklamayı simüle eder.

drag and drop to object: Bir elementi sürükler ve başka bir elemente bırakır.

add selection: Bir liste kutusuna seçenek ekler.

answer on next prompt: Bir sonraki giriş iletişim kutusuna cevap verir.

debugger: JavaScript kodunu hata ayıklamak için bir noktaya ara ekler.

do: Belirli bir bloğu belirli bir koşula göre yürütür.

echo: Bir mesajı loga veya konsola yazdırır.

edit content: Bir elementin içeriğini düzenler.

end: Bir döngü veya koşullu ifadenin sonunu belirtir.

execute async script: Asenkron JavaScript kodunu yürütür.

mouse down: Fare düğmesini basılı tutar.

mouse down at: Belirli bir konumda fare düğmesini basılı tutar.

mouse move at: Belirli bir konumda fareyi hareket ettirir.

mouse out: Fareyi bir elementin üzerinden çıkarır.

mouse over: Fareyi bir elementin üzerine getirir.

mouse up: Fare düğmesini bırakır.

mouse up at: Belirli bir konumda fare düğmesini bırakır.

open: Bir URL'yi açar.

remove selection: Bir listeden seçimi kaldırır.

repeat if: Belirli bir koşula göre belirli bir bloğu tekrarlar.

run: Bir test senaryosunu yürütür.

run script: JavaScript kodunu yürütür.

select: Bir listeden seçim yapar.

select frame: Bir frame içine geçer.

select window: Bir pencereyi seçer.

send keys: Tuş kombinasyonları gönderir.

set speed: Komut hızını ayarlar.

set window size: Pencere boyutunu ayarlar.

store attribute: Bir elementin özniteliğini saklar.

store json: JSON verisini saklar.

store text: Bir elementin metnini saklar.

store title: Sayfa başlığını saklar.

store value: Bir elementin değerini saklar.

store window handle: Pencere tanımlayıcısını saklar.

store xpath count: XPath ifadesinin sayısını saklar.

submit: Bir formu gönderir.

type: Bir metin kutusuna metin yazar.

## Wait and Visibility Commands(Bekleme ve Görünürlük Komutları):

wait for text: Belirli bir metni bekler.

wait for element editable: Bir elementin düzenlenebilir olmasını bekler.

wait for element not editable: Bir elementin düzenlenebilir olmamasını bekler.

wait for element present: Bir elementin varlığını bekler.

wait for element not present: Bir elementin var olmamasını bekler.

wait for element visible: Bir elementin görünür olmasını bekler.

wait for element not visible: Bir elementin görünür olmamasını bekler.


## Other Commands(Diğer Komutlar):

pause: Test yürütmesini belirli bir süre için duraklatır.

store: Daha sonra kullanmak üzere bir değeri saklar.

execute script: JavaScript kodunu yürütür.

if, else if, else: Koşullu ifadeler.

for each: Bir element kümesi üzerinde döngü yapar.

while: Belirli bir koşul doğru olduğu sürece bir bloğu yürütür.

times: Belirli bir sayıda kez bir bloğu yürütür.

webdriver answer on visible prompt: Görünür bir giriş iletişim kutusuna cevap verir.

webdriver choose cancel on visible prompt: Görünür bir giriş iletişim kutusunu iptal eder.

webdriver choose ok on visible confirmation: Görünür bir onay iletişim kutusunu kabul eder.

webdriver choose cancel on visible confirmation: : Görünür bir onay iletişim kutusunu iptal eder.


Bu komutlar, Selenium IDE'nin otomasyon test senaryoları oluşturmak için kullandığı komut setinin bir parçasıdır. Her komutun belirli parametreleri ve kullanım yönergeleri vardır.
