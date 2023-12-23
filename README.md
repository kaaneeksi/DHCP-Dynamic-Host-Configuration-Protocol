# DHCP
DHCP (Dynamic Host Configuration Protocol) ağınızda bulunan bilgisayar, tablet, akıllı telefonlar gibi cihazlarınıza ip adresi, ağ maskesi, ağ geçidi ve DNS adresini otomatik atamak için kullanılan bir protokoldür.

## DHCP Nasıl Çalışır ?

* Bir ağa bağlandığımızda eğer manuel olarak kendimize bir IP adresi atamadıysak, ağda herhangi bir DHCP sunucusunun olup 
* olmadığını görmek için bir istek göndeririz **(DHCP Discover)**.
* Daha sonra DHCP sunucusu bize o ağda olmayan bir IP adresini gönderir.**(DHCP Offer)**. 
* Bizde IP adresini aldığımızı onaylayan bir yanıt göndeririz.**(DHCP Request)** 
* Son olarak DHCP sunucusu bize işlemin tamamlandığını söyleyen bir bilgilendirme yanıtı yollar.**(DHCP ACK)**

> TryHackMe

![DHCP](https://github.com/kaaneeksi/DHCP-Dynamic-Host-Configuration-Protocol/blob/main/G%C3%B6rsel/dhcp.png?raw=true)
