# [Verkefnaheiti]

> Stutt lýsing á verkefninu — ein til tvær setningar um hvað þið eruð að gera og hvers vegna.

## Hópurinn

| Nafn | GitHub | Hlutverk |
|------|--------|----------|
|  | [@notandanafn](https://github.com/) |  |
|  | [@notandanafn](https://github.com/) |  |
|  | [@notandanafn](https://github.com/) |  |

Sjá [TEAM.md](TEAM.md) fyrir samning hópsins og verkaskiptingu.

## Vandamálið

Lýsið vandamálinu sem þið eruð að leysa. Hvaða spurningar viljið þið svara?

## Gagnasafnið

- **Uppruni:** _(hvaðan koma gögnin? Setjið inn hlekk ef við á)_
- **Umfang:** _(hversu margar línur/dálkar?)_
- **Tímabil:** _(ef við á)_
- **Leyfi:** _(t.d. [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/deed.is) eða [opið gögn Íslands](https://opingogn.is/))_

## Uppbygging gagnageymslunnar

```
├── data/
│   ├── raw/          ← Upprunagögn — breytist aldrei
│   └── processed/    ← Hreinsuð og umbreytt gögn
├── src/              ← Kóði (SQL, Python, R o.fl.)
├── docs/             ← GitHub Pages skýrslur (útgefið á /docs á main)
│   └── iREF/         ← Einstaklingsbundnar ígrundanir
├── TEAM.md           ← Hópsamningur
└── README.md         ← Þetta skjal
```

## Hvernig á að keyra

```bash
# Setja upp umhverfið (ef við á)
...

# Keyra greiningu
...
```

_(Uppfærið þetta þegar þið hafið eitthvað til að keyra)_

### Skoða GitHub Pages-síðuna (docs/) staðbundið

`docs/index.html` er upphafssíðan fyrir mælaborðið/skýrsluna ykkar. Til að skoða
hana á eigin tölvu áður en hún fer á netið:

```bash
# Opna beint í vafra (einfaldast, dugar fyrir hreina HTML/CSS/JS)
open docs/index.html        # macOS
start docs/index.html       # Windows

# Eða keyra staðbundinn vefþjón (þarf ef síðan sækir gögn með fetch/AJAX)
cd docs
python3 -m http.server 8000
# Opnið svo http://localhost:8000 í vafranum
```

_(Ef þið notið Shiny/Flexdashboard/Quarto í staðinn fyrir hreina HTML-skrá,
uppfærið þessar leiðbeiningar samkvæmt því — sjá dæmi í `src/README.md`.)_

## Niðurstöður

_(Uppfærið þetta eftir hverja lotu — hvað lærðuð þið? Hvað kom á óvart?)_

Lifandi skýrsla er birt á [GitHub Pages](https://upplysingaverkfraedi.github.io/[nafn-gagnageymslu]/)
(útgefið sjálfkrafa úr `docs/` á `main`).

## Leyfi

[MIT](LICENSE) — eða tilgreinið annað leyfi ef við á.
Athugið að gagnasafnið gæti haft sitt eigið leyfi (sjá að ofan).
