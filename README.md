# linux_komutlari_101

   Linux terminali, kabul (Shell) ile etkileşime geçmek için kullandığımız bir grafik arabirimidir. Yani kabuk (Shell) kullanarak komut ve programları çalıştırırız. Terminal ekranı da bu çalışan komutların çıktılarını görmemizi sağlar. 

### **Komutlara giriş:**
- `ismail@kaya:~$`     --->  Yandaki terminal komutunda  **ismail** adlı kullanıcı **kaya** isimli makinede oturum açmış anlamına gelmektedir.




- ---

- `ismail@kaya:~$whoami`  ---> Yandaki  komut  **ismail** adlı kullanıcının **kaya** isimli makinede oturum açtığını terminale yazdırır. Örnek çıktı şu şekilde olur:

     ![whoami](https://github.com/ismailkaya32/linux_komutlari_101/assets/122615472/14047737-3a12-4691-8b8a-6b9c1278fb2c)



- ---

-  `ismail@kaya:~$unema-a`  ---> Yandaki  komut sistem özelliklerini ayrıntılı bir şekilde terminale yazdırır. Örnek çıktı şu şekilde olur:




- ---

-  `ismail@kaya:~$date`  ---> Yandaki  komut şuanki tarih ve zamanı görüntüler.. Örnek çıktı şu şekilde olur:




- ---

- ` ismail@kaya:~$ls ` ---> Yandaki  komut bir dizinin içindeki dosya ve klasörleri listelemek için kullanırız.




- ---

-  `ismail@kaya:~$ls-a`  ---> Yandaki  komut şuanki konumda bulunan gizli dosyalar dahil tüm dosyaları listeler. Örnek çıktı şu şekilde olur:




- ---

- ` ismail@kaya:~$ls-l`     ---> Yandaki  komut dosyaları dizin içerisinde listeler. Örnek çıktı şu şekilde olur:




---


- ` ismail@kaya:~$history ` ---> Yandaki  komut geçmişte yaptığımız işlemleri gösterir. Örnek çıktı şu şekilde olur:




---

-  `ismail@kaya:~$history-c `---> Yandaki  komut ile geçmişi sileriz .




---

-`ismail@kaya:~$touch  DosyaIsmi `---> Yandaki komut dosya oluşturmaya yarıyor.



---

-`ismail@kaya:~$cd  GidecegimizKonum `---> Yandaki komutu herhangi bir dizinin içine gidebilmek için kullanırız.



---

- `ismail@kaya:~$cd  .. `---> Yandaki komut bulunduğumuz dizinden bir önceki dizine dönemmeiz sağlar.



---

- `ismail@kaya:~$mkdir DizininIsmi `---> Yandaki komut klasör oluşturmaya yarıyor.



---

- `ismail@kaya:~$cp DosyaIsmi TasinacakYer`---> Yandaki komut dosyayı veya klasörü bir dizinden başka bir dizine kopyalamayı sağlar.



---

- `ismail@kaya:~$mv TasiyacagimizDosyaninIsmi/ TasinacakYer/`---> Yandaki komut dosyayı veya klasörü bir dizinden başka bir dizine taşımayı sağlar.



---

- `ismail@kaya:~$mv eski_dosya_adi yeni_dosya_adi `---> Yandaki komut bir dosyanın ya da klasörün ismi değiştirmeye yarıyor.



---

- `ismail@kaya:~$rm DosyaAdi `---> Yandaki komut dosya silmeye yarıyor.



---

 - `ismail@kaya:~$rmdir KlasörAdi `---> Yandaki komut  klasör silmeye yarıyor.



---

- `ismail@kaya:~$rm -r `---> Yandaki komut içi dolu olan klasörü ne olursa olsun silmeye yarıyor.



---

- `ismail@kaya:~$nano DosyaAdi `---> Yandaki komut ile içindeki bilgileri düzeltemediğimiz dosyanın içindeki bilgileri düzeltmeye yarar.



---

 - `ismail@kaya:~$cat>DosyaAdi `---> Yandaki komut ile dosyanın içine yazı yazabiliriz.



--- 

- `ismail@kaya:~$pwd`---> Yandaki komut ile içinde bulunduğumuz dizini bize gösterir.



---

- `ismail@kaya:~$file DosyaAdi `---> Yandaki komut ile dosyanın ne tür bir dosya olduğunu öğrenebiliriz.



---

- `ismail@kaya:~$wc DosyaAdi `---> Yandaki komut ile dosya hakkında bilgi alırız.(Satır sayısı, kelime sayısı, dosyanın bayt türünden dosya boyutu)



---

- `ismail@kaya:~$wc -w DosyaAdi`---> Yandaki komut ile dosyanın içinde kaç kelime olduğunu öğreniriz.



---

- `ismail@kaya:~$wc -l DosyaAdi`---> Yandaki komut ile dosyanın içinde kaç satırdan oluştuğunu öğreniriz.



---

- `ismail@kaya:~$wc -c DosyaAdi`---> Yandaki komut ile dosyanın kaç byte olduğunu öğreniriz.



---

- `ismail@kaya:~$wc -L DosyaAdi`---> Yandaki komut ile dosyanın içindeki en uzun satırın kaç harften oluştuğunu öğreniriz.



---

- `ismail@kaya:~$wc -w DosyaAdi`---> Yandaki komut ile dosyanın içinde kaç kelime olduğunu öğreniriz.


---


-  `ismail@kaya:~$man KullanmayiÖgrenmekIstedigimizKomut`---> Yandaki komut; kılavuzu bulunan komut ve programların kılavuzlarını okur.



---

-  `ismail@kaya:~$head DosyaAdi`---> Yandaki komut bir dosyanın ilk 10 satırını yazdırır.



-

-  `ismail@kaya:~$wc -w DosyaAdi`---> Yandaki komut ile dosyanın içinde kaç kelime olduğunu öğreniriz.



---

-  `ismail@kaya:~$tail DosyaAdi`---> Yandaki komut ile dosyanın son 10 satırını yazdırır.



---

-  `ismail@kaya:~$wc -w DosyaAdi`---> Yandaki komut ile dosyanın içinde kaç kelime olduğunu öğreniriz.


---

-  `ismail@kaya:~$more DosyaAdi`---> Yandaki komut terminal ekranına sığmayan metinleri okumayı kolaylaştırır.



---

-  `ismail@kaya:~$nl DosyaAdi`---> Yandaki komutu boş olan satırlar hariç diğer satırlara satır numarası ekler.



---

-  `ismail@kaya:~$sort DosyaAdi`---> Yandaki komut ile dosyanın içinde yazan yazıları sırası ile yazdırır.



---

-  `ismail@kaya:~$sort -R DosyaAdi`---> Yandaki komut ile dosyanın içindeki bilgileri karışık olarak sıralar.



---

-  `ismail@kaya:~$sort -r DosyaAdi`---> Yandaki komut ile dosyanın içindeki bilgileri tersten sıralar.



---

-  `ismail@kaya:~$sort -c DosyaAdi`---> Yandaki komut ile dosyanın sıralı olup olmadığını bize söyler.



---

- `ismail@kaya:~$sort -k DosyaAdi`---> Yandaki komut dosyaları belirttiğimiz sütundan sıralamamızı sağlar.
-  `ismail@kaya:~$sort -k SayiDegeri DosyaAdi`---> Yandaki komut dosyanın verdiğimiz sayının sütununda bulunan satıra göre sırayla listeler.
-  `ismail@kaya:~$sort -k SayiDegeri DosyaAdi`--->  Yandaki komut dosyanın verdiğimiz sayının sütununda bulunan satıra göre tersten sıralamayla listeler.
