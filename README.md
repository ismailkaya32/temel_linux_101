 # **Komutlara giriş:**

   Linux terminali, kabul (Shell) ile etkileşime geçmek için kullandığımız bir grafik arabirimidir. Yani kabuk (Shell) kullanarak komut ve programları çalıştırırız. Terminal ekranı da bu çalışan komutların çıktılarını görmemizi sağlar. 


- `ismail@kaya:~$`     --->  Yandaki terminal komutunda  **ismail** adlı kullanıcı **kaya** isimli makinede oturum açmış anlamına gelmektedir.

- ---

- `ismail@kaya:~$whoami`  --->  **ismail** adlı kullanıcının **kaya** isimli makinede oturum açtığını terminale yazdırır.

<div align="center">
	<img  src="https://github.com/ismailkaya32/linux_komutlari_101/assets/122615472/14047737-3a12-4691-8b8a-6b9c1278fb2c"/>
<div>
   	

- ---

-  `ismail@kaya:~$unema-a`  ---> Sistem özelliklerini ayrıntılı bir şekilde terminale yazdırır. 




- ---

-  `ismail@kaya:~$date`  ---> Şuanki tarih ve zamanı görüntüler.

<div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlari_101/assets/122615472/275e0b13-ec88-4f8e-a719-c3eabbe45537"/>
<div>
   



- ---

- ` ismail@kaya:~$ls ` ---> Bir dizinin içindeki dosya ve klasörleri listelemek için kullanırız. Aşağıdaki örnekte Desktop'ta bulunan dosya ve klasörlei listeledik.
 
<div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlari_101/assets/122615472/601b69a1-eb28-4dbe-81e4-8b743a634dc6"/>
<div>




- ---

-  `ismail@kaya:~$ls-a`  ---> Şuanki dizinde bulunan gizli dosyalar dahil tüm dosyaları listeler. 




- ---

- ` ismail@kaya:~$ls-l`     ---> Dosyaları dizin içerisinde listeler.




---


- ` ismail@kaya:~$history ` ---> Geçmişte yaptığımız işlemleri gösterir.

<div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlari_101/assets/122615472/5d3a953a-fed6-405a-8fea-0df1b2a7d155"/>
<div>
   


---

-  `ismail@kaya:~$history-c `---> Geçmişi silmek için kullanırız .




---

-`ismail@kaya:~$touch  DosyaIsmi `---> Dosya oluşturmaya yarıyor. Aşağıdaki örnekte Desktop'a ismail adında bir dosya oluşturduk.

<div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlari_101/assets/122615472/b2f803dc-0080-442e-b564-b1d0236562f0"/>
<div>
 

---

-`ismail@kaya:~$cd  GidecegimizDizin `---> Herhangi bir dizinin içine gidebilmek için kullanırız. Aşağıdaki örnekte **Desktop** dizininden **deneme** dizinine geçtik.

 <div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlari_101/assets/122615472/e2eb220b-5030-4f71-8bd2-f8acb07906ab"/>
<div>
 


---

- `ismail@kaya:~$cd  .. `---> Bulunduğumuz dizinden bir önceki dizine dönemmeiz sağlar. Aşağıdaki örnekte **deneme** dizininden **Desktop** dizinine geri dönüyoruz.

<div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlari_101/assets/122615472/ed450445-8f87-4de5-a7e7-94fbc7249dbd"/>
<div>


---

- `ismail@kaya:~$mkdir DizininIsmi `---> Klasör oluşturmaya yarıyor. Aşağıdaki örnekte Desktop'a  kaya adında bir klasör oluşturduk.

<div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlari_101/assets/122615472/4c5aeea3-556f-40a8-baf5-324db2a3bade7"/>
<div>
  
---

- `ismail@kaya:~$cp DosyaIsmi TasinacakYer`---> Dosyayı veya klasörü bir dizinden başka bir dizine kopyalamayı sağlar. Aşağıdaki örnekte ismail adlı dosyayı Desktop dizininden deneme dizinine kopyaladık.

 <div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlari_101/assets/122615472/ed8ce2fa-4f6b-4d42-a7f0-d5536f4a8b66"/>
<div>
 


---

- `ismail@kaya:~$mv TasiyacagimizDosyaninIsmi/ TasinacakYer/`---> Dosyayı veya klasörü bir dizinden başka bir dizine taşımayı sağlar. Aşağıdaki örnekte ismail adlı dosyayı Desktop dizininden deneme dizinine taşıdık.

 <div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlari_101/assets/122615472/89a476b7-4189-43c2-8d37-a223511b0ead"/>
<div>
  


---

- `ismail@kaya:~$mv eski_dosya_adi yeni_dosya_adi `---> Bir dosyanın ya da klasörün ismi değiştirmeye yarıyor. Aşağıdaki örnekte ismail adlı dosyanın ismimi kaya adına çevirdik.
<div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlari_101/assets/122615472/30940e6f-9af2-4c07-8825-3ec2dbc5f2c4"/>
<div>



---

- `ismail@kaya:~$rm DosyaAdi `---> Dosya silmeye yarıyor. Aşağıdaki örnekte kaya adlı dosyayı sildik.

 <div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlari_101/assets/122615472/72bfd8a1-268b-4a02-8cd7-2c4e96b3d2e9"/>
<div>



---

 - `ismail@kaya:~$rmdir KlasörAdi `---> Klasör silmeye yarıyor. Aşağıdaki örnekte kaya adlı dizinini sildik.

<div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlari_101/assets/122615472/4a21b3b0-7504-415d-baaf-db4bf64e392c"/>
<div>
  

