Pågåande og ønskd starta prosjekt
=================================

Dette er prosjekt eg har lyst til og/eller allereie har starta med, i vilkårleg
rekkjefølgje.


Programmeringsprosjekt
----------------------

Her er små og store ting eg har lyst å implementere for å lære meg korleis dei
verkar, eller for å lære meir om paradigme innanfor språka.

### Alle permutasjonar av lister ###

Implementer ei algoritme / funksjon av typen `List a -> List (List a)` som
genererer alle moglege permutasjonar av lista i C, Python og Haskell.

### Implementasjon av irrationale (og transendentale?) tal ###

Implementer, vha. lazy evaluation, uendeleg presisjon for reelle tal. Dette kan
gjerast slik at dei spyttar ut siffer etterkvart som dei blir spurne om det.
Slik kan vi ha vilkårleg presisjon, ikkje berre i talet sjølv, men ved addisjon
med andre reelle tal.

Rota av 2 og &pi; kjem til tankane.

### Rabin-Karp String Search ###

Rabin-Karpalgoritma som lært i OPT, båe med XOR og rullerande potenshash, som
definert på Wikipedia.

Her er noko som heiter Bloom(?)filter, også definert på Wikipedia, som burde
undersøkjast.

### Newtons Metode ###

Implementer på 3(?) forskjellige måtar, inkludert ein tail-recursive ein, i
Haskell.

### RAG ###

Skriv eit spel (Raptor Galore) i svart kvitt som køyrer på terminalen ved bruk
av framebufferen på Linux i C (og ingen andre bibliotek). Inspirert av offline-
Chrome-dinosaurspelet.

