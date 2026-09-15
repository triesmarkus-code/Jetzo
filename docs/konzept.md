# Jetzo – Konzept

Arbeitstitel: **Jetzo**. Lokale App für tagesaktuelle Angebote und spontane Aktivitäten, Start-Testmarkt Stadt Bebra (Region Waldhessen).

## Grundidee

„Was geht heute in Bebra?“ – Eine App, die tagesaktuelle Gastro-Deals, Shopping-Rabatte, spontane Freizeit-Treffs, Mitfahrgelegenheiten und Nachbarschaftshilfe an einem Ort bündelt, gefiltert nach Stadt/Region und Kategorie.

## Geografisches Konzept: Stadt & Region

Statt eines Kilometer-Radius arbeitet Jetzo mit zwei festen Ebenen:

- **Stadt Bebra**: Die Standard-Ansicht beim Öffnen der App – tagesaktuelle Gastro-Deals, Shopping-Rabatte und spontane Treffs direkt vor Ort.
- **Region Waldhessen**: Ein Umschalter erweitert die Ansicht auf die Region – sinnvoll für Mitfahrgelegenheiten, überregionale Events (JetzoLive) und Sportgruppen, die auch außerhalb der Stadtgrenze Teilnehmer suchen.

Vorteil gegenüber einem Radius-Schieberegler: klarere Erwartung ("Das ist meine Stadt" vs. "Das ist meine Region"), einfacher zu kommunizieren an Partner und Nutzer, und die Ebenen lassen sich unabhängig von GPS-Genauigkeit pflegen.

**Städte in Region Waldhessen** (Landkreis Hersfeld-Rotenburg): Bad Hersfeld, **Bebra** (Pilot-Testmarkt), Rotenburg an der Fulda, Heringen (Werra). Die Warteliste auf der Landingpage erlaubt bereits die Anmeldung aus allen vier Städten – die Region wird dabei automatisch aus der gewählten Stadt abgeleitet. Der Wirte-Vertrieb (Gründungsmitglieder-Aktion) startet trotzdem zunächst konzentriert in Bebra.

## KI-Unterstützung für Wirte

Wirte laden ein Foto ihrer Kreidetafel/Tageskarte hoch (App oder WhatsApp an Service-Nummer), die KI liest das Gericht aus und erstellt automatisch das digitale Angebot. Kein Formular-Tippen nötig – „Foto statt Tippen“.

## Preismodell (Gastro-Partner)

- Erste 6 Monate kostenlos
- Danach: 10 €/Monat für 3 Aktionen, 15 €/Monat für 7 Aktionen, etc. (gestaffelt)
- Push-Nachrichten + tägliche Angebote: 29 €/Monat
- Hervorhebung „oben in der Liste“: 5–10 €

## Go-to-Market: Erste 50 Partner (Stadt Bebra, Region Waldhessen)

Größtes Hindernis: Zeitmangel der Wirte. Devise: **„Wir nehmen dir die Arbeit komplett ab.“**

- **Gründungsmitglieder-Vorteil**: Lebenslange kostenlose Nutzung des Basis-Abos für die ersten 50 Gastronomen – nimmt finanziellen Druck, schafft Vertrauen.
- **Manuelles Onboarding**: Persönlich ins Restaurant gehen, Speisekarte holen, Profil selbst anlegen. Der Wirt muss beim ersten Mal nichts selbst tun.
- **Foto-statt-Tippen**: Morgens ein Foto der Tageskarte per WhatsApp oder App-Upload – KI (oder anfangs manuell) liest das Gericht aus und stellt es online.

## Roadmap in Phasen

### Phase 1 – Start: Gewerbliche Tages-Deals
- 🍔 **JetzoDeals / JetzoEssen**: Tagesaktuelle Angebote (Mittagstisch, 2-für-1-Cocktails, Last-Minute-Tische)
- 🛍️ **JetzoShoppen**: Spontane Rabatte im lokalen Einzelhandel (Mode, Deko, Elektronik)

### Phase 2 – Community-Erweiterung: Spontane Freizeit
- 🏃 **JetzoSport / JetzoAktiv**: Lauf-/Freizeitpartner-Finder, Sportvereine melden spontane freie Plätze
- ☕ **JetzoTreffen**: Rein soziale Kontakte, ideal für Neuzugezogene (spontaner Kaffee, Spieleabend)

### Phase 3 – Mobilität & Nützliches
- 🚗 **JetzoMitfahren**: Ultraspontane Mitfahrzentrale für heute/morgen (Pendler, Event-Besucher)
- 🤝 **JetzoHelfer**: Nachbarschaftshilfe in Echtzeit (z. B. Couch tragen, Baumarkt-Mitbringservice)