---

- `ismail@kaya:~$rm -r `---> İçi dolu olan klasörü ne olursa olsun silmeye yarıyor.




---

- `ismail@kaya:~$nano DosyaAdi `---> Yandaki komut ile içindeki bilgileri düzeltemediğimiz dosyanın içindeki bilgileri düzeltmeye yarar.

 <div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlari_101/assets/122615472/c0594593-5e77-4495-884a-5e8b4d464f45"/>
<div>


---

 - `ismail@kaya:~$cat>DosyaAdi `---> Yandaki komut ile dosyanın içine yazı yazabiliriz.

 <div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlari_101/assets/122615472/234a8ccf-61c2-4089-b010-659805a1cf16"/>
<div>



--- 

- `ismail@kaya:~$pwd`---> İçinde bulunduğumuz dizini bize gösterir.
	
<div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlari_101/assets/122615472/5e96b340-e0f8-48e5-bc96-e799d4fb3af0"/>

<div>



---

- `ismail@kaya:~$file DosyaAdi `---> Dosyanın ne tür bir dosya olduğunu öğrenebiliriz.
	
<div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlari_101/assets/122615472/0b39830e-81e3-434e-a9b9-db245f7dfbe1"/>

<div>



---

- `ismail@kaya:~$wc DosyaAdi `---> Ddosya hakkında bilgi alırız.(Satır sayısı, kelime sayısı, dosyanın bayt türünden dosya boyutu)

<div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlari_101/assets/122615472/a4672a1c-997e-4d1b-aa99-bf341316788b"/>
<div>



---

- `ismail@kaya:~$wc -w DosyaAdi`---> Dosyanın içinde kaç kelime olduğunu öğreniriz.

<div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlari_101/assets/122615472/c18687a3-0e5a-46b9-8fb6-fa6a5fab7b9f"/>

<div>


---

- `ismail@kaya:~$wc -l DosyaAdi`---> Dosyanın içinde kaç satırdan oluştuğunu öğreniriz.
	
<div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlari_101/assets/122615472/de2768cb-297c-4a07-b6cf-aeeb5c92f106"/>

<div>



---

- `ismail@kaya:~$wc -c DosyaAdi`---> Dosyanın kaç byte olduğunu öğreniriz.
	
<div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlari_101/assets/122615472/d48d70a1-fa2b-4cca-896a-4eb51bd68ab1"/>

<div>



---

- `ismail@kaya:~$wc -L DosyaAdi`---> Dosyanın içindeki en uzun satırın kaç harften oluştuğunu öğreniriz.
	
<div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlari_101/assets/122615472/9d3d8332-4826-4f5e-9efe-250f2378170f"/>

<div>



---

-  `ismail@kaya:~$man KullanmayiÖgrenmekIstedigimizKomut`---> Kılavuzu bulunan komut ve programların kılavuzlarını okur.

	
---

-  `ismail@kaya:~$head DosyaAdi`---> Bir dosyanın ilk 10 satırını yazdırır.

 <div align="center">
	<img src="(https://github.com/ismailkaya32/linux_komutlari_101/assets/122615472/c62036e7-e552-4e80-96b0-3d452aee072a"/>

<div>

---

-  `ismail@kaya:~$tail DosyaAdi`---> Dosyanın son 10 satırını yazdırır.

<div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlari_101/assets/122615472/442b8446-a815-40b2-97dc-32a47bccec8e"/>
<div>
	

---

-  `ismail@kaya:~$more DosyaAdi`---> Terminal ekranına sığmayan metinleri okumayı kolaylaştırır.

<div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlari_101/assets/122615472/393b69f7-43a3-43b7-9c31-da01bda56a69"/>

<div>

---

-  `ismail@kaya:~$nl DosyaAdi`---> Boş olan satırlar hariç diğer satırlara satır numarası ekler.

<div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlari_101/assets/122615472/61f77e5f-6949-47e1-8d0b-e66b32207041"/>

<div>

---

-  `ismail@kaya:~$sort DosyaAdi`---> Dosyanın içinde yazan yazıları sırası ile yazdırır.

<div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlari_101/assets/122615472/806a33d8-3780-4761-8099-5b9614a3def3"/>

<div>

---

-  `ismail@kaya:~$sort -R DosyaAdi`---> Dosyanın içindeki bilgileri karışık olarak sıralar.

<div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlari_101/assets/122615472/40124014-3785-40d2-8d0b-c308c4b2405a"/>

<div>

---

-  `ismail@kaya:~$sort -r DosyaAdi`---> Dosyanın içindeki bilgileri tersten sıralar.


---

-  `ismail@kaya:~$sort -c DosyaAdi`---> Yandaki komut ile dosyanın sıralı olup olmadığını bize söyler.

<div align="center">
	<img src="https://github.com/ismailkaya32/linux_komutlari_101/assets/122615472/00321265-645b-4d37-bb84-89d1bc86369d"/>
<div>


---

- `ismail@kaya:~$sort -k DosyaAdi`---> Yandaki komut dosyaları belirttiğimiz sütundan sıralamamızı sağlar.
-  `ismail@kaya:~$sort -k SayiDegeri DosyaAdi`---> Yandaki komut dosyanın verdiğimiz sayının sütununda bulunan satıra göre sırayla listeler.
-  `ismail@kaya:~$sort -k SayiDegeri DosyaAdi`--->  Yandaki komut dosyanın verdiğimiz sayının sütununda bulunan satıra göre tersten sıralamayla listeler.