[Referanse for å skrive til framebufferen](http://betteros.org/tut/graphics1.php)

### Monopolstrategi ###

Inspirert av Matt Parker-video om temaet. Implementer i Python og sjå på Markov-
chains.

### Høgreklikksanimasjon ###

Fine og brukervenlege brukergrensesnitt er viktige. Testinterface med to
variantar av høgreklikk/nedtrekksmeny. I den eine forsvinn alle andre val enn
det valde i det ein held nede museklikkerten, i den andre er det omvendt, berre
dette feltet forsvinn.

Dot NET Core har støtte for grafisk teikning? Sjekk [her.](https://medium.com/@cameronaavik/cross-platform-graphics-in-net-core-901be29dabd7#.l3a2mjjlx)

Eventuelt look into Treejs.

### Straum i den engelske kanal ###

* Sanke marinetraffic-data i den engelske kanal, vha. API vi fann på GitHub - 
  NPM.

Det er fleire måtar denne dataen kan analyserast på. For eksempel er det mogleg
det er høve for å nytte maskinlæring. Ei anna tilnærming kan vere manuell.

Eg er meir interessert i å sjå på matta bak, ved å sjå på denne dataen som å
vere ei tilnærming til eit underliggjande vektorfelt `F(x,y,t)`, og å bruke
diverse numeriske metoder for å estimere dette feltet.

For eksempel ein slags vekta (med eksponensial avstandsfatkor?) sum av vektorane
, som gir meir vekt til nærliggande vektorar.

### Kreysig numerisk varmefordeling i kaffekanne ###

Kaffekanna er ein sylinder med `h` høgde, `r` radius, `86 °C` botn og
romtemperert sidevegger og topp. Korleis ser den statiske varmefordelinga ut?

Numerisk løysing av Laplace-likninga.
  
### Praktisk anvending av ML ###

I dusjen er det fint å kunne skifte sang, helst ved å rope neste - maskinlæring
kan brukast for å "høre" dette gjennom lyden av dusjen. For også slik praktisert
 / lært meir om Android (om dette skal implementerast på Anroid, ettersom det
verkar vanskeleg å gjere på iOS).

### R-tutorial ###

Følg R-tutorial på [tutorialspoint.](http://tutorialspoint.com/r/r_basic_syntax.htm)

### Vim-tutorial ###

~~[Følg Vim-tutorial på stackoverflow.](http://stackoverflow.com/questions/1218390/what-is-your-most-productive-shortcut-with-vim#1220118)~~

~~[Vist til av denne redditkommentar-primeren.](https://www.reddit.com/r/ProgrammerHumor/comments/59pipx/apple_touch_bar_for_developers_will_look_like_this/d9alcde/)~~

### Perl og Git ###

Perl 5 eller 6? Gjer research.

Følg [Ry's git Tutorial.](http://rypress.com/tutorials/git/index)

~~[PeepCode Git Internals (PDF)](https://github.com/pluralsight/git-internals-pdf/releases)~~

### Webinar om Web ###

[Lærte redditbrukar betre enn hans eigen professor](https://m.reddit.com/r/programming/comments/5hlx4e/this_guy_taught_me_better_than_my_professor/)

Antakeleg om diverse Webteknologiar?

### Open Source ###

Bidra til **Dolphin** (GameCube- og Wii-emulatoren) og **VSCodeVim**.

 * **Dolphin (C++)** har støtte for 3D. Her er det to frie variablar, avstanden
 mellom dei virtuelle kameraa og forskyvninga mellom bileta som blir vist fram.
 På ein gitt fysisk skjerm er det derimot ikkje noko reelt val kor stor denne
 forskyvinga skal vere; for lita og uendeleg langt borte blir ikkje så langt,
 for stor og sjåaren blir kryss-augd. Gjer slik skjermstorleiken kan setjast,
 og deretter kan storleiken på verda bestemmast etter sjåarens preferanse (ein
 reelt fri variabel), og resten blir implementert deretter.

 * **VSCodeVim (TypeScript)** Fix buggar: record and playback (q) fungerer
 dårleg, og manøvrering med haker ([), (]) og krøllparenteser ({) og ({), er
 feil.


Skriveprosjekt
--------------

Her er ting eg har lyst å skrive ein dissertasjon / utgreiing om, anten med
tanke på portfølgje eller for å hugse kunskapen eg har kome over.

### Gjennomsnittsalgoritmer ###

Her er fleire ting eg vil sy saman til ein. For det fyrste, skriv om
gjennomsnitt som definisjon av `argmin b f` der f er summen av avstanden mellom
punkta og b, opphøgd i ein potens `p`. Det interessante er `p = 0` gir typetal,
`p = 1` gir median og `p = 2` det vanlege snittet. `p = inf` gir mitten mellom
dei to ekstremala.

På debbie ligg ei GeoGebrafil som har implementert dette. Eg har også skrive
båe Python- og Haskellkode som implementerer denne algoritma.

I tillegg kan eg skrive om korleis standardavvik og gjennomsnittsberekning i
praksis kan uttrykkast som onlinealgoritmer (dvs. algoritmer som kan utførast
inkrementelt i det data kjem inn). Dette i henhald med databaseoppgåva med Gleb
og André i ODA.

### Kompleksitetsberekning av stokastiske algoritmer ###

Meir spesifikt, kompleksiteten av

```
visited = [False] * N
for 1..N:
    do {
        r = rand % N
    } while(visited[N])
    ... # Konstant tid
```

og korleis rekker kan brukast for å vise at han er `n log n`.

### Den deriverte av Knuths Up Arrow ###

Skriv om analytisk utleding av den deriverte av Up Arrow funksjonen.

Eg har også skrive Haskellkode som implementerer ein numerisk verifikasjon.


Diverse
-------

### Leseprosjekt ###

Ting eg vil lese om er

* SSE Intersection Sorted Ints (paper)

* FPGA Sorting Network (paper)

* Binary Packing (paper)

Sistnemnde vil eg og prøve å implementere i C.

### Pianoprosjekt ###

Eg vil lære å spele piano, men med sangar / melodiar eg likar. Til dømes har eg
lyst å lære meg å spele desse:

* Waiting for Love - Avicii

* Heathens

* Interstellar (score)

* Scary Monsters and Nice Spirites - Skrillex

* Firestone - Kygo

### Rubiks kube ###

* [2-Kube](http://www.cubewhiz.com/ortegapbl.php)

* [3-Kube](http://peter.stillhq.com/jasmine/JasmineLeeBeginnerRubikSolution.pdf)