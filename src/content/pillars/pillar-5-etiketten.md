---
order: 5
anchor: "etiketten"
eyebrow: "Säule 5"
title: "Etiketten & Markenkennzeichnung"
lede: "Das Etiketten-Modul direkt in Business Central — Nachfolger des Eigenentwicklungs-Tools aus Navision 5. Anwender pflegen Etikettenparameter am Artikel und drucken im gewohnten Workflow; Layout und Bausteine sind fest im System verankert."
situation: "Optimo erzeugt für Matratzen und Lattenroste großformatige, farbige Produktetiketten, die direkt auf das fertige Produkt aufgeklebt werden. Sie tragen Logos, Markenzeichen, Produkthinweise (zum Beispiel „elektrische Federleiste“) und Symbole für Recycling, Pflege und Zertifikate. Heute wird jedes Etikett aus vielen kleinen Bitmap-Bausteinen zusammengesetzt — gesteuert über ein Eigenentwicklungs-Tool in Navision 5, das in dieser Form nicht zukunftsfähig ist und in der Migration auf die aktuelle Business-Central-Version nicht mitwandert. Damit fällt eine produktionskritische Funktion weg. Das neue Modul schließt diese Lücke — Pflicht-Ersatz, nicht optionaler Ausbau."
features:
  - title: "Bitmap-Bibliothek in BC"
    description: "Logos, Markenzeichen, Recycling-, Pflege- und Hinweissymbole — gepflegt wie jede andere BC-Stammdatentabelle, mit Bildvorschau und Versionierung."
  - title: "Etikettenparameter am Artikel"
    description: "Welche Vorlage gilt, welche Bausteine sind aktiv, welche Texte (mehrsprachig), welche Größe — alles direkt auf der Artikelkarte, dort, wo der Sachbearbeiter ohnehin arbeitet."
  - title: "Feste Etikettenvorlagen"
    description: "Vom Entwickler einmal angelegt und bei Bedarf erweitert — analog zu allen anderen Reports in BC. Anwender pflegen Parameter, keine Layouts."
  - title: "Druck direkt aus BC"
    description: "Aus der Artikelkarte, aus dem Produktionsauftrag oder als Stapelverarbeitung — an die Optimo-Farbetikettendrucker, in der gewünschten Menge."
  - title: "PDF-Ausgabe"
    description: "Für Vorschau, Archivierung oder Kleinauflagen — derselbe Druckauftrag, ein Klick mehr."
  - title: "Druckhistorie pro Artikel"
    description: "Welche Etikettenfassung wurde wann gedruckt — nachvollziehbar direkt im ERP, relevant für Qualitäts- und Reklamationsfälle."
notIncluded:
  - "Kein WYSIWYG-Editor für Endanwender — Layoutänderungen sind selten und werden vom Entwickler in den festen Vorlagen umgesetzt."
  - "Keine Versand- oder Logistiketiketten — diese deckt der BC-Standard bzw. die Versand-App (Säule 4) ab."
  - "Keine Grafikbearbeitung der Bitmaps selbst — Logos und Symbole werden weiterhin in den jeweiligen Grafikprogrammen erstellt und als fertige Bausteine ins ERP eingespielt."
keyMessage: "Nachfolger des Navision-5-Etikettentools — sauber als integriertes Modul in der neuen Business-Central-Version. Anwender pflegen Parameter am Artikel und drucken im gewohnten Workflow; Layout, Bausteine und Vorlagen sind fest im System verankert."
architecture:
  title: "Warum als BC-Modul und nicht als eigene App"
  intro: "Das Modul ist eine native Erweiterung in Business Central. Bitmap-Bibliothek, Vorlagen und Etikettenparameter liegen direkt im ERP; der Druck wird aus BC heraus angestoßen, ohne Umweg über ein zweites System. Vier sachliche Gründe, warum diese Lösung als BC-Modul besser passt als eine eigenständige Webanwendung."
  arguments:
    - title: "Starre Layouts"
      description: "Etikettenvorlagen werden vom Entwickler angelegt; Anwender pflegen Parameter, keine Layouts. Damit entfällt das Hauptargument für einen WYSIWYG-Editor — und damit für eine eigene App."
    - title: "Daten leben in BC"
      description: "Artikel, Texte, Übersetzungen, Produktionsaufträge — alle Quellen sind im ERP. Eine zweite Anwendung würde Schnittstellen und doppelte Stammdatenführung schaffen, ohne fachlichen Mehrwert."
    - title: "Bürotätigkeit, kein Außeneinsatz"
      description: "Anders als Scanner, Außendienst und Versand findet diese Arbeit am Schreibtisch im BC-Client statt. Kein Grund, daneben eine zweite Anwendung zu öffnen."
    - title: "Vertraute Bedienung"
      description: "In Navision 5 war es integriert. Die Mitarbeiter kennen den Ablauf seit Jahren — die Akzeptanz des neuen Moduls ist damit deutlich höher als bei einem Umzug in eine separate App."
techSpecs:
  - label: "Plattform"
    value: "Native Business-Central-Erweiterung"
  - label: "Bibliothek und Vorlagen"
    value: "Gepflegt als BC-Stammdaten, Vorlagen als Reports"
  - label: "Ausgabe"
    value: "Direkter Druck an Farbetikettendrucker, alternativ PDF"
  - label: "Entwicklung und Betrieb"
    value: "PITapp"
galleryLayout: "laptop"
gallery:
  - src: "/mockups/etiketten-editor.svg"
    alt: "Muster-Screenshot der Artikelkarte in Business Central mit dem Reiter Etikettenparameter"
    caption: "Artikelkarte in Business Central — Reiter „Etikettenparameter“ mit Vorlage, aktiven Bausteinen, Hinweistext und kleiner Druckvorschau."
  - src: "/mockups/etiketten-bibliothek.svg"
    alt: "Muster-Screenshot der Bitmap-Bibliothek als BC-Stammdatenseite auf einem Laptop"
    caption: "Bitmap-Bibliothek in BC — gepflegt wie jede andere Stammdatentabelle, gruppiert nach Kategorie, mit Suche, Bildvorschau und Versionsinfo."
  - src: "/mockups/etiketten-fertig.svg"
    alt: "Muster-Vorschau eines fertigen Optimo-Produktetiketts im Hochformat"
    caption: "Fertiges Etikett — wie es nach dem Druck aussieht: Marken-Block, Symbol-Reihe, Hinweistext und Artikel-Identifikation."
    layout: "label"
---

<!-- TODO: Optionaler Langtext mit einem konkreten Workflow-Beispiel
     (BRIEFING Kapitel 4.5): neuer Artikel in BC angelegt → Etiketten-
     parameter direkt auf der Artikelkarte gepflegt → Druck aus dem
     Produktionsauftrag an den Farbdrucker. Vergleich zum integrierten
     Workflow aus Navision 5. Bis dahin tragen die Frontmatter-Felder
     den Inhalt. -->
