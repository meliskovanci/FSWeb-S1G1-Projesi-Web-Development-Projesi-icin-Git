## Araştırma Soruları

Şimdi görevi gerçekleştirmek için hazırsınız. Şimdi biraz daha kullandığımız araçları anlama zamanı. Bu dokümanı güncelleyerek, aşağıdaki soruları cevaplayınız. Git'e biraz daha aşina olmaya başladığınızı göreceksiniz. 

Soruları cevaplamak için [GitHub docs](https://docs.github.com/en)'u kullanabilirsiniz. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçer.

Eğer aradığınız soruların cevapları GitHub docs'ta yok ise Google'lama becerileriniz size yardımcı olacaktır :)

1. Git nedir?
Git, yazılım geliştirme süreçlerinde kullanılan bir versiyon kontrol sistemidir.

2. Git ile GitHub arasında ne fark var?
Git bir versiyon kontrol sistemidir. GitHub ise bu versiyon kontrol sistemi ile kullandığımız projeleri depolayabildiğimiz bir portaldır.

3. Neden bir branch oluşturuyoruz? 
Branch oluşturmak kullanıcıya çalıştığı projenin farklı versiyonlarına erişmesini sağlar. Kullanıcı, projesine bir yenilik eklemek istediğinde, yaptığı değişiklik projenin çalışmasını olumsuz etkileyebilir. Bu gibi durumlarda projemizin o anki halini bozmamak için branch kullanabiliriz.

4. Pull Request'in amacı nedir?
Pull request talebi, temelde branch'dan sorumlu kişiden kodunuzu eklemesini istemektir. Ayrıca o kişinin kodda tam olarak neyi değiştirdiğinizi görmesine de yardımcı olur.
5. Bir Branchten diğerine geçmek için kullanıdığımız KOMUT nedir? Örneğin ADINIZ-SOYADINIZ branch'inde çalıştığınızı hayal edin ve main branch'ine geçmek istiyorsunuz.
git checkout

6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.

Git fetch, başka bir sunucunun projesindeki her türlü içeriği veya veriyi yerel sisteminize indirmek için kullanılan bir komuttur.
Git merge işlemi başka bir branch'deki değişiklikleri üzerinde çalıştığınız kendi branch'inize entegre etme işlemidir. Git merge işlemi sırasında değişikliklerin çoğunu sizin için otomatik olarak entegre eder.
Git pull komutu, git fetch ve git merge komutlarının amacına tek bir komutta hizmet eden bir komuttur. Pulls teriminin kendisi, bu komutu kullanan kullanıcının depodan veri veya içerik çekmeye çalıştığını açıklar. Git pull, kullanıcıdan izin istemeden veya belirtmeden git fetch işlevini yerine getirir ve kullanıcıya haber vermeden değişiklikleri birleştirir, yalnızca sonuç, yani bu komutun işleminin başarılı olup olmadığı ve uyarılar vb. kullanıcı tarafından bilinir.

7. Merge conflict nedir?
İki kişi aynı dosyayı ve aynı satırı değiştirirse ve git otomatik olarak merge edemezse bu durumda conflict yani çakışma olacaktır.

8. Merge conflict'i nasıl çözeriz?

Çakışma gerçekleşmeden önce bunu önlemenin en iyi yolu, üzerinde çalıştığımız özellik dalını sıklıkla master üzerinden rebase komutuyla güncelleştirmektir.
