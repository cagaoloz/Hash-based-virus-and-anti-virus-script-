# Hash-based-virus-and-anti-virus-script-
Hash-based virus and anti-virus script 

Bir adet virüs oluşturucu ve bir adet de virüs tespit edici uygulamalar bash scripting ile
yazılacak. Scriptler eğitimde kurulan Ubuntu Linux VM üzerinde çalıştırılacaktır.
 Virüs tespiti hash değeri ile yapılacak.
 İlk uygulama manuel tetikleme ile /tmp/script1 dizini altında 1&#39;den 500000&#39;e kadar .exe
uzantılı dosya oluşturacak ve dosyanın adını, uzantısı olmadan dosyanın içine yazacak.
Örneğin 500.exe adındaki dosyanın içeriği 500 olacak.
 İkinci uygulama ise MD5 hashi &quot;d6ea69a5401ef7e5e953c0edaa16cd50&quot; olan dosyanın adını
tespit edip bu dosyanın adını /var/log/av.log dosyasının içine aşağıdaki formatta yazacak:
&quot;Tespit zamanı, Tespit edilen hostname, Tespit eden kullanıcı adı, Dosya hash değeri, Dosya
yoluyla birlikte dosya adı&quot;