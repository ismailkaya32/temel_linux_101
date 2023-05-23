 # **Komutlara giriş:**

   Linux terminali, kabul (Shell) ile etkileşime geçmek için kullandığımız bir grafik arabirimidir. Yani kabuk (Shell) kullanarak komut ve programları çalıştırırız. Terminal ekranı da bu çalışan komutların çıktılarını görmemizi sağlar. 


- `ismail@kaya:~$`     --->  Yandaki terminal komutunda  **ismail** adlı kullanıcı **kaya** isimli makinede oturum açmış anlamına gelmektedir.

- ---

- `ismail@kaya:~$whoami`  --->  **ismail** adlı kullanıcının **kaya** isimli makinede oturum açtığını terminale yazdırır.

     ![whoami](https://github.com/ismailkaya32/linux_komutlari_101/assets/122615472/14047737-3a12-4691-8b8a-6b9c1278fb2c)

- ---

-  `ismail@kaya:~$unema-a`  ---> Sistem özelliklerini ayrıntılı bir şekilde terminale yazdırır. 




- ---

-  `ismail@kaya:~$date`  ---> Şuanki tarih ve zamanı görüntüler.



    ![date](https://github.com/ismailkaya32/linux_komutlari_101/assets/122615472/275e0b13-ec88-4f8e-a719-c3eabbe45537)

- ---

- ` ismail@kaya:~$ls ` ---> Bir dizinin içindeki dosya ve klasörleri listelemek için kullanırız. Aşağıdaki örnekte Desktop'ta bulunan dosya ve klasörlei listeledik.


     ![ls](https://github.com/ismailkaya32/linux_komutlari_101/assets/122615472/601b69a1-eb28-4dbe-81e4-8b743a634dc6)


- ---

-  `ismail@kaya:~$ls-a`  ---> Şuanki dizinde bulunan gizli dosyalar dahil tüm dosyaları listeler. 




- ---

- ` ismail@kaya:~$ls-l`     ---> Dosyaları dizin içerisinde listeler.




---


- ` ismail@kaya:~$history ` ---> Geçmişte yaptığımız işlemleri gösterir.


    ![history](https://github.com/ismailkaya32/linux_komutlari_101/assets/122615472/5d3a953a-fed6-405a-8fea-0df1b2a7d155)


---

-  `ismail@kaya:~$history-c `---> Geçmişi silmek için kullanırız .




---

-`ismail@kaya:~$touch  DosyaIsmi `---> Dosya oluşturmaya yarıyor. Aşağıdaki örnekte Desktop'a ismail adında bir dosya oluşturduk.


   ![touch](https://github.com/ismailkaya32/linux_komutlari_101/assets/122615472/b2f803dc-0080-442e-b564-b1d0236562f0)

---

-`ismail@kaya:~$cd  GidecegimizDizin `---> Herhangi bir dizinin içine gidebilmek için kullanırız. Aşağıdaki örnekte **Desktop** dizininden **deneme** dizinine geçtik.

   ![cd](https://github.com/ismailkaya32/linux_komutlari_101/assets/122615472/e2eb220b-5030-4f71-8bd2-f8acb07906ab)


---

- `ismail@kaya:~$cd  .. `---> Bulunduğumuz dizinden bir önceki dizine dönemmeiz sağlar. Aşağıdaki örnekte **deneme** dizininden **Desktop** dizinine geri dönüyoruz.


   ![cd geri gelme](https://github.com/ismailkaya32/linux_komutlari_101/assets/122615472/ed450445-8f87-4de5-a7e7-94fbc7249dbd)

---

- `ismail@kaya:~$mkdir DizininIsmi `---> Klasör oluşturmaya yarıyor. Aşağıdaki örnekte Desktop'a  kaya adında bir klasör oluşturduk.


   ![mkdir](https://github.com/ismailkaya32/linux_komutlari_101/assets/122615472/4c5aeea3-556f-40a8-baf5-324db2a3bade)

---

- `ismail@kaya:~$cp DosyaIsmi TasinacakYer`---> Dosyayı veya klasörü bir dizinden başka bir dizine kopyalamayı sağlar. Aşağıdaki örnekte ismail adlı dosyayı Desktop dizininden deneme dizinine kopyaladık.

   ![cp](https://github.com/ismailkaya32/linux_komutlari_101/assets/122615472/ed8ce2fa-4f6b-4d42-a7f0-d5536f4a8b66)


---

- `ismail@kaya:~$mv TasiyacagimizDosyaninIsmi/ TasinacakYer/`---> Dosyayı veya klasörü bir dizinden başka bir dizine taşımayı sağlar. Aşağıdaki örnekte ismail adlı dosyayı Desktop dizininden deneme dizinine taşıdık.

   ![mv](https://github.com/ismailkaya32/linux_komutlari_101/assets/122615472/89a476b7-4189-43c2-8d37-a223511b0ead)


---

- `ismail@kaya:~$mv eski_dosya_adi yeni_dosya_adi `---> Bir dosyanın ya da klasörün ismi değiştirmeye yarıyor. Aşağıdaki örnekte ismail adlı dosyanın ismimi kaya adına çevirdik.

   ![mv isim](https://github.com/ismailkaya32/linux_komutlari_101/assets/122615472/30940e6f-9af2-4c07-8825-3ec2dbc5f2c4)


---

- `ismail@kaya:~$rm DosyaAdi `---> Dosya silmeye yarıyor. Aşağıdaki örnekte kaya adlı dosyayı sildik.


   ![rm](https://github.com/ismailkaya32/linux_komutlari_101/assets/122615472/72bfd8a1-268b-4a02-8cd7-2c4e96b3d2e9)

---

 - `ismail@kaya:~$rmdir KlasörAdi `---> Klasör silmeye yarıyor. Aşağıdaki örnekte kaya adlı dizinini sildik.


   ![rmdir](https://github.com/ismailkaya32/linux_komutlari_101/assets/122615472/4a21b3b0-7504-415d-baaf-db4bf64e392c)

---

- `ismail@kaya:~$rm -r `---> İçi dolu olan klasörü ne olursa olsun silmeye yarıyor.




---

- `ismail@kaya:~$nano DosyaAdi `---> Yandaki komut ile içindeki bilgileri düzeltemediğimiz dosyanın içindeki bilgileri düzeltmeye yarar.


    ![nano](https://github.com/ismailkaya32/linux_komutlari_101/assets/122615472/c0594593-5e77-4495-884a-5e8b4d464f45)

---

 - `ismail@kaya:~$cat>DosyaAdi `---> Yandaki komut ile dosyanın içine yazı yazabiliriz.

![cat](https://github.com/ismailkaya32/linux_komutlari_101/assets/122615472/234a8ccf-61c2-4089-b010-659805a1cf16)


--- 

- `ismail@kaya:~$pwd`---> İçinde bulunduğumuz dizini bize gösterir.



---

- `ismail@kaya:~$file DosyaAdi `---> Dosyanın ne tür bir dosya olduğunu öğrenebiliriz.



---

- `ismail@kaya:~$wc DosyaAdi `---> Ddosya hakkında bilgi alırız.(Satır sayısı, kelime sayısı, dosyanın bayt türünden dosya boyutu)



---

- `ismail@kaya:~$wc -w DosyaAdi`---> Dosyanın içinde kaç kelime olduğunu öğreniriz.



---

- `ismail@kaya:~$wc -l DosyaAdi`---> Dosyanın içinde kaç satırdan oluştuğunu öğreniriz.



---

- `ismail@kaya:~$wc -c DosyaAdi`---> Dosyanın kaç byte olduğunu öğreniriz.



---

- `ismail@kaya:~$wc -L DosyaAdi`---> Dosyanın içindeki en uzun satırın kaç harften oluştuğunu öğreniriz.



---

- `ismail@kaya:~$wc -w DosyaAdi`---> Dosyanın içinde kaç kelime olduğunu öğreniriz.


---


-  `ismail@kaya:~$man KullanmayiÖgrenmekIstedigimizKomut`---> Kılavuzu bulunan komut ve programların kılavuzlarını okur.



---

-  `ismail@kaya:~$head DosyaAdi`---> Bir dosyanın ilk 10 satırını yazdırır.



-

-  `ismail@kaya:~$wc -w DosyaAdi`---> Dosyanın içinde kaç kelime olduğunu öğreniriz.



---

-  `ismail@kaya:~$tail DosyaAdi`---> Dosyanın son 10 satırını yazdırır.



---

-  `ismail@kaya:~$wc -w DosyaAdi`---> Dosyanın içinde kaç kelime olduğunu öğreniriz.


---

-  `ismail@kaya:~$more DosyaAdi`---> Terminal ekranına sığmayan metinleri okumayı kolaylaştırır.



---

-  `ismail@kaya:~$nl DosyaAdi`---> Boş olan satırlar hariç diğer satırlara satır numarası ekler.



---

-  `ismail@kaya:~$sort DosyaAdi`---> Dosyanın içinde yazan yazıları sırası ile yazdırır.



---

-  `ismail@kaya:~$sort -R DosyaAdi`---> Dosyanın içindeki bilgileri karışık olarak sıralar.



---

-  `ismail@kaya:~$sort -r DosyaAdi`---> Dosyanın içindeki bilgileri tersten sıralar.



---

-  `ismail@kaya:~$sort -c DosyaAdi`---> Yandaki komut ile dosyanın sıralı olup olmadığını bize söyler.



---

- `ismail@kaya:~$sort -k DosyaAdi`---> Yandaki komut dosyaları belirttiğimiz sütundan sıralamamızı sağlar.
-  `ismail@kaya:~$sort -k SayiDegeri DosyaAdi`---> Yandaki komut dosyanın verdiğimiz sayının sütununda bulunan satıra göre sırayla listeler.
-  `ismail@kaya:~$sort -k SayiDegeri DosyaAdi`--->  Yandaki komut dosyanın verdiğimiz sayının sütununda bulunan satıra göre tersten sıralamayla listeler.