### Phase 4 – Kultur & Entertainment
- 🎉 **JetzoLive**: Resttickets/Kurzfristevents von Kinos, Live-Musik-Bars, Clubs

### Weitere Idee (unsortiert)
- 🛏️ **Abends Zimmer günstiger**: Kurzfristige Übernachtungsangebote / Last-Minute-Zimmerrabatte (Anknüpfungspunkt zu Vermietung/Hotellerie)

## Screendesign Startseite (Wireframe-Konzept)

Prinzip: **Erst filtern, dann entdecken.**

- **Header**: Logo „Jetzo“ links, Profil-Icon + Herz-Icon (Favoriten) rechts. Darunter fixe Suchleiste: „Was suchst du heute? (z. B. Schnitzel, Joggen)“.
- **Filter-Leiste**: Umschalter **Stadt Bebra / Region Waldhessen** (statt Kilometer-Radius), darunter horizontal scrollbares Band mit runden Kategorie-Icons (🍔 Essen, 🏃 Sport, 🚗 Mitfahren, 🛍️ Shoppen) – Tippen filtert sofort.
- **Feed / Hauptbereich**: Angebote als Karten mit großem Bild, fetter Überschrift (z. B. „Knuspriges XXL-Schnitzel für 12,- €“), Entfernungsangabe (z. B. „350 m entfernt“), Herz-Symbol oben rechts zum Speichern.

## Login & Favoriten

Login ist langfristig zwingend, aber mit Einschränkung für den Start:

- **„Gucken-ohne-Anmeldung“-Modus**: Keine Zwangsregistrierung beim Öffnen – Angebote müssen sofort sichtbar sein (sonst hohe Absprungrate).
- **Login bei Aktion**: Erst nötig, wenn der Nutzer aktiv wird – Favorit setzen, Gutschein reservieren, Kontakt aufnehmen/Aktivität erstellen.
- **Mehrwert Favoriten**: Nutzer folgen Lieblingsbetrieben/-personen und erhalten Push-Benachrichtigung bei neuen Angeboten.

## Business-Zugang für Partner

Getrennt vom normalen Nutzer-Login gibt es einen eigenen **Business-Zugang** für Gastronomen, Händler und andere professionelle Anbieter – kein Konsumenten-Account, sondern ein Partner-Dashboard.

- **Eigener Login-Bereich**: E-Mail + Passwort (oder Magic Link), führt direkt ins Partner-Dashboard statt in die normale Nutzer-Ansicht.
- **Funktionen im Dashboard**:
  - Angebote verwalten (anlegen, bearbeiten, löschen – inkl. „Foto-statt-Tippen“)
  - Profil pflegen (Name, Adresse, Öffnungszeiten, Kategorie)
  - Abo & Preisstufe einsehen (Anzahl Aktionen, Rechnung, Upgrade/Downgrade)
  - Push-Kampagnen planen (für das 29-€-Paket)
  - Reichweiten-Statistik (Ansichten, Speicherungen, Klicks) – **Phase 2**
- **Einrichtung beim Onboarding**: Beim persönlichen Besuch (Gründungsmitglieder-Aktion) legt das Jetzo-Team den Business-Zugang direkt mit an – der Wirt bekommt nur noch Zugangsdaten, keine Selbstregistrierung nötig.
- **Unabhängig vom Konsumenten-Login**: Ein Partner kann Jetzo zusätzlich privat als Nutzer verwenden, Business-Zugang und Nutzer-Account bleiben aber getrennte Logins.

## Premium-Mitgliedschaft (Nutzer)

„Jetzo-Plus“ für 1,99 €/Monat: komplette Werbefreiheit, unbegrenzt private Aktivitäts-Inserate pro Woche, exklusive Gastro-Deals nur für Plus-Nutzer.

## Eingabeformulare

Prinzip: so wenig Text wie möglich, so viele Auswahllisten wie möglich – Kriterien beim Hochladen müssen exakt zu den Suchfiltern passen.

### Formular Händler (Gastro & Shop) – < 30 Sekunden ausfüllbar
- Titel des Angebots (Pflicht, Kurztext)
- Kategorie (Pflicht, Auswahl): 🍔 Essen / 🍹 Trinken / 🛍️ Shopping
- Preis (Pflicht): Normalpreis + Jetzo-Aktionspreis
- Gültigkeit: Standard „Nur heute“, optional Datum wählbar
- Foto (optional, empfohlen): Upload, sonst automatisches Standard-Symbol
- Standort & Name: automatisch aus dem Profil des Händlers

