# toprock
setup
CISCO PROJE

Cihazları koy.

Access pointe sifre ver
Ona baglancak pc lere ag karti koy WPC300N sonra inte bagla
Telefon ise wireless 0dan

Sonra cihazlara ip ver
Ilk servere ver 

Sonra serverda servislerde mail ata
Domain gir set et
Sonra kullanıcı ata
Sonra pc ye gir desktop maile gir

Http server atama -> servis, http on, index edit, renk degistir basligi değiştir, welcome i degistir. Save yes

Dns server yapma -> servis, dns on, name www, address http server, add
Sonra bilgisayarlara dns server ip si ver

Dhcp server -> servis, dhcp on, dns server ip gir, sonra ip baslangic gir, save
Sonra serverlara ip ve dns ata

Simdi routerla baglama
1941 router
Her bina icin bir tane
Sonra router i switche gigabit portundan bagla
HWIC2T yi router a koy
Sonra serial dce kablosu ile routelari birbirine bagla
Kablo no larini yaz

Router a tikla, config, gigabit0 on , router a ip ata x.x.x.10 yao akilda kalici olsun

Sonra bilgisayarlara kendi switch ine bagli routerin ip sini ver

Dhcp ise servis dhcp gateway değiştir

Sonra kabloya ip ata 10.0.0.1 gibi
Sonra router in serial daki yere ip ata

Simdi dinamic routing yapcaz

Router a bas, RIP, 10.0.0.0
Sonra binanin ip sini gir
SIRAYLA GIR
