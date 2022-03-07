# kuyruklama

## Görev
Size verilen json dosyalarındaki ( users dizininde bulabilirsiniz ) user bilgilerini Http ile Json kullanarak, sunucuya taşınması gerekli. Sunucuda kuyruklama ( redis queue ) kullanılarak, postgresql veritabanına kaydetmeniz istenmektedir.

## Beklenen
Flask (http isteğini karşılayıp, kuyruğa gönderecek) sunucu, postgresql, redis ve kuyruktaki işleri postgresql e kaydedecek (python) kod için ayrı ayrı docker container ile çalışılması gerekli. Toplam 4 docker ayakta olmalı. 

## Bilgi 
docker-compose ile çalışmanız gerekmektedir.

## Sonuç
Bu görev için hazırladığınız projeyi tek repoda Github, Bitbucket veya Gitlab üzerinde yayınlayıp bize info (at} swordsec noktacom adresimiz üzerinden ulaştırabilirsiniz.
Projenizi indirdikten sonra çalıştırabilmemiz için gerekli adımları açıklamanız önemli. İngilizce veya Türkçe Readme dosyası ile paylaşabilirsiniz.

## Bonus
Son json dosyasına yazacak olan kodun hızlı bir şekilde kuyruğu eritebilmesi için birden fazla consumer&docker ( iş yapan python kod ) çalışması tercih sebebimizdir.
