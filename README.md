# NLP-Spellchecker-Machine-Learning

Phyton used with the help of neural network library tensorflow (keras) and its sublibraries for
optimizers.<br />
Test sentences are the same with the HW3.<br />
# Texts to test!
tests = ["cin seddi sinirina yaklastilar",<br />
 "baskentinin istedigi buydu",<br />
 "guneye dogru ilerlediler",<br />
 "uc tane asker cin'in hakimiydi",<br />
 "suslu manciniklari ogretti",<br />
 "yapabilecek durumda degildi",<br />
 "muhafiz kitasi oldu",<br />
 "surlara dogru surdu",<br />
 "oldugu tartisma konusudur",<br />
 "celaleddin'in pesine dustu",<br />
 "ayrildigi haberini aldi",<br />
 "hanedaninin tavrini unutmamisti",<br />
 "ele gecirmek konu oldu",<br />
 "oncu birlik dayanmisti",<br />
 "ilk kez gerceklesmisti",<br />
 "cengiz han da ona katildi",<br />
 "sehri ele gecirdi",<br />
 "yapabilecek durumda degildi",<br />
 "saldiri tuzagı kurmustu",<br />
 "duvarlari onune yıgdı",<br />
 ]

Result format :
I uploaded both .ipynb and .py versions of it to this file. You can check both.<br />

# Model training
Used “Adam” optimizer with 0.05 value.
![Ekran görüntüsü_20230102_163010](https://user-images.githubusercontent.com/61903795/210237990-87e697ef-143f-4f29-96af-6f8b85f18655.png)

# Results
unchanged = cin seddi sinirina yaklastilar<br />
predicted = çın şeddı şınırına yaklaştılar<br />
---<br />
unchanged = baskentinin istedigi buydu<br />
predicted = başkentının ıştedığı büydü<br />
---<br />
unchanged = guneye dogru ilerlediler<br />
predicted = ğüneye döğrü ılerledıler<br />
---<br />
unchanged = uc tane asker cin'in hakimiydi<br />
predicted = üç tane aşker çın'ın hakımıydı<br />
---<br />
unchanged = suslu manciniklari ogretti<br />
predicted = şüşlü mançınıkları öğrettı<br />
---<br />
unchanged = yapabilecek durumda degildi<br />
predicted = yapabıleçek dürümda değıldı<br />
---<br />
unchanged = muhafiz kitasi oldu<br />
predicted = mühafız kıtaşı öldü<br />
---<br />
unchanged = surlara dogru surdu<br />
predicted = şürlara döğrü şürdü<br />
---<br />
unchanged = oldugu tartisma konusudur<br />
predicted = öldüğü tartışma könüşüdür<br />
---<br />
unchanged = celaleddin'in pesine dustu<br />
predicted = çelaleddın'ın peşıne düştü<br />
---<br />
unchanged = ayrildigi haberini aldi<br />
predicted = ayrıldığı haberını aldı<br />
---<br />
unchanged = hanedaninin tavrini unutmamisti<br />
predicted = hanedanının tavrını ünütmamıştı<br />
---<br />
unchanged = ele gecirmek konu oldu<br />
predicted = ele ğeçırmek könü öldü<br />
---<br />
unchanged = oncu birlik dayanmisti<br />
predicted = önçü bırlık dayanmıştı<br />
---<br />
unchanged = ilk kez gerceklesmisti<br />
predicted = ılk kez ğerçekleşmıştı<br />
---<br />
unchanged = cengiz han da ona katildi<br />
predicted = çenğız han da öna katıldı<br />
---<br />
unchanged = sehri ele gecirdi<br />
predicted = şehrı ele ğeçırdı<br />
---<br />
unchanged = yapabilecek durumda degildi<br />
predicted = yapabıleçek dürümda değıldı<br />
---<br />
unchanged = saldiri tuzagı kurmustu<br />
predicted = şaldırı tüzağı kürmüştü<br />

İlkan Mert Okul


