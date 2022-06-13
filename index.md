### Python Checkers

## *Pravidlá*

Existuje mnoho rôznych variantov pravidiel hry, ja som vybral tieto (klasická anglická dáma)
* _Cieľom hry je vyhodiť všetky súperove figurky._
* _Dáma sa hrá sa na šachovnici 8x8, pričom každý hráč má na začiatku 12 figúrok (pešiakov)
stojacich oproti sebe v prvých dvoch radoch na čiernych políčkach._
* _Pešiaci sa pohybujú po diagonálach (šikmo) a nesmú preskakovať svoje vlastné figúrky. 
Pešiak sa môžete pohybovať iba smerom vpred, nesmie "cúvať". 
Pri bežnom ťahu sa figúrky smú pohybovať iba po jednom políčku._ 
* _Vyhodenie súperovej figúrky sa uskutoční jej preskočením. 
Ak sa v ceste figúrky, ktorá vyhadzuje, nachádza aj ďalšia súperova figúrka, tak ju môže takisto preskočiť. 
Medzi preskakovanými súperovými figúrkami musí byť vždy jedno pole voľné - figúrky nemôžu stáť tesne za sebou. 
Po každom dopade sa môže zmeniť smer ďalšieho skoku(ale len dopredu, ak nie je dámou)._ 
* _Ak sa pešiak dostane na druhú stranu šachovnice, stane sa z neho dáma. Tá sa môže pohybovať po diagonálach vpred aj vzad na 1 polé._
* _Ak mate možnosť vyhodiť súperovu figúrku, tak musite ju vyhodiť._
* _Hru vyhráva hráč, ktorý zoberie súperovi všetky jeho figúrky._

---
## *Ovládanie hry*
Hru môžete ovládať ľavým tlačidlom myši a ťahanim.

---

## *Režimy hry*
1. Player vs Player
2. Player vs Computer

---
## *Player vs Computer*
Umelá inteligencia je implementovaná takým spôsobom, že na základe každého ťahu hráča vypočíta nasledujúci ťah s najvyššou pravdepodobnosťou vyhodenia nepriateľovej dámy. Ťahy umelej inteligencie sú teda vypočítané počas hry a žiadne stratégie nie sú dopredu pripravené. Zajatie nepriateľskej dámy je prioritou, keďže výrazne zvyšuje šance na výhru (zároveň podľa pravidiel hry, ak existuje možnosť - musíte ju využiť). Ak neexistuje žiadna iná možnosť, počítač sa rozhodne vykonať ťah na základe týchto rôznych situácií:
1. Príležitosť urobiť z pešiaka dámu.
2. Pokus o obranu pešiaka/damy, ktorú sa hráč snaží získať.
3. Ak nie je žiadna iná možnosť realizovať predchádzajúce možnosti, vykoná sa náhodný ťah.
Umelá inteligencia používa 1-sekundové oneskorenie ťahu pre dosiahnutie prirodzenosti.

---
## *Vlastnosti*
* Po každej akcii hráča alebo počítača sa prehrá hudba (ťah, koniec hry, vyhodenie súperovej figúrky).
* Ak hráč nechce hru dokončiť, môže ju uložiť do textového súboru. Kedykoľvek sa k nej môže vrátiť a dokončiť ju. Táto funkcia funguje v dvoch režimoch(P vs P, P vs C).

---
# [*Stiahnuť hru*](https://www.google.com/search?q=im+gay)
