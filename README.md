# Bezpečná práce na počítači
## Upozornění!
Slouží výhradně pro informační účely a má pouze oznámkovatelský charakter. Chceme vás upozornit na důležitost bezpečného používání softwaru.

Používání neoprávněných nebo neověřených programů může mít nepředvídatelné následky. Tyto programy mohou obsahovat malware, spyware nebo jiný škodlivý software, což může ohrozit bezpečnost vašich zařízení a dat.

Doporučujeme používat pouze licencovaný software od důvěryhodných poskytovatelů. Licencovaný software zajišťuje, že obdržíte podporu, aktualizace a záruku bezpečnosti od výrobce. Používání neoprávněných programů může vést k právním důsledkům, včetně možných sankcí.

Dále bychom vás rádi upozornili na soulad s pravidly a směrnicemi školy. Používání neoprávněných programů může být v rozporu se školními pravidly a mít disciplinární následky.

Je důležité, abyste dbali na ochranu vašich dat a zařízení. Pokud máte podezření, že některý program je neoprávněný nebo má pochybný původ, obraťte se na svého učitele nebo správce sítě pro další pokyny a podporu.

Používání pouze licencovaného a ověřeného softwaru je nejlepší způsob, jak chránit sebe, své kolegy a naše školní prostředí.

V dolní části se nachází část s katalogem důvěryhodného softwaru.
Děkujeme za vaši pozornost a spolupráci.
## Popis témat
## Úvod
## Před čím se chránit?
### Hackersky útoky
### Data
### Wifi
### Web
### Pracé z Software
### Pracé z Hardware
## Typy ochrany
## Odborná část
### RSA
RSA (Rivest-Shamir-Adleman) je asymetrický šifrovací algoritmus, který se používá pro šifrování a dešifrování dat a také pro digitální podpisy. Jeho fungování je založeno na matematických principech teorie čísel, konkrétně na obtížnosti faktorizace velkých prvočísel.

Algoritmus RSA využívá klíčový pár, který se skládá z veřejného a soukromého klíče. Veřejný klíč je používán pro šifrování dat, zatímco soukromý klíč je používán pro jejich dešifrování. Generování klíčů začíná výběrem dvou velkých prvočísel, jejichž součin je modulus n. Dále je spočítána Eulerova funkce phi(n), která udává počet relativně prvočíselných čísel menších než n a nesoudělných s n. Poté je vybrán veřejný exponent e, který musí být relativně prvočíselný s hodnotou phi(n). Soukromý exponent d je zvolen tak, aby byl inverzní k veřejnému exponentu modulo phi(n).

Pro šifrování zprávy se používá veřejný klíč, zatímco pro dešifrování se používá soukromý klíč. Šifrování probíhá výpočtem zprávy na e-tou mocninu modulo n. Dešifrování probíhá výpočtem šifrované zprávy na d-tou mocninu modulo n.

RSA zůstává bezpečný, pokud je obtížné faktorizovat velká prvočísla n. Bez soukromého klíče je faktorizace n prakticky nemožná pro dostatečně velká prvočísla p a q. RSA je jedním z nejpoužívanějších asymetrických šifrovacích algoritmů a má široké uplatnění v digitální komunikaci, elektronickém podpisu a bezpečném přenosu dat přes internet.

### Hash
Hashování je proces, při kterém se vstupní data transformují do pevného formátu fixní délky, který se nazývá hash. Tato hash hodnota je pak používána pro rychlé ověření integrity dat. Hashovací funkce, která provádí tuto transformaci, musí být deterministická a vysoce odolná vůči kolizím. Hashování má mnoho využití včetně ověřování integrity dat, ukládání hesel, digitálních podpisů a rychlého vyhledávání v databázích. Bezpečné hashovací algoritmy jsou klíčové pro zachování integrity a bezpečnosti dat v různých počítačových aplikacích.

## Zajímavé aplikace

### VPN/Proxies
- Tor browser - https://www.torproject.org/download/ 
- Tailscale - https://tailscale.com
- Hamachi - https://vpn.net

### Zip Unlocker
- LostMyPass - https://www.lostmypass.com/file-types/zip/
- ZipCracker - https://github.com/TrollSkull/ZipCracker

### Packet sniffers
- solarwinds - https://www.solarwinds.com/network-performance-monitor/use-cases/wifi-packet-sniffer
- wireshark - https://www.wireshark.org

### Port scanners
- nmap - https://nmap.org
- RustScan - https://github.com/RustScan/RustScan
- Pentest-Tools - https://pentest-tools.com/network-vulnerability-scanning/port-scanner-online-nmap

### Password managers
- 1password - https://1password.com
- Total Password - https://www.totalpassword.com
- Keeper - https://www.keepersecurity.com

### Encryption Software 
- AxCrypt Premium - https://axcrypt.net/premium/
- NordLocker - https://nordlocker.com
- Encrypto - https://macpaw.com/encrypto
