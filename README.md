# path
## Örnek Butonlar

## Rozet Stili Butonlar

## Yapılacaklar Listesi
### SIGN UP
- [ ] Kayit olma asamasinda SSTI dene ve mailine gelen kisimda isleme girmis mi bak <%= 7 * 7 %> %{8 * 8}
- [ ] Mail kisminda json verisi olarak mumkunse cift mail gir ikisinede gelecek mi?
- [ ] Mail kisminda ;sleep+10; denemesi yap Command injection |whoami -- ||nslookup+x.BURP-COLLABORATOR-SUBDOMAIN||


### LOGIN
- [ ] Login kisminda mail icin ping denemsi : @mail ||ping+-c+10+127.0.0.1||
- [ ] Login icin mail kismina cift mail ekleme json verisi olarak
- [ ] Mailin Host kismini abc123 gonder bakalim gelen baglantida abcd123 subdomaini yer aliyor mu? olursa exploit serverini gir host olarak
- [ ] Login kismindaki session cookileri kontrol et decode edip icerigine bak ve serialize zafiyeti varmi?
- [ ] Jwt Tokenleri kontrol et ve zafiyet var mi arastir
- [ ] Login kismina XOR time based testi yap

### EDIT  PROFILE
- [ ] Profil fotografi yukleme kisminda File Upload  zafiyetlerini dene - cmd=ls shell.php - exiftool - lfi shell.php - .htaccess
- [ ] Mail dogrulama isterse tekrar json olarak cift mail denemesi yapabilirsin.


### HOME

- [ ] Web Cache Poisoning - MISS HIT - X-Forwarded-Host: ngrok.com X-Host: ngrok.com X-Forwarded-Server: ngrok.com 
