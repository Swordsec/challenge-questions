# gRPC & redis

## Görev
Size verilen json dosyalarındaki ( users dizininde bulabilirsiniz ) user bilgilerini gRPC kullanarak, sunucuya taşınması gerekli. Sunucuda kuyruklama ( redis queue ) kullanılarak, tek bir json dosyasına kaydetmeniz istenmektedir.

## Beklenen
gRPC server, gRPC sunucu, redis ve dosyaya yazacak olan (python) kod için ayrı ayrı docker container ile çalışılması gerekli.

## Bilgi 
Docker-compose ile çalışmanız önemli. 

## Sonuç
Bu görev için hazırladığınız projeyi tek repoda Github, Bitbucket veya Gitlab üzerinde yayınlayıp bize info (at} swordsec noktacom adresimiz üzerinden ulaştırabilirsiniz.
Projenizi indirdikten sonra çalıştırabilmemiz için gerekli adımları açıklamanız önemli. İngilizce veya Türkçe Readme dosyası ile paylaşabilirsiniz.

## Bonus
Son json dosyasına yazacak olan kodun hızlı bir şekilde kuyruğu eritebilmesi için birden fazla consumer&docker ( iş yapan python kod ) çalışması tercih sebebimizdir.
Flask ya da native python 3x kullanabilirsiniz.
