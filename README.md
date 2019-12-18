# YoutubeYorumSiniflandirma
Amaç: Youtube yorumlarına atılan yorumların pozitif negatif olarak sınıflandırılması.

- YouTube Data API v3 kullanarak CommentThread:list başlığı altından belirli müzik videolarının yorumları çekilip csv dosyasına kayıt edildi.
- Yorumlar ve Etiket sütunları ile olumlu yorumlara “1” olumsuz yorumlara “0” etiketi konuldu.
- NLTK, doğal dil araç takımı anlamına gelir. Natural Language Toolkit; insan dili verileriyle çalışmak için Pyhton programlama dili ile geliştirilmiş ve geliştirilmekte olan 50’nin üzerinde derlem ve sözcük kaynağı ile oluşturulmuş açık kaynaklı bir kütüphanedir. İnsanlar tarafından söylenen cümlelerin parçalara ayrılması anlaşılması ve insanların anlayacağı bir şekilde cevaplanması süreçlerini en iyi şekilde yönetmek.
```
Pip ile kurulum : pip install –user –U nltk
```
- RegexpTokenizer : Yorumun sembollerden arındırılması.
- sent_tokenize : Sembollerden arındırılmış parçalanmış kelimeleri tek bir cümle haline çevirir.
- word_tokenize : Cümleleri kelime kelime ayırır.
- stop_words : Gramerce anlamı olup fakat konuşma dilinde anlamı olmayan kelimelri ayıklar.
- Lemmatize : Kelimelerin köklerine göre ayırır.

## KULLANILAN YÖNTEM : LOJİSTİK REGRESYON

- Bağımlı değişkenin kesikli olduğu durumlarda bir sonucu belirlemek için kullanılan istatistik yöntemidir.
- İkili (Binary) 1 veya 0 olarak etiketlenmiş veriler için kullanılır.</br>
Kaynak : [NLP and Machine Learning Techniques for Detecting Insulting Comments on Social Networking Platforms](https://ieeexplore.ieee.org/document/8441728).





Projeyi hazırlayanlar :
1. Büşra Abay
2. Furkan Güneştaş
3. Hilal Yıldırım
