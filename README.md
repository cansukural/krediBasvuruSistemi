# # krediBasvuruSistemi
## Projenin Amacı:
Bu projenin amacı, kişinin kredi isteğine ve kredi skorunun yeterliliğine göre red ya da onay vermektir.<br/>

**PROJEYİ ZIP HALİNE TIKLAYARAK SAĞDA BULUNAN 'DOWNLOAD' BUTONUNDAN İNDİREBİLİRSİNİZ YA DA GIT'TEN CLONE ALARAK BİLGİSAYARINIZA CLONE'LAYABİLİRSİNİZ.**<br/>

Bu projede; kullanıcıdan isim, soyisim, TC Kimlik bilgileri, telefon ve istenilen kredi bilgileri alınarak 
kişiye ilgili kredi notuna göre kredi limiti çıkartılır.<br/>
Eğer kişinin kredi notu 500'den aşağıdaysa, kredi isteği onaylanmaz ve kişi red cevabını alır.<br/>
Eğer kişinin kredi notu 500 ve 1000 arasında ve geliri 5000'den aşağıdaysa, <br/>
kişinin kredi isteği onaylanır ve kişiye 1000 TRY kredi limiti tanımlanır.
Eğer kişinin kredi notu 1000 den yukarıdaysa, <br/>
kişinin kredi isteği onaylanır ve kişiye gelirinin kredi risk çarpanı katı kadar (4 katı) kredi limiti tanımlanır.<br/>
<br/>
 Proje Apache NetBeans 11.1 IDE'sinde yazılmıştır. <br/>

Proje geliştirilirken Java kullanılmış olup, önyüzde JSF'den yararlanılmıştır.
 XHTML uzantılı dosyaların içerisinde JSF kodları bulunmaktadır.
 
 
 
 ### GEREKSİNİMLER
 Java JDK 8 ve üzeri olmalıdır.<br/>
 Proje GlassFish Server'ında olduğu için; <br/>
 1-C:\Users\XXX\SERVERS adlı bir dosya açılıp içine glassfish-5.1.0.zip dosyası SERVER dosyasına (zip halinden extract edilip) konulmalıdır.(istenilen yerden indirilebilir.)<br/>
 2-Aynı dosyaya javaee-api-8.0.1.jar adlı jar dosyası direkt (jar şeklinde) konulmalıdır.<br/>
 #### Gerekli dosyanın adresi: https://www.oracle.com/java/technologies/java-ee-sdk-download.html <br/>
 3-Aynı dosyaya ogs-3.1.2.2-web.zip adlı zip dosyası direkt (zip şeklinde)konulmalıdır.(istenilen yerden indirilebilir.)<br/>
 4-IDE'de açıldığında javaee-api-8.0.1 jar adı dosyanın yolu gösterilmelidir. <br/>
### *NOT: 1.MADDEDE XXX İLE YAZILAN YOL SİZİN KENDİ KULLANDIĞINIZ USER'INIZ OLMALIDIR.(C:\Users\XXX\SERVERS)* <br/>
### *NOT: Bu projede kredi skoru servisi kullanılmamıştır. Kredi skoru servisi yerine servis afaki olarak varmış gibi gelirin 5 te 1' i alınmıştır.*
 

