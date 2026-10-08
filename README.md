# <p align="center">❀Zinekide❀</p>

## <p align="center">--------------------AURKIBIDEA--------------------</p>

- [SARRERA](#sarrera)
- [IKERKETA](#ikerketa)
  - [★Benchmark★](#benchmark)
  - [★Ondorioak★](#ondorioak)
  - [★Userprofila★](#userprofila)
  - [★Helburuak★](#helburuak)
- [ARKITEKTURA](#arkitektura)
  - [★Nabigazio mapa★](#nabigazio-mapa)
  - [★User flows★](#user-flows)
  - [★Krokisa★](#krokisa)
  - [★Erabilgarritasuna★](#erabilgarritasuna)
- [ESTILO GIDA](#estilo-gida)
  - [★Koloreak★](#koloreak)
  - [★Tipografia★](#tipografia)
  - [★Ikonoak★](#ikonoak)
  - [★Botoiak★](#botoiak)
  - [★Irudiak★](#irudiak)
- [EDUKIEN LIZENTZIA](#edukien_lizentzia)
- [ERABILGARRITASUNAREN AZTERKETA](#erabilgarritasunaren_azterketa)
- [PROTOTIPOA](#prototipoa)
- [BIBLIOGRAFIA](#bibliografia)

## <p align="center">--------------------SARRERA--------------------</p>
Orrialde honetan, zinema alternatibo eta independetearen inguruko komunitatearen ingurukoa izango da.
bertan, streaming emanaldiak egongo dira ikusi ahal izateko eta kontu bat sortzen baldin baduzu, aukera
izango duzu eztabaida-foruetan zure iritzia esateko edota lagun berriak egin kendearekin eztabaidatzen eta
aukera emango da pelikulen zuzendariekin elkarrizketa esklusiboak egin ahal izatea.

## <p align="center">--------------------IKERKETA--------------------</p>
### ★Benchmark★
| Webgunea | Indarguneak | Ahuleziak | Esteka |
| :--- | :--- | :--- | :--- |
| **Netflix** | Streaming-a, bilaketa, kategoriak eta gomendio pertsonalizatuak | Nabigazio erraza eta edukien antolaketa | [Ikusi](https://www.netflix.com/es)
| **MUBI** | Zinema independentea eta autore-zinema, katalogo zaindua | Identitate bisuala eta filmen aurkezpena | [Ikusi](https://mubi.com/es/us)
| **Filmin** | Zinema independentea, europarra eta klasikoa | Katalogoaren antolaketa eta filmen sailkapena | [Ikusi](https://www.filmin.es/)

### ★Ondorioak★

**Netflix**-etik, nabigazio sinplea eta edukien antolaketa.
**MUBI**-tik, zinema independentearen presentzia eta diseinu bisuala.
**Filmin**-etik, filmen katalogoa eta kategoriaka antolatzeko modua.

Zinekidek ideia hauek elkartu nahi ditu, baina **komunitateari eta ekitaldiei garrantzi handiagoa emanez**. Horretarako, streaming-az gain, foroak, elkarrizketak eta ekitaldien egutegia izango ditu.

Diseinuari dagokionez, **interfaze iluna eta minimalista** erabiliko da, filmen irudiei protagonismoa emateko.

### ★Userprofila★

Zinekideren erabiltzaile nagusia zinema gustuko duen eta zinema independentea eta alternatiboa ezagutzeko interesa duen pertsona da.

→16 - 35 Urteen artean izango da.

→Orrialdea simplea izango da.

→Nabigazio erraza eta intuitiboa.

→Filmak bilatzeko eta iragazteko aukera.

→Filmen informazio argia.

→Gomendioak jasotzea.

→Ekitaldien egutegia kontsultatzea.

### ★Helburuak★

→Film independente berriak aurkitzea.

→Filmen informazioa eta iritziak kontsultatzea.

→Gustuko dituen filmak gordetzea.

→Zinema inguruko eztabaidetan parte hartzea.

→Proiekzioak eta bestelako ekitaldiak aurkitzea.

## <p align="center">--------------------ARKITEKTURA--------------------</p>
### ★Nabigazio mapa★
→Atal ezbederdinak ikusi ahal izateko, menu bat edukiko du bertatik sartu ahal izateko.

<img width="622" height="182" alt="Nabigazio mapa drawio" src="https://github.com/user-attachments/assets/951af49c-00d5-45aa-820b-c5671255e97b" />

→Index-etik menu-aukera guztietara sar zaitezke: foroa, zuzendariarekiko elkarrizketak eta streaming emanaldiak.

→Atzera bueltatzeko atzera geziari klik eman beharko zaio edota menuan hasiera sakatu.

### ★User flows★
__Aurkikuntza- eta erregistro-fluxua__

```

[Hasierako orria]

       │
       ▼
[Arakatu katalogoa]

       │
       ▼

[Sakatu "Ikusi filma" edo "Parte hartu foroan"]

       │       
       ▼

[Erregistratzeko / Kontua sortzeko pantaila]

       │    
       ▼
  
[Erabiltzailearen panel pertsonalizatua]
```
__Komunitatearen arteko elkarreragin-fluxua__
```
[Menu nagusia: Komunitatea / Foroak] 
       │
       ▼
[Gaien zerrenda] (filma eta zuzendaria)
       │
       ▼
[Irakurri eztabaida-haria] 
       │
       ▼
[Erantzuna / Iruzkina argitaratu] 

```
### ★Krokisa★

__ESKRITORIOA__

__Orrialde printzipala__

→Hasiera profila dagoen lekuan agertuko da login bat edota erregistratu ahal izateko botoiak bata edo bestea egin ondoren zure profila agertuko da.

→Orrialde printzipala

<img width="1002" height="1001" alt="ZineKide krokis drawio" src="https://github.com/user-attachments/assets/a7190940-57b4-4a26-9e8a-9eed235bb575" />


__Foro atala__

<img width="800" height="892" alt="Foro atala drawio" src="https://github.com/user-attachments/assets/04e52d3c-aa58-4bc7-9f83-55a30ade2aa5" />

__Mugikor formatua__

<img width="1312" height="1199" alt="c0d76f43-4ef6-4f40-9f19-02fc7f49449d" src="https://github.com/user-attachments/assets/2cff49b1-672a-4412-b123-d3d0257277df" />

## <p align="center">--------------------ESTILO GIDA--------------------</p>

### ★Koloreak★

| Funtzioa | Kolorea | Hex Kodea | Helburua / Aplikazioa |
| :--- | :--- | :---: | :--- |
| **Lehena** | Ia beltz purua | #0B0B0B | Gune publikoko atzealde iluna darkmode-rako. |
| **Bigarrena** | Gris oso iluna  | #141414 | Textu koadroak ezberdindu ahal izateko fondotik kolore tono argiago bat |
| **Botoiak** | Terrakota iluna | #812E2E | Botoien kolorea izango da, honek kontrastea egingo du kolore ilunekin orrialdea pixka biziagoa egiteko |
| **Testua** | Gris argia  | #E2E2E2  | Irakurgarritasun handia, ilunarekin kontrastea argia edukitzeko. |

→Texturako zuria erabiliko da eta gris oso iluna beltza erabiliko da

→Interfaze iluna edukiko du beraz kolore paleta iluna/hotzak erabiliko dira orrialdea sortu ahal izateko.

→Botoi fondoa terrakota iluna izango da eta eta letra gris argia izango du.

<img width="1200" height="760" alt="paleta-812E2E-E2E2E2-FF4D4D-0B0B0B-141414" src="https://github.com/user-attachments/assets/b40859c5-a2e1-41bd-a744-52d4bb3d1922" />

### ★Tipografia★

→Izenburuentzako Merriweather tipografia erabiliko da.

→Izenburuak lodiz izango dira esta testuak baina pixka bat handiagoak izango dira.

→Testu normala idazteko Raleway tipografia erabiliko da.

→Izenburuak 24 tamainekoa izango da.

→textua 16-18ko tamaina izango du.

### ★Ikonoak★

→Footer-ean sare sozialen ikonoak jarriko dira.

→Orrialdeak favicon logoa edukiko du.

→Orrialdeak bere logo bat edukiko du header-ean.

→Orrialda edukiko du gezi ikono bat orrialdeak gora egin ahal izateko.

→Ikonoak jpg edo png formatuan izango dira.

→Ikonoak tamaina txikia izango dute.

### ★Botoiak★

→Menuko atal/aukera guztiak botoiak izango dira beste ataletara nabigatu ahal izateko.

→Botoi honek ez dira oso handiak izango tipografiaren baina tamaina pixka bat gehiago edukiko dute.

### ★Irudiak★

→Sare sozialeko irudiak egongo dira, honek txikiak izango dira eta footerra-ren barruan egongo dira.

→Orrialdearen logo header-aren barruan egongo da eta ertaina izango da.

→Orriaren eduki irudiak handiagoak izango dira ondo ikus ahal izateko.

## <p align="center">--------------------EDUKIEN LIZENTZIA--------------------</p>

Tipografia:

→Google Fonts erabiliko da letra motarentzat. Hau kode irekiko lizentzia da, dohakoa.

Ikonoak:

→BootStrap Icons erabiliko da. Hau 2000 ikonoz goraztik osatutako kode irekiko, dohakoa eta kalitate handiko erraminta da. Ordainketa ikonoak visa txartela etab... Banku pasarelak samurtutakoak izango dira.

Irudiak:

→Webgune honetarako irudi portzentai handiena zinema kartelerak eta ateratako argazkiak izango dira, hauen irudiak, zinemako argazki arduradunak erraztuko ditu. Arduradun hauek izango direlarik lizentziaren arduradunak.

Web orrialdea:

→Web orrialde hau CC-BY-NC lizentzia izango du, pertsonak jatorrizko lana partekatu, egokitu eta horretan oinarritutako lanak sor ditzake, baldin eta egileari aitorpena egiten badio eta lana ez badu helburu komertzialekin erabiltzen. 

## <p align="center">--------------------ERABILGARRITASUNAREN AZTERKETA--------------------</p>

→Sistemaren eta mundu errealaren arteko erlazioa: erabiltzaileek ezagutzen dituzten 'Like', 'Comment', 'Share' eta 'Account' bezalako terminoak eta ekintzak erabiltzen ditu.

→Sendotasuna eta estandarrak: elementu desberdinentzako egitura bisual koherentea.

→Ezagutzea, gogoratzea baino hobeto: aukera nagusiak argi ikus daitezke eta ez diote erabiltzaileari komandoak gogoratu beharrik uzten.

→Erabilera malgutasuna eta efizientzia: menuan nabigatzeko eta hasierara itzultzeko aukera ematen dizu.

→Diseinu estetiko eta minimalista: beharrezko elementu soilik erakusten ditu, interfazea karga gehiegirik gabe mantenduz.

## <p align="center">--------------------PROTOTIPOA--------------------</p>

[Esteka](https://www.figma.com/design/l1MEqTy1dToPld67jAebnu/ZineKide?node-id=0-1&p=f&t=DzYoFYNvR0hiMI9G-0)

## <p align="center">--------------------BIBLIOGRAFIA--------------------</p>

→[NETFLIX](https://www.netflix.com/es)

→[MUBI](https://mubi.com/es/us)

→[FILMIN](https://www.filmin.es/)

→[LIZENTZIA MOTAK](https://es.wikipedia.org/wiki/Licencias_Creative_Commons)

→[KOLOREAK](https://paletadecolores.org/)

→[TIPOGRAFIA](https://fonts.google.com/)

→[FIGMA](https://www.figma.com/es-es/)
