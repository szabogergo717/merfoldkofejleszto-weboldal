# Mit tartalmaz ez a frissítés, és hogyan told fel

## Amit hozzáadtam a csatolt specifikációból

Ezek mind **beépültek** az `index.html`-be és a `foglalas.html`-be, kitalált adat nélkül:

1. **"Nem tudod, mire van szükségetek?" szekció** — egy rövid, kattintható kérdéssor a főoldalon, ami a válasz alapján egy ajánlott szolgáltatással a foglalási rendszerbe irányítja a szülőt.
2. **Bizalomépítő statisztika-sáv** — a valós adatok (2015, 6 terület, 491 követő) mellett egy jól látható placeholder ("[VALÓS ADAT]") ott, ahol nem tudtam számot kitalálni — ezt neked kell majd kitöltened.
3. **GYIK (FAQ) szekció** — kinyitható kérdés-válasz blokkokkal, a specifikációdban szereplő leggyakoribb kérdésekkel.
4. **"Honnan érkeztek hozzánk" szekció** — Tök + a környező települések (Zsámbék, Páty, Biatorbágy, Budaörs, Budakeszi) kiemelve, SEO céllal.
5. **Sticky mobil "Időpontot foglalok" gomb** — mobilon a képernyő alján marad, amint elgörgetsz a hero szekció alá.
6. **SEO-csomag**: Open Graph és Twitter meta tagek (szebb megjelenés, ha valaki megosztja a linket), Schema.org strukturált adat (LocalBusiness + FAQPage — ez segíthet, hogy Google közvetlenül megjelenítse a kérdéseket a találati listában), `sitemap.xml` és `robots.txt`.
7. A **foglalási rendszer** most már felismeri, ha valaki a kérdéssorból érkezett, és megmutatja neki, melyik szolgáltatást ajánlottuk.

## Amit szándékosan NEM adtam hozzá

A specifikációd kérte, hogy *"soha ne találj ki számokat"* — ugyanezt az elvet alkalmaztam a szövegre és a fényképekre is. Ezért **nem** készítettem:
- Egyéni terapeuta-profiloldalakat (fotó, végzettség, bemutatkozás nélkül üresek vagy kitaláltak lennének)
- Vélemény-karusszelt több véleménnyel (csak 1 valós véleményetek van most)
- Blogot / CMS-t (folyamatos tartalom kellene hozzá)

Ha ezekhez adsz nekem valós anyagot (terapeuták fotói + rövid bemutatkozása, több vásárlói vélemény), szívesen beépítem legközelebb.

## Lépésről lépésre: hogyan told fel

1. Nyisd meg a GitHub repódat böngészőben.
2. **Add file → Upload files**.
3. Húzd be mind az **5 fájlt**: `index.html`, `foglalas.html`, `sitemap.xml`, `robots.txt` — ha bármelyik már létezik, a GitHub felajánlja a felülírást, fogadd el.
4. Görgess le, és kattints a **Commit changes** gombra.
5. Várj 1-2 percet, amíg a GitHub Pages újraépíti az oldalt.
6. Nyisd meg a `www.merfoldkofejleszto.hu`-t — nézd meg új sorrendben: Hero → **kérdéssor** → **statisztikák** → Rólunk → Szolgáltatások → Vélemények → **GYIK** → **Környék** → Foglalás → Kapcsolat.
7. Mobilon görgess el a hero alá, és nézd meg, megjelenik-e a lenti sticky "Időpontot foglalok" gomb.

## Egy apró, de fontos teendő

A statisztika-sávban ott van egy jól látható "[VALÓS ADAT]" placeholder ("eddig fejlesztett gyermek" felirattal) — keresd meg az `index.html`-ben a `stat-placeholder` classt, és írd át a valós számra, mielőtt sokan látják. Szólj, ha segítsek megkeresni a pontos sort.
