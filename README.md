# <p align="center">❀Zinekide❀</p>

## <p align="center">--------------------SARRERA--------------------</p>
Orrialde honetan, zinema alternatibo eta independetearen inguruko komunitatearen ingurukoa izango da.
bertan, streaming emanaldiak egongo dira ikusi ahal izateko eta kontu bat sortzen baldin baduzu, aukera
izango duzu eztabaida-foruetan zure iritzia esateko edota lagun berriak egin kendearekin eztabaidatzen eta
aukera emango da pelikulen zuzendariekin elkarrizketa esklusiboak egin ahal izatea.

## <p align="center">--------------------IKERKETA--------------------</p>
### ★Benchmark★
| Plataforma | Ezaugarri nagusiak | Zinekiderako interesgarria |
|---|---|---|
| **Netflix** | Streaming-a, bilaketa, kategoriak eta gomendio pertsonalizatuak | Nabigazio erraza eta edukien antolaketa |
| **MUBI** | Zinema independentea eta autore-zinema, katalogo zaindua | Identitate bisuala eta filmen aurkezpena |
| **Filmin** | Zinema independentea, europarra eta klasikoa | Katalogoaren antolaketa eta filmen sailkapena |

__<ins>Ondorioak</ins>__

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

__<ins>Helburuak</ins>__

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

→Interfaze iluna edukiko du beraz kolore paleta iluna/hotzak erabiliko dira orrialdea sortu ahal izateko.
Beltza: Hex
#000000
Zuria: Hex
#FFFFFF
### ★Tipografia★

→Izenburuentzako Merriweather tipografia erabiliko dut.

→Izenburuak lodiz izango dira esta testuak baina pixka bat handiagoak izango dira.

→Testu normala idazteko Raleway tipografia erabiliko dut.

### ★Ikonoak★

→Footer-ean sare sozialen ikonoak jarriko ditut.

→Orrialdeak favicon logoa edukiko du.

→Orrialdeak bere logo bat edukiko du header-ean.

→Orrialda edukiko du gezi ikono bat orrialdeak gora egin ahal izateko.

### ★Botoiak★

→Menuko atal/aukera guztiak botoiak izango dira beste ataletara nabigatu ahal izateko.

→Botoi honek ez dira oso handiak izango tipografiaren baina tamaina pixka bat gehiago edukiko dute.

### ★Irudiak★

→Sare sozialeko irudiak egongo dira, honek txikiak izango dira eta footerra-ren barruan egongo dira.

→Orrialdearen logo header-aren barruan egongo da eta ertaina izango da.

→Orriaren eduki irudiak handiagoak izango dira ondo ikus ahal izateko.


