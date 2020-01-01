### Linux'da VPN Kullanmadan Yasaklı Sitelere Giriş Rehberi

Bu rehber şu an yapım aşamasındadır. Geliştirmek isteyenler geliştirebilirler.

#### Gerekenler
* [dnscrypt-proxy](https://github.com/DNSCrypt/dnscrypt-proxy)
* [green-tunnel](https://github.com/SadeghHayeri/GreenTunnel/releases)
* Smart HTTPS ([Mozilla Firefox](https://addons.mozilla.org/en-US/firefox/addon/smart-https-revived/) ve [Google Chrome](https://chrome.google.com/webstore/detail/smart-https/cmleijjdpceldbelpnpkddofmcmcaknm) eklentisidir)

#### Kurulum
* Linux dağıtımınıza göre paket yöneticiniz ile __npm__ ve __dnscrypt-proxy__ paketlerini yükleyin.
Örneğin:
````
$ sudo apt-get install npm
$ sudo apt-get install dnscrypt-proxy
````

* Green Tunnel uygulamasını yeni yüklediğiniz npm paket yöneticisiyle indirin.
````
$ sudo npm i -g green-tunnel
````
* Bu [linkte](https://github.com/DNSCrypt/dnscrypt-proxy/wiki/Installation-linux) verilen dnscrypt-proxy kurulum rehberini Linux dağıtmınıza göre takip edip uygulayın (Kurulumu her Linux dağıtımında farklı yöntemler gerektirdiği için buraya yazmadım.)

* DNSCrypt kurulup ayarlandıktan sonra Green Tunnel uygulamasını çalıştırın
````
$ gt
````
* Eğer bilgisayarı her başlattığınızda Green Tunnel'in de başlamasını istiyorsanız masaüstü ortamınızın Otomatik Başlatılan Uygulamalar bölümüne ekleyin.(Örneğin, XFCE kullanıyorsanız __Ayarlar > Oturum ve Başlangıç > Uygulama Otomatik Başlat__ kısmına ````gt```` komutunu ekleyin)
* 
