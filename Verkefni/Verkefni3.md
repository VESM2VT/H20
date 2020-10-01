# Verkefni 3 (25%) - Nálægðartakmarkarinn

Núna þegar að þriðja bylgja COVID-19 er í fullum gangi væri gott að eiga tæki sem hjálpaði fólki að virða hina almennu nálægðartakmörkun (e. social distancing).

Í þessu verkefni átt þú að smíða tæki sem skynjar hvort einhver er eins meters frá tækinu.

## Verkþættir

- 3d hönnun á hýsingu (e. casing)
- hönnun rafrásar, lóðun íhluta.
- Forritun

## Kröfulýsing

- Tækið skal vera í glæsilegri 3d prentaðri hýsingu sem annaðhvort getur staðið á borði eða notandi getur haft á sér (e. wearables) td. í belti, á tösku eða hengt á sig. 
- Tækið skal geta gengið fyrir rafhlöðu.
- Tækið getur mælt fjarlægðir.
- Ef nálægðartakmörkun er brotin gefur tækið frá sér hljóðmerki ([buzzer](https://create.arduino.cc/projecthub/SURYATEJA/use-a-buzzer-module-piezo-speaker-using-arduino-uno-89df45)) og kveikir á viðvörunarljósi.
- Tækið hefur skjá sem sýnir mælda fjarlægð.
- Með [fjarstýringu](https://github.com/VESM2VT/H20/blob/master/Verkefni/ir_remote.md) eða [talnaborði (e. keypad) ](https://www.circuitbasics.com/how-to-set-up-a-keypad-on-an-arduino/ ) er hægt að slá inn lykilorð til að slökkva á viðvörun.
- Hægt er að breyta nálægðartakmörkun með fjarstýringu eða talnaborði. 

Íhugaðu hvernig þú ætlar að leysa verkefnið. [Hér](https://github.com/VESM2VT/H20/blob/master/Verkefni/V3_skrefin.md) er dæmi um hvernig verkferlið gæti verið.

## Námsmat og skil

1. 30% Lóðun, veróborðasmíð og samsettning.
   - 30% Allar tengingar milli Arduino og annarra íhluta fara fram í gegn um veróborð sem er vel útfært, lóðun er til fyrirmyndar.
   - 25% Tengingar, lóðun eða veróborð útfærsla er ábótavant.
   - 15% Tvennt af eftirtöldu er ábótavant; tengingar, lóðun, veróborð.
   - 10% Tengingar, lóðun og veróborð er ábótavant.
   -  5% Tengingar, veróborð og lóðun er stórlega ábótavant.
   -  0% Vantar. 
 
1. 20% Þrívíddarhönnun.<br>
     - 20% Hýsing fyrir teikniborð er mjög vel útfært.
     - 16% Hýsing fyrir teikniborð er vel útfært, en getur verið betri mtt. pláss og lögun.
     - 12% Hýsing fyrir teikniborðið er nothæft, sést ekki í op eða víra.
     -  8% Hýsing fyrir teikniborðið er nothæft en það sést í víra eða op sem þurfa ekki að vera.
     -  4% Stórlega ábótavant.
     -  0% Vantar. 

1. 50% Kóðun og virkni.

   - 20%  
      - Tækið getur mælt fjarlægðir
      - Tækið hefur skjá sem sýnir mælda fjarlægð
   - 30%  
      - Tækið getur mælt fjarlægðir
      - Tækið hefur skjá sem sýnir mælda fjarlægð
      - Ef nálægðartakmörkun er brotin gefur tækið frá sér hljóðmerki og kveikir á viðvörunarljósi.
   - 40%  
      - Tækið getur mælt fjarlægðir
      - Tækið hefur skjá sem sýnir mælda fjarlægð
      - Ef nálægðartakmörkun er brotin gefur tækið frá sér hljóðmerki og kveikir á viðvörunarljósi.
      - Með fjarstýringu eða talnaborði (e. keypad) er hægt að slá inn lykilorð til að slökkva á viðvörun.      
   - 50%  
      - Tækið getur mælt fjarlægðir
      - Tækið hefur skjá sem sýnir mælda fjarlægð
      - Ef nálægðartakmörkun er brotin gefur tækið frá sér hljóðmerki og kveikir á viðvörunarljósi.
      - Með fjarstýringu eða talnaborði (e. keypad) er hægt að slá inn lykilorð til að slökkva á viðvörun.
      - Hægt er að breyta nálægðartakmörkun með fjarstýringu eða talnaborði. 
      
## Skil

Skilaðu hlekk á github geymslu sem er e. private í Innu.<br>
Í Github geymslu á að vera eftirfarandi:

- Allur kóði
- 3d teikningar og model (.stl skráin)
- Rökrásarhönnunarteikning
- Ljósmynd af lóðun (báðar hliðar)
- Tveimur myndböndum af virkni (tengil á youtube) 
    - frumgerð, virkni með tengingum íhluta á brauðbretti (ekki lóðun, veroborð og casing)
    - lokaafurð, virkni með veróborðasmíð og hýsingu.
- Skýrsla (í readme.md) þar sem gerð er grein fyrir helstu hönnunarákvörðunum, erfiðleikum og öðru sem þér dettur í hug.