### Formular Privatpersonen (Sport/Treffen/Mitfahren)
- Kategorie (Pflicht, Auswahl): 🏃 Sport / ☕ Treffen / 🚗 Mitfahren
- Aktion/Titel (Pflicht, Kurztext)
- Wann (Pflicht): Uhrzeit + Datum (Vorauswahl: heute)
- Treffpunkt/Ort (Pflicht): Textfeld bei Sport/Treffen, „Start“ + „Ziel“ bei Mitfahren
- Maximale Teilnehmerzahl (Auswahl): z. B. „Suche 1 Person“, „Gruppe bis 5“, „Noch 2 Plätze frei“

## Landingpage (Test vor App-Entwicklung)

Ziel: Validierung der Idee über eine einfache Landingpage + Warteliste, bevor die App gebaut wird.

### Hero-Section
- **Überschrift**: Was geht heute in Bebra? 🍔🏃
- **Unterüberschrift**: Schluss mit langem Suchen. Jetzo zeigt dir tagesaktuelle Gastro-Deals, spontane Freizeit-Treffs und Mitfahrgelegenheiten in Stadt Bebra und der Region Waldhessen. Genau jetzt.
- **CTA**: E-Mail-Feld + Button „Ich will beim Start dabei sein! (Kostenlos)“

### Nutzen für Nutzer
- 🍔 Nie wieder Schnitzel-Deals verpassen
- 🏃 Spontan nie mehr allein
- 🚗 Schnell von A nach B

### Nutzen für Gastronomen & Händler
- 📢 Tagesgerichte blitzschnell ausverkauft (Foto der Kreidetafel → KI stellt es online)
- 👥 Neue Kunden aus der Region

### Footer
- Hinweis: „Wir entwickeln Jetzo gerade mit viel Herzblut für Bebra. Trage dich oben ein, und wir informieren dich exklusiv, sobald die App im App Store verfügbar ist. Kein Spam, versprochen!“
- Links: Impressum | Datenschutz (DSGVO)

## Test-Strategie

1. Landingpage erstellen (Baukasten, ca. 1–2 Std.)
2. Link in lokalen Facebook-Gruppen teilen (z. B. „Bebraer Gerüchteküche“, Nachbarschafts-Gruppen)
3. Ziel: 150–200 Eintragungen aus Stadt Bebra und Region Waldhessen innerhalb von 2 Wochen → Signal für Marktpotenzial

### Facebook-Post (Entwurf)

> **Hallo Bebra! Schnitzellust & Laufpartner-Suche? 🍔🏃**
>
> Mal ehrlich: Wie oft habt ihr spontan Lust auf ein bestimmtes Essen (z. B. ein richtig gutes Schnitzel-Angebot) und wisst nicht, welcher Laden in der Nähe heute eine passende Aktion hat? Oder ihr wollt eine Runde joggen gehen, aber im Freundeskreis hat gerade niemand Zeit?
>
> Weil es dafür bisher keine einfache Lösung gibt, entwickle ich gerade eine App speziell für Bebra und die Region Waldhessen: Jetzo! 📍
>
> Das Prinzip ist super simpel:
> 1. App öffnen
> 2. Thema auswählen (z. B. Gastro-Deals, Sport, spontane Mitfahrgelegenheiten)
> 3. Sofort sehen, was HEUTE in und um Bebra abgeht.
>
> Gastronomen und Händler können ihre Tageshits morgens einfach per Foto hochladen, und ihr seht es sofort auf dem Schirm.
>
> Die App ist aktuell in der Planung. Um zu sehen, ob sich die Entwicklung für Bebra lohnt, habe ich eine kleine Warteliste gestartet. Wenn ihr die Idee cool findet, tragt euch bitte komplett unverbindlich und kostenlos ein.
>
> Hier geht's zur Seite: 👇
> [LANDINGPAGE-LINK]
>
> Teilt den Beitrag gerne mit Freunden aus der Region. Lasst uns Bebra gemeinsam digitaler und spontaner machen! 💪

### Tipps für den Post
- **Bild statt reiner Text**: appetitliches Schnitzel-Foto oder Bild vom Bebraer Stadtkern/Breitenbacher See (3x höhere Reichweite laut Facebook-Algorithmus)
- **Zeitpunkt**: sonntags 18–20 Uhr oder unter der Woche gegen 19:30 Uhr
- **Aktiv in Kommentaren bleiben**: Jede Interaktion pusht den Beitrag im Algorithmus
