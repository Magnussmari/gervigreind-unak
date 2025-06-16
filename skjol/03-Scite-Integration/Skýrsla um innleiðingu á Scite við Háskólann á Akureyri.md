**Dagsetning:** 7. apríl 2025\
**Tengiliður verkefnis:** Magnús Smári Smárason, verkefnastjóri
gervigreindar

**Aðgangur:** Allir *starfsmenn* og *nemendur* Háskólans á Akureyri munu
hafa aðgang að Scite sem hluta af Enterprise-leyfi háskólans.

**Tenglar: [www.scite.ai](http://www.scite.ai) ,
[www.researchsolutions.com](https://www.researchsolutions.com/)**

# 1. Yfirlit

Starfsmenn bæði Kennslu- og upplýsingatæknimiðstöðvar og Bókasafns
Háskólans á Akureyri hafa undanfarið haft aðgang að Scite-kerfinu til
prófunar. Niðurstaðan úr þeirri yfirferð er samhljóða, lausnin telst
bæði hagkvæm og vel til þess fallin að mæta þörfum háskólans í ljósi ört
vaxandi notkunar og þróunar á sviði gervigreindar í rannsóknum og
kennslu.

Scite sameinar styrkleika hefðbundinna vísindagagnagrunna og nýjustu
tækni í gervigreind með snjöllum tilvísunum, greiningartólum og aðgengi
að víðtækum gögnum. Lausnin byggir á þróuðum vélnámslíkönum, gagnagrunni
sem tengist síðan við stórt mállíkan, sem styðja bæði nemendur og
kennara í heimildaleit, greiningu og gagnrýninni hugsun.

Sameiginlegur aðgangur allra starfsmanna og nemenda að slíku tæki eykur
möguleika á að innleiða markvissar breytingar á námsleiðum og
námskeiðum, þar sem lausnin verður hluti af rafrænu námsumhverfi
skólans.

Verkefnið er í samræmi við hlutverk verkefnastjóra gervigreindar og
styður við stefnur Háskólans á Akureyri og aðgerðaráætlun stjórnvalda um
gervigreind 2024--2026.

Scite uppfyllir helstu öryggis- og persónuverndarstaðla á borð við GDPR,
AES-256 dulkóðun og ISO 27001 (í gegnum AWS). Gert er ráð fyrir tveggja
ára samstarfssamningi að upphafi, með sjálfvirkri framlengingu og 5%
árlegri verðhækkun. Heildarkostnaður fyrir fyrstu tvö árin er 20.500
USD, sem jafngildir tæplega 3 milljónum ISK miðað við gengi 7. apríl
2025.

# 2. Helstu kostir Scite

1.  **Snjallar tilvísanir (Smart Citations)\
    **

    -   Flokkaðar sem styðjandi, minnst á eða andstæðar (supporting,
        mentioning, contrasting).

    -   Yfir 1,9 milljarðar tilvísunar sem byggja á opinberum (OA) og
        áskriftargreinum.

2.  **Skilvirk uppgötvun og ritdómgreining\
    **

    -   Flýtir fyrir heimildaleit, staðfestir áreiðanleika greina og
        auðveldar fjölbreyttar rannsóknir.

    -   Minnkar hættu á að nemendur og kennarar reiði sig á óstaðfestar
        gervigreindarlausnir.

3.  **Markviss innleiðing**

    -   Tengingar við Zotero og möguleika á Single Sign-On (SAML 2.0).

    -   API og innviðir til að styðja við fjölbreytta innleiðingu í
        kennslukerfum HA.

4.  **Fræðsla og kennsla\
    **

    -   Sérsniðnir „masterclass"-tímar fyrir kennara og nemendur.

    -   „Train the Trainer" námskeið fyrir lykilaðila innan Háskólans.

    -   Hægt að þróa stutt skyldunámskeið í Articulate Rise áður en
        notendur fá aðgang.

### 🔹 Tæknigrunnur Scite: Gagnagrunnur, vélnám og stór mállíkan

Scite byggir á samþættu tæknikerfi sem sameinar hefðbundinn
fræðigagnagrunn við nýjustu aðferðir í gervigreind. Kerfið samanstendur
af þremur meginþáttum:

#### 1. Gagnagrunnur fræðigreina og tilvísana

Í hjarta Scite liggur yfir 1,2 milljarða tilvísana sem dregnar eru úr
yfir 180 milljónum fræðigreina, bæði með opnum aðgangi og
áskriftargögnum. Þetta gerir Scite að einum víðtækasta uppsprettugrunni
tilvísanagreiningar í heiminum í dag.

#### 2. Vélrænt nám og máltækni (machine learning & NLP)

Tilvísanagreining Scite byggir á sérþjálfuðum *deep learning* líkönum
sem hafa verið fínstillt til að lesa og flokka setningar úr greinum
eftir því hvort þær séu **styðjandi**, **gagnrýnar** eða **hlutlausar**
gagnvart tiltekinni heimild. Þessi aðferð skapar svokallaðar *snjallar
tilvísanir* (*Smart Citations*), þar sem samhengi tilvísunar er metið í
stað þess að telja aðeins fjölda.

#### 3. Stórt mállíkan í Scite Assistant

Scite Assistant byggir á *large language model* (LLM) sem hefur verið
sérsniðið að fræðilegri notkun. Í stað þess að spá eingöngu eftir
líkindum eins og almennir spjallmenn (t.d. ChatGPT) notar Assistant LLM
sem er bundið við fræðilegan gagnagrunn Scite og skilar alltaf svari með
tilvísun. Þetta minnkar hættu á haldvillum (*hallucinations*) og eykur
gagnsemi í akademísku samhengi. Assistant nýtir m.a. retrieval-augmented
generation (RAG) með beinum tengslum við gagnagrunn til að tryggja
samhengi og áreiðanleika.

#### Tæknileg yfirsýn

  -------------------------------------------------------------------------
  **Þáttur**     **Tæknilausn**
  -------------- ----------------------------------------------------------
  Gagnageymsla   PostgreSQL gagnagrunnur með skráningu á \>1 milljarð
                 tilvísana

  Málgreining    Sérþjálfaðar deep learning módel byggðar á BERT og öðrum
                 transformer-arkitektúrum

  Spjallkerfi    LLM með fræðilegu samhengi (RAG), fínstillt á
                 fræðigreinasamantektir

  Öryggi         GDPR samræmi, AES-256 dulkóðun, ISO 27001 í gegnum AWS

  Samþætting     SAML 2.0 (SSO), API REST þjónusta, Zotero viðmót
  -------------------------------------------------------------------------

## 3. Samningur og skilmálar

-   **Ársgjald**: 10.000 USD fyrsta árið (2025--2026), hækkar í 10.500
    USD (2026--2027) með 5% hækkun árlega eftir það.

-   **Tímabil**: Lágmark 2 ára upphafstímabil, sjálfvirk framlenging
    nema sagt sé upp með 60 daga fyrirvara.

-   **Notendaleyfi**: Takmarkast við HA (Enterprise-leyfi), óheimilt að
    selja áfram eða breyta.

-   **Ábyrgð og samræmi**:

    -   GDPR-eftirfylgni og persónuverndarrammi að fullu.

    -   Öryggisstaðlar: Dulkóðun í flutningi og við geymslu,
        viðurkenndir ferlar fyrir innbrotsvörn og dulkóðun.

## 4. Innleiðingarferli

1.  **Tæknileg uppsetning\
    **

    -   Samráðsfundur með Scite til að samræma innskráningu (SSO) og
        notendaaðgang (8. apríl).

    -   Uppsetning á API og tengingum við möguleg kennslukerfi.

2.  **Fræðsla og "Train the Trainer"\
    **

    -   „Masterclass"-námskeið með sérfræðingum Scite (m.a. Prof. Sean
        Rife).

    -   Yfirfærslunámskeið fyrir kennara og bókasafnsstarfsfólk til að
        útbreiða þekkingu.

    -   Stutt netnámskeið verður skilyrði fyrir aðgang notenda.

## 5. Tímalína

  --------------------------------------------------------------------------
  **Aðgerð**                                   **Dagsetning**   **Staða**
  -------------------------------------------- ---------------- ------------
  Kynningarfundur (Magnús & Béatrice)          21\. mars        Lokið

  Prófun í bókasafnshópi                       24\. mars        Lokið

  Áætluð endurgjöf og næstu skref              10\. apríl       Fyrirhugað

  Yfirferð og formleg staðfesting samnings     14\. apríl       Fyrirhugað

  Tæknilegur samráðsfundur (m. Johnathan)      8\. apríl        Skipulagt

  Masterclass fyrir bókasafn og                5\. maí          Fyrirhugað
  lykilstarfsmenn                                               

  „Train the Trainer" undirbúningur            maí              Í vinnslu

  Heildarinnleiðing -- eftir netnámskeið       júní 2025        Fyrirhugað
  --------------------------------------------------------------------------

## 6. Áherslur og ávinningur

-   **Aukið rannsóknaröryggi**: Háskólinn fær aðgang að áreiðanlegum
    gögnum og dregur úr áhættu á óstaðfestum AI-verkfærum.

-   **Hraðari og gagnsærri leit**: Mikill sparnaður á tíma í
    heimildaöflun og yfirlit.

-   **Siðferðileg notkun AI**: Sérsniðin fræðsla tryggir að nemendur og
    kennarar kunni á Scite og noti tæknina með ábyrgum hætti.

-   **Samræming við stefnu HA**: Byggir undir nýsköpun og gæðakennslu,
    um leið og innviðir rafrænna lærdómsumhverfa eru styrktir.

## 7. Næstu skref

1.  **Formleg staðfesting** samnings og lokafrágangur (14. apríl).

2.  **Tæknilegur samráðsfundur** til að tryggja skilvirka innskráningu
    og notendaaðgang (8. apríl).

3.  **Fræðsla og kynning** -- „Masterclass", „Train the Trainer" og
    netnámskeið verða innleidd samhliða tæknilegri uppsetningu.

4.  **Ráðningartími**: Innleiðing og vöktun fram í júní, þegar notendur
    fara almennt að nýta Scite í rannsóknum og námi.

5.  **Eftirfylgni**: Regluleg skýrslugjöf og stuðningur frá Scite
    varðandi notkunartölfræði og þjónustu.

## Samantekt

Scite er öflugt tæki til að efla rannsóknarvinnu við Háskólann á
Akureyri, draga úr áhættu í notkun gervigreindar og tryggja betrumbætur
í kennslu og rannsóknarþjónustu. Áhersla á ábyrgð, öryggi og innri
fræðslu mun stuðla að farsælli notkun Scite sem hluta af
nýsköpunarstefnu HA í stafrænu umhverfi.

**Teymi**:

Í dag samanstendur teymið af fulltrúum KHA og Bókasafns, en í
innleiðingaferlinu verður fræðasviðum og áhugasömum boðin þátttaka.

-   **Magnús Smári Smárason**, Verkefnastjóri Gervigreindar,
    magnussmari@unak.is

-   **Auðbjörg Björnsdóttir**, Forstöðumaður kennslu- og
    upplýsingatæknimiðstöðvar

-   **Astrid Margrét Hoddevik Magnúsdóttir**, Forstöðumaður bókasafns

-   **Gunnar Ingi Ómarsson,** Verkefnastjóri tæknimála

-   **Helgi Freyr Hafþórsson**, Umsjón með innleiðingu og fræðslu

Mat á Scite-verkefninu í samhengi við stefnu Íslands í gervigreind
2024--2026

[Aðgerðaáætlun stjórnvalda um gervigreind
(2024--2026)](https://www.stjornarradid.is/library/04-Raduneytin/Haskola---idnadar--og-nyskopunarraduneytid/A%C3%B0ger%C3%B0a%C3%A1%C3%A6tlun%20um%20gervigreind%20n%C3%B3vember%202024.pdf)
kallar á ábyrga, gagnsæja og siðferðilega samþætta innleiðingu
gervigreindarlausna. Scite-verkefnið styður við alla meginþætti
stefnunnar:

### 1. Opin og ábyrg vísindi (Markmið A.5)

-   Scite eykur gagnsæi í vísindalegum greiningum með snjöllum
    tilvísunum og traustri heimildaskráningu.

-   Styður við að rannsóknaniðurstöður verði aðgengilegar og gagnlega
    notaðar í samfélaginu.

### 2. Menntun og stafrænt læsi (Markmið C.1--C.3)

-   Nemendur og kennarar fá þjálfun í siðferðilegri notkun AI í námi og
    kennslu.

-   Fræðsluverkefni (Masterclass, Train the Trainer, netnámskeið) efla
    gervigreindarfærni og gagnrýna hugsun.

### 3. Stafrænir innviðir og öryggi (B.4, D.2)

-   Innleiðingin fer fram með samræmingu við SSO og GDPR, og API
    samþættingu.

-   Öll gagnavinnsla fylgir alþjóðlegum öryggisstöðlum (t.d. ISO 27001,
    AES-256).

### 4. Almenn velferð og jafnrétti (A.3--A.4)

-   Með aðgangi allra notenda stuðlar verkefnið að jöfnu aðgengi og
    dregur úr þekkingar misræmi.

-   Kennslu- og stuðningsverkefni taka mið af ólíkum hópum innan háskóla
    samfélagsins.

### 5. Alþjóðlegt samstarf og nýsköpun (A.6, B.6)

-   Með Scite tengist HA alþjóðlegum vísinda gagnagrunnum og gagnast af
    nýjungum í ábyrgri gervigreind.

-   Styður við markmið Íslands um virka þátttöku í Nordic AI samstarfi
    og Digital Europe.

### Ályktun

Scite-verkefnið er **í fullu samræmi við íslenska stefnu um
gervigreind** og þjónar markmiðum hennar um:

-   Siðferðislega og gagnsæja notkun AI í menntakerfinu.

-   Bætt aðgengi og jafnrétti til rannsókna.

-   Nýtingu gervigreindar til eflingar vísindastarfs og kennslu.

-   Þróun stafræns lærdómsumhverfis í opinberri menntastofnun.

Verkefnið sýnir hvernig innleiðing á alþjóðlegri gervigreindar tækni,
með skýrum áherslum á öryggi, menntun og samræmi við opinbera stefnu,
getur orðið fyrirmynd annarra íslenskra stofnana í þekkingariðnaði.
