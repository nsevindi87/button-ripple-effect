# button-ripple-effect
When the cursor is over the button, an effect will be applied on the button.

HEDEF: Imlecin buton üzerine gelmesiyle baloncuk efekti olusturulmasi hedeflenmektedir.
ÖGRENME HEDEFI: Baloncugun baslama noktasi imlecin buton üzerine ilk girdigi nokta olmasi.

SUREC
1- a ve span elementleri kullanilarak bir buton olusturulur.
2- css ile görsel düzenlemeler yapilir.
3- Buton elementine baglanti saglanir. 
   - addeventLidtener ile eylem atama. 
   - eylem farenin üzerinden gecmesi ile baslar.
   - farenin butonun neresine geldiginin bulunmasi icin X ve Y noktalari tespit edilir.
   - Bunun icin de Butonun X ve Y boylamlarinda sayfanin nerede durdugu pageX ve pageY ile tespit edilir. 
   - Buton üzerinde olusacak baloncuk ::before veya ::after ile olusturulu. 
   - Olusturulan baloncugun merkezinin tespit edilen X ve Y noktalarinda baslayabilmesi icin CSS tarafinda Top ve Left bir degisken olarak tanimlanir.
   - Baloncugun merkezinin belirlenmesi ise; daha önce butonun durdugu noktadan - butonun Top ve Left kisimlar cikarili.
   - Böylece left:0 veya top:0 bulunur. 
   - Bulunan degerler de CSSdeki degiskenlerin yerine atanir. Bu noktada setPropery kullanilir.

KABACA: Imlecin kabarcik cikarmasini istedigin noktayi matematik islemleriyle bul ve kabarcigin hover ile baslamasini istedigin Css özelligine ata.

Z-index özelligi her zaman position özellikleri ile birlikte kullanilir.!



setProperty
style
e.pageX
e.pageY
btn.offsetLeft
btn.offsetTop
