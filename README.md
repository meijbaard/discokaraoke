# Disco Karaoke Loterij

Welkom bij de Disco Karaoke Loterij\! Dit is een eenvoudige webapplicatie die het organiseren van een karaokeavond een stuk leuker maakt. De tool kiest willekeurig twee deelnemers die samen een duo vormen en wijst hen vervolgens een willekeurig nummer toe uit een vooraf gedefinieerde lijst. Perfect voor feestjes en evenementen\!

De applicatie is live te bekijken op: **[disco.markeijbaard.nl](https://www.google.com/search?q=http://disco.markeijbaard.nl)**

![Disco Karaoke Loterij Screenshot](https://raw.githubusercontent.com/meijbaard/discokaraoke/main/screenshot.png)

## ✨ Features

  - **Willekeurige Duo Loting**: Klik op de "SPIN THE DISCO BALL\!" knop om willekeurig twee deelnemers te selecteren.
  - **Willekeurige Nummertoewijzing**: Tegelijk met het duo wordt er een willekeurig karaokenummer gekozen.
  - **Nieuw Nummer Optie**: Niet blij met het toegewezen nummer? De "NIEUW NUMMER\!" knop laat hetzelfde duo een nieuw nummer trekken.
  - **Volledig Aanpasbaar**: Deelnemers en nummers kunnen eenvoudig worden aangepast door de `deelnemers.json` en `nummers.json` bestanden te wijzigen.
  - **Werkt Overal**: De applicatie werkt zowel online via GitHub Pages als lokaal op je computer.

## 🚀 Hoe te gebruiken

Je kunt de Disco Karaoke Loterij op twee manieren gebruiken:

### 1\. Online

De makkelijkste manier is om de live versie te bezoeken via de volgende link:
[http://disco.markeijbaard.nl](https://www.google.com/search?q=http://disco.markeijbaard.nl)

### 2\. Lokaal

Als je de applicatie lokaal wilt draaien of aanpassingen wilt maken, volg dan deze stappen:

1.  **Clone de repository** naar je lokale machine:
    ```bash
    git clone https://github.com/meijbaard/discokaraoke.git
    ```
2.  **Navigeer naar de map**:
    ```bash
    cd discokaraoke
    ```
3.  **Open het `index.html` bestand** in je favoriete webbrowser (zoals Chrome, Firefox of Safari).

Dat is alles\! Er is geen webserver of complexe installatie nodig.

## ✏️ Deelnemers en nummers aanpassen

Je kunt de lijsten met deelnemers en nummers eenvoudig zelf aanpassen.

### Deelnemers aanpassen

1.  Open het bestand `deelnemers.json`.
2.  Voeg deelnemers toe of verwijder ze volgens het onderstaande formaat.

**Voorbeeld `deelnemers.json`:**

```json
[
  {
    "naam": "Naam A"
  },
  {
    "naam": "Naam B"
  },
  {
    "naam": "Team 1"
  }
]
```

### Nummers aanpassen

1.  Open het bestand `nummers.json`.
2.  Voeg nummers toe of verwijder ze. Elk nummer moet een `artiest` en een `titel` hebben.

**Voorbeeld `nummers.json`:**

```json
[
  {
    "artiest": "ABBA",
    "titel": "Dancing Queen"
  },
  {
    "artiest": "Queen",
    "titel": "Bohemian Rhapsody"
  }
]
```

*Tip: Je kunt "Vrije keuze" als artiest en "Verras Ons Maar\!" als titel toevoegen om deelnemers de vrijheid te geven zelf een nummer te kiezen.*

## 📄 Licentie

Dit project is gelicenseerd onder de MIT Licentie. Zie het [LICENSE](https://www.google.com/search?q=LICENSE)-bestand voor meer details.

-----
