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
Téma "Zásady bezpečné práce na PC" zahrnuje klíčové principy a postupy pro ochranu počítače a dat. To zahrnuje používání silných hesel, pravidelné aktualizace softwaru, instalaci antivirového softwaru a firewalu. Důraz je kladen na obezřetnost při otevírání e-mailových příloh a odkazů, aby se zabránilo phishingovým útokům. Dalšími důležitými aspekty jsou zálohování dat, používání dvoufaktorové autentizace a obezřetnost při stahování nebo sdílení souborů online. Téma také zahrnuje zásady bezpečné práce na veřejných PC a ve veřejných Wi-Fi sítích, včetně opatrnosti při zadávání citlivých informací a používání šifrovaných spojení.
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

### Kryptografie
Kryptografie je věda, která se zabývá zabezpečením komunikace a dat pomocí různých technik a algoritmů. Jedním z hlavních cílů kryptografie je zajistit, aby pouze autorizovaní uživatelé mohli číst, modifikovat nebo dekódovat data. Existují různé metody kryptografie, z nichž některé jsou symetrické a jiné asymetrické.

Symetrická kryptografie používá stejný klíč pro šifrování a dešifrování dat. Tento klíč musí být sdílen mezi komunikujícími stranami před začátkem komunikace. Příkladem symetrického šifrování je šifra AES (Advanced Encryption Standard), která je široce používána pro zabezpečení dat v různých aplikacích.

Na druhou stranu asymetrická kryptografie používá dva klíče: veřejný a soukromý. Veřejný klíč je sdílen s kýmkoli, kdo chce komunikovat s uživatelem, zatímco soukromý klíč je udržován v tajnosti. Tento přístup umožňuje bezpečnou komunikaci bez předchozího výměny klíčů. Nejznámějším asymetrickým kryptografickým systémem je RSA (Rivest-Shamir-Adleman), který se používá pro šifrování zpráv a digitální podpisy.

Kryptografie je klíčovým nástrojem pro ochranu důvěrnosti, integrity a autentičnosti dat v moderní digitální éře. Používá se v mnoha oblastech, včetně komunikace mezi uživateli, bankovních transakcí, e-mailových zpráv a elektronického obchodování. Zabezpečení dat pomocí kryptografie je důležité pro ochranu soukromí a citlivých informací v online prostředí.

### RSA
RSA (Rivest-Shamir-Adleman) je asymetrický šifrovací algoritmus, který se používá pro šifrování a dešifrování dat a také pro digitální podpisy. Jeho fungování je založeno na matematických principech teorie čísel, konkrétně na obtížnosti faktorizace velkých prvočísel.

Algoritmus RSA využívá klíčový pár, který se skládá z veřejného a soukromého klíče. Veřejný klíč je používán pro šifrování dat, zatímco soukromý klíč je používán pro jejich dešifrování. Generování klíčů začíná výběrem dvou velkých prvočísel, jejichž součin je modulus n. Dále je spočítána Eulerova funkce phi(n), která udává počet relativně prvočíselných čísel menších než n a nesoudělných s n. Poté je vybrán veřejný exponent e, který musí být relativně prvočíselný s hodnotou phi(n). Soukromý exponent d je zvolen tak, aby byl inverzní k veřejnému exponentu modulo phi(n).

Pro šifrování zprávy se používá veřejný klíč, zatímco pro dešifrování se používá soukromý klíč. Šifrování probíhá výpočtem zprávy na e-tou mocninu modulo n. Dešifrování probíhá výpočtem šifrované zprávy na d-tou mocninu modulo n.

RSA zůstává bezpečný, pokud je obtížné faktorizovat velká prvočísla n. Bez soukromého klíče je faktorizace n prakticky nemožná pro dostatečně velká prvočísla p a q. RSA je jedním z nejpoužívanějších asymetrických šifrovacích algoritmů a má široké uplatnění v digitální komunikaci, elektronickém podpisu a bezpečném přenosu dat přes internet.

### Hash
Hashování je proces, při kterém se vstupní data transformují do pevného formátu fixní délky, který se nazývá hash. Tato hash hodnota je pak používána pro rychlé ověření integrity dat. Hashovací funkce, která provádí tuto transformaci, musí být deterministická a vysoce odolná vůči kolizím. Hashování má mnoho využití včetně ověřování integrity dat, ukládání hesel, digitálních podpisů a rychlého vyhledávání v databázích. Bezpečné hashovací algoritmy jsou klíčové pro zachování integrity a bezpečnosti dat v různých počítačových aplikacích.

### Packet sniffer
Packet sniffer je nástroj nebo software, který umožňuje sledovat a analyzovat datový provoz na síťové úrovni. Tento typ nástroje zachytává data, která procházejí přes síť, a zobrazuje je uživateli v podrobné podobě. Mezi hlavní využití patří diagnostika síťových problémů, monitorování síťového provozu a bezpečnostní analýza.

Pomocí packet snifferu můžete sledovat různé informace o síťovém provozu, jako jsou zdrojové a cílové IP adresy, porty, přenosové rychlosti a obsah datových paketů. To umožňuje administrátorům sítě identifikovat potenciální problémy, jako jsou přetížené linky, ztracené pakety nebo síťové útoky.

### VPN/Proxies
VPN (Virtual Private Network) a proxy server jsou dva nástroje používané k zabezpečení a anonymizaci internetového připojení, ale fungují trochu odlišně.

VPN vytváří soukromou síť pomocí veřejné sítě, jako je internet. Pomocí VPN se vaše data šifrují před odesláním přes internet a poté dešifrují na cílovém serveru. To znamená, že vaše internetové aktivity jsou chráněny proti odposlouchávání a sledování. VPN také může skrýt vaši skutečnou IP adresu tím, že přesměruje vaši síťovou aktivitu přes server umístěný v jiné zemi, což vytváří dojem, že připojení pochází z jiného místa.



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
